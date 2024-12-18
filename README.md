# Facial Emotion Recognition Using HoG and LBP

## Project Description
This project implements a facial emotion recognition system using Histogram of Oriented Gradients (HoG) and Local Binary Patterns (LBP) as feature extraction techniques. 
The system is evaluated on two datasets: the JAFFE dataset and the Cohn-Kanade (CK+) dataset, and classification is performed using Support Vector Machines (SVM) and Decision Tree classifiers.

## Features
- Facial emotion recognition using HoG and LBP features.
- Classification using SVM and Decision Tree models.
- Evaluation on JAFFE and Cohn-Kanade (CK+) datasets.
- Comparison of model performance.

## Project Structure
- `facialrecog.ipynb`: The primary notebook containing the code for training and evaluating the models.
- `JAFFE-[70,30](2).zip`: Folder containing the JAFFE dataset.
- `CK_Dataset(3)`: Folder containing the Cohn-Kanade dataset.
- `README.md`: This file, providing an overview of the project.

## How to Run
1. Clone the repository:
   ```
   git clone https://github.com/rkkapali/FacialEmotionRecognition.git
   ```
2. Open `facialrecog.ipynb` in Google Colab or Jupyter Notebook.
3. Upload the datasets (`JAFFE` and `Cohn-Kanade`) to the specified folders.
4. Run the cells in the notebook to train and evaluate the models.
