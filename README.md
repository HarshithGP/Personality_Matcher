# Personality_Matcher
Python Application to determine compatibility using the IBM Bluemix's Personality Insights API

Packages Installed

python-twitter - package needed to interact with the twitter api
watson-developer-cloud - package needed to interact with the Personality Insights API


Developed an application in python to find the compatibility between two individuals by using IBM Watson’s Personality Insights API 
on a dataset constructed from the tweets of the two Twitter personalities. 

The application uses the Twitter API (python-twitter package) to retrieve the 300 most recent tweets of a person 
using the twitter handle corresponding to his/her username. The retrieved data is parsed and concatenated into a string of text
and sent to the Personality Insights API to be analyzed.

The Personality Insights API (watson-developer-cloud package)  service of IBM’s Watson Developer Cloud 
uses linguistic analytics to analyze unstructured text(Twitter Data) and infers personality and social characteristics 
by using three models - Big Five, Needs and Values. The JSON results resembling a tree like structure 
re flattened to derive insights about personality traits in various categories. 

Individuals displaying similar probabilities for personality traits are termed as “Compatible”.
