# **Topic-Emotion Approach to NLP-driven Research Using BERTopic and XLM-EMO**

## **Author**
Giuseppe Bonsignore

## **Description**
This repository contains the code used in my data science project titled "Analyzing Political Discourse on r/Politics: A Topic-Emotion Approach Using BERTopic and XLM-EMO." The study focuses on analyzing the topic distribution and emotional trends in the most upvoted comments from highly engaged posts on the r/Politics subreddit.

The study aims to leverage transformer-based models to gain insights into the emotional dynamics of political discussions, with potential applications in journalism, business intelligence, and opinion monitoring.

## **Features**

Data Collection: Uses the Python Reddit API Wrapper (PRAW) to fetch highly upvoted comments from top Reddit posts on a subreddit.

Topic Modeling: Implements BERTopic for clustering comments into meaningful topics.

Emotion Analysis: Implements XLM-EMO, a transformer-based model, to classify emotions into four categories (anger, joy, fear, sadness).

Visualization: Provides insights into topic distribution and emotional trends using data visualization and analyzing the statistical distribution of emotions across topics. 

## **Installation**

### **Prerequisites**

Ensure you have Python 3.8+ installed. The following Python packages are required:

pip install praw bertopic umap-learn hdbscan scikit-learn transformers pandas matplotlib seaborn

## **Usage**

1. Clone or Download the Repository

2. Create your Reddit API credentials: https://www.reddit.com/prefs/apps/

3. Modify reddit_scraper.ipynb in the notebooks directory as instructed in the comments, then run it.

4. Modify bertopic.ipynb in the notebooks directory as instructed in the comments, then run it.

5. Modify sentiment_analysis.ipynb in the notebooks directory as instructed in the comments, then run it.

For more details, read the paper in the dedicated directory of this repository. 

If you use this code or my paper in your research, please cite:

@article{bonsignore2025political,
  author    = {Giuseppe Bonsignore},
  title     = {Analyzing Political Discourse on r/Politics: A Topic-Emotion Approach Using BERTopic and XLM-EMO},
  year      = {2025},
  journal   = {Preprint},
  url       = {https://github.com/giuseppe-bonsignore/reddit-topic-modeling-and-emotion-analysis}
}

## **License**

This project is licensed under the MIT License - see LICENSE file for details.

## **Contact**

For questions or collaborations, feel free to reach out to giuseppe.bonsignore02@icatt.it
