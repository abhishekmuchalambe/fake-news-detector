Ever wondered if someone is using your username across different platforms? 🤔  I built a solution! 🕵️‍♂️

# 📰 Fake News Detector

A Machine Learning + NLP application that classifies news articles as **Real** or **Fake** in real-time. Built with Python, scikit-learn, and Streamlit for an interactive interface.

![Python](https://img.shields.io/badge/python-v3.8+-blue.svg)
![Streamlit](https://img.shields.io/badge/streamlit-v1.24+-orange.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

## ✨ Features

### 🔍 **Real-Time Predictions**
- **Instant Classification**: Input a news headline or full article to get immediate results
- **Interactive UI**: Built with Streamlit for a seamless experience
- **High Accuracy**: Over 92% on test data
- **Clean Preprocessing**: Removes stopwords, punctuation, and applies stemming

### 📊 **Model Details**
- **Algorithms**: Logistic Regression & PassiveAggressiveClassifier
- **Feature Extraction**: TF-IDF vectorization
- **Saved Models**: Trained models saved for faster predictions
- **Reproducible Results**: Can retrain on updated datasets easily

---

## 🚀 Quick Start

### Prerequisites
- Python 3.8 or higher
- pip (Python package installer)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/YOUR-USERNAME/fake-news-detector.git
cd fake-news-detector
````

2. **Create a virtual environment**

```bash
python -m venv .venv
```

3. **Activate the virtual environment**

Windows:

```bash
.venv\Scripts\activate
```

macOS/Linux:

```bash
source .venv/bin/activate
```

4. **Install dependencies**

```bash
pip install -r requirements.txt
```

5. **Download the dataset**

* [Kaggle Fake News Dataset](https://www.kaggle.com/c/fake-news/data) → `train.csv`
* Place it inside the `data/` folder

6. **Train the model**

```bash
python train.py
```

7. **Run the Streamlit app**

```bash
streamlit run app.py
```

8. **Open your browser**
   Navigate to the URL shown in the terminal (usually `http://localhost:8501`)

---

## 🎯 How to Use

1. **Enter News Text**: Type or paste a news headline/article
2. **Click Predict**: Get instant prediction
3. **View Result**: Displays **Real** or **Fake** classification
4. **Optional**: Retrain model with updated data if needed

---

## 🔧 Technical Details

### Architecture

* **Backend**: Python
* **Frontend**: Streamlit
* **Model**: PassiveAggressiveClassifier + Logistic Regression
* **Feature Extraction**: TF-IDF
* **Data Preprocessing**: NLTK stopwords removal, stemming, text cleaning

### Key Files

* `train.py` – Training and saving models
* `app.py` – Streamlit interface
* `models/` – Saved trained model and vectorizer
* `data/train.csv` – Dataset file
* `requirements.txt` – Dependencies

---

## 📦 Dependencies

```
pandas
numpy
scikit-learn
nltk
joblib
streamlit
```

---

## 📸 Screenshots

### Main Interface

![Main Interface](https://via.placeholder.com/800x400?text=Fake+News+Detector+Interface)

### Prediction Example

![Prediction Example](https://via.placeholder.com/800x400?text=Real+or+Fake+Result)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Abhishek Muchalambe**

* GitHub: [@AbhishekMuchalambe](https://github.com/YOUR-USERNAME)

---

## 🙏 Acknowledgments

*Dataset: Kaggle Fake News Challenge
 – for providing the labeled dataset used to train the model.

*Libraries & Tools:

*Python
 – programming language

*scikit-learn
 – machine learning algorithms

*NLTK
 – text preprocessing

*Streamlit
 – interactive web app interface

*Tutorials & Guides: Online ML/NLP tutorials that helped structure preprocessing, feature extraction, and model deployment.

*Open-Source Community: For guidance, sample projects, and inspiration in building ML-based applications

---

⭐ **Star this repository if you found it helpful!**

```

---



```
