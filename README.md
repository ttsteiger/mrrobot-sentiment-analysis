# mrrobot-sentiment-analysis

## Data
Subtitles:
https://www.opensubtitles.org/en/ssearch/sublanguageid-eng/idmovie-197690

Episode Names:
https://en.wikipedia.org/wiki/List_of_Mr._Robot_episodes

IMDB Scores:

Repo: https://github.com/ttsteiger/mrrobot-sentiment-analysis





Part 1:
- Data prep. & cleaning
- Applied to subtitles, remove all timestamps & empty lines, score each line? What about sentences going over multiple lines?
- Scoring of long texts -> Score sentences, average for chapters, great visualizations: https://towardsdatascience.com/basic-nlp-on-the-texts-of-harry-potter-sentiment-analysis-1b474b13651d

Part 2:
- Lexical analysis



Part 3: 
- VADER Sentiment Analysis
- http://datameetsmedia.com/ranking-the-negativity-of-black-mirror-episodes-with-sentiment-analysis/
- http://datameetsmedia.com/vader-sentiment-analysis-explained/
- https://github.com/cjhutto/vaderSentiment
- https://towardsdatascience.com/basic-nlp-on-the-texts-of-harry-potter-sentiment-analysis-1b474b13651d


Part 4: 
- ML for Sentiment Analysis
- https://levelup.gitconnected.com/sentiment-analysis-using-machine-learning-python-9122e03f8f7b
- http://www.laurentluce.com/posts/twitter-sentiment-analysis-using-python-and-nltk/
- https://www.twilio.com/blog/2017/12/sentiment-analysis-scikit-learn.html
- https://towardsdatascience.com/sentiment-analysis-with-python-part-1-5ce197074184
- https://stackabuse.com/python-for-nlp-movie-sentiment-analysis-using-deep-learning-in-keras/




## Notes:


- Try with MonkeyLearn API: 
	https://app.monkeylearn.com/main/classifiers/cl_CsfDyd3m/tab/demo/
	https://monkeylearn.com/pricing/ 


- Twitter SA: https://www.geeksforgeeks.org/twitter-sentiment-analysis-using-python/

- Next Idea: Customer Review Sentiment Analysis for Restaurants in Zürich -> Display in WebApp
https://rstudio-pubs-static.s3.amazonaws.com/155272_c91116f9fd774349bef82cb154b62f5c.html

 Lexical Approach -> VADER
- Machine Learning Approach -> Training Data??
- Negativity vs. IMDB Scores?
- Positiv vs. negative/split into individual sentiments
- IMDB score for episode vs. sentiment -> predict IMDB scores for S04 based on subtitles

http://millionsongdataset.com/