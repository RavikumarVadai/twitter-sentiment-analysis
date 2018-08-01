# Introduction
The video assistant referee (VAR) is a football assistant referee who reviews decisions made by the head referee with the use of video footage and a headset for communication.The use of video technology has been a major talking point in 2018 Russia fifa world cup. However, the new system resulted in more discussion and controversy over officiating than would be expected as normal. Football throughout the world took twitter to express their views on VAR system. Objective of this project is to do sentiment analysis on unique tweets and to find the words used in describing their emotion.

# Steps involved
1) Crawl unique tweets against hash tags
2) Pre-processing tweets
3) Feature extraction from tweet text
4) Vader Sentiment Analysis
5) Sentiment score and visualization

# Vader Sentiment analysis(lexicon method)
VADER (Valence Aware Dictionary and sEntiment Reasoner) is a lexicon and rule-based sentiment analysis tool that is specifically attuned to sentiments expressed in social media. VADER text sentiment analysis uses a human-centric approach, combining qualitative analysis and empirical validation by using human ratings and the wisdom of the crowd. It combines a dictionary, which maps lexical features to emotion intensity, and five simple heuristics, which encode how contextual elements increment, decrement, or negate the sentiment of text.
Five simple heuristics are:
1)punctuation
2)capitalization
3)degree modifiers
4)shift in polarity due to “but”
5)examining the tri-gram before a sentiment-laden lexical feature to catch polarity negation
  
 for more information on Vader sentiment analysis please refer 
 http://comp.social.gatech.edu/papers/icwsm14.vader.hutto.pdf
 http://datameetsmedia.com/vader-sentiment-analysis-explained/
 https://github.com/cjhutto/vaderSentiment