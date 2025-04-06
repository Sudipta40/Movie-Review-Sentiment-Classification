# Movie-Review-Sentiment-Classification

**Sentiment Analysis Comparison**
This repository contains code for comparing several deep learning models on the IMDB movie reviews sentiment analysis task. The models include:
LSTM
CNN-LSTM
BiGRU
DistilBERT (via Hugging Face Transformers)

**Overview**
The code demonstrates how to:
Load and preprocess the IMDB dataset.
Train and evaluate three neural network models (LSTM, CNN-LSTM, and BiGRU) using TensorFlow/Keras.
Use a pre-trained DistilBERT model for sentiment analysis via the Hugging Face Transformers library.
Visualize results with confusion matrices and print accuracy scores.
Test the models on a few sample reviews.

**Setup Instructions**

*Clone the Repository*
Clone this repository to your local machine:
git clone <repository_url>
cd <repository_directory>

*Create and Activate a Virtual Environment (Optional but Recommended)*
python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

*Install Dependencies*
Install all required Python packages using pip:
pip install datasets transformers tensorflow scikit-learn matplotlib seaborn
Note: The code uses TensorFlow 2.x and Hugging Face’s Transformers library.

*Download the IMDB Dataset*
The IMDB dataset will be downloaded automatically when running the code via the Hugging Face datasets library.

**Execution Instructions**

*Run the Script*
python main.py

The script will:
Preprocess the dataset.
Train the LSTM, CNN-LSTM, and BiGRU models.
Evaluate each model, displaying confusion matrices and accuracy scores.
Test the DistilBERT model on a subset of reviews.
Print a final comparison of the model accuracies.

*Viewing Visualizations*
The script generates plots for the confusion matrices using Matplotlib and Seaborn.

**Course Instructor Acknowledgment**
This project was developed as part of the coursework for Deep Learning. Special thanks to Md. Mynoddin for his guidance and support throughout the course.

