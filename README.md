# mnist-digit-recognition
Handwritten Digit Recognition with Neural Networks
A simple PyTorch project that trains a Multilayer Perceptron (MLP) to recognize handwritten digits from the MNIST dataset. It includes training, evaluation, visualization of results, and an option to predict on external images.

Project Overview
Goal: Classify 28×28 images of handwritten digits (0–9) with high accuracy.

Approach:

Use the MNIST dataset for training and testing.

Build an MLP model with fully connected layers and ReLU activations.

Train using the Adam optimizer and CrossEntropyLoss.

Evaluate with accuracy and a confusion matrix.

(Optional) Predict custom handwritten digit images.

Features
Data Loading & Preprocessing:

Automatically downloads MNIST.

Normalizes images for consistent training.

Model Training & Evaluation:

Prints training loss and accuracy per epoch.

Computes test accuracy and confusion matrix.

Visualization:

Plots training loss and accuracy curves with Matplotlib.

Displays a confusion matrix.

External Image Prediction (Optional):

Loads and preprocesses your own digit image.

Outputs the predicted digit after applying the trained model.

Setup & Installation
Clone the Repository:

bash
Copy
git clone https://github.com/<USERNAME>/<REPO>.git
cd <REPO>
Install Dependencies:

bash
Copy
pip install torch torchvision torchaudio
pip install matplotlib scikit-learn
(Or use conda install pytorch torchvision torchaudio -c pytorch if using Conda.)

Run the Script:

Python Script:

bash
Copy
python main.py
Jupyter Notebook:
Open Handwritten_Digit_Recognition.ipynb in Jupyter and run the cells.

Usage
Training:

Edit num_epochs and batch_size if desired.

Run the training cell or script to train the MLP on MNIST.

Testing:

The script automatically evaluates the model on the test set.

Prints the final accuracy and displays a confusion matrix.

External Image Prediction:

Place your digit image in the project folder.

Update the image_path variable in the code.

Set parameters like invert_image and apply_threshold if needed.

Run the prediction cell or function call to see the result.

Visualizations:

The script generates Matplotlib plots of the training loss, accuracy, and confusion matrix.
