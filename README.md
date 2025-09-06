# AI-Driven-Delay-Prediction-and-Optimization-for-Train-Scheduling
This project builds a deep learning regression model to predict arrival and departure delays of high-speed trains based on operational and environmental factors.

Project Overview
Uses a dataset of train operation records and weather data.
Predicts both arrival delays and departure delays.
Employs a deep learning approach (DNN with Keras/TensorFlow) for regression-based predictions.
Provides insights that can be applied to scheduling optimization, resource allocation, and passenger experience improvements.

Technologies Used
Python (Data preprocessing, model training, evaluation)
TensorFlow / Keras (Deep Neural Network)
Scikit-learn (Preprocessing, train/test split, scaling, label encoding)
Pandas & NumPy (Data manipulation and cleaning)

Dataset

The dataset is not included in this repository due to size limitations.
You can download it directly from the official source:

Download Dataset from Figshare

📌 Citation:
Xiangrui Meng, Qiangqiang Yuan, Yuankai Wu, Zhiwei Feng, Xianfeng Huang, & Ziyou Gao. (2021).
A high-speed railway network dataset from train operation records and weather data. Figshare. Dataset.
https://doi.org/10.6084/m9.figshare.15087882.v1

How to Run
Clone the repository:
git clone https://github.com/akalamj/Train-Delay-Prediction.git
cd Train-Delay-Prediction

Install dependencies:
pip install -r requirements.txt

Download the dataset from Figshare and place it in the project directory.

Open the Jupyter Notebook:

jupyter notebook train_delay_prediction.ipynb


Run the notebook to train and evaluate the model.
