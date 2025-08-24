# 📊 YouTube Channel Analysis

This project demonstrates how to use the **YouTube Data API v3** to extract, analyze, and visualize YouTube channel and video statistics.  
It is a complete end-to-end data project built in **Python** and **Jupyter Notebook**, showcasing how to work with APIs, clean and process data, and build meaningful insights with visualizations.

---

## 🌟 Highlights
- 🔑 **API Integration** → Connects directly to the YouTube Data API with an API key (no OAuth flow needed).  
- 📈 **Channel Analytics** → Collects subscribers, views, and video counts for multiple creators.  
- 🎥 **Video Statistics** → Extracts views, likes, and comments for videos in batches.  
- 🧹 **Data Processing** → Cleans raw data into pandas DataFrames for easy analysis.  
- 📊 **Visualization** → Compares channels side by side with clear, well-formatted bar charts.  
- 🛡 **Error Handling** → Includes batching (50 IDs per request), retries, and fixes for common API errors.  

---

## 🚀 Project Overview
The aim of this project is to compare YouTube creators (e.g., Ken Jee, Luke Barousse, Alex The Analyst, Tina Huang, etc.) by:
1. Collecting their channel and video-level data.
2. Analyzing key metrics like subscribers, total views, and engagement.
3. Visualizing results in a way that is easy to understand.  
---

## 🛠️ Tools & Libraries Used
- **Python 3.10+**
- **Conda** → environment management  
- **Jupyter Notebook** → interactive analysis  
- **google-api-python-client** → API calls  
- **pandas** → data wrangling  
- **matplotlib** → plots  
- **seaborn** → styled visualizations  

---

## 📦 Setup & Installation

Follow these steps to set up the project on your local machine:

### 1. Clone this repository
```bash
git clone https://github.com/yourusername/yt-analysis.git
cd yt-analysis
```

### 2. Create and activate a conda environment
```bash
conda create -n YT-env python=3.10
conda activate YT-env
```

### 3. Install dependencies
```bash
python -m pip install --upgrade pip
python -m pip install google-api-python-client pandas matplotlib seaborn jupyter
```

### 4. Setup Jupyter Notebook to use the environment
```bash
python -m pip install ipykernel
python -m ipykernel install --user --name=YT-env --display-name "Python (YT-env)"
```

### 5. Launch Jupyter Notebook
```bash
jupyter notebook
```

1. Open YT_Analysis.ipynb.
2. From the kernel dropdown, select Python (YT-env).
3. Run all cells.

### 🔑 API Key Setup
1. Go to Google Cloud Console
2. Enable YouTube Data API v3.
3. Generate an API key.

In the notebook, replace:
```bash
API_KEY = "YOUR_API_KEY"
```
---

## 🎯 Learning Outcomes

- How to work with REST APIs in Python.
- Handling API quotas and limits (batching 50 video IDs).
- Data cleaning with pandas.
- Visualization with matplotlib and seaborn.
- Structuring and documenting a project for GitHub.

---

## 📌 Future Improvements

- Add trend analysis (views over time).
- Build an interactive dashboard (Streamlit or Plotly Dash).
- Export cleaned data to CSV/Excel for BI tools.
- Add topic/category analysis of videos.
