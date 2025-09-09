# chat-moderation-bot
Sentiment analysis classification

This project was completed for 41079 - Computing Science Studio 2 at UTS. Adam C., Shifali L. and Fritzy J. S. were responsible for data preparation and model training.


## Installation
1. Clone repo
2. Create virtual env & install dependencies:
```
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
pip install -r requirements.txt
```
(Include a requirements.txt with libraries like torch, transformers, pandas, etc.)

## Preprocessing 
Run the preprocessing notebook to clean and prepare your datasets:
```
jupyter notebook notebooks/preprocessing.ipynb
```
## Training
Fine-tune the BERTweet model on your dataset:
```
jupyter notebook notebooks/training.ipynb
```
## Deployment 
Use the deployment notebook to start the chat moderation bot or make predictions:
```
jupyter notebook notebooks/deployment.ipynb
```
## Datasets 
new_train.csv: Training data for fine-tuning the model

new_test.csv: Testing data for evaluation

## Model 
Base Model: Pretrained BERTweet

Custom Weights: Fine-tuned on the dataset
