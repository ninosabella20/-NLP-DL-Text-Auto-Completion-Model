# Star Wars Movie Scripts Text Autocompletion

## Overview

This project explores the capabilities of deep learning in natural language processing (NLP) by developing a text autocompletion model based on the original three Star Wars movie scripts. Leveraging recurrent neural networks (RNNs), specifically Long Short-Term Memory (LSTM) networks, we aim to predict the next word in a given sequence of dialogue, thereby facilitating interactive text generation that aligns with the iconic narratives of the Star Wars universe.

## Table of Contents

- [Project Motivation](#project-motivation)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Results](#results)
- [Visualizations](#visualizations)

## Project Motivation

The advent of artificial intelligence and machine learning has revolutionized various fields, with natural language processing being at the forefront of this transformation. By utilizing the rich dialogues found in the Star Wars scripts, this project aims to not only demonstrate the technical prowess of deep learning models but also engage with the narrative creativity that defines the franchise. 

This initiative serves as an educational exploration into text generation, enabling insights into model training, data processing, and the underlying algorithms that facilitate language understanding.

## Dataset

The dataset utilized in this project consists of the complete scripts from the original three Star Wars films. The data was sourced from Kaggle and is accessible [here](https://www.kaggle.com/datasets/xvivancos/star-wars-movie-scripts). The scripts were processed to extract meaningful dialogues and character interactions, forming the basis for training our predictive model.

## Methodology

### Data Processing

1. **Data Cleaning**: The scripts were analyzed and cleaned to remove extraneous characters and annotations, resulting in a structured DataFrame comprising two primary columns: **Character** and **Dialogue**.
2. **Word Analysis**: We performed an exploratory data analysis (EDA) to identify the most frequently used words, facilitating a better understanding of dialogue patterns within the scripts.

### Model Development

1. **Tokenization**: The cleaned dialogues were tokenized to convert text data into a format suitable for input into the LSTM model.
2. **LSTM Architecture**: The model architecture was defined using Keras, comprising an embedding layer, two LSTM layers, and a dense output layer. The model was trained for 50 epochs with a batch size of 50.

### Training and Evaluation

The model was evaluated based on accuracy and loss metrics, achieving a notable accuracy of **90%** and a loss of **0.4185**. These metrics indicate the model's robustness in learning the context and structure of the dialogues.

## Results

The LSTM model successfully generated contextually relevant sentences reminiscent of Star Wars dialogues, showcasing its capacity for creative text generation. The high accuracy and low loss underscore the model's effectiveness in understanding the nuances of the training data.

## Visualizations

To illustrate the training process and model performance, we generated visualizations of accuracy and loss metrics over epochs. These visualizations serve as an effective means of demonstrating the model's learning progression and convergence.
