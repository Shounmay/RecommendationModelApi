# RecommendationModelApi


Welcome to the SVD Recommender System project! This repository showcases the implementation of a Singular Value Decomposition (SVD) based recommendation system using a dataset. The project takes it a step further by deploying the recommendation system using Flask, allowing users to receive personalized recommendations.
## Data Link -https://drive.google.com/drive/folders/1mjblgY1C_C0fmyxYrfsoI21uMptBwRQu?usp=sharing
## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [For Flask App](#flask_app)
- [For Model](#for_model)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Snaps](#snaps)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The SVD Recommender System is a collaborative filtering technique that provides personalized recommendations based on user preferences. In this project, we've utilized a dataset to train the SVD model, and then deployed it using Flask to create a user-friendly API for obtaining recommendations.

## Features

- SVD-based personalized recommendations
- Flask-based API deployment
- Easy-to-use API endpoints for retrieving recommendations

## For Flask App

1. Clone this repository: `git clone https://github.com/yourusername/svd-recommender-flask.git`
2. Install required packages: `pip install -r requirements.txt`
3. Just run the app.py file : 'python app.py' in root directory
   
## For Model
1. Download the Dataset and load them in the notebook in 'Recomnedation Model' Folder
2. We have used 'Suprise Library' which has issues running in local system so upload the notebook in collab and run the model.
3. If you want your changes to be shown, just generate the new pickel file and upload it into the existing one in root flask directory.

## Usage

Once you've followed the setup steps, the Flask app will be up and running. You can now make API requests to get recommendations.

## API Endpoints

- `/getitemlistforeachuser` (GET): Produces recommended item ids for each user
- `/getitemforrandomuser` (GET): gets recommended Product Id for a random user
- `/getitemforuser` (POST)-gets recommended Product id for a user (body has userid). {Further we will update with how many query for each user, so POST method}

## Snaps

### Model Snaps:
![snap-2](https://github.com/Shounmay/RecommendationModelApi/assets/90774417/5c46515d-ea57-4449-9a26-c091afe92660)
![snap_1](https://github.com/Shounmay/RecommendationModelApi/assets/90774417/e3586a3a-3b49-4d33-a6f8-65a7fe8eb3b3)

### Backend API Snap:
![snap-3](https://github.com/Shounmay/RecommendationModelApi/assets/90774417/104e0501-60fe-42b6-96e5-927583bace16)



## Contributing

Contributions are welcome! If you'd like to add new features, improve existing ones, or fix any issues, feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
