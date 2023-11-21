<div align='center'>

<h1>Plant disease diagnosis Using ResNet50</h1>
<p>Multi class classifier made using transfer learning with pre-trained model ResNet50 , that detects 12 different diseases in plant leaves of three different plant types: Pepper, Potato, and Tomato</p>

</div>

# About
This GitHub repository contains the code and resources for a multi-class classifier for diagnosing diseases in plant leaves. The classifier is built using transfer learning with the pre-trained ResNet50 model. It can identify diseases in leaves of three different plant types: Pepper, Potato, and Tomato. The classifier can distinguish between various disease classes and healthy leaves within these plant categories, with a total of 15 different classes. The goal of this project is to help identify plant diseases early, which can be crucial for preventing crop loss and ensuring food security


Plant diseases can significantly impact crop yields and quality. Early detection of these diseases is vital for timely intervention. This project leverages the power of transfer learning and the ResNet50 model to create a multi-class classifier capable of identifying 15 different types of plant diseases. The classifier can be used to analyze images of plant leaves and determine if they are healthy or affected by one of the specified diseases.

# Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Libraries Used](#libraries-used)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Contributing](#contributing)

## Installation

To use this project, follow these steps:

1. Clone the repository:

```bash
   git clone https://github.com/Sukanyasingh3/plant-disease-diagnosis.git
   ```
2. Install the required dependencies:
  ```bash
   pip install -r requirements.txt
```
## Usage

1. Navigate to the project directory:

```bash
   cd plant-disease-diagnosis
   ```
2. Install the required dependencies:
  ```bash
   python app.py
```
This will start the plant disease diagnosis application.

# Dataset
The PlantVillage Dataset is used for training and evaluating the model, it can be found on Kaggle at the following link: [The PlantVillage Dataset](https://www.kaggle.com/datasets/emmarex/plantdisease)

It consists of images of plant leaves from three different plant types (pepper, potato, and tomato) and 15 different classes of diseases. The dataset is structured as follows:

 - Pepper__bell___Bacterial_spot

 - Pepper__bell___healthy

 - Potato___Early_blight

 - Potato___Late_blight

 - Potato___healthy

 - Tomato_Bacterial_spot

 - Tomato_Early_blight

 - Tomato_Late_blight

 - Tomato_Leaf_Mold

 - Tomato_Septoria_leaf_spot

 - Tomato_Spider_mites_Two_spotted_spider_mite

 - Tomato__Target_Spot

 - Tomato__Tomato_YellowLeaf__Curl_Virus

 - Tomato__Tomato_mosaic_virus

 - Tomato_healthy

# Libraries Used
The project utilizes the following libraries: 

 - TensorFlow 

 - Keras 

 - NumPy 

 - OpenCV (cv2) 

 - Matplotlib

# Model Architecture
The core of this project is the ResNet50 model, a powerful convolutional neural network pre-trained on ImageNet. Transfer learning is employed to fine-tune this model on the plant disease dataset. The model is trained to recognize the unique patterns and features associated with each disease class.

The ResNet50 model is employed for transfer learning. The training script and pre-trained weights are available in the train_model directory.

To train the model, run:
  ```bash
   python train_model.py
```

# Results
After training, the model achieves an accuracy of 98% on the train set and 96% on the test set.
## Acuracy:
![Accuracy](https://github.com/Sukanyasingh3/Plant-disease-diagnosis/assets/113462236/65bf4c26-4826-425f-93a7-8be9a7ea5dfa)

## Loss:

![Loss](https://github.com/Sukanyasingh3/Plant-disease-diagnosis/assets/113462236/73cf6cb7-fb0a-46e8-8d11-d7dd5a2b7ac6)

# Contributing

If you would like to contribute to the project, follow these steps:

 - Fork the repository.
 - Create a new branch for your feature or bug fix.
 - Make your changes and submit a pull request.









