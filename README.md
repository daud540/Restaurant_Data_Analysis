# 🍽️ Zomato Restaurant Data Analysis

## 📌 Project Overview

This project explores and analyzes Zomato restaurant data using Python to uncover meaningful insights about restaurant ratings, customer preferences, voting patterns, pricing, and online ordering behavior.

The goal is to transform raw restaurant data into useful insights through data cleaning, exploratory data analysis (EDA), statistical summaries, and data visualization.

## 🎯 Project Objectives

- Analyze customer votes across different restaurant types.
- Understand table booking availability.
- Identify the most popular restaurants based on customer votes.
- Explore the relationship between restaurant ratings and votes.
- Calculate average ratings for different restaurant categories.
- Identify the most common restaurant types.
- Understand the distribution of restaurant ratings.
- Compare average restaurant costs.
- Analyze ratings for online and offline ordering.
- Examine online ordering availability across restaurant types.

## 🛠️ Technologies & Libraries Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation and cleaning |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Development environment |

## 📂 Project Structure

```text
Zomato-Restaurant-Data-Analysis/
│
├── Zomato_Restaurant_Analysis.ipynb
├── zomato_data.csv
└── README.md
```

## 📊 Analysis & Key Questions

The project investigates 10 important questions:

1. How many customer votes has each restaurant type received?
2. How many restaurants offer table booking?
3. Which five restaurants have the highest number of votes?
4. Is there a relationship between restaurant ratings and customer votes?
5. What is the average rating for each restaurant type?
6. Which restaurant type is most common in the dataset?
7. What ratings do restaurants most commonly receive?
8. Which restaurant type has the highest average cost for two people?
9. Which ordering mode, online or offline, receives better ratings?
10. Which restaurant types have more records without online ordering?

## 📈 Data Visualization

The project uses several visualization techniques to understand the dataset:

- **Pie Chart:** Table booking distribution.
- **Bar Chart:** Top five restaurants based on customer votes.
- **Scatter Plot:** Relationship between restaurant ratings and votes.
- **Count Plot:** Distribution of restaurant types.
- **Histogram:** Distribution of restaurant ratings.
- **Box Plot:** Comparison of ratings for online and offline orders.
- **Heatmap:** Online ordering availability by restaurant type.

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Zomato-Restaurant-Data-Analysis.git
```

### 2. Navigate to the Project Folder

```bash
cd Zomato-Restaurant-Data-Analysis
```

### 3. Install Required Libraries

```bash
pip install pandas matplotlib seaborn jupyter
```

### 4. Add the Dataset

Place `zomato_data.csv` in the project directory.

Update the CSV file path in the notebook if necessary:

```python
df = pd.read_csv('zomato_data.csv')
```

### 5. Run Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook and run the cells to reproduce the analysis.

## 💡 Skills Demonstrated

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Data Aggregation and Grouping
- Handling Missing Values
- Duplicate Data Detection
- Statistical Analysis
- Data Visualization
- Business Insights and Interpretation

## 🚀 Future Improvements

- Build an interactive dashboard using Power BI or Tableau.
- Perform deeper statistical analysis.
- Explore geographical restaurant distribution if location data is available.
- Develop a machine learning model to predict restaurant ratings.
- Create an interactive web application using Streamlit.

## 👨‍💻 Author

**Daud**

Aspiring Data Scientist | Python | Data Analysis | Machine Learning

---

⭐ If you find this project useful, consider giving the repository a star!

**Note:** This project is intended for educational purposes and exploratory data analysis. The dataset and notebook results should be interpreted within the limitations of the available data.
