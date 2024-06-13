#  Language & Sentiment of Media Reported Pro-Palestine Protests

<img src="https://github.com/jjoycehu/poli-179/blob/640d2aaba13e5385b864f9e59fdb117e12c4300c/figures/news_sentiment.png" />

## Group 4
- Andrew Acosta
- Joyce Hu

## Introduction
   From the beginning of March 2024, the United States has experienced nationwide demonstrations across various college and university campuses. Students took to their campuses to protest Israel’s actions against the Palestinian people and show solidarity for the Palestinianes affected by Israel. The students called for their respective university to divest all assets tied to or supporting the state of Israel as a form of protest and dissatisfaction with Israel’s conduct. In response to the protests, many universities sought to shut down the demonstrations by having police crackdown on protesters leading to arrests and disciplinary action. Due to the amount of protests from high profile universities such as Harvard, Brown, etc. inspiring action to take place across the nation, major news outlets were quick to report on keeping up with every demonstration.

  Regardless of one’s opinion on the overall highly polarizing issue of Israel and Palestine, we believe this presented a unique opportunity to study media bias on this particular issue due to how polarizing it has been. Primarily, we seek to answer the question; Is there a relationship between the language used to report Pro-Palestine student protests and the media’s own political bias? We believe that media outlets that lean to the right politically would be found to use more generally negative language when it comes to reporting the Pro-Palestine student protests compared to their left leaning counterparts. For example, we expect that right leaning media sources would use words such as “disruption,” and  “agitators,” that paint the demonstrations in a more negative light while left leaning media sources may use language such as “walk-out,” “solidarity,” and “peaceful” to paint a more positive light of the protests.


### Research Question: 
Is there a relationship between the language used to report Pro-Palestine student protests and the news media site's political bias?

### Hypothesis: 
New media sites that are more right-leaning would use more negative language when reporting Pro-Palestine student protests in comparison to left-leaning media sites. 

## Methods
- K-means Clustering and Dimensionality Reduction
- Sentiment Analysis
- Linear Regression


## In this repo: 

### `notebooks`: 

`google news data collection.ipynb`: data collection script  
`analysis.ipynb`: notebook to replicate analysis  

### `data`: 
`news and keywords.xlsx`: keywords and news sites used for data collection  
`political_leaning.csv`: media bias scores  


## Results

<img src="https://github.com/jjoycehu/poli-179/blob/cc6246f38c44124cd12b87e23384f20629613748/figures/ols_results.png"/>

At the 0.01 significance level, there is a sigificant negative relationship between a news site's media bias score and the language it uses in articles about Pro-Palestine student protests. 

## Discussion 
Although the results support our initial hypothesis, the relationship found was weaker than expected. We believe this may be due to two reasons: a lack of right leaning sources that reported on the protests or did not pick up and that left leaning sources using more negative language than anticpated. We believe this may be due media outlet's different strategies in pushing their own bias.
 
## References 
**Brown, Danielle K. and Summer Harlow.** 2019. “Protests, Media Coverage, and a Hierarchy of Social Struggle.” The International Journal of Press/Politics 24(4) 508–530. [Link]

**Fu, King-Wa. 2023.** “Propagandization of Relative Gratification: How Chinese State Media Portray the International Pandemic.” Political Communication 40(6). [Link]

**Giersch, Jason.** 2019. “Punishing Campus Protesters Based on Ideology.” Research & Politics, 6(4). [Link]

