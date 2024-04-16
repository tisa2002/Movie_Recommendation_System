# Movie Recommendation System

This project is a movie recommendation system built using Python and Streamlit. It leverages collaborative filtering to recommend movies to users based on their preferences and the preferences of other users. The system utilizes the MovieLens dataset to train the model and provide recommendations.
### Deployment
https://movie-recommendation-system-tisa2002.streamlit.app/
## Features

- Movie recommendations based on user preferences.
- Utilizes collaborative filtering techniques.
- Interactive web app built with Streamlit for easy use.
- Fetches movie posters through an API for an engaging user experience.

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:
- Python 3.6 or higher
- pip

### Installation

1. Clone the repository:
 ```bash
 git clone https://github.com/tisa2002/movie_recommendation_system.git
```
2. Navigate to the project directory:
  ```bash
cd movie_recommendation_system
```
3. Install the required dependencies:
```bash
pip install -r requirements.txt
```
### Usage
To run the movie recommendation system, execute the following command:
```bash
streamlit run app.py
```
Navigate to the provided URL to interact with the application.
### Dependencies
The project relies on several Python packages listed in requirements.txt, including but not limited to:

- Streamlit for creating the web app
- Pandas for data manipulation
- Numpy for numerical operations
- Requests for API calls
### How It Works
The system uses a collaborative filtering approach to recommend movies. It calculates similarity scores between movies based on user ratings and suggests movies that are similar to the ones the user likes.

### Key Functions
- fetch_poster(movie_id): Fetches movie posters using an API.
- recommend(movie): Recommends movies based on similarity scores.
### Contributing
Contributions to the Movie Recommendation System are welcome. Please feel free to fork the repository and submit pull requests.

### License
This project is licensed under the MIT License - see the LICENSE file for details.

### Acknowledgments
This project is inspired by the MovieLens dataset.
Thanks to Streamlit for making interactive web apps easy to build.
