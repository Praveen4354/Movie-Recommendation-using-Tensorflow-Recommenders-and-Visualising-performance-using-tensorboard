# Movie Recommendation using TensorFlow Recommenders and Visualizing Performance using TensorBoard

This repository contains a Jupyter Notebook that demonstrates the implementation of two TensorFlow Recommenders (TFRS) models for the MovieLens dataset. It showcases how to build, train, and compare recommendation models, and how to visualize their performance using TensorBoard.

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Notebook Structure](#notebook-structure)
- [Results Visualization](#results-visualization)
- [Conclusion](#conclusion)
- [License](#license)

## Description

This repository includes:

- Implementation of two different recommendation models using TensorFlow Recommenders.
- Training and evaluation of the models on the MovieLens dataset.
- Visualization of the training process using TensorBoard.

## Installation

To run the notebook, you'll need to have Python installed along with several packages. You can install the necessary packages using pip:

```sh
pip install tensorflow tensorflow-recommenders tensorboard

## Usage

### Clone the repository:

```sh
git clone https://github.com/your-username/Movie-Recommendation-using-Tensorflow-Recommenders-and-Visualising-performance-using-tensorboard.git
cd Movie-Recommendation-using-Tensorflow-Recommenders-and-Visualising-performance-using-tensorboard

### Open the Jupyter Notebook:

- **Locally**: Run Jupyter Notebook:
  ```sh
  jupyter notebook

- **Open in Google Colab**:
  - Upload the notebook to Google Colab.
  
- **Run the Notebook**:
  - Follow the notebook instructions to load data, build models, train them, and visualize results.

## Notebook Structure

### Loading Data

- Load the MovieLens dataset.
- Prepare the data for modeling.

### Building Models

- Define user and movie models with different configurations.
- Create a TFRS model for each configuration.

### Training Models

- Compile models with appropriate optimizers and loss functions.
- Train models and log results using TensorBoard.

### Evaluating Models

- Set up retrieval using brute-force search with trained representations.
- Evaluate and compare model performance.

### Visualizing Results

- Visualize training metrics and compare models using TensorBoard.

## Conclusion

This notebook demonstrates building and comparing movie recommendation models using TensorFlow Recommenders. It illustrates effective use of TensorBoard for visualizing training and comparing model performance.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
