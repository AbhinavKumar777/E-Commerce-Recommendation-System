# Ecommerce Recommendation System

## 📌 Overview
This project implements an **Ecommerce Recommendation System** that suggests products based on user preferences. The system leverages **content-based filtering** and **rating-based recommendations** to enhance user experience.

## 📂 Project Structure
```
├── Data/
│   ├── dataset.tsv  # Product data
├── Ecommerce recommendation model.ipynb  # Main Jupyter Notebook
├── README.md  # Project documentation
```

## 📊 Dataset
- **Location:** `Data/dataset.csv`
- **Attributes:**
  - `Product Name`, `Brand`, `Category`, `Description`, `Ratings`, `Review Count`, `Tags`

## 🎯 Features
- 🔹 **Data Cleaning & Preprocessing**: Handles missing values and formats data appropriately.
- 🔹 **Exploratory Data Analysis (EDA)**: Visualizes user interactions and product popularity.
- 🔹 **Content-Based Filtering**: Uses **TF-IDF** and **cosine similarity** to recommend similar products.
- 🔹 **Rating-Based Recommendation**: Identifies top-rated products based on average ratings.

## 🚀 How to Use
1. Ensure `dataset.csv` is present in the `Data/` folder.
2. Open and run **Ecommerce recommendation model.ipynb** sequentially.
3. Input a product name to get **content-based recommendations**.
4. View **top-rated products** based on customer ratings.

## 🛠 Dependencies
Before running the notebook, install the required libraries:
```bash
pip install -r requirements.txt
```

## 📌 Output
- ✅ **Trending Products** based on ratings
- ✅ **Personalized Recommendations** using content similarity
- ✅ **Visual Insights** on product popularity and user interactions

## 📜 License
This project is intended for educational and research purposes only.

