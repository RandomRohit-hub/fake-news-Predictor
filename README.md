# 🕵️‍♂️ Fake News Detector

This project is a **Fake News Detector** built using **Streamlit** and **Machine Learning** to classify news articles as *real* or *fake*.

## 🚀 Features
- 🔍 Detects fake news using a **Logistic Regression** model.
- 📑 Text preprocessing with **NLTK** (stemming, stopword removal).
- 📊 TF-IDF Vectorization for better text representation.
- 🎨 User-friendly **Streamlit** interface.

## 📦 Installation

Clone the repository and install the required dependencies:

```bash
# Clone the repository
git clone https://github.com/your-username/fake-news-detector.git
cd fake-news-detector

# Install dependencies
pip install -r requirements.txt
```

## ▶️ Usage
Run the Streamlit app:

```bash
streamlit run app.py
```

## 📁 Project Structure
```
├── app.py  # Main application file
├── train.csv  # Dataset used for training
├── requirements.txt  # Required dependencies
├── README.md  # Project documentation
```

## 📜 Dataset
The dataset used for this project can be found here: [Fake News Labeled Dataset](https://www.kaggle.com/datasets/noorsaeed/scam-detection-fake-news-labelled-dataset).
The model is trained on a dataset containing labeled fake and real news articles. Ensure `train.csv` is in the root directory before running the app.

## 🤖 Model
- **Preprocessing**: Text cleaning, stemming, and stopword removal.
- **Vectorization**: TF-IDF.
- **Classifier**: Logistic Regression.

## 🤝 Contributing
Feel free to fork this repository and submit pull requests.

## 📜 License
This project is licensed under the **MIT License**.

---

