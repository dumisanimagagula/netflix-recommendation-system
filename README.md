# Netflix Recommendation System

![Netflix Recommendation System](https://img.shields.io/badge/Python-3.6%20%7C%203.7%20%7C%203.8%20%7C%203.9%20%7C%203.10-blue)

Welcome to the Netflix Recommendation System project! This Python project is perfect for aspiring data scientists and machine learning enthusiasts who want to build their own recommendation system for Netflix content.

## Table of Contents
- [Project Overview](#project-overview)
- [Getting Started](#getting-started)
- [How It Works](#how-it-works)
- [Usage](#usage)
- [Contributing](#contributing)

## Project Overview

This Netflix Recommendation System is designed to provide personalized recommendations for movies and TV shows available on Netflix. It uses machine learning techniques to analyze user preferences and suggests content based on similarity to their input.

## Getting Started

To get started with this project, follow these steps:

### Prerequisites

Before you begin, ensure you have the following dependencies installed:

- `tkinter`: for creating the graphical user interface.
- `re`, `nltk`, `pandas`, and `numpy`: for data preprocessing and manipulation.

You can install these dependencies using the following command:

```bash
pip install pandas numpy nltk
```
### Dataset
You'll need a dataset containing Netflix movies and TV shows. You can download the dataset from [here](#https://www.kaggle.com/datasets/satpreetmakhija/netflix-movies-and-tv-shows-2021?resource=download).

### Setting Up
1. Clone this repository to your local machine.

2. Place the downloaded dataset (CSV file) in the project directory and name it `netflixData.csv`.

### How It Works
This recommendation system uses the following steps:

1. **Data Preprocessing**: The dataset is loaded, and missing values are removed. The data is split into two categories: movies and TV shows.

2. **Feature Engineering**: Various features are extracted from the dataset, including actors, directors, production countries, genres, and ratings. These features are transformed into binary form for machine learning.

3. **Cosine Similarity**: The recommendation engine calculates the cosine similarity between user input and all items in the dataset. This similarity score is used to find the most similar items.

### Usage
To use the Netflix Recommendation System:

1. Run the provided Python script.

2. A graphical user interface (GUI) will appear. Enter the title of a movie or TV show you enjoyed on Netflix into the input field.

3. Click the "Find Recommendations" button.

4. The system will provide you with a list of recommended movies or TV shows based on your input.

### Contributing
If you'd like to contribute to this project, please follow these guidelines:

1. Fork the repository.

2. Create a new branch for your feature or bug fix.

3. Make your changes and ensure they are well-documented.

4. Test your changes thoroughly.

5. Create a pull request to merge your changes into the main branch.