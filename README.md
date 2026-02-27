<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
</head>
<body>

<div class="container">

<h1>📰 Fake News Detection System</h1>

<h2>Project Overview</h2>
<p>
This project focuses on detecting whether a news article is <strong>Fake or Real</strong> 
using Machine Learning (Text Classification) techniques.
</p>
<ul>
    <li>TF-IDF Vectorization</li>
    <li>Logistic Regression</li>
    <li>Evaluation using Accuracy and F1 Score</li>
    <li>Detailed data analysis to understand fake news patterns</li>
</ul>

<h2>Objectives</h2>
<ul>
    <li>Classify news articles as Fake or Real</li>
    <li>Analyze patterns in fake news headlines</li>
    <li>Study growth trends of fake news</li>
    <li>Identify keywords associated with fake and real news</li>
    <li>Compare article characteristics (length, category, source)</li>
</ul>

<h2>Dataset</h2>
<p><strong>Dataset Used:</strong> fake_real_news.csv</p>
<ul>
    <li><strong>title</strong> – News headline</li>
    <li><strong>text</strong> – News content</li>
    <li><strong>date</strong> – Publication date</li>
    <li><strong>source</strong> – News source</li>
    <li><strong>subject</strong> – News category</li>
    <li><strong>label</strong> – 0 (Real), 1 (Fake)</li>
</ul>

<h2>Technologies Used</h2>
<ul>
    <li>Python</li>
    <li>Pandas</li>
    <li>NumPy</li>
    <li>Matplotlib</li>
    <li>Seaborn</li>
    <li>Scikit-learn</li>
</ul>

<h2>Model Implementation</h2>

<h3>1. Data Preprocessing</h3>
<ul>
    <li>Combined title and text into a single content column</li>
    <li>Converted date to datetime format</li>
    <li>Applied TF-IDF vectorization</li>
</ul>

<h3>2. Train-Test Split</h3>
<ul>
    <li>80% Training Data</li>
    <li>20% Testing Data</li>
</ul>

<h3>3. Model Used</h3>
<ul>
    <li>Logistic Regression</li>
</ul>

<h3>4. Evaluation Metrics</h3>
<ul>
    <li>Accuracy Score</li>
    <li>F1 Score</li>
</ul>

<h2>Analysis Questions Answered</h2>
<ol>
    <li>What are the most common words used in fake news headlines?</li>
    <li>Do fake headlines use more sensational words?</li>
    <li>What is the average number of news per day?</li>
    <li>What is the monthly and yearly growth rate of fake news?</li>
    <li>Which keywords are strongly associated with real news?</li>
    <li>Which keywords are strongly associated with fake news?</li>
    <li>Which source is predicted most fake?</li>
    <li>Are international news articles more likely to be fake?</li>
    <li>Which topic/category has the highest percentage of fake news?</li>
    <li>Does the length of a news article influence prediction?</li>
</ol>

<h2>Key Insights</h2>
<ul>
    <li>Fake news often contains sensational words like <em>breaking</em>, <em>shocking</em>, and <em>exclusive</em>.</li>
    <li>Certain categories show higher fake news ratios.</li>
    <li>Specific keywords strongly influence classification decisions.</li>
    <li>Article length can impact prediction outcomes.</li>
</ul>

</div>

</body>
</html>
