
## Problem Statement

Rwanda has trensitional to distance based fare system in public transport. The government wants to understand public sentiment around this change using data from social media, news comments and surveys.

## Solutions
 we propose a sentiment analysis dashboard and report tha helps policymakers monitor public option, identify key concern and respond to misinformation.

    
 ## OBJECTIVES

 -Understanding public sentiment over time
 -Identify trending concern, complaints or support
 -Create a dashboard or report to assist policymaker

 ## Methodology


- Twitter: using snscrspe to gather tweeys containing keyword like " fare 
  system", 'transport Rwanda',...
- News websites: scrape reader comment from IGIHE, RBA, KT Press,......
- Survey: we design and distribute a google form to gather public feedback

  # Tools we can use to correct above data
  -Tweepy( Twitter API), PRAW( Reddit API), BeautifulSoup(Web scraping).

  ## Data processing
  - Data Cleaning: Remove URLs, emojis and special characters
  - Translation: by using google cloud transilation API
  - Tokenization: Split text into words/ phrases (NLTK for english, custom 
     rules for kinyarwanda)
 
    ## Sentiment and Topic analyses

    # Sentiment scoring
    - Use a pre-trained multilingual BERT model to classify sentiment 
     (Positive, Neutral, Negative)
   
      # Topic Medeling
      
      Apply BERTOPIC to dynamically cluster discussion

      example: - fare fairness
               - Route coverage
      # Misinformation Dection

      Fag claims contracting official statement

      example: - fare are free for students, using keyword matching and fact 
      checking API

      ## Visualization and Reporting

      - Matplotlib and seaborn for sentiment trends
      - WordCloud to exctract common Phrasee and keywords
      - Streamlit dashoboard (optional) to make insights interactive
      - PDF or Markdown report summirizing key findings
     
      ## Output
      - Sentiment charts by date/source
      - keyword cluouds showing concerns and praise
      - insights:
     
      -- % of people unheppy about about increased costs
      -- Misunderstanding about how fare is calculated
      -- suggestions from the public
   
  - ## Recommandations
 
  - after to make all above process and data analysis you can output from it. where yuou can use to recomamand policymaker
 
  



 # Tools I Can use

 -Python ( pandas, seaborn, nltk and texblob)
 -Web scraping ( BeautifulSoup)
 -Social media API ( Twitter API)
 -People Ideas ( Google form and interview)
 -Data visualization ( matplotlib, seaborn)
 -Streamlist(optional dashboard)
 -Google cloud transilate API












 


 
