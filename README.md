        *************** # Emotion-Detection-using-NLP ***************# Emotion Detection NLP 🚀

This project is a **text-based emotion classification system** built using **TF-IDF vectorization** and a **Random Forest Classifier**, deployed with **Flask** as a web application.

## 🎯 Objective

The goal is to classify input text into **emotions** represented as:
- `0`: Negative
- `1`: Neutral
- `2`: Positive

Users can enter any sentence, and the model will predict the corresponding emotion based on trained data.

---

## 🧠 Model Architecture

- **Vectorizer**: `TfidfVectorizer` (max 1000 features)
- **Classifier**: `RandomForestClassifier` with hyperparameter tuning
- **Framework**: Flask (for deployment)

---

## 📁 Project Structure

```bash
emotion-detection-nlp/
│
├── app.py                    # Flask backend
├── best_rf_model.pkl         # Trained model file
├── tfidf_vectorizer.pkl      # Saved TF-IDF vectorizer
├── templates/
│   └── index.html            # HTML UI for user input/output
├── static/                   # Optional: for CSS or JS files
│
└── README.md                 # Project documentation

I'm really disappointed with your service.
Predicted Emotion: 0 (Negative)
git clone https://github.com/your-username/emotion-detection-nlp.git
cd emotion-detection-nlp
Random Forest Classifier Accuracy: ~70%+
