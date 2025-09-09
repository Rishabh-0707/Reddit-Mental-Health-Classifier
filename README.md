# Reddit-Mental-Health-Classifier

📌 Project Overview-

This project analyzes and classifies mental health-related posts from Reddit using Logistic Regression and TF-IDF. The model categorizes posts into different mental health topics based on their content.

🛠 Features-

Data Cleaning & Preprocessing: Removes URLs, special characters, and HTML tags.

Text Classification: Uses Logistic Regression and TF-IDF Vectorization.

Data Visualization: Bar charts, pie charts, and confusion matrix for better insights.

Feature Importance Analysis: Identifies key words influencing classification.

📂 Dataset-

Dataset: Reddit Mental Health Data(kaggle)

Installation & Setup-

Run the following steps in Google Colab:
# Install Kaggle and upload kaggle.json
!pip install kaggle
from google.colab import files
files.upload()  # Upload kaggle.json

# Set up Kaggle authentication
!mkdir -p ~/.kaggle
!cp kaggle.json ~/.kaggle/
!chmod 600 ~/.kaggle/kaggle.json

# Download the dataset
!kaggle datasets download -d neelghoshal/reddit-mental-health-data -p /content/
!unzip /content/reddit-mental-health-data.zip -d /content/


How to Run-

Load and preprocess the dataset.

Train-test split the data.

Train a Logistic Regression model with TF-IDF.

Evaluate the model using accuracy, confusion matrix, and classification report.

Visualize class distributions and important features.

Visualizations-

Class Distribution (Bar Chart & Pie Chart)

Confusion Matrix

Top Words Influencing Predictions

📈 Model Performance-

Algorithm: Logistic Regression

Vectorization: TF-IDF (Term Frequency - Inverse Document Frequency)

Evaluation Metrics: Accuracy, Confusion Matrix, and Classification Report

🎯 Example Output-

Model Accuracy: 90.77


📌 Future Improvements-

Implement deep learning models (LSTM, BERT).

Explore other feature extraction techniques.

Improve text preprocessing with lemmatization and stopword removal.

Improving the accuracy by training it more to achieve more than 90% accuracy.

💡 Contributing-

Feel free to fork and improve the project. Suggestions and contributions are welcome! 😊

