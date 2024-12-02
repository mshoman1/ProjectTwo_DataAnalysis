# Real-world Data Wrangling Project

## Project Overview
This project focuses on gathering, cleaning, analyzing, and visualizing real-world data from Netflix and Amazon Prime. The goal is to compare the content available on both platforms by examining genres, content types (movies vs. TV shows), and other relevant factors, such as ratings and release years. The cleaned and processed data will be used to answer key research questions about the platforms' content distribution.

## Dataset Information
The datasets used in this project contain information about the movies and TV shows available on **Netflix** and **Amazon Prime**. The data includes details such as:
- **Title**: The name of the movie or TV show
- **Type**: Whether the content is a movie or a TV show
- **Genre**: The genre(s) of the content (e.g., drama, comedy)
- **Director**: The director of the content
- **Cast**: The actors and actresses featured
- **Release Year**: The year the content was released
- **Rating**: The rating assigned to the content
- **Duration**: Length of the movie or TV show
- **Country**: The country where the content was produced
- **Date Added**: The date when the content was added to the respective platform

The datasets were gathered using the **Kaggle API** and manually downloaded for Amazon Prime.

## Project Objectives
The project aims to:
1. **Clean and preprocess** the data, addressing issues like missing values, incorrect data types, and inconsistent formats.
2. **Combine** the data from Netflix and Amazon Prime into a single dataset.
3. **Perform exploratory data analysis (EDA)** to compare the genre distribution, content type (movies vs. TV shows), and other factors across both platforms.
4. **Visualize** key insights using various plots, including genre distributions, content type comparisons, and release year trends.
5. **Answer research questions** related to content distribution and platform differences.

## Key Research Questions
1. What are the top genres available on Netflix and Amazon Prime?
2. How do movies and TV shows compare in terms of availability on both platforms?
3. What are the trends in the release years of content on both platforms?
4. How do the platforms compare in terms of content ratings?

## Installation Instructions
To run this project on your local machine, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/Project2_Real_world_Data_Wrangling.git
   cd Project2_Real_world_Data_Wrangling
2. **Install the necessary dependencies**: You can use conda or pip to install the required packages:
   ```bash
    conda install --file requirements.txt
    or
    pip install -r requirements.txt
3. **Run the Jupyter notebook:**
   ```bash
   jupyter notebook


