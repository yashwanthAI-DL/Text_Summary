# Text_summary

Solution to Problem Statement

Based on the problem statement. Only getting sentiment or Titles wont get the exact Context for the problem
So to approach this problem we can use summarlization techniques which can generate a summary of the long reviews which contains the short summary of the review with context
To approach Summarization problem we can use different techniques like AutoSeq2Seq , Bert Summarizer etc .
By experiment we found that Bert summarization performs better than other tecniques
Preprocessing Techniques: a. Tried to remove punctuations but when we remove the punctuations reviews like 5'8 will be converted to 58. and sentenses will be converted to single sentences so making summarization bad. b. Tried removal of stopwords but there was no significant change in the summarization.
After Summarization is done, appended a summarization column to the original data set called Summary column
For the second question where max reviews was given for the cloth id 1078 which has 1024 reviews we can try using LDA which helps in finding the Top topics from the summary. For LDA stopwords removal and other preprocessing are used
