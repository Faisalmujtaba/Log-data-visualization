ChatGPT Query History and WhatsApp Chat Analytics

Project Overview
This project performs Exploratory Data Analysis (EDA) on two different communication datasets:
ChatGPT Query History 
WhatsApp Chat Export 
The project extracts meaningful insights about user activity, communication behavior, query domains, messaging trends, participant engagement, and commonly used words through statistical analysis and data visualization.
It demonstrates how Python can be used for behavioral analytics, text mining, and communication pattern analysis.

Objectives
Analyze ChatGPT query history over time. 
Identify frequently explored knowledge domains. 
Examine WhatsApp communication patterns. 
Visualize participant activity. 
Analyze hourly and daily messaging behavior. 
Generate word clouds from conversations. 
Identify the most frequently used words. 
Perform exploratory data analysis using visualizations. 

Datasets
1. ChatGPT Query History
Contains:
Date & Time 
Query Domain 
User queries 

2. WhatsApp Chat Dataset
Contains:
Date 
Time 
Sender 
Message 
System-generated messages are automatically removed before analysis.


Features
ChatGPT Query Analysis
Query timeline analysis 
Query frequency by date 
Domain-wise query distribution 
Time-based activity analysis 

WhatsApp Chat Analysis
Message count per participant 
Hourly messaging activity 
Daily messaging trends 
Most active participants 
Most common words 
Word cloud generation 
Statistical summary tables 

Data Preprocessing
The preprocessing pipeline includes:
Loading CSV datasets 
Date and time conversion 
Timestamp generation 
Missing value handling 
Sender name cleaning 
Message cleaning 
Removal of WhatsApp system messages 
Feature engineering (hour, date) 

Exploratory Data Analysis (EDA)
ChatGPT Dataset
The project visualizes:
Number of queries over time 
Distribution of queries by domain 

WhatsApp Dataset
The project analyzes:
Messages sent by each participant 
Hourly messaging activity 
Daily message volume 
Frequently occurring words 
Communication trends 

Text Mining
The project performs basic NLP preprocessing by:
Removing URLs 
Removing special characters 
Removing stopwords 
Tokenizing text 
Counting word frequencies 
A Word Cloud is generated to highlight the most commonly used words.

Visualizations
The project generates:
Query count over time 
Domain distribution chart 
Messages by participant 
Hourly activity histogram 
Daily message trend line 
Word cloud 
Frequency tables 

Technologies Used
Python 
Pandas 
NumPy 
Matplotlib 
Seaborn 
WordCloud 
Regular Expressions (Regex) 
Collections (Counter) 

Output
The project produces:
ChatGPT Analytics
Query activity timeline 
Domain-wise query frequency 

WhatsApp Analytics
Participant ranking 
Hourly activity distribution 
Daily activity trend 
Word cloud 
Most common words 
Statistical summary tables 

Installation
pip install pandas
pip install matplotlib
pip install seaborn
pip install wordcloud
pip install numpy



Applications
This project can be applied to:
Communication analytics 
User behavior analysis 
Social media analytics 
Productivity tracking 
Personal analytics dashboards 
Conversation mining 
Text analytics 
Exploratory data analysis (EDA) 

Future Improvements
Perform sentiment analysis on ChatGPT queries and WhatsApp messages. 
Apply topic modeling (e.g., BERTopic or LDA) to identify discussion themes. 
Build an interactive dashboard using Streamlit, Dash, or Power BI. 
Add emoji usage analysis and conversation response-time analysis. 
Include network analysis to visualize communication relationships among participants. 
Integrate predictive analytics for activity forecasting. 

Learning Outcomes
This project demonstrates practical knowledge of:
Exploratory Data Analysis (EDA) 
Data Visualization 
Time-Series Analysis 
Text Mining 
Natural Language Processing (basic) 
Behavioral Analytics 
Communication Analytics 
Python Data Analysis 
Statistical Summarization 
