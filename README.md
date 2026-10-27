# Netflix Movies and TV Shows — Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset using Python. The objective is to explore Netflix's content library, identify trends, analyze content types, and understand patterns in movie and TV show releases.

## 🎯 Objectives

- Analyze the distribution of Movies and TV Shows.
- Explore release-year trends.
- Identify countries contributing Netflix content.
- Analyze popular genres.
- Examine missing values and duplicate records.
- Calculate movie duration statistics.
- Perform a statistical hypothesis test.
- Create visualizations to communicate key findings.

## 🛠️ Technologies Used

- **Python**
- **Pandas** — Data cleaning and analysis
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization
- **SciPy** — Statistical hypothesis testing
- **Jupyter Notebook** — Interactive analysis

## 📂 Project Structure

```text
CodeAlpha_EDA_Netflix/
│
├── CodeAlpha_Netflix_EDA.ipynb
├── netflix_titles.csv
├── README.md
│
└── charts/
    ├── content_type_distribution.png
    └── release_year_trend.png
```

## 📊 Analysis Performed

### 1. Data Inspection
- Examined dataset dimensions and column information.
- Reviewed data types and descriptive statistics.
- Checked unique values, missing values, and duplicates.

### 2. Content Type Analysis
- Compared the number of Movies and TV Shows.
- Calculated content-type percentages.
- Created a bar chart for content distribution.

### 3. Release-Year Analysis
- Examined content distribution across release years.
- Visualized release trends using a line chart.

### 4. Missing Values Analysis
- Identified missing values in dataset columns.
- Visualized missing-value counts.

### 5. Country and Genre Analysis
- Explored countries associated with Netflix titles.
- Analyzed frequently occurring genres.

### 6. Movie Duration Analysis
- Extracted movie duration in minutes.
- Calculated average and median movie duration.
- Used the Interquartile Range (IQR) method to investigate potential outliers.

### 7. Statistical Hypothesis Testing
- Used a binomial test to investigate whether the proportion of Movies in the dataset is greater than 50%.
- Interpreted the result using statistical significance.

## 📈 Visualizations

The project generates charts to help understand:

- Movie and TV Show distribution.
- Release-year trends.
- Missing-value distribution.
- Country-wise content counts.
- Genre distribution.

The saved charts are available in the `charts/` folder.

## 🔍 Key Findings

The notebook summarizes the following findings based on the dataset:

- Total number of titles.
- Most common content type.
- Release year with the highest number of titles.
- Most frequently occurring genre.
- Average movie duration.

Refer to the Jupyter Notebook for the actual calculated results and visualizations.

## ▶️ How to Run the Project

1. Clone or download this repository.
2. Install the required Python libraries.
3. Ensure `netflix_titles.csv` is in the project directory.
4. Open `CodeAlpha_Netflix_EDA.ipynb` in Jupyter Notebook.
5. Run the notebook cells from top to bottom.

Install the required libraries using:

```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
```

## 📚 Dataset

The project uses the Netflix Movies and TV Shows dataset. The CSV file is included in this repository.

## 👨‍💻 Author

**Kushal Kumar**

GitHub: [@CodebyKushal](https://github.com/CodebyKushal)

---

⭐ If you find this project useful, feel free to star the repository!
