# 🌿 Plant Disease Detection

## Overview

The **Plant Disease Detection** project is a web application aimed at helping farmers and agricultural experts diagnose plant diseases through images of plant leaves. Leveraging a deep learning model trained on a dataset of plant leaf images, the tool quickly and accurately identifies diseases, providing timely insights to prevent disease spread and enhance crop health.

## ✨ Features

- **Image Upload**: Users can upload images of plant leaves via a user-friendly interface.
- **Disease Prediction**: The app processes uploaded images to predict the type of disease affecting the plant.
- **Class Labels**: Identifies 38 different plant diseases, including healthy plants.
- **Backend Processing**: Flask-powered backend handles image processing and model inference.

## 🛠️ Technical Details

- **Frontend**: Built with React, enabling users to upload images and view predictions.
- **Backend**: Flask backend manages HTTP requests, image processing, and model interactions.
- **Model**:Trained with Kaggle datasets using tensorflow and mobilenet pretrained model.
- **CORS**: Flask-CORS enabled for seamless frontend-backend communication.

## 🔧 Setup

To get started with this project:

1. **Clone the repository**:
    ```bash
    git clone  https://github.com/ESR-style/Crop-Disease-ml.git
    ```
   

2. **Backend Setup**:
    ```bash
        cd backend
        python app.py
    ```
3. **Frontend Setup**:
    ```bash
        npm install
        npm run dev
    ```

## 🚀 Usage
- Open the web application in your browser.
- upload an image of a plant leaf.
- Click the "Upload" button to submit the image.
- View the predicted disease and take appropriate action.

## 📋 Class Labels
The model can identify the following plant diseases:
- Apple: Apple scab, Black rot, Cedar apple rust, Healthy
- Blueberry: Healthy
- Cherry: Powdery mildew, Healthy
- Corn: Cercospora leaf spot, Common rust, Northern Leaf - Blight, Healthy
- Grape: Black rot, Esca (Black Measles), Leaf blight, Healthy
- Orange: Haunglongbing (Citrus greening)
- Peach: Bacterial spot, Healthy
- Pepper: Bacterial spot, Healthy
- Potato: Early blight, Late blight, Healthy
- Raspberry: Healthy
- Soybean: Healthy
- Strawberry: Leaf scorch, Healthy
- Tomato: Bacterial spot, Early blight, Late blight, Leaf Mold, Septoria leaf spot, Spider mites, Target Spot, Tomato Yellow Leaf Curl Virus, Tomato mosaic virus, Healthy

# Training Process
![alt text](/images/image.png)
![alt text](/images/image2.png)
![alt text](/images/image3.png)
![alt text](/images/image4.png)
