# Online Retail Data Analysis

## Project Overview

This project analyzes an Online Retail dataset to understand sales performance, customer behavior, product performance, and purchasing trends.

The analysis was performed using Python and Jupyter Notebook with data cleaning, exploratory data analysis, visualization, and business insights.

## Project Objectives

* Clean and prepare the retail dataset
* Analyze sales and transaction patterns
* Identify top-performing countries
* Identify the best sales month
* Analyze peak sales time
* Understand customer purchasing behavior
* Identify high-value customers
* Identify top-selling products
* Create visualizations to communicate business insights

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* Git & GitHub

## Project Structure

```text
Module-2-Online-Retail
│
├── data/
│   └── Online Retail (1).xlsx
│
├── notebooks/
│   └── Module_2.ipynb
│
├── screenshots/
│   ├── chart1.png
│   ├── chart2.png
│   └── ...
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Dataset

The project uses an Online Retail dataset containing transaction information such as:

* Invoice Number
* Product Description
* Quantity
* Invoice Date
* Unit Price
* Customer ID
* Country

## Analysis Performed

### Data Cleaning

* Checked missing values
* Removed invalid or unnecessary records
* Checked duplicate records
* Converted date columns into the appropriate format
* Created additional features required for analysis

### Exploratory Data Analysis

The project analyzes:

* Sales by country
* Monthly sales trends
* Sales by time of day
* Customer purchasing behavior
* High-value customers
* Top-selling products

### Business Insights

The analysis focuses on identifying:

* **Top Country:** Country generating the highest sales
* **Best Sales Month:** Month with the highest sales
* **Peak Sales Time:** Time period with the highest purchasing activity
* **High-Value Customers:** Customers contributing the most revenue
* **Top Products:** Products with the highest sales or quantity sold

## Visualizations

The project contains charts showing the major findings from the analysis.

The generated charts are available in the `screenshots/` folder.

## How to Run the Project
## Git Usage Commands

The following Git commands were used to maintain version control for this project.

### 1. Initialize Git Repository

```bash
git init
```

Creates a new local Git repository in the project folder.

### 2. Check Repository Status

```bash
git status
```

Shows modified, untracked, and staged files.

### 3. Add Files to Staging Area

```bash
git add .
```

Adds all project files to the staging area.

### 4. Create a Commit

```bash
git commit -m "Initial commit"
```

Creates a snapshot of the project with a meaningful commit message.

### 5. Rename Branch to Main

```bash
git branch -M main
```

Sets the main branch name to `main`.

### 6. Connect Local Repository to GitHub

```bash
git remote add origin <repository-link>
```

Connects the local Git repository to the GitHub repository.

### 7. Push Project to GitHub

```bash
git push -u origin main
```

Uploads the project files to the `main` branch on GitHub.

### 8. Future Updates

Whenever changes are made to the project:

```bash
git add .
git commit -m "Update project"
git push
```

These commands keep the GitHub repository updated with the latest version of the project.

1. Clone this repository.
2. Open the project in VS Code.
3. Install the required Python libraries:

```bash
pip install -r requirements.txt
```

4. Open the notebook:

```text
notebooks/Module_2.ipynb
```

5. Run the notebook cells to reproduce the analysis.

## Author

**Kathar Masthan A**

GitHub: https://github.com/katharmasthan997-pixel
