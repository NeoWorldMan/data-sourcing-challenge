# Jupyter Notebook: Movie Data Retrieval

## Overview

This Jupyter Notebook performs retrieving and merging of movie data using The New York Times (NYT) API and The Movie Database (TMDb) API.

## Purpose

This project retrieves movie data from two sources: The New York Times API and The Movie Database (TMDb) API, it cleans up and merges the data and exports it to a CSV file. The text extracted from these APIs can be used with natural language processing methods.

## Contents

	**Data Sources:**
	*	The primary data sources are The New York Times API and The Movie Database (TMDb) API. These APIs provide detailed information about various movies, including titles, genres, keywords, critic reviews, and more.
	**Main Functions and Code:**
	*	The notebook includes the following main functions:
	*	Functions to retrieve movie reviews and ratings using The New York Times API.
	*	extract_keywords: Extracts relevant ‘name’ and ‘value’ data from the “keywords” column in the movie dataset using data from TMDb.
	*	Additional helper functions that clean, filter, and process movie data for analysis.

## Methodology

The notebook follows a structured process where it first connects to The New York Times API and The Movie Database (TMDb) API to retrieve movie data. The data is then processed and analyzed to identify patterns, trends, and insights, such as common genres, popular keywords, critic ratings, and movie reviews. Various Python libraries are used for handling data retrieval, processing, and visualization.

## Step-by-Step Process

	1.	Data Retrieval: Connect to The New York Times API and The Movie Database (TMDb) API to extract movie data in JSON format.
	2.	Data Cleaning: Process the raw data to handle missing values, duplicates, and inconsistent entries.
	3.	Data Merging and Export: The data from both sources is merged and exported to a CSV file.

## Libraries Used

The notebook uses the following Python libraries:

	*	time: For handling time-related operations.
	*	pandas: For data manipulation and analysis.
	*	os: For interacting with the operating system.
	*	requests: For making HTTP requests to the NYT and TMDb APIs.
	*	json: For parsing JSON data returned by the APIs.

## How to Access and Use The APIs

**The New York Times (NYT) API**

	1.	Sign up for a free account at The New York Times Developer Network.
	2.	Apply for an API key by selecting the “Movie Reviews API.”
	3.	Insert the API key into the appropriate cell in the Jupyter Notebook.

**The Movie Database (TMDb) API**

	1.	Sign up on TMDb to create an account.
	2.	Go to your account settings and generate an API key.
	3.	Insert the API key into the relevant cell in the Jupyter Notebook where indicated.

## How to Use This Notebook

	1.	Clone the repository and navigate to the notebook file.
	2.	Install required packages
    3.	Set up API access: Obtain API keys from both The New York Times and The Movie Database (TMDb) and insert them in the appropriate cells in the notebook.
	4.	Run the Notebook: Open the notebook using Jupyter Notebook and execute the cells sequentially.

## Potential Use Cases

	*	Film Industry Analysis: Identifying popular genres and keywords that drive movie success, enhanced by professional critic reviews.
	*	Recommendation Systems: Using insights from both the NYT and TMDb datasets to enhance movie recommendation algorithms.
	*	Market Research: Understanding trends for strategic decision-making in the film industry.

## Author
This notebook was developed for educational purposes to demonstrate data retrieval and processing for further processing with AI methods using real-world movie data from both The New York Times and TMDb.
