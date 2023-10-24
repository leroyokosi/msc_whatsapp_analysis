# msc_whatsapp_analysis
An analysis of the WhatsApp group for 2022–2023 MSc Data Science & Artificial Intelligence | University of Suffolk

# Introduction:
This repository contains code and documentation for analyzing WhatsApp data. This project provides insights into communication patterns, user behaviour, and sentiment analysis around lecturers and course modules.


# Data Source/Collection:
The data was extracted from the WhatsApp group using the 'export chat' option in the group settings.


# Data Preprocessing:
This step involves cleaning and structuring the data to make it suitable for analysis. Steps such as splitting the data into appropriate columns and formatting into a Pandas data frame, ensuring the data and time are in the right format, and also slicing off a portion of the user name, to conceal the identity, as phone numbers were shown in full for some users.


# Data Analysis:
Once the data was preprocessed, I performed various types of analysis, such as:
- Sentiment Analysis: Analyze the sentiment of messages to understand the emotional tone of the conversation around the entire group, the lecturers, and some course modules. I used the VADER pre-trained sentiment analyzer in the provided code.

- Word Frequency Analysis: Find the most commonly used words in your chat history.

- Active users: Explored the group to find active users, months, and the most active time of the day in the group.


# Visualization:
Matplotlib and Seaborn were used for visualizing data to understand trends better. All data frames were exported for further visualization on PowerBI.
