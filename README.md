# Google Play Store Analytics – Internship Project

## 📌 Project Overview

This project was developed as part of my internship training using the **Google Play Store dataset**.

The main objective of the project is to analyze Android applications and generate meaningful insights about app ratings, reviews, installs, categories, app types, revenue, and growth trends.

The internship tasks were implemented as analytical features and visualizations using the Google Play Store dataset provided during the training.

---

## 🎯 Project Objectives

- Analyze Google Play Store application data.
- Clean and preprocess the dataset.
- Handle missing values and duplicate applications.
- Convert installs, size, price, and other columns into usable formats.
- Analyze application categories and performance.
- Compare free and paid applications.
- Analyze ratings, reviews, installs, and revenue.
- Identify significant growth patterns.
- Create interactive and informative data visualizations.
- Apply task-specific filtering and time-based dashboard availability.

---

## 📂 Dataset

The project uses the following datasets:

- **Play Store Data.csv**
- **User Reviews.csv**

The datasets contain information such as:

- App name
- Category
- Rating
- Reviews
- Size
- Installs
- Type
- Price
- Content Rating
- Genres
- Last Updated
- Android Version
- User reviews and sentiment information

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Plotly
- Matplotlib
- Jupyter Notebook
- Data Cleaning
- Data Analysis
- Data Visualization

---

## 📊 Project Analytics

The project contains multiple analytical tasks and visualizations.

### 1. Data Cleaning and Preprocessing

The raw Google Play Store dataset was cleaned by:

- Removing duplicate applications.
- Handling missing values.
- Converting installs into numerical values.
- Converting app size into numerical values.
- Processing ratings and reviews.
- Preparing data for analysis and visualization.

### 2. App Category Analysis

Application categories were analyzed to understand:

- Category distribution
- App performance
- Ratings
- Reviews
- Installs

### 3. Install and Growth Analysis

Application installation data was analyzed to identify installation trends and growth patterns across application categories.

### 4. Free vs Paid Application Analysis

Free and paid applications were compared based on:

- Average installs
- Revenue
- Application category

The analysis helps identify differences in performance between free and paid applications.

### 5. Category Rating and Review Analysis

A grouped/dual-axis visualization was created to compare:

- Average application rating
- Total review count

The analysis focuses on the top application categories by installs and applies the required filtering conditions.

### 6. Interactive Visualizations

The project includes multiple visualizations such as:

- Bar charts
- Line charts
- Dual-axis charts
- Stacked area charts
- Bubble charts
- Choropleth maps

These visualizations make the analytical results easier to understand.

---

## ⏰ Time-Based Dashboard Features

Some internship tasks include specific dashboard availability requirements.

The corresponding visualizations include time-based visibility controls according to the requirements of the assigned tasks.

These controls ensure that task-specific visualizations are displayed only during their designated availability periods.

---

## 📁 Project Structure

```text
Google_Play_Store_Internship_Project/
│
├── Data/
│   ├── Play Store Data.csv
│   └── User Reviews.csv
│
├── Notebooks/
│   ├── bar_chart.ipynb
│   ├── bubble_chart.ipynb
│   ├── Choropleth_Map.ipynb
│   ├── dual_axis.ipynb
│   ├── line_chart.ipynb
│   ├── stacked_area_chart.ipynb
│   └── Dashboard.ipynb
│
└── README.md
```

---

## 🔍 Key Skills Demonstrated

- Data preprocessing and cleaning
- Exploratory data analysis (EDA)
- Pandas DataFrame operations
- Data filtering, grouping, and aggregation
- Handling missing values and duplicate records
- Feature creation and data transformation
- Statistical analysis of ratings, reviews, and installs
- Interactive data visualization using Plotly
- Dashboard development using Jupyter Notebook
- Working with real-world datasets
- Extracting meaningful insights from data

---

## 📈 Key Outcomes

The analysis of the Google Play Store dataset produced several useful insights:

