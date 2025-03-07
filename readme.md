# Hinge Data Analysis

**🔗 Link to project:**  https://hazel-gandhi.github.io/hinge-data-analysis/

I asked 8 friends (4 male, 4 female) to share their Hinge data with me and analyzed it to do a gender analysis and things such as likes sent, likes received, matches, conversations and meetings.

## 📂 Repository Guide
1. **`hinge-analysis`**: Includes analysis of all Hinge data  
2. **`data`**: All CSV files that came from the analysis  

## 🎯 Aim
- Learn responsive design using ai2html and Adobe Illustrator  

## 📊 Findings
- As expected, on average, women gained a lot more matches and had a lot more conversations than men did. This happened even though men sent out a lot more likes but received very few in return.  
- Hinge says it is meant to be an app that users eventually uninstall once they meet someone good. This was true for my friend, who significantly reduced sending likes on the app after meeting a good match.  
- One of my male users bought Hinge Premium and saw an exponential increase in matches. This could possibly be true for other men who feel online dating doesn't offer them the same benefits as women.  

## 📝 Data Collection and Analysis Process
Hinge lets users export their Hinge data. I crowdsourced this data from 4 male and 4 female friends.  
The files arrived in `.json` format, which I then processed using pandas.  
I analyzed:
- The number of likes sent  
- The number of likes received  
- Matches from both  
- Count of conversations  
- Count of dates  

## 🎨 New Skills Acquired
- Learned how to use Adobe Illustrator better, specifically resizing and creating Sankey charts that are responsive.  
- Learned how to clean JSON data in pandas.  

## 🔍 Scope for Further Research
- **Sentiment/word analysis:** Since the data export includes messages sent by the user, I could have performed a word analysis to examine common openers. However, this was personal data that belonged to my friends, and I chose not to look at their messages.  
- **Time-based analysis:** Analyzing the hours during which users sent the most likes to see if there is a trend.  
