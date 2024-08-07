# YouTube Spam Detection with Flask and Machine Learning

This is a web application built using Flask that detects spam comments on YouTube using a Naive Bayes classifier. It leverages techniques such as CountVectorizer for feature extraction and scikit-learn for machine learning. The application reads data from a CSV file and predicts whether a comment is spam or not.

## Installation and Run

1. **Clone the repository:**
   ```sh
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Create a virtual environment and activate it:**
   ```sh
   python -m venv venv
   venv\Scripts\activate
   ```

3. **Install the dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

4. **Run the application:**
   ```sh
   python app.py
   ```

## Project Structure

```
.
├── templates
│   └── home.html
├── app.py
├── YoutubeSpamMergedData.csv
├── requirements.txt
└── README.md
```

## Dependencies and Techniques Used

- **Flask:** Web framework for Python.
- **Pandas:** Data manipulation and analysis.
- **scikit-learn:** Machine learning library.
- **CountVectorizer:** Feature extraction technique.
- **Naive Bayes Classifier:** Machine learning algorithm.
- **joblib:** Serialization of Python objects.

For any queries, contact me at:
- **Email:** rayyanahmed265@yahoo.com
- **LinkedIn:** [Rayyan Ahmed](https://www.linkedin.com/in/rayyan-ahmed9477/)