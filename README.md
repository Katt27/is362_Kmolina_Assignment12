# 📚 NY Times Books API Project

This project demonstrates how to interact with the **New York Times Books API** to fetch data about best sellers and book reviews, transform it into pandas DataFrames, and export the results to CSV files.

## 📝 Assignment Overview

The objectives of this assignment were:
1. Fetch the latest **Best Sellers list** from the New York Times API (e.g., Hardcover Fiction).
2. Retrieve **book reviews** based on title, author, or ISBN.
3. Transform the JSON responses into pandas DataFrames.
4. Save the resulting data into **CSV files** for further use or analysis.

---

## 📦 Features

- Fetch the current best sellers list for a specific category (e.g., "Hardcover Fiction").
- Search and retrieve book reviews by:
  - **Title** (e.g., "Becoming"),
  - **Author** (e.g., "Michelle Obama"), or
  - **ISBN** (e.g., "9781524763138").
- Convert JSON API responses into structured tabular data using **pandas**.
- Export the data as CSV files for offline use.

---

## 🔧 Setup and Installation

### Prerequisites
- Python 3.x
- Libraries: `requests`, `pandas`
- An API Key from the [NYT Developer Portal](https://developer.nytimes.com/).

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/nyt-books-api.git
