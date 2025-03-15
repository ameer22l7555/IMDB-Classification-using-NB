# IMDB Movie Review Sentiment Classification

This project implements a Naive Bayes classifier from scratch to perform sentiment analysis on IMDB movie reviews. The classifier categorizes movie reviews as either positive or negative based on the text content.

## Project Overview

The project demonstrates:
- Implementation of a Naive Bayes classifier from scratch
- Comparison with scikit-learn's built-in GaussianNB implementation
- Text preprocessing techniques for natural language processing
- Performance evaluation using metrics like accuracy, precision, and recall

## Dataset

The project uses the IMDB Dataset which contains 50,000 movie reviews labeled as positive or negative. The dataset is balanced, with an equal number of positive and negative reviews.

## Features

- **Text Preprocessing**: Removes punctuation, numbers, and stop words, and converts text to lowercase
- **Custom Naive Bayes Implementation**: Includes functions for calculating prior probabilities, class statistics, Gaussian density, and posterior probabilities
- **Performance Comparison**: Compares the custom implementation with scikit-learn's GaussianNB
- **Visualization**: Includes confusion matrices to visualize model performance

## Implementation Details

The project includes:
1. Data loading and exploration
2. Text preprocessing and feature extraction
3. Custom Naive Bayes classifier implementation
4. Model training and evaluation
5. Comparison with scikit-learn's implementation

## Results

The custom Naive Bayes implementation achieves high accuracy on the IMDB dataset, comparable to the built-in scikit-learn implementation.

## Requirements

The project requires the following Python libraries:
- numpy
- pandas
- matplotlib
- scikit-learn
- nltk
- gensim
- tensorflow
- keras

See `requirements.txt` for specific version information.

## Usage

1. Clone the repository
2. Install the required dependencies: `pip install -r requirements.txt`
3. Run the Jupyter notebook: `jupyter notebook IMDB-Classification.ipynb`

## Future Improvements

Potential enhancements for this project:
- Experiment with different feature extraction methods
- Implement other classification algorithms for comparison
- Optimize hyperparameters for better performance
- Explore more advanced text preprocessing techniques

## License

This project is open source and available under the MIT License.