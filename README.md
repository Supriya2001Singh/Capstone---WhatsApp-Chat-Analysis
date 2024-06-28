**WhatsApp Chat Analysis** This project aims to analyze a WhatsApp chat exported in .txt format to gain insights into the messaging behavior of a group or individual over time. The analysis includes visualizations and metrics covering message frequency, active users, message length, emoji usage, and temporal patterns.

Table of Contents Description Features Data Retrieval & Preprocessing Exploratory Data Analysis Total Messages Over Time Top 10 Most Active Days Top 10 Active Users Message Length Analysis Media Usage Emoji Analysis Temporal Patterns Heatmap Analysis WordCloud Analysis

**Description******

This project analyzes a WhatsApp chat log exported as a .txt file to uncover insights such as message frequency, active users, message length, emoji usage, and temporal patterns. By leveraging Python libraries like pandas, matplotlib, seaborn, and emoji, the project provides visualizations and statistical summaries to understand communication dynamics within the group.

**Features**

Data preprocessing to structure raw chat data into a pandas DataFrame. Visualizations include bar plots, line graphs, count plots, and heatmaps. Analysis of message frequency, active users, average message length, media usage, and emoji trends. WordCloud visualization to showcase the most used words in the chat. Insights into temporal patterns including most active days, hours, and months.

**Data Retrieval & Preprocessing**

To start the analysis, the WhatsApp chat .txt file was loaded into a pandas DataFrame. Messages were processed to extract timestamps, users, and message content, which were then used for further analysis.

**Exploratory Data Analysis**

**Total Messages Over Time** Visualizes the frequency of messages over months to identify trends in communication intensity.

![image](https://github.com/Supriya2001Singh/Capstone---WhatsApp-Chat-Analysis/assets/140324587/ccd44b89-28cc-4d11-92cf-598d2a127424)


**Top 10 Most Active Days** Identifies the days with the highest number of messages exchanged, providing insights into peak activity periods. 

![image](https://github.com/Supriya2001Singh/Capstone---WhatsApp-Chat-Analysis/assets/140324587/30c607f3-69fc-4300-89db-76e3bcaac2e2)


**Top 10 Active Users** Analyzes the participation of users based on the number of messages sent, highlighting the most active contributors.

![image](https://github.com/Supriya2001Singh/Capstone---WhatsApp-Chat-Analysis/assets/140324587/38f49eba-6f5a-4738-8a67-1c0dbd13f2ca)


**Message Length Analysis** Examines the average length of messages sent by top users, revealing communication styles and patterns. 

![image](https://github.com/Supriya2001Singh/Capstone---WhatsApp-Chat-Analysis/assets/140324587/887653bd-6515-47dd-ac71-167745685d51)


**Media Usage** Investigates the frequency of media sharing (images, videos) within the chat, identifying users who share media most frequently. 

![image](https://github.com/Supriya2001Singh/Capstone---WhatsApp-Chat-Analysis/assets/140324587/717a26b7-d535-4b61-9a11-c980d08c6db9)


**Emoji Analysis** Quantifies and visualizes the usage of emojis within the chat, revealing popular emoticons and expressions. 

![image](https://github.com/Supriya2001Singh/Capstone---WhatsApp-Chat-Analysis/assets/140324587/a3e60c21-5c55-42e4-b0f0-40ce99430e7e)


**Temporal Patterns** Analyzes message exchange patterns throughout the day to identify peak messaging hours. 

![image](https://github.com/Supriya2001Singh/Capstone---WhatsApp-Chat-Analysis/assets/140324587/a69c391b-34b3-4977-8e73-b733b7b85b6a)


**Heatmap Analysis** Combines day-wise and month-wise message counts into a heatmap to visualize communication patterns over different time frames. 

![image](https://github.com/Supriya2001Singh/Capstone---WhatsApp-Chat-Analysis/assets/140324587/d65b3bf1-7815-4450-8062-ae85035985c0)


**WordCloud Analysis** Generates a WordCloud to highlight the most frequently used words in the chat, excluding common stopwords.

![image](https://github.com/Supriya2001Singh/Capstone---WhatsApp-Chat-Analysis/assets/140324587/c774d247-850b-43d2-b8c6-3f6dd031776f)
