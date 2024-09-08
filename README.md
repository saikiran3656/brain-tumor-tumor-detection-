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

![Screenshot 2024-09-08 183604](https://github.com/user-attachments/assets/f1b592f1-2e89-48c9-8b3e-36e5e56b677b)

created a dataloader using PyTorch for dataset loadding and concatinationg the dataset

![Screenshot 2024-09-08 183628](https://github.com/user-attachments/assets/0798cf1e-f24e-4163-9dfb-985535924349)

![Screenshot 2024-09-08 183641](https://github.com/user-attachments/assets/29a76268-c95f-4fc9-b72c-d5de818662d9)

![Screenshot 2024-09-08 183641](https://github.com/user-attachments/assets/4ad4aa0a-a308-465b-bd5e-ada7468ed541)

imported seaborn for data visuvalization and sklearn for confision matrix

![Screenshot 2024-09-08 183713](https://github.com/user-attachments/assets/7d8407ec-cc48-4ade-aea8-db5f7d00e941)

separation between two classes: "Tumor" and "Healthy"

![Screenshot 2024-09-08 183728](https://github.com/user-attachments/assets/b4fe247c-1882-4235-a0c3-9cb162230b30)


accessing 100th index of MRI image

![Screenshot 2024-09-08 184050](https://github.com/user-attachments/assets/7ed72dde-2a2a-411d-8bf7-06badf5bb96d)

 the outputs list contains the feature maps of each layer in the CNN, and the layer_viz variable contains the feature maps of the current layer. 

 ![Screenshot 2024-09-08 184150](https://github.com/user-attachments/assets/11b40db2-05f6-4cdb-a335-3e161c7f6a7d)


 






