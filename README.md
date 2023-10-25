# FoodPair - Food Ingredient Relationship Exploration

Welcome to the FoodPair project! This repository contains code and data for exploring food ingredient relationships, suggesting creative recipes, measuring ingredient similarities, and more. The project leverages techniques such as co-occurrence matrices, word embeddings, and NLP analogies to provide insights into the culinary world.

## Table of Contents
1. [Overview](#overview)
2. [Data Loading and Exploration](#data-loading-and-exploration)
3. [Co-occurrence Matrix](#co-occurrence-matrix)
4. [Model Class](#model-class)
5. [Training the Model](#training-the-model)
6. [Ingredient Similarity](#ingredient-similarity)
7. [Creative Ingredient Suggestions](#creative-ingredient-suggestions)
8. [Recipe Generation](#recipe-generation)
9. [NLP Analogies](#nlp-analogies)
10. [Ingredient Clustering](#ingredient-clustering)
11. [Ingredient Dissimilarity](#ingredient-dissimilarity)
12. [Hyperparameter Evaluation](#hyperparameter-evaluation)
13. [Data Visualization](#data-visualization)

## Overview
FoodPair is a project that explores food ingredient relationships and offers various functionalities related to culinary creativity and insights. It uses a co-occurrence matrix, word embeddings, and NLP operations to analyze and recommend food ingredients.

## Data Loading and Exploration
- Data is loaded from two Gzipped text files.
- Unique food ingredients are counted and their distribution is visualized.
- An "Out Of Vocabulary" token is discussed as a relevant data point for meaningful relations.

## Co-occurrence Matrix
- The project creates a co-occurrence matrix to capture relationships between food ingredients based on how often they appear together.

## Model Class
- The `FoodPairModel` class is introduced to work with the co-occurrence matrix and provide various operations and functionalities.

## Training the Model
- The model is trained to learn word embeddings using a simplified version of the GloVe model.
- The goal is to capture ingredient relationships in the data.

## Ingredient Similarity
- Ingredient similarity is calculated using cosine similarity between word vectors.
- The project can suggest ingredients similar to a given one.

## Creative Ingredient Suggestions
- The project demonstrates how to suggest new ingredients based on existing ones.
- It starts with a set of ingredients and expands the suggestions based on similarity.

## Recipe Generation
- The project generates recipes based on ingredient combinations.
- It provides step-by-step instructions and titles for these recipes.

## NLP Analogies
- NLP analogy operations are employed to suggest ingredients similar to a given set.
- Analogies like "king - man + woman" are utilized for food ingredients.

## Ingredient Clustering
- Ingredients are clustered based on their embeddings.
- This provides insights into ingredient relationships or categories.

## Ingredient Dissimilarity
- The project identifies ingredients that are least similar to a given ingredient.

## Hyperparameter Evaluation
- The model's performance is evaluated with different hyperparameters, including epochs, embedding dimensions, and learning rates.

## Data Visualization
- The project provides visualizations of correlated word pairs and highly occurring word pairs in the co-occurrence matrix.

## Future Work
The project is ongoing, and there are several areas for potential expansion and improvement, including:
- Obtaining better data with cuisine type, cooking techniques, and ingredient amounts.
- Combining recipe data with food flavors data.
- Utilizing gastronomy literature for data to enhance recommendations.
- Predicting ingredient ratio-measurement for better taste.
- Tailoring ingredient recommendations for different cuisines.
- Recommending the best cooking techniques for given ingredients.
- Implementing human feedback reinforcement learning and collaborative filtering for personalized recommendations.
- Using Generative AI for creating fine-tuned recipe directions and images.

We hope you find the FoodPair project intriguing and useful for your culinary explorations! Feel free to contribute, provide feedback, or contact us with any questions.

