# Personalized Book Recommender System - README

## Overview
This project implements a **Personalized Book Recommender System** using collaborative filtering. The application is designed to suggest books based on user preferences, leveraging book ratings and metadata for personalized recommendations. It also highlights a curated list of the top 50 popular books.

## Features
1. **Top 50 Books:**  
   A sidebar feature showcasing the top 50 books from the catalog with titles, authors, and cover images.

2. **Book Recommendations:**  
   Personalized recommendations are generated using a collaborative filtering algorithm. Users can select a book from the catalog, and the system suggests similar books.

3. **Data Insights:**  
   Users can view the datasets used for training the model, including:
   - Books dataset
   - Users dataset
   - Ratings dataset

## How It Works
### 1. Collaborative Filtering
The system uses collaborative filtering to recommend books based on user preferences. The key steps are:
   - Identifying similar books based on user ratings.
   - Returning the top 5 books related to the selected book.

### 2. Application Interface
The application is developed using **Streamlit**, providing an intuitive interface for users to explore recommendations and view popular books.

## Getting Started
### Prerequisites
- Python 3.8 or higher
- Required libraries:
  - `streamlit`
  - `pandas`
  - `numpy`
  - `pickle`

### Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd book-recommender-system
   ```

2. Ensure the following files are available in the project directory:
   - `Data/Books.csv`
   - `Data/Users.csv`
   - `Data/Ratings.csv`
   ```

3. Datasets:
   - `Resource link`: https://www.kaggle.com/datasets/saurabhbagchi/books-dataset

### Running the Application
1. Launch the Streamlit application:
   ```bash
   streamlit run app.py
   ```

2. Access the application in your browser at `http://localhost:8501`.

## File Structure
- **`app.py`**  
  Contains the Streamlit application code for the recommender system.
- **`popular.pkl`**, **`books.pkl`**, **`pt.pkl`**, **`similarity_scores.pkl`**  
  Preprocessed model and data files for recommendations.
- **`Data/`**  
  Contains CSV files with book, user, and rating datasets.

## Usage
1. Open the application in your browser.
2. Use the **Top 50 Books** section to explore popular books.
3. Use the **Similar Book Suggestions** section to select a book and get personalized recommendations.
4. Explore the datasets in the **Data Used** section for insights into the training data.

## Future Enhancements
- Add user login and profile-based recommendations.
- Implement additional recommendation algorithms like content-based filtering.
- Enable dynamic dataset updates for real-time suggestions.

## Acknowledgments
This project was built using publicly available book data and open-source libraries. Collaborative filtering techniques were inspired by standard recommendation system methodologies.

--- 

Feel free to customize further as per your project specifics!
