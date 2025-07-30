
📱 Google Play Store App Data Analysis (Streamlit Dashboard)
Welcome to the Google Play Store App Data Analysis project!
This project dives deep into the app trends, categories, installs, ratings, and user behavior using the Google Play Store dataset. The interactive analysis is done with Streamlit, and visualizations are crafted using Matplotlib and Seaborn.

🔍 Project Overview
This project aims to analyze various characteristics of Google Play Store apps to derive meaningful business insights for developers, marketers, and app designers.

Objectives:

Identify top categories based on installs and ratings.

Analyze app size and pricing strategy trends.

Explore factors influencing app popularity.

Create an interactive EDA web app using Streamlit.

📦 Dataset Information
Feature Name	Description
App	Name of the app
Category	App category
Rating	Average rating
Reviews	Number of user reviews
Size	App size
Installs	Number of installs
Type	Free or Paid
Price	App price (0 for free)
Content Rating	Target audience age group
Genres	Sub-category or genre
Last Updated	Last update date
Current Ver	Current version
Android Ver	Minimum Android version required

🛠️ Tools & Technologies Used
Python (Pandas, NumPy) – Data Cleaning & Processing

Matplotlib, Seaborn – Data Visualization

Streamlit – Building the EDA Web App

GitHub Pages – Project Hosting

⚙️ Data Cleaning Steps
Converted size into numerical values (KB/MB handling)

Removed duplicates and invalid entries

Imputed missing values using median/mode strategy

Handled inconsistent formats in columns like Installs, Price, and Android Ver

Converted categorical data for visualization

📊 Key Visualizations
📊 Top 10 Categories by App Count

🔥 Top Categories by Total Installs (Billions)

⭐ Distribution of App Ratings

📥 Rating vs Installs Distribution

💰 Price Distribution in Paid Apps

🔎 KDE plots for Numerical Columns

📦 Interactive filters for categories and content rating

🚀 Streamlit App Features
Sidebar filters (Category, Content Rating, Type)

Interactive Bar Charts, Pie Charts, and KDE plots

Responsive layout with custom styling

Clean navigation and modern UI

👉 Launch Streamlit App (Add your deployed link here, e.g., Streamlit Share or GitHub Pages)
 
 
    
📷 Sample Visualizations
![image_alt]()

🤝 Credits
Dataset from Kaggle

Visualizations by Seaborn & Matplotlib

Streamlit App design inspired by modern dashboard UIs

