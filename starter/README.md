# Product Review Classification Pipeline - Starter Code

This folder contains all the files for the Product Review Classification Pipeline project. 

## Folder Structure

- `starter.ipynb`: The Jupyter notebook containing the code skeleton and project instructions
- `data/reviews.csv`: The dataset containing product reviews and associated metadata
- `results/`: Directory where model checkpoints and training results will be saved

## Tasks Completed

1. **Data Exploration**: Understand the dataset structure and relationships between features
2. **Data Preprocessing**:
   - Handle numerical features using appropriate scaling
   - Process categorical features through encoding
   - Transform text data (Title and Review Text) using NLP techniques
3. **Pipeline Construction**: Create a scikit-learn pipeline that handles all data transformations
4. **Model Selection**: Compare multiple classification models and evaluate their performance
5. **Model Optimization**: Fine-tune your best model using hyperparameter optimization
6. **Advanced Implementation**: Explore transformer-based models for improved performance

## Data Description

The dataset contains the following features:
- **Clothing ID**: Integer categorical variable that refers to the specific product being reviewed
- **Age**: Positive integer variable of the reviewer's age
- **Title**: String variable for the title of the review
- **Review Text**: String variable for the review body
- **Positive Feedback Count**: Positive integer counting how many found this review helpful
- **Division Name**: Categorical name of the product high-level division
- **Department Name**: Categorical name of the product department
- **Class Name**: Categorical name of the product class
- **Recommended IND**: Target variable (1 = recommended, 0 = not recommended)

## Pipeline Components

1. **Data Preprocessing**:
   - Numerical features: Scaling
   - Categorical features: One-hot encoding
   - Text features: TF-IDF vectorization

2. **Model Training and Evaluation**:
   - Traditional ML models (Random Forest, Logistic Regression, etc.)
   - Neural network (MLP Classifier)
   - Transformer model (DistilBERT)

3. **Model Optimization**:
   - Bayesian optimization for hyperparameter tuning
   - Performance evaluation using metrics like F1 score, accuracy, precision, and recall

## Results

The project compares several classification models and identifies the best-performing model based on F1 score. The MLP Classifier showed strong performance after hyperparameter optimization, and the transformer model demonstrated the potential of deep learning approaches for this task.
