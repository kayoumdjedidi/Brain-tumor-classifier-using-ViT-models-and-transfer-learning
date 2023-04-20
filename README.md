# Brain-tumor-classifier-using-ViT-models-and-transfer-learning
This was done as part of my participation in the Code to Cure Kaggle competition: https://www.kaggle.com/competitions/code-to-cure-10

In conclusion, this code is a machine learning script that loads image data from the dataset, which can be found on: https://www.kaggle.com/competitions/code-to-cure-10/data, preprocesses it using data augmentation techniques, trains a ViT model using transfer learning, and fine-tunes the model to improve its performance on the given dataset. The code utilizes various deep learning libraries such as Keras, PyTorch, and FastAI, and is designed for use in a Kaggle environment.
You will also find submission files.

The notebook performs the following operations:

1- Imports necessary libraries such as NumPy and Pandas.
2- Prints the list of files in the input directory.
3- Imports some deep learning libraries such as Keras, PyTorch, and FastAI.
4- Defines the path to the training data directory.
5- Defines data augmentation techniques such as flipping, rotating, zooming, and lighting.
6- Defines the datablock and dataloaders by specifying the blocks, items, labels, splitter, item transforms, and batch transforms.
7- Defines the model architecture using the Vision Transformer (ViT) model.
8- Fine-tunes the ViT model on the given dataset using transfer learning to improve the model's performance on the task.

