# Fake News Classifier

**Overview**

This project aims to develop a robust text classification model capable of detecting fake news articles. Leveraging a pre-trained language model, this solution fine-tunes on a rich dataset of labeled news articles to achieve high accuracy. The project includes steps for training the model, evaluating it with an AUC curve, and deploying it on the Hugging Face Hub for easy access and integration.

**Dataset**

The dataset used for training the classifier can be downloaded from the following Kaggle link:
[Download Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)

This dataset comprises two types of articles: "Fake" and "Real," providing a balanced ground for training classification models.

**Model Training**

The model is based on a pre-trained language model, which is fine-tuned on the fake and real news dataset. The fine-tuning process adjusts the pre-trained model to better suit the specific nuances of news article language and the distinguishing features of fake versus real news.

**Prerequisites**

  1. Python 3.8+
  2. pip
  3. Access to a GPU (recommended for training speed)

This is my solution to fatima fellowship quick coding challenge

Task
The task was to train a text classification model to detect fake news articles!

Dataset
The dataset is the Fake and real news dataset form [Kaggle](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)

After training the model was also uploaded to [Huggingface](https://huggingface.co/yinde/fatimah_fake_news_bert) 
