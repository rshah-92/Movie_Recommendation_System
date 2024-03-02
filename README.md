
# Movie Recommendation System

Welcome to the Movie Recommendation System project! This system utilizes advanced techniques, including Demographic Filtering, Content-Based Filtering, and a Weighted Rating mechanism based on the IMDB formula, to offer personalized movie recommendations. The objective is to enhance users' movie-watching experience by considering their demographic information, individual preferences, and reliable movie ratings.

## Key Objectives

- **Demographic Filtering:** Understand user preferences based on demographic factors such as age and gender.
- **Content-Based Filtering:** Analyze movie features like cast, crew, genres, and keywords to generate tailored recommendations.
- **Weighted Rating:** Prioritize movies with higher average ratings and a substantial number of votes using the IMDB formula.
- **Evaluation Metrics:** Assess system performance through precision, recall, and user satisfaction metrics.
- **Interactive Interface:** Develop an intuitive Jupyter Notebook interface for users to explore and test the recommendation system.

## Data Enrichment and Cleaning

The project involves merging datasets to create a comprehensive dataset. Data cleaning steps include removing duplicates, dropping unnecessary columns, and handling discrepancies in titles and language information.

## Content-Based Filtering

Content-based filtering utilizes features such as cast, crew, genres, keywords, and overview to recommend movies based on their content characteristics. The process involves feature combination, vectorization, similarity measurement, and the creation of a recommendation function.

## Hybrid Recommendation System

A hybrid recommendation system is implemented by combining content-based recommendations with weighted ratings. This approach offers a more comprehensive and effective movie recommendation system.

## Usage

To run the project:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/rshah-92/Movie_Recommendation_System.git
   ```

2. **Navigate to the Project Directory:**
   ```bash
   cd Movie_Recommendation_System
   ```

3. **Run the Jupyter Notebook:**
   Open the notebook and explore personalized movie recommendations!

## Next Steps

- Enhance the significance of the "genres" and "keywords" columns.
- Explore additional text preprocessing techniques for improved recommendations.
- Consider creating a hybrid recommendation system incorporating both content-based recommendations and weighted ratings for a more comprehensive approach.

Feel free to explore the notebook, try out different movie titles, and enjoy a personalized movie recommendation experience!

