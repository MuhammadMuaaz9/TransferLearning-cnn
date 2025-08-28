# Transfer Learning for Dog Breed Classification

This project demonstrates transfer learning using Convolutional Neural Networks (CNNs) to classify dog breeds. The main notebook (`transfer_learning.ipynb`) guides you through loading a dog image dataset, visualizing images, extracting bottleneck features using VGG-16, building and training models, and evaluating their performance.

## Project Structure

- `transfer_learning.ipynb`: Main notebook for dog breed classification using transfer learning.
- `bottleneck_features.ipynb`: Demonstrates how to compute bottleneck features with VGG-16.
- `dogImages/`: Folder containing the dog breed images dataset (download required).
- `bottleneck_features/`: Folder for storing precomputed bottleneck features (download required).

## Setup Instructions

1. **Download the Dog Images Dataset**  
   Download [dogImages.zip](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip) and extract it into the project folder.

2. **Download Bottleneck Features**  
   Download [DogVGG16Data.npz](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz) and place it in the `bottleneck_features/` folder.

3. **Install Required Packages**  
   Install dependencies using:
   ```
   pip install -r requirements.txt
   ```

## Usage

Open `transfer_learning.ipynb` in Jupyter Notebook or VS Code and run the cells sequentially. Follow the instructions in the markdown cells to download datasets and bottleneck features before running relevant code cells.

## Requirements

See `requirements.txt` for a list of required Python packages.

## References

- [VGG-16 Paper](https://arxiv.org/abs/1409.1556)
- [Keras Documentation](https://keras.io/)

- [Udacity Dog Project](https://github.com/udacity/dog-project)

  👨‍💻 Author Muhammad Muaaz
