# 🎬 Movie Data Sentiment Analysis

## 📌 Project Overview
This project analyzes movie data by scraping reviews, ratings, and key attributes from **IMDb**. The data is then cleaned, processed, and visualized using **Power BI** to identify trends in **genre popularity, audience sentiment, and revenue correlation**.

## 🚀 Key Features
- **Web Scraping**: Extracts IMDb movie ratings, genres, and reviews using **BeautifulSoup & Selenium**.
- **Data Cleaning & Processing**: Handles missing values, normalizes ratings, and prepares structured datasets.
- **Data Visualization**:
  - **Power BI Dashboard**: Interactive filters and charts for deep data analysis.
  - **Matplotlib & Seaborn**: Used for initial exploratory analysis.
- **Insights Generation**: Analyzes **rating distributions, genre popularity, and sentiment trends**.

## 🔧 Tech Stack
| Technology | Purpose |
|------------|---------|
| **BeautifulSoup** | Web scraping for static content |
| **Selenium** | Extracting JavaScript-rendered content |
| **Pandas** | Data cleaning and transformation |
| **Matplotlib & Seaborn** | Initial data visualization |
| **Power BI** | Interactive dashboard for insights |

## 📊 Power BI Dashboard Highlights
- **Total Movies**: 3,540
- **Key Metrics**: Budget, Gross Earnings, Likes, Reviews
- **Visualizations**:
  - **Genre-wise IMDb Ratings** (Bar Chart)
  - **Language-wise Ratings** (Pie Chart)
  - **Director-wise IMDb Ratings** (Treemap)
  - **Budget vs Gross Earnings** (Scatter Plot)
- **Filters for deep exploration** (Year, Country, Content Rating, etc.)

## 🎯 Insights
- **Drama & Crime** movies have higher IMDb ratings compared to Comedy.
- **Italian & French** movies tend to receive higher ratings.
- **Big-budget movies generally perform well**, but some low-budget movies achieve high ratings.
- **Martin Scorsese & Steven Spielberg** are among the top-rated directors.

## 🛠 Challenges & Solutions
### **1. Handling JavaScript-Rendered Content in IMDb**
**Problem:** BeautifulSoup could not extract dynamically loaded ratings & reviews.
**Solution:** Used Selenium to **load & interact** with the webpage before parsing it with BeautifulSoup.

### **2. Optimizing Scraping to Avoid IP Blocking**
**Problem:** IMDb blocked repeated requests.
**Solution:** Implemented **rotating user agents & random delays** to mimic human behavior.

## 👨‍💻 Contribution
- **Developed Web Scraper** using **Selenium & BeautifulSoup**.
- **Cleaned & Processed Data** using **Pandas**.
- **Designed Power BI Dashboard** with interactive filters.
- **Performed Sentiment & Trend Analysis**.

## 📂 Project Structure
```
Movie-Data-Sentiment-Analysis/
│-- data/              # Raw and cleaned datasets
│-- notebooks/         # Jupyter notebooks for initial analysis
│-- scripts/           # Web scraping scripts
│-- dashboard/         # Power BI .pbix file
│-- README.md          # Project documentation
```

## 🔥 Getting Started
### **1. Clone Repository**
```bash
git clone https://github.com/your-username/Movie-Data-Sentiment-Analysis.git
cd Movie-Data-Sentiment-Analysis
```
### **2. Install Dependencies**
```bash
pip install -r requirements.txt
```
### **3. Run Web Scraper**
```bash
python scripts/scraper.py
```
### **4. Open Power BI Dashboard**
Load `dashboard/Movie Data Sentiment Analysis.pbix` in Power BI.

## 📌 Future Improvements
- **Deploy an interactive web app** using **Streamlit or Flask**.
- **Expand dataset** by scraping additional platforms (Rotten Tomatoes, TMDb).
- **Perform deeper NLP-based sentiment analysis**.

## 📜 License
This project is open-source and available under the **MIT License**.

---
### ⭐ Feel free to fork, star, and contribute!
