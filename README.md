# Fake News Detection System
## Project Overview
•	This project focuses on detecting whether a news article is Fake or Real using Machine Learning (Text Classification) techniques.
•	The model is built using:
•	TF-IDF Vectorization
•	Logistic Regression
•	Evaluation using Accuracy and F1 Score
•	The project also performs detailed data analysis to understand patterns in fake news.

---

 ## Objectives
•	Classify news articles as Fake or Real
•	Analyze patterns in fake news headlines
•	Study growth trends of fake news
•	Identify keywords strongly associated with fake and real news
•	Compare article characteristics (length, category, source, etc.)

---

## Dataset
•	Dataset used: fake_real_news.csv
•	Main columns:
•	title – News headline
•	text – News content
•	date – Publication date
•	source – News source
•	subject – News category
•	label – 0 (Real), 1 (Fake)

---

##Technologies Used
•	Python
•	Pandas
•	NumPy
•	Matplotlib
•	Seaborn
•	Scikit-learn

---

## Model Implementation
1.	Data Preprocessing
•	Combined title + text into a single content column
•	Converted date to datetime format
•	Applied TF-IDF vectorization

2.	Train-Test Split
•	80% Training Data
•	20% Testing Data

3.	Model Used
•	Logistic Regression

4.	Evaluation Metrics
•	Accuracy Score
•	F1 Score

---

## Analysis Questions Answered
1.	What are the most common words used in fake news headlines?
2.	Do fake headlines use more sensational words?
3.	What is the average number of news per day?
4.	What is the monthly and yearly growth rate of fake news?
5.	Which keywords are strongly associated with real news?
6.	Which keywords are strongly associated with fake news?
7.	Which source is predicted most fake?
8.	Are international news articles more likely to be fake?
9.	Which topic/category has the highest percentage of fake news?
10.	Does the length of a news article influence prediction?

---

## Key Insights
•	Fake news often contains sensational words like breaking, shocking, exclusive.
•	Certain categories have higher fake news ratios.
•	Some keywords strongly influence classification decisions.
•	Article length can impact prediction results.
