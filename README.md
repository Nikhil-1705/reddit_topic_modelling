# 📌 Reddit Topic Modelling

## 📖 Overview
This project performs **topic modeling** on Reddit posts using **BERTopic**. It retrieves and processes data from Reddit, applies topic modeling, and visualizes key topics discussed within a subreddit. 🚀

## 🔧 Features
- ✅ **Data Retrieval**: Extracts posts and comments from Reddit 📥
- ✅ **Text Preprocessing**: Cleans and prepares text for analysis 🛠️
- ✅ **Topic Modelling**: Uses BERTopic to identify key discussion topics 🎯
- ✅ **Visualization**: Generates insightful visual representations of the extracted topics 📊
- ✅ **Labelling Docs**: Generates a well labelled Json file for your Docs file, segregating each document to its topic (example at the end)


## 📂 Project Structure
```
📁 Reddit Project
│-- 📜 README.md
│-- 📜 Data_retrieval.ipynb  # Fetches Reddit data using API
│-- 📜 main.ipynb            # Preprocessing & Topic Modeling
│-- 📁 data                  # Stores raw & processed data
│-- 📁 models                # Trained topic models
│-- 📁 visualizations        # Graphs and topic word clouds
```

## 🛠️ Setup & Installation
### 1️⃣ **Clone the Repository**
```sh
git clone https://github.com/Nikhil-1705/reddit_topic_modelling.git
cd reddit_topic_modelling
```
### 2️⃣ **Create a Virtual Environment**
```sh
python -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate     # Windows
```
### 3️⃣ **Install Dependencies**
```sh
pip install -r requirements.txt
```

## 🚀 How to Run the Project
1. **Run Data Retrieval Notebook** 📥
   ```sh
   jupyter notebook Data_retrieval.ipynb
   ```
2. **Run Topic Modeling Notebook** 🧠
   ```sh
   jupyter notebook main.ipynb
   ```

## 📊 Output Examples
- **Word Clouds** showing top words in topics 🌥️
- **Bar Charts** ranking most common topics 📊
- **Tables** listing top keywords per topic 📜

## 📝 Contributing
Contributions are welcome! Feel free to **fork** the repository, create a **new branch**, and submit a **pull request**. 🤝

## 📜 License
This project is licensed under the **MIT License**. 🔓

---
📩 **Developed by [Nikhil Bhandari](https://github.com/Nikhil-1705)** | 

![newplot](https://github.com/user-attachments/assets/c4d4d894-e5ed-4e00-98d7-a5ab7af56841)
![newplot1](https://github.com/user-attachments/assets/8d2e21d1-b382-46f2-b86a-98b63b5dac1d)
![newplot](https://github.com/user-attachments/assets/bdef4889-c877-4bcb-87bc-074b59c284a6)
![image](https://github.com/user-attachments/assets/4df28ce8-ea57-465c-940f-fb0c6f88ffdf)



