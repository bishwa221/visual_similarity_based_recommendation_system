# Visual similarity-based Recommendation System
Content-based recommendation system model that utilizes features of images.
It recommends similar products, based on images of products which are similar to the one selected.

The steps involved:
- Load and explore the data
- Feature extraction using Transfer Learning with ResNet50 with Imagenet weights.
- Generate dataframe of similarity indices using cosine similarity. The index and columns are ids of the images used.
- Extract top 3 similar images using these similarity values.

Input:
It utilizes Style Images found at : https://www.kaggle.com/datasets/olgabelitskaya/style-color-images

Output: 
It generates dataframes of cosine similarities and saves them as csv file and a pickle file.


