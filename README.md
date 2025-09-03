# Detecting Fake News with Python

This project demonstrates how to use machine learning to detect fake news using Python and scikit-learn. It uses a dataset of news articles and applies text classification techniques.

## Features
- Loads and processes a news dataset (`news.csv`)
- Uses TF-IDF vectorization for text features
- Trains a Passive Aggressive Classifier to distinguish between real and fake news
- Evaluates model accuracy

## Requirements
- Python 3.13+
- numpy
- pandas
- scikit-learn
- jupyterlab (for running notebooks)

## How to Run
1. Install dependencies:
	```sh
	pip install numpy pandas scikit-learn jupyterlab
	```
2. Start JupyterLab:
	```sh
	jupyter lab
	```
3. Open `main.ipynb` and run the cells to train and evaluate the model.

## File Structure
- `news.csv`: Dataset containing news articles and labels
- `main.ipynb`: Jupyter notebook with code for data processing, model training, and evaluation
- `main.py`: (Optional) Python script version

## Usage
- The notebook loads the dataset, splits it into training and test sets, vectorizes the text, trains the classifier, and prints the accuracy.

## License
This project is for educational purposes.
