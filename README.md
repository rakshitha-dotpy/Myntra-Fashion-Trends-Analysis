<p align="center">
  <img src="myntra_logo.png.webp" width="160">
</p>

<h1 align="center">Myntra Fashion Trends Analysis</h1>

<p align="center">
Data analysis of 14,330 fashion products using Python, Pandas and Matplotlib
</p>

---

## Project Overview

This project explores a Myntra fashion products dataset to understand pricing patterns, brand representation, and customer rating trends.

The goal was to perform exploratory data analysis (EDA) on real-world e-commerce data and extract meaningful business insights through data cleaning, aggregation, and visualization.

---

## Dataset Summary

| Metric | Value |
|----------|----------|
| Products | 14,330 |
| Features | 11 |
| Domain | Fashion E-Commerce |
| Tools | Python, Pandas, Matplotlib |

---

## Objectives

- Analyze product pricing patterns
- Identify the most represented brands
- Examine customer rating distribution
- Compare premium brands based on average pricing

---

## Data Preparation

Before analysis, the dataset was cleaned and validated.

Steps included:

- Removing unnecessary index columns
- Checking missing values
- Handling incomplete records
- Verifying column data types
- Preparing data for visualization

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Top Brands

Roadster was the most represented brand in the dataset, followed by Tokyo Talkies and MANGO.

<p align="center">
  <img src="top_brands.png.jpeg" width="850">
</p>

---

## Product Price Distribution

Most products fall within lower and mid-range price categories, while a smaller set of premium products extends the distribution.

<p align="center">
  <img src="price_distribution.png.jpeg" width="850">
</p>

---

## Rating Distribution

Customer ratings are heavily concentrated between 4.0 and 4.5, indicating generally positive product feedback.

<p align="center">
  <img src="rating_distribution.png.jpeg" width="850">
</p>

---

## Highest Priced Brands

Brands with the highest average product prices:

| Brand | Average Price (₹) |
|---------|---------:|
| MOKSHA DESIGNS | 24,865 |
| SAPTRANGI | 22,499 |
| Masaba | 20,888 |
| Teakwood Leathers | 19,999 |
| NAKKASHI | 17,537 |

<p align="center">
  <img src="expensive_brands.png.jpeg" width="850">
</p>

---

## Key Findings

- Roadster had the highest number of listed products.
- Average product price was approximately ₹2,964.
- Most products were priced below ₹5,000.
- Ratings were concentrated in the 4.0–4.5 range.
- Premium brands showed significantly higher average pricing compared to the overall dataset.

---

## Future Scope

Possible extensions include:

- Interactive dashboard development using Streamlit
- Product recommendation system
- Sentiment analysis on customer reviews
- Machine learning based trend prediction

---

## Repository Structure

```text
Myntra-Fashion-Trends-Analysis
│
├── README.md
├── myntra_analysis.ipynb
├── myntra_analysis.html
├── top_brands.png.jpeg
├── price_distribution.png.jpeg
├── rating_distribution.png.jpeg
├── myntra_logo.png.webp
└── expensive_brands.png.jpeg
```

---

## Running the Project

Install dependencies:

```bash
pip install pandas numpy matplotlib
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
myntra_analysis.ipynb
```

and run all cells.
