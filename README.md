# 🌍 Language Detection using Machine Learning

A Machine Learning-based Language Detection System that identifies the language of a given text sentence. The model is trained on multilingual text data and can predict the language of user-provided input with high accuracy.

## 🚀 Features

- Detects the language of a text sentence.
- Built using Natural Language Processing (NLP).
- Text vectorization using CountVectorizer.
- Language encoding using LabelEncoder.
- Classification using Multinomial Naive Bayes.
- Fast and lightweight prediction system.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- CountVectorizer
- Multinomial Naive Bayes

## 📂 Project Workflow

1. Load and analyze dataset.
2. Perform data preprocessing.
3. Convert text into numerical vectors using CountVectorizer.
4. Encode language labels using LabelEncoder.
5. Split data into training and testing sets.
6. Train the model using Multinomial Naive Bayes.
7. Evaluate model accuracy.
8. Predict language from custom user input.

## 📊 Model Pipeline

Text Input
↓
CountVectorizer
↓
Multinomial Naive Bayes
↓
Language Prediction

## 📈 Performance

The model achieved approximately **95% accuracy** on the test dataset.

> Note: Accuracy may vary depending on dataset quality, size, and class distribution.

## 💻 Example

Input:

```text
Me llamo Sanyam
```

Output:

```text
Spanish
```

Input:

```text
How are you?
```

Output:

```text
English
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/sanyamjain-2006/language-detection-ml.git
```

Navigate to the project folder:

```bash
cd language-detection-ml
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the project:

```bash
python language_detector.py
```

## 📁 Project Structure

```text
Language-Detection/
│
├── language.csv
├── language_detector.py
├── README.md
└── requirements.txt
```

## 🔮 Future Improvements

- Web application using Flask.
- Streamlit deployment.
- Character-level TF-IDF vectorization.
- Support for more languages.
- Deep Learning-based language detection.

## 👨‍💻 Author

Sanyam Jain

B.Tech Student | Machine Learning Enthusiast | AI Engineer Aspirant

## ⭐ Support

If you found this project useful, consider giving it a star on GitHub.
