📊 Reddit Smartphone Discussion Analysis

Welcome to the Reddit Smartphone Discussion Analysis project! 🚀 This project is designed to scrape, analyze, and visualize discussions about smartphones on Reddit. Whether you're a data enthusiast, a smartphone geek, or just curious about online discussions, this project provides valuable insights into trending topics and user sentiments. 📱✨

🔥 Features

✅ Reddit Data Scraping 🕵️‍♂️

Collects posts from popular subreddits such as smartphones, Android, iPhone, GooglePixel, and Samsung.

Uses praw to interact with Reddit's API efficiently.

✅ Text Preprocessing 🔍

Cleans and processes the text data.

Removes stopwords and irrelevant characters for better analysis.

✅ Topic Modeling with BERTopic 🤖

Identifies key topics from discussions.

Extracts keywords and trends from Reddit posts.

✅ Data Visualization 📊

Generates interactive bar charts and topic relationship graphs.

Helps understand key discussion points at a glance.

✅ Structured Output 📁

Saves analyzed topics and probabilities in a structured JSON format.

Makes it easy to further analyze or integrate the data elsewhere.

🛠 Requirements

Before running the project, install the required Python libraries:

pip install praw pandas numpy nltk bertopic

Make sure you have a Reddit API key for scraping data. 🔑

🚀 How to Use

Step 1: Scrape Reddit Data 📡

Run Data_retrieval.ipynb to collect posts and save them as a CSV file.

Step 2: Process and Analyze Data 🧠

Run main.ipynb to:

Load the scraped data 📥

Preprocess text ✍️

Perform topic modeling with BERTopic 🛠

Save structured results 📊

📂 Output Files

📜 reddit_smartphone_posts.csv - Contains raw Reddit post data.

📝 structured_topics.json - Stores analyzed topics, keywords, and probabilities.

📊 Visualizations - Graphs depicting topic distributions and relationships.

👨‍💻 Author

This project was created by Nikhil Bhandari. 🚀

If you find this project useful, feel free to ⭐ the repository and contribute! 🏆

