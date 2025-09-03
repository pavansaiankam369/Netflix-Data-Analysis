# Netflix Movies and TV Shows Analysis

[![Python Version](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![Pandas](https://img.shields.io/badge/Pandas-1.3.3-blue)](https://pandas.pydata.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.11.2-blue)](https://seaborn.pydata.org/)

## 🎬 About

This project provides an in-depth exploratory data analysis (EDA) of the Netflix dataset, which includes information on TV shows and movies available up to 2021. The analysis is conducted within a Jupyter Notebook (`NetflixAnalysis.ipynb`) and leverages Python libraries such as Pandas and Seaborn for data manipulation, cleaning, and visualization.

## 📊 Dataset

The dataset was sourced from Flixable, a third-party Netflix search engine, and is publicly available on [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows).

It features the following columns:

* `Show_Id`
* `Category` (Movie/TV Show)
* `Title`
* `Director`
* `Cast`
* `Country`
* `Release_Date`
* `Rating`
* `Duration`
* `Type` (Genre)
* `Description`

## 🔍 Key Analyses & Questions Answered

The notebook performs several data cleaning and analysis tasks to uncover insights from the dataset.

1.  **Data Cleaning & Preparation:**
    * Handling of duplicate entries.
    * Detection and visualization of null values using a heatmap.
    * Creation of new features (like `Year` from `Release_Date`) for better analysis.

2.  **Exploratory Analysis:**
    * What was the year with the most content releases?
    * What is the breakdown of movies vs. TV shows?
    * Who are the top 10 directors with the most content on Netflix?
    * What are the different content ratings available?
    * Which country has produced the most TV shows?
    * What is the maximum duration of a movie on the platform?

## ✨ Visualizations

The analysis includes several visualizations to represent the findings, such as the distribution of content releases over the years.



## 🚀 Getting Started

To run this analysis on your local machine, please follow the instructions below.

### Prerequisites

* Python 3.7 or higher
* pip (Python package installer)

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/pavansaiankam369/netflix-analysis.git](https://github.com/pavansaiankam369/netflix-analysis.git)
    cd netflix-analysis
    ```

2.  **Install the required libraries:**
    It is recommended to use a virtual environment.
    ```bash
    pip install -r requirements.txt
    ```
    *(Note: You would need to create a `requirements.txt` file containing `pandas`, `seaborn`, `matplotlib`, and `jupyter`)*

### Usage

1.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```

2.  Open the `NetflixAnalysis.ipynb` file and run the cells sequentially.

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements, please fork the repository and create a pull request, or open an issue with the tag "enhancement".

