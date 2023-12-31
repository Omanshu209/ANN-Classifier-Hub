<div align = "center">
  <h1>
    <img src = "https://github.com/Omanshu209/ANN_ClassifierHub/assets/114089324/aa692968-2503-4b77-9647-df239588401d" width = "30px" />
    ANN Classifier Hub
    <img src = "https://github.com/Omanshu209/ANN_ClassifierHub/assets/114089324/aa692968-2503-4b77-9647-df239588401d" width = "30px" />
  </h1>
</div>

Welcome to this repository! This repository contains various **artificial neural network models** for different tasks, including the `Brain Tumor Classifier`, `Chess Piece Classifier model` and `Pepsi OR Coca Cola Classifier`.

<div align = "center">
  
  ![AltruisticInferiorFantail-max-1mb](https://github.com/Omanshu209/ANN_ClassifierHub/assets/114089324/98ebdcb0-12f6-4c09-b5d3-100dd9a24a20)
</div>

## Models

### Airline Passenger Satisfacton Classifier

- `Description` : The Airline Passenger Satisfacton Classifier model is **designed to classify whether a passenger is satisfied from his/her experience in the airline or not**. It has been trained on a large dataset and utilizes deep learning techniques to achieve accurate classification.

- `Accuracy Score` : **0.9199645826917154**

- `Precision` : **0.9186422413793104**

- `Recall` : **0.897132333596422**

- `F1 Score` : **0.9077598828696926**

- `Model` : **Available in the folder itself**

### Brain Tumor Classifier

- `Description` : The Brain Tumor Classifier model is **designed to classify whether a patient is suffering from `brain tumor` or not**. It has been trained on a large dataset of brain images and utilizes deep learning techniques to achieve accurate classification.

- `Accuracy Score` : **0.832**

- `Precision` : **0.8725490196078431**

- `Recall` : **0.7542372881355932**

- `Model` : [**Available on Google Drive**](https://drive.google.com/file/d/11a29WPOhG8jvzIhn3RZ8vqys0PURo7OB/view?usp=drivesdk)


### Chess Piece Classifier

- `Description` : The Chess Piece Classifier model is **designed to classify images of chess pieces into their respective categories**. It has been trained on a large dataset of labeled chess piece images and utilizes deep learning techniques to achieve accurate classification. The model can be used to identify the type of chess piece present in an image, such as `King`, `Queen`, `Bishop`, `Knight`, `Rook`, or `Pawn`.

- `Accuracy Score` : **0.8253968253968254**

- `Precision` : **0.8398689721270367**

- `Recall` : **0.8253968253968254**

- `Model` : [**Available on Google Drive**](https://drive.google.com/file/d/11xXDLyP71muAhgM3hyYnnBCOjyNDskf-/view?usp=drivesdk)


### Pepsi OR Coca Cola Classifier

- `Description` : The Pepsi OR Coca Cola Classifier model is **designed to classify a drink as `Pepsi` or `Coca Cola`**.

- `Accuracy Score` : **0.8833333333333333**

- `Precision` : **0.96**

- `Recall` : **0.8**

- `Model` : [**Available on Google Drive**](https://drive.google.com/file/d/123kZCDZvAtYs3TXL-1SYpCAf2YQ4Nvho/view?usp=drivesdk)


### Vehicle Classifier

- `Description` : The Vehicle Classifier model is **designed to classify images of vehicles into different categories**, such as `car`, `truck`, `bike`, `cycle`, `bus`, `helicopter`, `scooty` and `plane`. It has been trained on a diverse dataset of labeled vehicle images. The model can identify the type of vehicle present in an image, making it useful for applications like traffic analysis, object detection, and more.

- `Accuracy Score` : **0.3888888888888889**


### Tomato OR Apple Classifier

- `Description` : The Tomato OR Apple Classifier model is **designed to classify `tomatoes` and `apples`**.

- `Accuracy Score` : **0.6804123711340206**

- `Model` : [**Available on Google Drive**](https://drive.google.com/file/d/11yrMqLH9EhPUPzjgPXWj62kmrDSvu1bX/view?usp=drivesdk)


## Repository Structure
The repository is organized as follows:

```
- /Airline Passenger Satisfacton Classifier
  - /data                # data for training and testing
  - /model               # saved model
  - /notebook.ipynb      # jupyter notebook

- /Brain Tumor Classifier
  - /data                # data for training and testing
  - /notebook.ipynb      # jupyter notebook
  - /Brain Tumor.csv     # CSV file

- /Chess Piece Classifier
  - /data                # data for training and testing
  - /notebook.ipynb      # jupyter notebook

- /Pepsi OR Coca Cola Classifier
  - /data                # data for training and testing
  - /notebook.ipynb      # jupyter notebook

- /Tomato OR Apple Classifier
  - /data                # data for training and testing
  - /notebook.ipynb      # jupyter notebook

- /Vehicle Classifier
  - /data                # data for training and testing
  - /notebook.ipynb      # jupyter notebook

- LICENSE                # license

- README.md              # Overview and instructions for using the repository

- requirements.txt       # requirements.txt
```

## Requirements
To use the models, the following libraries must be installed:

```
torch            [v2.1.0+cu118]
torchaudio       [v2.1.0+cu118]
torchdata        [v0.7.0]
torchsummary     [v1.5.1]
torchtext        [v0.16.0]
torchvision      [v0.16.0+cu118]
matplotlib       [v3.4.3]
OpenCV           [v4.5.3.0]
numpy            [v1.21.2]
scikit-learn     [v1.0]
pandas           [v1.3.3]
joblib           [v1.0.1]
jupyter notebook [v1.0.0]
```
Run the following command in the terminal to install the libraries mentioned above:
```
pip3 install -r requirements.txt
```

## Usage
To run and use the models, follow the steps given below:

**1)** Run `Jupyter Notebook` using the following command

```
jupyter notebook
```

**2)** Go to the appropriate directory and open the `notebook.ipynb` file

**3)** Run all the cells

**4)** A file `savedModel.pkl` or `*****.pt` will be created(`or download it` from the link provided above in this README.md file), this is the saved model.

## Credits
The notebooks and models available in this repository are created and trained by **Omanshu**.
