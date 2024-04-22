# Facial Age Recognition

## Description
This project aims to develop a facial age recognition system using deep learning techniques. The system takes facial images as input and predicts the age range of the person in the image. It can be used for various applications such as age-based demographic analysis, targeted advertising, and personalized content recommendation.

## Features
- Dataset download and preprocessing using the Kaggle API.
- Visualization of age-labeled facial images.
- Data augmentation for improving model generalization.
- Training of a Convolutional Neural Network (CNN) model for age prediction.
- Evaluation of the model's performance using test data.
- Saving and loading of the trained model for inference.

## Requirements
- Python
- TensorFlow 
- Keras
- NumPy
- Pandas
- Matplotlib
- Pillow
- scikit-learn

## Usage
1. Clone the repository:
`git clone https://github.com/abdallaellaithy/Facial-Age-Recognition.git`
2. Navigate to the project directory:
`cd Facial-Age-Recognition`
3. Install dependencies:
`pip install -r requirements.txt`
4. Run the Jupyter notebook `Facial_Age_Recognition.ipynb` to execute the entire pipeline from dataset download to model evaluation.
5. Optionally, you can use the trained model for inference by running the script `predict_age.py` and providing a path to the image you want to analyze.

## Dataset
The dataset used in this project is the "Facial Age" dataset available on Kaggle. It contains images of faces labeled with age ranges. The dataset is downloaded and preprocessed automatically using the Kaggle API.

## Contributors
- [Abdalla Ellaithy](https://github.com/abdallaellaithy) - Project Lead & Developer

## License
This project is licensed under the **MIT License**.
