# Movie Recommendation System

This project implements a movie recommendation system based on user ratings and movie titles. It utilizes the TF-IDF algorithm for text vectorization and cosine similarity for movie similarity calculations. The system uses that for one main functionalities:

1.  Given a movie title, it searches for similar movies to recommend based on user ratings.

## Requirements

To run the project, you need to have the following dependencies installed:

- pandas
- numpy
- scikit-learn
- ipywidgets

You can install them using pip:

pip install pandas 

pip install numpy 

pip install scikit-learn 

pip install ipywidgets 

In the terminal of Jupyter Notebook.


## Dataset

The project uses two CSV files as the dataset:

1. `movies.csv`: Contains movie information including movie IDs, titles, and genres.
2. `ratings.csv`: Contains user ratings for movies including user IDs, movie IDs, and ratings.

Make sure to place these files in the project directory before running the code.

## Usage

To use the movie recommendation system, follow these steps:

1. Clone the repository to your local machine:  https://github.com/Guilhermedbs/Movie-Recommendation-System.git

2. Install the required dependencies mentioned in the "Requirements" section.

3. Run every cell of the main script: python movie_recommendation.ipynb


4. The script will prompt you to enter a movie title. Type the title and press Enter.

5. The system will display the top 10 most similar movies based on the entered title and users ratings.

6. Enjoy exploring movie recommendations!

## Contribution

Contributions to the project are welcome! If you have any suggestions or improvements, feel free to create a pull request. You can also open an issue if you encounter any problems or bugs.

## License

This project is licensed under the MIT License. You can find the details in the [LICENSE](LICENSE) file.







