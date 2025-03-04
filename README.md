# Flower Classification using Deep Learning

## Overview
This project is a deep learning-based flower classification system that can recognize different types of flowers using a trained model. The model is built using **TensorFlow/Keras** and trained in **Jupyter Lab**, while the deployment is handled using **Flask** in **VS Code**.

## Features
- Image classification of flowers into categories such as **daisy, dandelion, rose, sunflower, and tulip**.
- Model trained using a dataset of flower images.
- Web-based application for uploading and predicting flower types.
- Uses a pre-trained **CNN (Convolutional Neural Network)** model.

## Project Structure
```
Flower-Classification-DeepLearning/
│── images/                   # Dataset of flower images
│── Sample/                   # Sample images for testing
│── upload/                   # Uploaded images for prediction
│── app.py                    # Flask web application
│── Flower_Recog_Model.h5      # Trained deep learning model
│── Flower_Recognition_Model.ipynb # Jupyter Notebook for training
│── .gitignore                 # Files to ignore in GitHub
│── README.md                  # Project Documentation
```

## Installation & Setup
### Prerequisites
Make sure you have the following installed:
- Python 3.x
- Jupyter Lab
- VS Code
- TensorFlow/Keras
- Flask

### Install Dependencies
```bash
pip install tensorflow keras flask numpy pandas matplotlib
```

## Running the Model
### Train the Model
Run the Jupyter Notebook to train the model:
```bash
jupyter lab
```
Open `Flower_Recognition_Model.ipynb` and execute the cells.

### Run the Web Application
Start the Flask server:
```bash
python app.py
```
The application will be available at `http://127.0.0.1:5000/`.

## Usage
1. Upload an image of a flower using the web app.
2. The model will predict and display the flower type.
3. View classification results in real time.
   
```bash
## License
This project is open-source and available under the MIT License.

## Author
**W G Lahiru Dhananjaya Bandara**

```
