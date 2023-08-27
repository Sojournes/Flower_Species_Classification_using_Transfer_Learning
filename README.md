Project Name: Flower Species Classification using Transfer Learning

Project Description:
In this project, a deep neural network is developed to classify images of flowers into one of five species using transfer learning. The dataset used for training and testing contains images of various flower species. The goal is to leverage the pre-trained GoogLeNet model, adapt it for flower classification, and achieve accurate predictions on new flower images.

Tools & Technologies Used:

--MATLAB
--Deep Learning Toolbox
--Pre-trained GoogLeNet model
--imageDatastore for data loading and organization
--AugmentedImageDatastore for image resizing
--TrainingOptions for configuring the training process
Project Output:

1. Data Preparation: The flower dataset is downloaded and organized into training and testing sets using the imageDatastore. Random splitting ensures diversity in both sets.
2. Model Architecture: The GoogLeNet architecture is imported and modified for the specific flower classification task. The classification and output layers are replaced to match the number of flower species.
3. Transfer Learning: The modified GoogLeNet model is fine-tuned on the flower dataset using a Stochastic Gradient Descent with Momentum (SGDM) optimization algorithm. The learning rate is set to 0.001 to facilitate effective transfer learning.
4. Training: The model is trained on the resized training images using the training options. The training process aims to adapt the pre-trained model to recognize and classify the distinct features of different flower species.
5. Testing and Evaluation: The trained model is used to predict the species of flowers in the testing set. The accuracy of the model is calculated by comparing the predicted labels with the actual labels of the test images.
6. Accuracy Assessment: The accuracy of the model is calculated by dividing the number of correct predictions by the total number of predictions made on the testing set.
7. Visualization: The confusion matrix is plotted using a confusion chart to provide a visual representation of the model's performance in classifying different flower species.

By implementing this project, the team aims to showcase the effectiveness of transfer learning in adapting pre-trained models for specific classification tasks. The output of the project is a trained model capable of accurately classifying flower species, along with an evaluation of its performance using accuracy metrics and a confusion matrix. This project serves as an example of how to leverage existing deep learning architectures and tools to create powerful image classification solutions with minimal data and computation effort.
