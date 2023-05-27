# Twitter-Analysis
The goal is to to identify whether Twitter can be considered a credible source of information, reflects the emergence of important trends or topics in education, specifically: “Online Learning”.

**(More details in the Code.ipynb and Presentation.pdf file)**

## Data
The collection of Twitter data that is stored in Google Cloud Storage.  Once combining individual JSON files, there will be ~100 million Tweets (~500GB).  These tweets are collected on the topics of education, schools, universities, learning, knowledge sharing, etc., with only a fraction of them would be directly related to either primary, secondary or higher education.

## Steps
### Discard irrelevant tweets
### Complete thorough EDA 
### Identify the most prolific / influential Twitterers
  - By message volume (original content)
  - By message retweet (how often their messages are being retweeted).  
  - Who are these Twitterers (government entities / universities / schools / nonprofit organizations / news outlets / social media influencers / someone else)?
  - Visualize the distribution of tweet / retweet volume by Twitterers and types of organizations
### Figure out where are these Twitterers (all of them, not just influencers) located?
  - See any relationship between the emergence of new issues in education and progression and locations of these Twitterers?
  - Visualize the geographical distribution
### Figure out what are the timelines of these tweets? 
  - Any data collection gaps?
  - Plot the timelines of these tweets
### Figure out how unique are the messages?
  - Are they mostly unique? Or usually people are just copy-pasting the same text?
  - Use Jaccard similarity to measure uniqueness / similarity
  - Visualize message duplication for each group of Twitterers (government entities / health organizations / news outlets / social media influencers / other)
