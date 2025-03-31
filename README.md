# Movie-Review-Sentiment-Classification
1. Install Dependencies

Before running the code, ensure you have Python installed along with the required libraries. You can install them using:

pip install transformers datasets tensorflow scikit-learn numpy

2. Download the IMDb Dataset

The script automatically downloads the IMDb dataset using the datasets library:

from datasets import load_dataset
dataset = load_dataset("imdb", download_mode="force_redownload")

3. Run the Code

Save the script as sentiment_analysis.py and execute it:

python sentiment_analysis.py

4. Model Training and Evaluation

The script will:

Preprocess the IMDb dataset.

Train and evaluate three deep learning models:

LSTM

CNN-LSTM

BiGRU

Evaluate the DistilBERT model using a pre-trained transformer pipeline.

Display accuracy results for each model.

5. Sample Predictions

The script tests the trained models on custom sample reviews, printing sentiment predictions along with confidence scores.
