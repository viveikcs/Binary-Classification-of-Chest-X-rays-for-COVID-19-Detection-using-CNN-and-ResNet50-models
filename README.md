# Binary Classification of Chest X-rays for COVID-19 Detection using CNN and ResNet50 models

**DESCRIPTION**

Trained and Developed a CNN model for detecting COVID-19 using the concept of binary image classification of the COVID-infected and normal chest X-ray images that were used as the training and testing data. The performance and accuracy of the developed CNN model was compared with a pre-trained ResNet50 CNN model.

**OBJECTIVES**
- Predict COVID-19 infection from a chest CT scan image
- Train CNN model with normal & infected chest X-ray images.
- Compare the developed CNN model with the pretrained ResNet50 model using performance metrics and visualizations.

**STRUCTURE**

The repository includes three Jupyter notebooks:
- CNN Model - Pre-trained
-     The pre-trained ResNet50 model
  
- CNN Model - Trained Phase-1
-   The trained and developed CNN model along with results of Phase-1 of the Testing phase.

- CNN Model - Trained Phase-2
-   The trained and developed CNN model along with results of Phase-2 of the Testing phase.

**DATASET**
- COVID-19 Chest X-ray Image Dataset (Link: https://www.kaggle.com/datasets/alifrahman/covid19-chest-xray-image-dataset/data?select=dataset)
- COVID-19 Radiography Dataset (Link: https://www.kaggle.com/datasets/preetviradiya/covid19-radiography-dataset)

**TECHNOLOGIES**

Python, TensorFlow, Keras, NumPy, Matplotlib, Seaborn, Image Preprocessing, Google Colab

**TESTING**

The trained and developed CNN model was tested in two distinct phases to assess generalization and robustness. Both testing phases utilized different quantites of the chest X-ray images.

**RESULTS**

| Model      | Training Accuracy | Validation Accuracy |
| ---------- | ----------------- | ------------------- |  
| Custom CNN |        100%       |         90%         |
| ResNet50   |        84%        |         96%         |

The CNN model showed Accuracy in detecting the presence of COVID-19, compared to the ResNet50 model.

**CONTACT**

Feel free to reach out: viveikcs@gmail.com
