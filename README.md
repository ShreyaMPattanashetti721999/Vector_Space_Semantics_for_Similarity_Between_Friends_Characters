# Vector Space Semantics for Similarity Between Friends Characters

This project involves creating vector representations of documents containing lines spoken by characters in the Friends script data. The goal is to improve these representations such that each character vector is maximally distinguished from others. This distinction is measured by how well a simple information retrieval classification method can select documents from validation and test data as belonging to the correct class of document (i.e., deciding which character spoke the lines by measuring the similarity of those character document vectors to those built in training).

## Project Structure

- `Vector-Space-Semantics-for-Similarity-Between-Friends-Characters.ipynb`: This notebook contains the entire workflow, including data loading, preprocessing, feature extraction, and evaluation using various techniques.

## Notebooks Overview

### `Vector-Space-Semantics-for-Similarity-Between-Friends-Characters.ipynb`

This notebook includes:
- Loading and parsing data from CSV files.
- Preprocessing text data (tokenization, normalization, etc.).
- Feature extraction using various techniques.
- Creating vector representations for character documents.
- Implementing and evaluating different improvements to enhance vector space semantics.
- Evaluating the performance of the character similarity classification method.

## Installation

To run the notebook, you need to have Python installed along with several packages. You can install the required packages using the following command:

```bash
pip install -r requirements.txt
