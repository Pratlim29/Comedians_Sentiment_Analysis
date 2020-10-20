## Sentiment Analysis for Top 10 Comedians

1. Extracted the transcripts for the top 10 comedians in the United States using python libraries like requests and Beautiful Soup and then stored the transcripts with comedians in the python data frames, so it can easily accessible 
2. Performed following data preprocessing techniques 
- Tokenization: - It is way of separating a piece of text into smaller units called as tokens. (Word, character, subwords)
- Stemming: - It is the process of reducing inflected words to their word stem, base or root form

3. Performed regular expression operations to remove unwanted data such a bracket, punctuation marks, numbers.
4. Performed Exploratory Data Analysis to find out insights about comedians’ transcripts such as Top 50 words said by comedians, Unique words, most common words etc. and then visualized this using python libraries Matplotlib, seaborn.
5. Calculated Polarity and Subjectivity scores for each comedian, like how much S-word, F-words said by that comedians and classified them into positive, negative and neutral classes.
- Ploarity: - (TextBlob package) negativity and positivity [-1,1] <<<neg ----- pos>>>>>>
- Subjectivity: - refers to opinion, emotion or judgement [0,1] <<<facts -------- opinion >>>>>>
.
