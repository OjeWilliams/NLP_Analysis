 # Game of Thrones Analysis
 ## Proposal: The Beginner’s Guide to Game of Thrones

Game of Thrones, also known for GOT, is a fantasy drama television series that contains 73 episodes in 8 seasons. Analyzing a complete set of the script from all the characters for all seasons by sentiment analysis and aspect mining, we can start with cleaning the text, tokenization, and Named Entity Recognition (NER). By answering questions such as the change in main characters' sentiment, frequent words used in each family, and the comparison of the word usage of the two main characters, we can provide better and deeper insights to the audience. The GOT script analysis can help the audience understand the impact of each main character, classify the attitude of each family, and learn two main characters in 10 mins.

A complete set of GOT for all seasons in form of a table containing 6 columns with different data types used for various purposes. The GOT script dataset is generated through scrapping the whole URLs provided on Genius.com for the Game of Thrones series and organized into csv files on Kaggle. 


#### Data Source:
https://www.kaggle.com/albenft/game-of-thrones-script-all-seasons

####Dataset Overview

●	Release Date: Original air date of the episode.
●	Season: Season number.
●	Episode: Episode number
●	Title: Title of each episode.
●	Name: Name of a character in Game of Thrones.
●	Sentence: Sentence spoken in the series. (22300 unique value)

#### Text Pre-processing 

●	Cleaning (getting rid of punctuations & numbers): use word comparison operators
●	Tokenization: break up the string into words and produce a list using tokenizers or regular expressions
●	Normalization: normalize the text to lowercase to ignore the case distinction
●	Stemming/lemmatization: try different stemmers to strip off any affixes; use lemmatizer to make sure the resulting form is a known word in a dictionary and get a list of valid lemmas

####Text Analysis

When it comes to Natural Language Processing and analyzing text there are many methods that can prove very useful for us in extracting valuable information. Primarily with the GOT script, it would be useful for us to conduct Sentiment Analysis combined with Aspect Mining via NLTK and spaCy packages. But before we can get to those methods, it might be helpful to first start with Named Entity Recognition (NER). NER allows us to obtain from the text the possible objects with the text i.e dates, people, locations, etc. It will allow us to quickly extract these entities giving us semantic knowledge from the script such as who are the persons as well as what are the places or dates and times mentioned in each dialogue.

Once NER is complete, we can then move on to Sentiment Analysis paired with Aspect mining. Sentiment analysis seeks to determine how the text is expressed in terms of being negative, neutral, or positive. In this sense, we can search the text and identify how each character’s sentiment changed from line to line or episode to episode. Aspect mining attempts to identify the different features or common concerns in a text. An example of aspect mining is using the part of speech tagger (POS) on the text. Ideally combining sentiment analysis and aspect mining will allow us to gain insight on different topics/concerns in the script and determine whether each major topic/concern had a negative, neutral or positive sentiment attached to it.


####Research Questions

●	How does the sentiment of the main characters change with time? – Sentiment Analysis
●	What are the most used words in each important family? – Stemming, FreqDist
●	Comparing characters: between Cersei and Daenerys, who says more times the word "kill"? And what about the word "love"? – Stemming, FreqDist

#### Practical Implications

A story often tends to be interpreted in various ways by audiences. Examining the three proposed research questions will help the audience understand the impact of each main character, how the story revolves around them, and the importance of their actions. The first proposed research question focuses on tracking the sentiment of each main character over time. By performing sentiment analysis, we can extract the polarity and subjectivity of a character in an episode or event. This helps the audience gain a better overview of a character’s opinion behind certain scenes. The second question focuses on text classification based on the most used words in each family. Instead of looking at a specific character, exploring the frequent used words in a family helps to classify the overall attitude of the family as positive, negative, or neutral. 

Many ask, “who is the better queen, Cersei, or Daenerys?” The main premise of Game of Thrones is the fight for the coveted Iron Throne. Many kings and queens want to sit on it, but no one fights for it harder than Cersei Lannister and Daenerys Targaryen. The third research question focuses on a comparison of characters: Cersei and Daenerys. Although there is a wide range of considerations and perspectives in determining who is the better queen, such as selflessness, just, knowledge of politics, wealth, and resourcefulness. Perhaps, many agree that the most important one will be mercy.  Therefore, counting the words "kill" and "love,” spoken by Cersei and Daenery aims to help the audience compare the two main characters, Cersei and Daenerys. 

By leveraging all three proposed research questions, we can help audiences who have watched Game of Thrones gain deeper insights of the story and each main character. For those who have not watched any of the seasons, this will act as a beginner’s guide to Game of Thrones.

#### Assets
[Data]()
[Notebooks]()
[Presentations]()



**Group Information**	
Wei Chi Yeh	
Oje Williams	
Jack Yang	
Yichuan Hu	
Sanket Patel	
Jingnan Qi
