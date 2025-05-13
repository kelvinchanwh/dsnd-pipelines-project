# Product Review Classification Pipeline

A machine learning pipeline project that processes product review data to predict whether a customer recommends a product based on their review. The pipeline handles numerical, categorical, and text data through appropriate preprocessing steps and employs various classification models to make predictions.

## Project Overview

This project demonstrates how to:
1. Build an end-to-end machine learning pipeline for text classification
2. Process and transform mixed data types (text, categorical, numerical)
3. Compare multiple machine learning models
4. Fine-tune model parameters using Bayesian optimization
5. Train and evaluate a transformer-based model (DistilBERT)

The project uses a dataset of clothing product reviews to predict whether customers recommend the products based on various features including review text, age, product details, and more.

## Getting Started

### Prerequisites

The project requires Python 3.7+ and the following libraries:

```
pandas
numpy
scikit-learn
transformers
spacy
matplotlib
seaborn
joblib
datasets
skopt
```

All dependencies are listed in the requirements.txt file.

### Installation

1. Clone the repository:
```
git clone https://github.com/kelvinchanwh/dsnd-pipelines-project.git
cd dsnd-pipelines-project
```

2. Create and activate a virtual environment (optional but recommended):
```
python -m .venv venv
source .venv/bin/activate
```

3. Install the required packages:
```
pip install -r requirements.txt
```

4. Download the required spaCy language model:
```
python -m spacy download en_core_web_sm
```

## Project Structure

- `starter.ipynb`: Main notebook containing all code and analysis
- `data/reviews.csv`: Dataset of clothing product reviews
- `results/`: Saved model checkpoints from the transformer model training

## Built With

* [scikit-learn](https://scikit-learn.org/) - Machine learning library
* [Hugging Face Transformers](https://huggingface.co/transformers/) - For transformer models
* [spaCy](https://spacy.io/) - NLP library for text preprocessing
* [skopt](https://scikit-optimize.github.io/stable/) - For Bayesian optimization

## License

[License](LICENSE.txt)
