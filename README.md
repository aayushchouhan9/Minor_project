# 🛡️ TruthLens — AI Fake News Detector

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Enabled-success)
![NLP](https://img.shields.io/badge/NLP-TF--IDF-orange)
![Status](https://img.shields.io/badge/Project-Active-brightgreen)
![License](https://img.shields.io/badge/License-Educational-red)

An AI-powered Fake News Detection System that analyzes news headlines and articles to determine whether they are likely **Real** or **Fake** using Machine Learning.

This project combines a trained NLP model with a modern web-based interface to provide fast and interactive fake news detection.

---

# ✨ Features

- Detects fake and real news articles using Machine Learning
- Uses Natural Language Processing (NLP)
- Interactive and modern frontend UI
- Trained using real-world fake news datasets
- Lightweight and fast prediction system
- Exported model support for web integration
- Clean and responsive design

---

# 🛠️ Technologies Used

## Frontend
- HTML5
- CSS3
- JavaScript

## Backend / Machine Learning
- Python
- Scikit-learn
- Pandas
- NumPy
- Flask
- Joblib

## NLP Techniques
- TF-IDF Vectorization
- Passive Aggressive Classifier
- Text Preprocessing

---

# 📁 Project Structure

```bash
Minor Project/
│
├── fake_news_detector.html
├── train_model.py
├── model_weights.js
│
├── model/
│   └── model.pkl
│
├── data/
│   ├── Fake.csv
│   ├── True.csv
|
└── README.md
```

---

# 📊 Workflow Visualization

```text
+----------------+
|  User Input    |
| News Headline  |
+--------+-------+
         |
         v
+----------------+
| Text Cleaning  |
| NLP Processing |
+--------+-------+
         |
         v
+----------------+
| TF-IDF Feature |
| Vectorization  |
+--------+-------+
         |
         v
+----------------+
| ML Prediction  |
| Fake / Real    |
+--------+-------+
         |
         v
+----------------+
| Display Result |
+----------------+
```

---

# 🔍 Example Predictions

## Example 1

### Input News
> "Scientists discover a new planet capable of supporting human life."

### Prediction

```text
✅ REAL NEWS
Confidence: 91%
```

---

## Example 2

### Input News
> "Drinking hot water cures all diseases instantly."

### Prediction

```text
❌ FAKE NEWS
Confidence: 96%
```

---

# 📈 Model Accuracy Visualization

```text
Accuracy Comparison

Passive Aggressive Classifier  ████████████████████ 92%
Logistic Regression            ████████████████░░░ 85%
Naive Bayes                    ██████████████░░░░░ 80%
```

---

# ⚙️ Installation & Setup

## 1. Clone the Repository

```bash
git clone https://github.com/your-username/truthlens-fake-news-detector.git
cd truthlens-fake-news-detector
```

## 2. Install Dependencies

```bash
pip install pandas numpy scikit-learn flask flask-cors joblib newspaper3k
```

## 3. Add Dataset

Place the following files inside the `data/` folder:

- `Fake.csv`
- `True.csv`

## 4. Train the Model

```bash
python train_model.py
```

## 5. Run the Project

Open:

```bash
fake_news_detector.html
```

in your browser.

---

# 🤖 Machine Learning Model

## Passive Aggressive Classifier

Why this model?

- Fast training speed
- Good performance on text classification
- Works efficiently for large datasets
- Suitable for real-time prediction systems

---

# 🚀 Future Improvements

- Live news URL verification
- Deep Learning integration
- Real-time news API support
- Browser extension support
- Multi-language fake news detection
- User authentication system
- Accuracy improvement using transformers/BERT

---

# 📚 Learning Outcomes

Through this project, I learned:

- Machine Learning model training
- NLP preprocessing techniques
- Text classification methods
- Frontend and backend integration
- Dataset handling and model deployment
- Building AI-powered web applications

---

# 👩‍💻 Author

AAYUSHMAN CHOUHAN
SHREYANSH KASHYAP
GEETANSH PANDYA
AKSHAT GOUR

Minor Project — AI Fake News Detection System

---

# 📄 License

This project is for educational and academic purposes.
