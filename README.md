# 🗑️ Waste Classification Web App

This project is a web-based image classifier built using **FastAPI** and a **TensorFlow (Keras)** model. It classifies waste images into categories like cardboard, glass, metal, paper, plastic, and trash.

## 🔍 Features

- Upload an image of waste material.
- Predict the waste type using a trained deep learning model.
- Display the predicted class with confidence percentage.
- View the uploaded image along with the prediction.
- Fully integrated with `FastAPI`, `Jinja2` templating, and HTML UI.

## 🚀 Tech Stack

- **Backend:** FastAPI
- **ML Model:** TensorFlow (Keras `.h5` model)
- **Frontend:** HTML via Jinja2 Templates
- **Image Processing:** Pillow (PIL), NumPy
- **Server:** Uvicorn

## Install Requirements

- pip install -r requirements.txt

## Run the app

- uvicorn a:app --reload

Visit http://127.0.0.1:8000 in your browser.

