# 🎥 Prince’s Movie Recommender

Unlock Your Next Favorite Film!  
Our NLP-powered Streamlit web app delivers tailored suggestions based on cast, genres, studios, and now:
- 🎨 **Custom Branding**: Your logo, page title & icon  
- ⏳ **Year Filter**: Pick any release-year range  
- 📊 **Top-10 Chart**: See most popular picks in your range  
- ⚡ **Instant Load**: Cached data for lightning speed  

---

## 🚀 Live Demo

[![Launch on Streamlit Cloud](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/PrinceObasi/Movie-Recommender-System/main.py)

---

## 🛠️ How It Works

1. Forked & enhanced from [AnupamMittal-21/Movie-Recommender-System](https://github.com/AnupamMittal-21/Movie-Recommender-System)  
2. Brand & layout tweaks in `main.py`  
3. Year-filter slider + Top-10 sidebar chart  
4. Cached I/O with `@st.cache_data` in `processing/display.py`  

---

## 📸 Screenshots

![Year Filter & Chart](assets/screenshots/filter_and_chart.png)  
![Custom Logo & Title](assets/screenshots/branding.png)  

---

## 📦 Installation & Run Locally

```bash
git clone https://github.com/PrinceObasi/Movie-Recommender-System.git
cd Movie-Recommender-System
pip install -r requirements.txt
streamlit run main.py

