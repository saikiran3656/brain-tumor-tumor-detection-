# brain-tumor-tumor-detection

Overview

This project aims to classify brain tumors as either malignant or benign using Convolutional Neural Networks (CNNs).
The dataset consists of MRI images of brains, which are preprocessed and fed into a CNN model for classification.

Dataset

The dataset used for this project is the Brain Tumor Dataset, which consists of 253 images of brains with tumors.
The images are divided into two classes: malignant (155 images) and benign (98 images).
The images are preprocessed to resize them to 128x128 pixels and normalize the pixel values.

Model

The CNN model used for this project consists of multiple convolutional layers, followed by fully connected layers.
The model is trained using the Adam optimizer and binary cross-entropy loss function.
The model is implemented using PyTorch.

Features

- Data preprocessing: Resizing images to 128x128 pixels, normalizing pixel values
- Data augmentation: Random flipping, rotation, and cropping
- CNN model: Multiple convolutional layers, fully connected layers
- Training: Adam optimizer, binary cross-entropy loss function
- Evaluation: Accuracy, precision, recall, F1-score

Results

The model achieves an accuracy of 95% on the test dataset. The precision, recall, 
and F1-score are also calculated to evaluate the model's performance.

Requirements

- Python 3.8+
- PyTorch 1.9+
- Torchvision 0.10+
- OpenCV 4.5+
- NumPy 1.20+
- Matplotlib 3.4+

used mathplotlib for Visualizing Brain MRI Images

![Screenshot 2024-09-08 113926](https://github.com/user-attachments/assets/2028db22-9071-4b31-a04f-ce0c9c02df86)

created a dataloader using PyTorch for dataset loadding and concatinationg the dataset

![Screenshot 2024-09-08 113943](https://github.com/user-attachments/assets/89906fb1-e4d6-48d3-a42d-cc2fb19bc36a)

![Screenshot 2024-09-08 122130](https://github.com/user-attachments/assets/d0e6864b-b52d-4b1e-8426-a7735dfdf9a1)


imported seaborn for data visuvalization and sklearn for confision matrix

![Screenshot 2024-09-08 114022](https://github.com/user-attachments/assets/5f9d62f6-7db8-4c6d-85ef-43a105662f55)

separation between two classes: "Tumor" and "Healthy"

![Screenshot 2024-09-08 114039](https://github.com/user-attachments/assets/422952fa-bc17-43fb-bad6-4fdd049057ff)

accessing 100th index of MRI image

![Screenshot 2024-09-08 114140](https://github.com/user-attachments/assets/84597c6b-c01b-4066-9633-91a517d165f9)

 the outputs list contains the feature maps of each layer in the CNN, and the layer_viz variable contains the feature maps of the current layer. 

 ![Screenshot 2024-09-08 114156](https://github.com/user-attachments/assets/208c2ff8-d5ec-4eb9-b071-e136c7e53d81)

 






