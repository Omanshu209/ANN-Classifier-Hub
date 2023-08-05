# ANN Classifier Hub
Welcome to this repository! This repository contains various **artificial neural network models** for different tasks, including the `Chess Piece Classifier model`, `Vehicle Classifier model` and `Tomato OR Apple Classifier model`.

<div align = "center">
  
  ![AltruisticInferiorFantail-max-1mb](https://github.com/Omanshu209/ANN_ClassifierHub/assets/114089324/98ebdcb0-12f6-4c09-b5d3-100dd9a24a20)
</div>

## Models

### Chess Piece Classifier
The Chess Piece Classifier model is **designed to classify images of chess pieces into their respective categories**. It has been trained on a large dataset of labeled chess piece images and utilizes deep learning techniques to achieve accurate classification. The model can be used to identify the type of chess piece present in an image, such as `King`, `Queen`, `Bishop`, `Knight`, `Rook`, or `Pawn`.

### Vehicle Classifier
The Vehicle Classifier model is **designed to classify images of vehicles into different categories**, such as `car`, `truck`, `bike`, `cycle`, `bus`, `helicopter`, `scooty` and `plane`. It has been trained on a diverse dataset of labeled vehicle images. The model can identify the type of vehicle present in an image, making it useful for applications like traffic analysis, object detection, and more.

### Tomato OR Apple Classifier
The Tomato OR Apple Classifier model is **designed to classify `tomatoes` and `apples`**.

## Repository Structure
The repository is organized as follows:

```
- /Chess Piece Classifier
  - /data                # data for training and testing
  - /model.ipynb         # jupyter notebook

- /Tomato OR Apple Classifier
  - /data                # data for training and testing
  - /model.ipynb         # jupyter notebook

- /Vehicle Classifier
  - /data                # data for training and testing
  - /model.ipynb         # jupyter notebook

- README.md              # Overview and instructions for using the repository

- requirements.txt       # requirements.txt
```

## Requirements
To use the models, the following libraries must be installed:

```
matplotlib       [v3.4.3]
OpenCV           [v4.5.3.0]
numpy            [v1.21.2]
scikit-learn     [v1.0]
joblib           [v1.0.1]
jupyter notebook [v1.0.0]
```
Run the following command in the terminal to install the libraries mentioned above:
```
pip3 install -r requirements.txt
```
**OR**
```
pip3 install matplotlib==3.4.3 opencv-python==4.5.3.0 numpy==1.21.2 scikit-learn==1.0 joblib==1.0.1 jupyter==1.0.0
```

## Usage
To run and use the models, follow the steps given below:

**1)** Run `Jupyter Notebook` using the following command

```
jupyter notebook
```

**2)** Go to the appropriate directory and open the `model.ipynb` file

**3)** Run all the cells

**4)** A file `savedModel.pkl` will be created, this is the saved model. You can use this saved model in any python script by loading it using the `joblib` library.

```
from joblib import load
model = load("savedModel.pkl")
#.........Rest of the python code
```

## Credits
The models available in this repository are created and trained by **Omanshu**.
