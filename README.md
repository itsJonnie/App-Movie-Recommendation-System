# Movie Recommendation System

A movie recommendation system built with Python that leverages collaborative filtering techniques. This project uses the MovieLens 100k dataset to suggest movies to users based on their historical ratings. The system implements multiple recommendation models including a simple k‑Nearest Neighbors (k‑NN) model, an SVD-based model, and a hybrid approach. The application is deployed as a Streamlit web app via GitHub and Streamlit Community Cloud.

## Live Demo

Check out the live app at:  
**[https://app-movie-recommendation-system-jsher.streamlit.app/](https://app-movie-recommendation-system-jsher.streamlit.app/)**

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Data](#data)
- [Usage](#usage)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Overview

This repository contains a movie recommendation system that:
- Loads and processes the MovieLens 100k dataset.
- Constructs a filtered user–movie rating matrix.
- Implements various recommendation models:
  - **Simple k‑NN Model:** Uses scikit‑learn’s k‑Nearest Neighbors for user-based collaborative filtering.
  - **SVD-based Model:** Uses Singular Value Decomposition to predict user ratings.
  - **Hybrid Model:** Combines user-based and item-based recommendations.
- Provides an interactive Streamlit web application for generating recommendations.
- Is deployed on Streamlit Community Cloud for free hosting.

## Features

- **Data Loading from Google Drive:**  
  The app automatically downloads and extracts the MovieLens 100k dataset from Google Drive if not already present locally.
  
- **User–Movie Matrix Construction:**  
  The system creates a pivot table of user ratings, filtering out movies and users with very few ratings, and fills missing values with 0.

- **Recommendation Models:**  
  Implements:
  - A **simple k‑NN model** for collaborative filtering.
  - An **SVD-based model** for rating prediction.
  - A **hybrid approach** combining user-based and item-based recommendations.

- **Interactive UI:**  
  A Streamlit web app that allows users to input a User ID and select the recommendation model, displaying recommended movies interactively.

- **Deployment:**  
  The app is deployed on Streamlit Community Cloud, with the live demo available at the link above.
