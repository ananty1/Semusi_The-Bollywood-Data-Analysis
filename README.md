# Bollywood Data NLP Analysis Project

This project focuses on analyzing Bollywood movie data using Natural Language Processing (NLP) techniques. The goal is to preprocess the data, apply NLP methods, and use a pretrained DistilBERT model from the Transformers library to categorize text into stereotype and non-stereotype classes.

## Project Structure

The project is structured as follows:

- **data/**
  - Contains the raw data files, including scripts, posters, trailers, and Wikipedia data.

- **notebooks/**
  - Jupyter notebooks for data preprocessing, NLP analysis, and model training.

- **models/**
  - Pretrained model files and scripts for model evaluation.

- **results/**
  - Output files and visualizations generated during the analysis.

- **README.md**
  - This README file providing an overview of the project.

## Data Preprocessing

1. **Poster Data:** Extracted text summaries from images using the BLIP-2 model for text summarization.
2. **Trailer Data:** Preprocessed trailer data containing frame-wise emotion and gender information.
3. **Scripts Data:** Extracted text from movie scripts using PyPDF2 and applied standard NLP techniques for preprocessing.
4. **Wikipedia Data:** Utilized various datasets, including female and male adjectives/adverbs, centrality plots, and coreference plot data. Preprocessed these datasets for analysis.

## NLP Domain Analysis

1. Applied NLP techniques such as tokenization, stop word removal, and lemmatization to clean and process the text data.
2. Created word clouds and visualizations to explore the most common terms and patterns in the data.
3. Utilized domain-specific datasets to enhance the NLP analysis, including gender stereotype indicators and role centrality plots.

## Pretrained DistilBERT Model

1. Used the DistilBERT model from the Transformers library for sentence-level stereotype classification.
2. Fine-tuned the pretrained model on the Bollywood movie dataset to categorize text into stereotype and non-stereotype classes.
3. Evaluated the model's performance using metrics such as accuracy, precision, recall, and F1-score.

## Usage

To replicate the analysis and run the code:

1. Clone the repository to your local machine.
2. Install the required Python libraries listed in `requirements.txt`.
3. Use the Jupyter notebooks in the `notebooks/` directory to preprocess the data, perform NLP analysis, and train the DistilBERT model.
4. Modify the paths and configurations as needed for your specific setup.
5. Refer to the documentation and comments in the code for detailed instructions and explanations.

## Results

The project results include:

- Visualizations of word clouds, role centrality plots, and model performance metrics.
- Trained DistilBERT model files for stereotype classification.
- Output files containing categorized text data and analysis insights.

