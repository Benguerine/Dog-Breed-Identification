# Dog Breed Identification

## Description

Who's a good dog? Who likes ear scratches? Well, it seems those fancy deep neural networks don't have all the answers. However, maybe they can answer that ubiquitous question we all ask when meeting a four-legged stranger: what kind of good pup is that?

In this playground competition, you are provided a strictly canine subset of ImageNet in order to practice fine-grained image categorization. How well can you tell your Norfolk Terriers from your Norwich Terriers? With 120 breeds of dogs and a limited number of training images per class, you might find the problem more, err, ruff than you anticipated.

## Example Image

![Dog Example](https://storage.googleapis.com/kaggle-media/competitions/kaggle/3333/media/border_collies.png)

## Installation

To run this project, you will need the following packages installed:

```bash
pip install tensorflow tensorflow-hub
```
or
```base
pip install -r requirements.txt
```
## Folder Structure
```base
Dog-Breed-Identification/
│
├── Data/                   # Dataset files (excluded from Git due to size)
├── Model/                  # Model training and evaluation notebooks
├── README.md               # This file
├── .gitignore              # Ignored files/folders (e.g., Data/)
├── requirements.txt        # Python dependencies
```

## Usage
1. Clone this repository.
2. Make sure your dataset is placed inside the Data folder (this folder is excluded from Git due to size).
3. Run the Jupyter notebooks inside the Model folder to train or evaluate models.
4. Start a notebook with:
```base
jupyter notebook Model/Dog-Breed-Identification.ipynb
```
## Features
1. Fine-grained classification of 120 dog breeds.
2. Built using deep convolutional neural networks with TensorFlow.
3. Uses TensorFlow Hub for transfer learning with pretrained models.
4. Designed to work well with limited labeled data per class.