- Identified categories with high application installations.
- Compared application ratings across different categories.
- Analyzed the relationship between ratings and review counts.
- Compared free and paid applications based on their performance.
- Identified categories with high user engagement through reviews and installs.
- Analyzed installation and growth trends over time.
- Used filtering and aggregation to identify important category-level patterns.
- Created interactive visualizations to communicate analytical findings effectively.
- Developed a consolidated dashboard containing the major project visualizations.

---

## 📊 Dashboard

A dedicated Jupyter Notebook dashboard was created to bring together the major visualizations from the internship tasks.

The dashboard includes:

- Key performance indicators
- Category-wise analysis
- Top categories by installations
- Category-wise average ratings
- Free vs paid application analysis
- Ratings vs reviews analysis
- Installs vs reviews analysis
- Category-wise review analysis
- Task-specific filtered analysis
- Dual-axis visualization comparing average ratings and total reviews

**Dashboard Notebook:** `Notebooks/Dashboard.ipynb`

---

## 📚 Notebooks

The project contains individual Jupyter Notebooks for the major visualizations:

| Notebook | Purpose |
|---|---|
| `bar_chart.ipynb` | Bar chart analysis |
| `bubble_chart.ipynb` | Bubble chart analysis |
| `Choropleth_Map.ipynb` | Choropleth map visualization |
| `dual_axis.ipynb` | Dual-axis visualization |
| `line_chart.ipynb` | Line chart analysis |
| `stacked_area_chart.ipynb` | Stacked area chart analysis |
| `Dashboard.ipynb` | Consolidated project dashboard |

---

## 🧰 Project Workflow

The project follows a structured data analytics workflow:

1. Load the datasets.
2. Inspect the dataset structure and data types.
3. Identify missing values and duplicate records.
4. Clean and preprocess the data.
5. Convert columns into analysis-ready formats.
6. Perform filtering and data transformation.
7. Group and aggregate the data.
8. Generate analytical insights.
9. Create interactive visualizations.
10. Combine major visualizations into a dashboard.
11. Test the notebooks and dashboard.
12. Document the completed project.

---

## 💻 How to Run the Project

### Requirements

Install the required Python libraries:

```bash
pip install pandas numpy plotly matplotlib jupyter
```

### Run the notebooks

1. Clone or download the repository.
2. Open the project directory.
3. Start Jupyter Notebook or JupyterLab.
4. Open the required notebook from the `Notebooks` folder.
5. Run the cells from top to bottom.

The datasets required by the notebooks are available in the `Data` folder.

---

## 📌 Key Insights

The project demonstrates several important analytical relationships within the Google Play Store dataset:

- Application categories differ significantly in installation levels.
- Review counts provide an indication of user engagement.
- Ratings can be compared across categories to identify highly rated application groups.
- Free applications represent a large portion of the available applications.
- Installs and reviews can be analyzed together to understand application popularity.
- Filtering and aggregation can reveal category-level patterns that are not immediately visible in the raw dataset.

---

## 🚀 Future Improvements

Possible future improvements include:

- Adding interactive category and application filters.
- Improving dashboard responsiveness and visual design.
- Adding more advanced KPI cards and summary statistics.
- Deploying the dashboard as an online interactive application.
- Adding automated data updates.
- Adding advanced predictive analytics and machine-learning models.
- Adding additional user-review sentiment analysis.

---

## 👨‍💻 Project Author

**Name:** Ranith Bollavathri  
**Domain:** Data Analytics / Data Science  
**Project:** Google Play Store Analytics – Internship Project

---

## 📌 Conclusion

This project applies data analytics and visualization techniques to the Google Play Store dataset provided during the internship.

The completed work demonstrates the complete analytics workflow, from data cleaning and preprocessing to filtering, aggregation, analysis, visualization, and dashboard-oriented reporting.

The project also demonstrates the ability to work with real-world datasets and communicate analytical findings through interactive visualizations.
