# Dog-Breed-Image-Classifier-

## Description

This project is an image classification application that uses a convolutional neural network (CNN) to classify images of dogs into different breeds. The CNN has been pre-trained on a vast dataset of 1.2 million images from ImageNet. The goal of this project is to explore and compare three different CNN architectures (`AlexNet`, `VGG`, and `ResNet`) to determine which one is best suited for the dog breed classification task.

## Features

- Utilizes pre-trained CNN models (`AlexNet`, `VGG`, and `ResNet`).
- Measures program runtime using the Python `time` module.
- Accepts user inputs via command line arguments.
- Creates pet image labels based on image filenames and stores them in a dictionary.
- Uses the classifier function to classify images and generate classifier labels.
- Compares classifier labels to pet image labels and stores the results in a complex data structure.
- Classifies labels as "Dogs" or "Not Dogs" using the `dognames.txt` file.
- Calculates and prints the algorithm's performance results, including accuracy metrics.

## Getting Started

### Prerequisites

Ensure you have the following prerequisites installed:

- Python 3.x
- PyTorch
- ...

### Installation

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip` or `conda`.
3. Download the pre-trained model weights if necessary.
4. Prepare your input images and create a JSON file for category names.

## Usage

To classify dog breeds in your images, run the following command:

```bash
python test_classifier.py -d input_images -a resnet18 -k 3 -c category_names.json
