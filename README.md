# 🍽️ Zomato Data Analysis Project

An Exploratory Data Analysis (EDA) project on Zomato's restaurant dataset to uncover dining trends, customer preferences, rating patterns, and ordering behaviour using Python.

---

## 📌 Project Overview

This project analyzes Zomato restaurant data to understand how different factors — such as restaurant type, ordering mode (online vs offline), cost, and ratings — relate to customer preferences and votes.

---

## 📂 Dataset

**File:** `Zomato data .csv`

| Column | Description |
|---|---|
| `name` | Name of the restaurant |
| `online_order` | Whether online ordering is available (Yes/No) |
| `book_table` | Whether table booking is available (Yes/No) |
| `rate` | Customer rating (e.g., 4.1/5) |
| `votes` | Total number of votes received |
| `approx_cost(for two people)` | Approximate cost for two people (in INR) |
| `listed_in(type)` | Type/category of the restaurant |

---

## 🔍 Analysis Performed

- **Data Loading & Cleaning** – Loading the dataset and cleaning the `rate` column (converting `4.1/5` → `4.1`)
- **Restaurant Type Distribution** – Count of restaurants across different listing categories
- **Votes by Restaurant Type** – Total votes received per restaurant type
- **Rating Distribution** – Histogram showing how ratings are spread across all restaurants
- **Couple Spending Analysis** – Most common approximate cost for two people
- **Online vs Offline Order Ratings** – Boxplot comparing ratings for online and offline orders
- **Heatmap Analysis** – Relationship between restaurant type and online ordering availability

---

## 📊 Key Insights

- **Dining** restaurants are the most common category on Zomato.
- **Dining** restaurants also receive the maximum number of votes from customers.
- Majority of restaurants have ratings between **3.5 and 4.0**.
- Most couples prefer restaurants with an approximate cost of **₹300 for two**.
- Restaurants accepting **online orders tend to receive higher ratings** compared to offline-only restaurants.
- The heatmap reveals that certain restaurant types heavily favour online ordering over offline.

---

## 🛠️ Tech Stack

- **Python 3**
- **Pandas** – Data loading and manipulation
- **NumPy** – Numerical operations
- **Matplotlib** – Static visualizations
- **Seaborn** – Statistical data visualizations
- **Google Colab** – Development environment

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/zomato-data-analysis.git
cd zomato-data-analysis
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Add the dataset
Place `Zomato data .csv` in the project root directory (or update the file path inside the notebook).

### 4. Run the notebook
```bash
jupyter notebook Zomato_Data_Analysis.ipynb
```

Or open it directly in [Google Colab](https://colab.research.google.com/).

---

## 📁 Project Structure

```
zomato-data-analysis/
│
├── Zomato_Data_Analysis.ipynb    # Main analysis notebook
├── Zomato data .csv              # Dataset (add manually)
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation
```

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
