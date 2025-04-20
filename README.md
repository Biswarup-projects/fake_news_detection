# fake_news_detection

#### 📂 Dataset Overview

The dataset used for this project is a labeled collection of news articles consisting of two main components:

- **Title**: The headline of the news article  
- **Text**: The main body/content of the news article  
- **Label**: The target variable, where:
  - `1` indicates **fake news**
  - `0` indicates **real news**

#### 🔢 Dataset Summary:
- Format: CSV (`fake news.csv`)
- Total rows: ~20,800+
- Features: `id`, `title`, `author`, `text`, `label`
- Missing values: Present in some `author` and `title` fields

> The dataset offers a strong foundation to train a model that learns patterns in linguistic features distinguishing fake and real news.
