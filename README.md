# DTSA5510

Overview

This repository contains the deliverables for the DTSA5510 project, focusing on different aspects of machine learning and data analysis. The repository is organized into distinct folders and notebooks to facilitate easy navigation and understanding of the project components.
Repository Structure

    data: This folder contains all the datasets used in the project. The datasets include:
        BBC_News_Train.csv: Training data for the BBC news classification task.
        BBC_News_Test.csv: Test data for the BBC news classification task.
        users.csv: User data for the movie ratings task.
        movies.csv: Movie data for the movie ratings task.
        train.csv: Training data for the movie ratings task.
        test.csv: Test data for the movie ratings task.

    output: This folder contains the output files generated during the project. The outputs include:
        BBC_News_Test_Predictions.csv: Predictions for the BBC news test data.
        Embedding_Comparison_Plot.png: Plot comparing different embeddings used in the project.

    Notebook_1.ipynb: Jupyter notebook for the BBC News Classification task. This notebook includes:
        Exploratory Data Analysis (EDA)
        Model building and training using matrix factorization techniques
        Comparison with supervised learning methods
        Submission of predictions to Kaggle

    Notebook_2.ipynb: Jupyter notebook for analyzing the limitations of sklearn’s non-negative matrix factorization (NMF) library. This notebook includes:
        Loading and preprocessing movie ratings data
        Using matrix factorization techniques to predict missing ratings
        Measuring the performance using RMSE
        Discussion on the performance and potential improvements

    README.md: This readme file provides an overview of the project, the structure of the repository, and brief descriptions of the contents.
