Music Playlists Clustering using Data Science
--------------------------------------------

Table of Contents:
- Introduction
- Project Overview
- Installation
- Usage
- Data
- Dependencies
- Contributing

Introduction:
Welcome to the Moosic Playlists Clustering project! This project aims to use Data Science techniques to automate the creation of curated music playlists. The goal is to cluster songs based on their audio features and group them into playlists that encapsulate similar moods or styles. By doing so, we aim to enhance the user experience by providing personalized, expert-curated playlists.

Project Overview:
The project consists of several key components:
1. Data Collection: We gather audio feature data for thousands of songs using the Spotify API.
2. Data Preprocessing: We clean and prepare the data, selecting relevant audio features for clustering.
3. Clustering: We use the K-Means algorithm to cluster the songs into playlists based on their audio features.
4. Visualization: We visualize the results using 3D scatter plots, displaying the clusters and their distinct features.

Installation:
To run this project locally, you need to have Python 3 installed. Clone the repository to your local machine using the following command:

git clone https://github.com/your-username/Moosic-Unsupervised-ML-Clustering-Songs
.git

Navigate to the project directory and install the required dependencies:

cd Moosic-Unsupervised-ML-Clustering-Songs
pip install -r requirements.txt

Usage:
Once the installation is complete, you can execute the main script to perform clustering and visualization:

python main.py

The script will gather data, preprocess it, perform K-Means clustering, and display the 3D scatter plot.

Data:
The audio feature data used in this project is collected from the Spotify API (and provided by WBS Coding School). It contains information such as energy, speechiness, acousticness, instrumentalness, loudness, tempo, danceability, valence, and liveness for thousands of songs.

Dependencies:
The project relies on the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- plotly

These dependencies are listed in the requirements.txt file and can be installed using pip.

Contributing:
Contributions to this project are welcome! If you have any suggestions, improvements, or new features to add, please feel free to open an issue or submit a pull request.


