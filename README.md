# Recommender Algorithm for Japanese Animes

This github repo contains the code while data in the data folder can be downloaded separately from a drive link

## A. Codes in the notebooks folder should be run in the following sequence

### Data Analysis and Modelling
1. Part 0a - EDA and Topic Modelling for Synopsis Data used in Model 2b
2. Part 0b - Scope of Analysis
3. Part 0c - Model 0 Baseline Random Selection
4. Part I - Model 1 Content Based Filtering with Synopsis Similarity
5. Part II - Model 2a Content Based Filtering with Image Similarity
6. Part II - Model 2b Content Based Filtering with Image Similarity - Transfer Learning and Classification
7. Part III - Model 3 SVD User Interaction
8. Part IV - Model 4 Autoencoder User Interaction

### Data extraction - Optional to run
1. Webscraping Part I - Anime Dataset - this will create 'dataset_full.csv'
2. Webscraping Part II - Anime Images - this reads from 'dataset_EDA_Topic_14022021.csv' and will create the images found in the images folder

## B. Data files in the data folder can be downloaded via the following link: 
`pending`
## C. Data file desciption
1. 'dataset_full.csv' contains the data scraped from myanimelist website and is used in 'Part 0a - EDA and Topic Modelling for Synopsis Data used in Model 2b'
 
2. 'dataset_EDA_Topic_14022021.csv' contains the anime data and topic models and is used in 'Part 0b - Scope of Analysis'

3. 'reviews.csv' contains the ratings given by users for animes and is obtained from kaggle: https://www.kaggle.com/marlesson/myanimelist-dataset-animes-profiles-reviews. It is used in 'Part 0b - Scope of Analysis'
 
4. images folder in images.zip contains the images scraped from myanimelist website and is used in 'Part 0b - Scope of Analysis'


