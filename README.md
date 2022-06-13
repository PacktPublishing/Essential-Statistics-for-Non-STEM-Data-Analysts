# Essential Statistics for Non-STEM Data Analysts

<a href="https://www.packtpub.com/product/essential-statistics-for-non-stem-data-analysts/9781838984847"><img src="https://static.packt-cdn.com/products/9781838984847/cover/smaller" alt="Essential Statistics for Non-STEM Data Analysts" height="256px" align="right"></a>

This is the code repository for [Essential Statistics for Non-STEM Data Analysts](https://www.packtpub.com/product/essential-statistics-for-non-stem-data-analysts/9781838984847), published by Packt.

**Get to grips with the statistics and math knowledge needed to enter the world of data science with Python**

**Errata**
Page 13
section "Data Imputation"

It lookss like as follows:
    df2[columnName] = df2[columnName].apply(replace-question_mark)
 
It should look like as follows: 
    df2[columnName] = df2[columnName].apply(replace_question_mark)

## What is this book about?
Statistics remain the backbone of modern analysis tasks, helping you to interpret the results produced by data science pipelines. This book is a detailed guide covering the math and various statistical methods required for undertaking data science tasks.

This book covers the following exciting features: 
* Find out how to grab and load data into an analysis environment
* Perform descriptive analysis to extract meaningful summaries from data
* Discover probability, parameter estimation, hypothesis tests, and experiment design best practices
* Get to grips with resampling and bootstrapping in Python
* Delve into statistical tests with variance analysis, time series analysis, and A/B test examples

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1838984844) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>


## Instructions and Navigations
All of the code is organized into folders. For example, Chapter02.

The code will look like the following:
```
import pandas as pd 
df = pd.read_excel("PopulationEstimates.xls",skiprows=2) 
df.head(8)  margin: 0
```

**Following is what you need for this book:**
This book is an entry-level guide for data science enthusiasts, data analysts, and anyone starting out in the field of data science and looking to learn the essential statistical concepts with the help of simple explanations and examples. If you’re a developer or student with a non-mathematical background, you’ll find this book useful. Working knowledge of the Python programming language is required.

With the following software and hardware list you can run all code files present in the book (Chapter 1-13).

### Software and Hardware List

| Chapter  | Software required                   | OS required                        |
| -------- | ------------------------------------| -----------------------------------|
| 1        | Google Colab or Jupyter Notebook                  | Windows, Mac OS X, and Linux (Any) |



We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://static.packt-cdn.com/downloads/9781838984847_ColorImages.pdf).


### Related products <Other books you may enjoy>
* Practical Data Analysis Using Jupyter Notebook [[Packt]](https://www.packtpub.com/product/practical-data-analysis-using-jupyter-notebook/9781838826031) [[Amazon]](https://www.amazon.com/dp/1838826033)

* Hands-On Mathematics for Deep Learning [[Packt]](https://www.packtpub.com/product/hands-on-mathematics-for-deep-learning/9781838647292) [[Amazon]](https://www.amazon.com/dp/1838647295)

## Get to Know the Author(s)
**Rongpeng Li**
is a data science instructor and a senior data scientist at Galvanize, Inc. He has previously been a research programmer at Information Sciences Institute, working on knowledge graphs and artificial intelligence. He has also been the host and organizer of the Data Analysis Workshop Designed for Non-STEM Busy Professionals at LA.


### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSdy7dATC6QmEL81FIUuymZ0Wy9vH1jHkvpY57OiMeKGqib_Ow/viewform) if you have any feedback or suggestions.
