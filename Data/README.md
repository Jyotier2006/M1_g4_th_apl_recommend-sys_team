# Dataset - MovieLens 1M

This project uses the MovieLens 1M dataset released by GroupLens Research.

## Dataset Summary

MovieLens 1M contains approximately:

- 1,000,000 ratings
- 6,000 users
- 4,000 movies
- Ratings on a 1-5 scale

The main rating fields are:

- User ID
- Movie ID
- Rating
- Timestamp

Additional information includes user attributes such as age group, gender and occupation, and movie information such as genres.

## Use in This Project

MovieLens 1M is the main benchmark for our Matchbox study. It will be used for:

- ADF vs. repeated EP comparison
- latent dimensionality experiments
- metadata vs. no-metadata experiments
- sparsity and cold-start experiments

The dataset is also relevant because MovieLens was used in the original Matchbox evaluation.

## Download

Official GroupLens source:

https://grouplens.org/datasets/movielens/1m/

The raw dataset is not duplicated in this repository. It can be downloaded from the official source and will be preprocessed during the technical implementation stage.
