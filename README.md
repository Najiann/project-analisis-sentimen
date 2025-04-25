# 📊 Webtoon Review Sentiment Analysis - Indonesian Language

## 📌 Project Description
This project is an **automated sentiment analysis system** for user reviews of the Webtoon app on the Google Play Store. It uses web scraping and Natural Language Processing (NLP) to classify reviews into three categories: positive, neutral, or negative.

---

## ⚙️ Features
- 📥 Scrape reviews from Google Play Store (up to 15,000)
- 🧹 Text preprocessing (cleansing, slang normalization, stopword removal, stemming)
- 🏷️ Automatic sentiment labeling via keyword matching
- 🧠 Machine learning classifier training
- 📊 Usable scraped dataset (`webtoon_ripiu.csv`)

---

## 🧱 Folder Structure
```
project_anses_revisi_2/
│
├── pelatihan_model.ipynb     # Training notebook
├── scraping.ipynb            # Review scraping notebook
├── webtoon_ripiu.csv         # Scraped dataset
└── requirements.txt          # Dependency list
```

---

## 🧪 Installation & How to Run

### 1. Clone this repository
```bash
git clone https://github.com/yourname/project_anses_revisi_2.git
cd project_anses_revisi_2
```

### 2. (Optional) Activate virtual environment
```bash
python -m venv env
source env/bin/activate      # Linux/macOS
env\Scripts\activate         # Windows
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Open the notebook
Use Jupyter Notebook or Google Colab to open the `.ipynb` files.

---

## 💻 Usage Example
- Run `scraping.ipynb` to collect latest user reviews.
- Run `pelatihan_model.ipynb` to clean, label, and train sentiment classification model.

---

## ✅ Pros
- Full pipeline from scraping to classification
- Tailored for Indonesian language with slang and local terms
- Real-world dataset with over 10,000 entries

## ❌ Cons
- No web UI provided yet
- Labeling uses keywords, not supervised training
- Model isn't saved or deployed as `.pkl` or API
- No explicit train/test data split

---

## 🚀 Future Plans
- 🔧 Add web-based UI (Streamlit/Flask)
- 💾 Store model as `.pkl`
- 🔮 Add sentiment prediction feature for custom input
- 📈 Visualize model performance and sentiment distribution
