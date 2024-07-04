Movie Recommendation using TensorFlow Recommenders and Visualizing Performance using TensorBoard
This repository contains a Jupyter Notebook that demonstrates the implementation of two TensorFlow Recommenders (TFRS) models for the MovieLens dataset. It showcases how to build, train, and compare recommendation models, and how to visualize their performance using TensorBoard.

Table of Contents
Description
Installation
Usage
Notebook Structure
Results Visualization
Conclusion
License
Description
This repository includes:

Implementation of two different recommendation models using TensorFlow Recommenders.
Training and evaluation of the models on the MovieLens dataset.
Visualization of the training process using TensorBoard.
Installation
To run the notebook, you'll need to have Python installed along with several packages. You can install the necessary packages using pip:

sh
Copy code
pip install tensorflow tensorflow-recommenders tensorboard
Usage
Clone the repository:

sh
Copy code
git clone https://github.com/your-username/Movie-Recommendation-using-Tensorflow-Recommenders-and-Visualising-performance-using-tensorboard.git
cd Movie-Recommendation-using-Tensorflow-Recommenders-and-Visualising-performance-using-tensorboard
Open the Jupyter Notebook:

You can run Jupyter Notebook locally:
sh
Copy code
jupyter notebook
Or, open the notebook in Google Colab by uploading it.
Run the Notebook:

Follow the instructions provided in the notebook to load data, build models, train them, and visualize the results.
Notebook Structure
The notebook is divided into the following sections:

Loading Data:

Load the MovieLens dataset.
Prepare the data for training.
Model Definitions:

Define two different models with varying configurations:
Model v1: Uses swish activation functions and additional dense layers.
Model v2: Uses relu activation functions and additional dense layers.
Training:

Train both models for a specified number of epochs.
Save training logs to separate directories for TensorBoard visualization.
Evaluation:

Evaluate the performance of each model using metrics like categorical accuracy and loss.
Visualize the training process and results using TensorBoard.
Results Visualization
To view the training logs in TensorBoard:

Start TensorBoard:

python
Copy code
%load_ext tensorboard
%tensorboard --logdir logs/
Accessing TensorBoard:

If running locally, open the provided URL to access TensorBoard.
If running on Google Colab, follow the instructions in the notebook to access TensorBoard using ngrok (Note: Ensure you have an ngrok account and authtoken).
Conclusion
This notebook serves as a comprehensive guide for building and comparing different recommendation models using TensorFlow Recommenders. By following the steps outlined in the notebook, you can understand how different model configurations affect performance and how to visualize training metrics using TensorBoard.

License
This project is licensed under the MIT License. See the LICENSE file for details.

