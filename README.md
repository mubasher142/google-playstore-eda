📱 Google Play Store Apps – Exploratory Data Analysis (EDA)

An in-depth exploratory analysis of the Google Play Store dataset to uncover trends, patterns, and insights influencing app popularity, ratings, downloads, and user engagement. This project highlights key factors that contribute to app success on one of the world’s largest mobile platforms.

📌 Table of Contents

Project Overview

Dataset Description

Data Cleaning

Exploratory Data Analysis (EDA)

Data Visualization

Insights

Conclusion

How to Run

Requirements

📊 Project Overview

Objective:
To analyze Google Play Store apps and identify key factors influencing popularity, ratings, installs, price, and user engagement.

Scope:

Cleaning and preprocessing a dataset of 10,000+ apps

Examining category trends, ratings distribution, free vs paid apps, and content rating patterns

Creating visualizations to support findings

📁 Dataset Description

The dataset includes information on:

App category

Reviews & ratings

Installs/downloads

App size & price

Content rating

Free vs paid classification

Genres & other metadata

The dataset used is a cleaned version of the Google Play Store apps dataset.

🧹 Data Cleaning

Key preprocessing steps include:

Standardizing formats (size, installs, price)

Removing duplicates and invalid entries

Handling missing values

Converting categorical data into usable formats

🔍 Exploratory Data Analysis (EDA)

The analysis explores:

Category distribution and popularity

Free vs paid app comparison

Rating patterns and user engagement trends

Content rating breakdown

Top-performing categories by installs and reviews

📈 Data Visualization

Visualizations used include:

Bar charts for category distribution

Histograms for rating & install patterns

Boxplots for price and review analysis

Comparative graphs for free vs paid apps

(All visual outputs are available in the notebook.)

💡 Insights

Free apps dominate the Play Store in both count and total installs.

FAMILY and GAME categories lead in volume and downloads.

Most apps are rated 4.0+, indicating generally positive user satisfaction.

The majority of apps are rated “Everyone”, showing broad accessibility.

Paid apps represent a small portion of the market, with fewer installs but often higher individual ratings.

Proper data cleaning (duplicates, outliers) is crucial for reliable analysis.

🏁 Conclusion

This analysis highlights clear patterns in app development and user preferences on Google Play. Free, broad-audience apps—especially in FAMILY and GAME categories—dominate the ecosystem. High ratings correlate strongly with visibility and engagement.

This project provides a foundation for deeper insights and can be extended into predictive modeling or market strategy analysis for app developers.

▶ How to Run

Clone the repository:

git clone https://github.com/mubasher142/google-playstore-eda.git
cd google-playstore-eda


Install required libraries:

pip install pandas matplotlib seaborn


Open and run the notebook:

jupyter notebook

📦 Requirements

Python 3.x

Pandas

Matplotlib

Seaborn

👤 Author

Mubashir Rasool
