## Project Overview

This project aims to detect fake news using various machine learning techniques. The project utilizes datasets from Snopes and Kaggle to train and evaluate models for classifying news articles as true or false.

## Datasets

- **Snopes**: A single file containing both true and false articles.
- **Kaggle Fake News**: Two separate files, one containing true articles and the other containing false articles.

## Dependencies

The project requires the following Python libraries:

- `datasets`
- `gensim`
- `os`
- `sklearn`
- `spacy`
- `transformers`
- `pandas`
- `numpy`
- `urllib`

To install the required libraries, run:

```bash
pip install datasets gensim spacy transformers pandas numpy
```

## Usage

The main analysis and model training are conducted in the `FAKENEWS.ipynb` Jupyter notebook. You can open this notebook to explore the code and run the analysis.

## Models Used

- **Word2Vec**: For word embeddings.
- **Logistic Regression**: For classification.
- **GPT-2**: For language modeling.

## Evaluation Metrics

The models are evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1 Score

## How to Run

1. Ensure all dependencies are installed.
2. Open the `FAKENEWS.ipynb` notebook.
3. Follow the instructions in the notebook to load datasets and train models.

## License

This project is licensed under the MIT License.

## Acknowledgments

- Snopes and Kaggle for providing the datasets.