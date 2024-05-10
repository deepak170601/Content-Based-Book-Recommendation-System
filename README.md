

---

# Content-Based Book Recommendation System

This project implements a content-based book recommendation system using a neural network with triplet loss and sentence embeddings. The model is trained using triplet data and evaluated using test datasets generated with a nearest neighbors approach.

## Table of Contents

- [Project Overview](#project-overview)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Test Data Generation](#test-data-generation)
- [Evaluation and Fine-Tuning](#evaluation-and-fine-tuning)

## Project Overview

The content-based book recommendation system uses a Sentence Transformer model to encode book titles and descriptions into numerical embeddings that capture the semantic meaning of texts. A triplet loss model is trained on triplet data consisting of anchor, positive, and negative samples. The trained model is evaluated using test data sets and optimized for accurate recommendations.

## Setup and Installation

To set up and install the project, follow the instructions below:

1. **Clone the Repository**:
    Clone the repository and navigate to the project directory:
    ```bash
    git clone [https://github.com/deepak170601/Content-Based-Book-Recommendation-System]
    cd [content-based-book-recommendation]
    ```

2. **Create a Virtual Environment**:
    Create and activate a virtual environment to manage dependencies:
    ```bash
    python -m venv venv
    source venv/bin/activate  # For Linux/Mac
    # For Windows, use:
    # venv\Scripts\activate
    ```

3. **Install Dependencies**:
    Install the required Python packages using the following command:
    ```bash
    pip install torch torchaudio torchvision sentence-transformers faiss-gpu
    ```

## Usage

Provide instructions here for how to use the recommendation system. This can include how to input data and receive book recommendations.


## Test Data Generation

To generate test data:

1. **Run the Script**:
    Run the script to generate test data:
    ```bash
    python test_data_generation.py
    ```

## Evaluation and Fine-Tuning

To evaluate and fine-tune the model:

1. **Run the Script**:
    Run the script for evaluation and fine-tuning:
    ```bash
    python fine_tune_model.py
    ```



