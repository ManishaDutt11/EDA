# 📊 EDA — Exploratory Data Analysis

A collection of exploratory data analysis (EDA) and feature engineering notebooks applied to real-world datasets, including flight pricing, wine quality, and Google Play Store data. This repo focuses on uncovering patterns, cleaning data, and preparing it for downstream machine learning tasks.

## 📁 Contents

| File | Description |
|---|---|
| [`flight_fe_and_eda.ipynb`](./flight_fe_and_eda.ipynb) | Exploratory data analysis and feature engineering on the flight price dataset — data cleaning, visualization, and feature extraction (e.g., from date/time columns). |
| [`flight_price (1).xlsx`](<./flight_price (1).xlsx>) | Raw flight price dataset used in the flight EDA notebook. |
| [`WineQT.xls`](./WineQT.xls) | Wine quality dataset used for exploratory analysis of physicochemical properties and quality ratings. |
| [`google_cleaned.xls`](./google_cleaned.xls) | Cleaned Google Play Store dataset, ready for exploratory analysis and visualization. |

## 🎯 Purpose

Exploratory Data Analysis is the foundation of any good data science project — understanding the shape, quality, and relationships within data before modeling. This repository documents my practice in:

- Cleaning and preprocessing raw datasets
- Handling missing values and inconsistent formats
- Extracting and engineering new features from raw columns
- Visualizing distributions and relationships between variables
- Drawing insights to guide further analysis or modeling

## 🛠️ Tech Stack

- **Python 3**
- **Jupyter Notebook**
- **Pandas**
- **NumPy**
- **Matplotlib / Seaborn**

## 🚀 Getting Started

### Prerequisites

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter openpyxl xlrd
```

### Running the notebooks

1. Clone the repository:
   ```bash
   git clone https://github.com/ManishaDutt11/EDA.git
   cd EDA
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Open [`flight_fe_and_eda.ipynb`](./flight_fe_and_eda.ipynb) (or any other notebook) and run the cells in order. Make sure the corresponding dataset file is in the same directory.

## 📈 Datasets Explored

- ✈️ **Flight Price** — analyzing airline ticket pricing trends and engineering features from raw booking data.
- 🍷 **Wine Quality (WineQT)** — exploring the relationship between chemical properties and wine quality scores.
- 📱 **Google Play Store** — examining app ratings, categories, and other store metadata.

## 🤝 Contributing

This is primarily a personal learning repository, but suggestions and improvements are always welcome! Feel free to open an issue or submit a pull request.

## 👩‍💻 Author

**Manisha Dutt**
GitHub: [@ManishaDutt11](https://github.com/ManishaDutt11)

---

⭐ If you find this helpful, consider starring the repo!
