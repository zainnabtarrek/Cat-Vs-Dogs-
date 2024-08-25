# Cat-Vs-Dogs-

# ResNet-18 Transfer Learning with PyTorch

This project demonstrates transfer learning using a pre-trained ResNet-18 model to classify images from the Microsoft Cats vs. Dogs dataset. The project uses PyTorch for model training and validation and TensorBoard for visualization.

## Project Overview
This project applies transfer learning by fine-tuning a ResNet-18 model on a custom dataset (Cats vs. Dogs). The model is trained using PyTorch, and various metrics like accuracy, precision, recall, and F1-score are calculated. TensorBoard is used to visualize the training process, including losses, accuracy, and the confusion matrix.

## Prerequisites
- Python 3.x
- PyTorch
- torchvision
- TensorBoard
- Matplotlib
- Seaborn
- PIL (Python Imaging Library)
- scikit-learn




   Download the Microsoft Cats vs. Dogs dataset from Kaggle [here](https://www.kaggle.com/datasets/shaunthesheep/microsoft-catsvsdogs-dataset).

   After downloading, extract the dataset and place it in the `PetImages/` directory. The directory structure should look like this:
   ```
   PetImages/
   ├── train/
   │   ├── Dog/
   │   └── Cat/
   └── val/
       ├── Dog/
       └── Cat/
   ```
Evaluating the Model :
The model's performance is evaluated on the validation set after each epoch. Key metrics include:
- Loss
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

These metrics are printed to the console and logged to TensorBoard.

