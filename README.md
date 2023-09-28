<div align='center'>

<h1>Plant disease diagnosis Using ResNet50</h1>
<p>Multi class classifier made using transfer learning with pre-trained model ResNet50 , that detects 12 different diseases in plant leaves of three different plant types: Pepper, Potato, and Tomato</p>

</div>

# About
This GitHub repository contains the code and resources for a multi-class classifier for diagnosing diseases in plant leaves. The classifier is built using transfer learning with the pre-trained ResNet50 model. It can identify diseases in leaves of three different plant types: Pepper, Potato, and Tomato. The classifier can distinguish between various disease classes and healthy leaves within these plant categories, with a total of 15 different classes. The goal of this project is to help identify plant diseases early, which can be crucial for preventing crop loss and ensuring food security


Plant diseases can significantly impact crop yields and quality. Early detection of these diseases is vital for timely intervention. This project leverages the power of transfer learning and the ResNet50 model to create a multi-class classifier capable of identifying 15 different types of plant diseases. The classifier can be used to analyze images of plant leaves and determine if they are healthy or affected by one of the specified diseases.
# Dataset
The PlantVillage Dataset is used for training and evaluating the model, it can be found on Kaggle at the following link: [The PlantVillage Dataset](https://www.kaggle.com/datasets/emmarex/plantdisease)
It consists of images of plant leaves from three different plant types (pepper, potato, and tomato) and 15 different classes of diseases. The dataset is structured as follows:

Pepper__bell___Bacterial_spot

Pepper__bell___healthy

Potato___Early_blight

Potato___Late_blight

Potato___healthy

Tomato_Bacterial_spot

Tomato_Early_blight

Tomato_Late_blight

Tomato_Leaf_Mold

Tomato_Septoria_leaf_spot

Tomato_Spider_mites_Two_spotted_spider_mite

Tomato__Target_Spot

Tomato__Tomato_YellowLeaf__Curl_Virus

Tomato__Tomato_mosaic_virus

Tomato_healthy

# Libraries Used
The project utilizes the following libraries: 

TensorFlow 

Keras 

NumPy 

OpenCV (cv2) 

Matplotlib

# Model Architecture
The core of this project is the ResNet50 model, a powerful convolutional neural network pre-trained on ImageNet. Transfer learning is employed to fine-tune this model on the plant disease dataset. The model is trained to recognize the unique patterns and features associated with each disease class.
# Results
After training, the model achieves an accuracy of 98% on the train set and 96% on the test set.






