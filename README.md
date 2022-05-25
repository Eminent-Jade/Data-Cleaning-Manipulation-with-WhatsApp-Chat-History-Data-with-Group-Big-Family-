# Data Cleaning & Text Data Manipulation with WhatsApp Chat with 'Big Family'

No original chat history provided for privacy reason

To showcase data manipulation and cleaning skills on whatsapp chat history containing chinese characters, with assistance of packages, wordclouds & jieba

### Therefore, BE OPEN-MINDED & OBJECTIVE with the contents while taking nothing personal.

## Can be applied to other chat history data with adjustments of several variables.

### !!!!!! There were bugs in WhatsApp chat history formatting, dates & message contents have been preprocessed by following steps,
#### - "replace" function in txt file, e.g. "1/1/2022" ➔ "01/01/2022"
#### - "replace" function in MS word (Ctrl+h), mainly replace ^p* (new line)  with * to combine msg contents

### Also, for privacy reasons, usernames(in both username columns & message content) have been sensored, e.g., 
#### - "+852 9169 9169" ➔ '+852 91** **69', 
#### - "Joe Biden" ➔ "Jo*  **den" & 
#### - "Vladimir Putin" ➔ "VladP."

Self-explanatory with table of content

## Content

1. Read & manage data
2. Extract dates, usernames & chat messages from data
!!. Further processing on usernames-code showcasing only, done beforehand
3. Create DataFrame for dates, usernames & chat messages
4. Data manipulation & Exploratory Analysis
4.1 Monthly message counts
4.2 Message frequencies by Hours & Day of the week respectively
4.2.1 Common keywords & their frequencies in corresponding chat messages & their rates of appearances
4.3 Message counts & word counts by month per user
4.3.1 Replace strings - '['<Media omitted>']' & '(file attached)' & create new column for word counts(message length)
4.3.2 Visualisations & comparison for "message count by month & user" & "word counts(message length) by month & user" respectively
4.3.3 Find correlations aong message counts, essage length (word counts) & Average words per message
4.3.4 Find correlation between common keywords & top 20% rank
