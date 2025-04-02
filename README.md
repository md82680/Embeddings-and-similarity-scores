# Embeddings and Similarity Scores with Google Gemini

This repository demonstrates the use of Google Gemini's embedding capabilities to calculate and analyze similarity scores between text samples. It showcases how to use the embedding API for semantic similarity analysis and visualization.

## Overview

This project implements a text similarity analysis system that:
- Generates text embeddings using Google Gemini API
- Calculates similarity scores between different text samples
- Visualizes the relationships using heatmaps
- Demonstrates practical applications with pangram variations

## Features

- **Text Embedding:** Convert text samples into vector embeddings
- **Similarity Analysis:** Calculate and compare similarity scores
- **Visualization:** Generate heatmaps of similarity relationships
- **Batch Processing:** Handle multiple text samples simultaneously

## Setup & Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/md82680/Embeddings-and-similarity-scores.git
   cd Embeddings-and-similarity-scores
   ```

2. **Install Dependencies:**
   ```bash
   pip install -U -q "google-genai==1.7.0"
   pip install pandas seaborn
   ```

3. **API Key Setup:**
   - Store your Google API key in your Kaggle secret (named GOOGLE_API_KEY)
   - Or set it as an environment variable

## Usage

Run the provided Jupyter Notebook to:
- Generate embeddings for text samples
- Calculate similarity scores
- Visualize relationships through heatmaps
- Analyze semantic similarities between text variations

## Example Applications

The notebook demonstrates:
- Similarity analysis of pangram variations
- Detection of spelling mistakes
- Comparison of related and unrelated texts
- Visualization of semantic relationships

## Project Structure

- **Notebook:** Contains the complete demonstration and analysis
- **README.md:** Project documentation
- **Requirements.txt:** Required dependencies

## Models Used

Available embedding models:
- models/embedding-001
- models/text-embedding-004
- models/gemini-embedding-exp-03-07
- models/gemini-embedding-exp

## License

This project is licensed under the Apache License 2.0.

## Acknowledgements

Thanks to:
- Google GenAI for the embedding API
- Kaggle for the development environment
- The data science community for visualization tools
