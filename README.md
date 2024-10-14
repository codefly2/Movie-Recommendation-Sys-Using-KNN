# Movie Recommendation System using KNN

## Project Overview
This project focuses on recommending movies based on their metadata using the K-Nearest Neighbors (KNN) algorithm. The recommendation system aims to help users discover movies similar to those they have enjoyed by analyzing features like genres, keywords, tagline, cast, and director.

## Dataset Information
The dataset used in this project contains various features about movies. Each entry includes:
- **genres**: The genre(s) of the movie.
- **keywords**: Keywords associated with the movie.
- **tagline**: A short, catchy phrase describing the movie.
- **cast**: Main actors in the movie.
- **director**: The director of the movie.

The dataset is preprocessed to handle missing values and combined into a single feature vector to facilitate similarity calculations.

### Dataset Download Link
Ensure you have the `movies.csv` file in the project directory. You can use any movie dataset or download from popular movie databases like [Kaggle](https://www.kaggle.com/) or [The Movie Database (TMDb)](https://www.themoviedb.org/).

## Objectives
The goal of this project is to develop a movie recommendation system that accurately suggests similar movies based on user input. The primary focus is on optimizing similarity measures using TF-IDF vectorization and cosine similarity.

## Libraries Used
The following libraries were utilized in this project:
- **pandas**: For data manipulation and handling.
- **numpy**: For numerical computations.
- **scikit-learn**: For implementing machine learning models, vectorization, and evaluation metrics.

## Algorithms Implemented
We implemented the following techniques to achieve movie recommendations:
1. **TF-IDF Vectorization**: Converts textual features into a numerical representation based on their importance in the dataset.
2. **Cosine Similarity**: Measures the cosine of the angle between two non-zero vectors, providing a metric for similarity between movies.
3. **K-Nearest Neighbors (KNN)**: A non-parametric method used for classification and regression, here applied to recommend similar movies.

## Model Performance
The recommendation system's performance is evaluated based on user satisfaction and the accuracy of recommendations. While quantitative metrics like precision and recall are not directly applicable, qualitative user feedback is crucial for assessing effectiveness.

### Performance Metrics
- **User Feedback**: Collecting ratings or reviews on recommendations to assess satisfaction.
- **Recommendation Accuracy**: Manual verification of the relevance of suggested movies.

## Future Work
- Enhance the model by incorporating additional features such as release date and runtime.
- Implement a user interface for easier interaction and user input.
- Experiment with advanced algorithms like collaborative filtering and deep learning techniques for improved recommendations.

## How to Run the Project
1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/movie-recommendation-system-knn.git
    ```
2. Navigate to the project directory:
    ```bash
    cd movie-recommendation-system-knn
    ```
3. Install the necessary libraries:
    ```bash
    pip install numpy pandas scikit-learn
    ```
4. Ensure the `movies.csv` dataset is present in the project directory.
5. Run the script to get movie recommendations:
    ```bash
    python recommendation.py
    ```

## Conclusion
This project demonstrates the application of machine learning models for recommending movies based on their metadata. By focusing on TF-IDF vectorization and cosine similarity, we can effectively identify and suggest similar movies to users. Future improvements could enhance the system's accuracy and user experience.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
