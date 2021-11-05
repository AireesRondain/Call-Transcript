# Presentation in Tableau Public
https://public.tableau.com/views/CallTranscripts-dataviz/Story1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

# FB-GOOG-transcripts.ipynb
- code for web scraping Facebook & Google's Call Transcripts for Q2 2021;
- I used BeautifulSoup for pulling out data out of HTML files; spacy for NLP
- I added additional stopwords manually based on the transcripts

# FB_Count_Unique_Words.ipynb and  GOOG_Count_Unique_Words.ipynb
- code to just count the unique words in the text file of the Call Transcripts generated from the code above.
- the text file still contains the stop words (not cleaned yet)
- converted the dictionary to list to dataframe
- exported the dataframe to csv file for data visualization
