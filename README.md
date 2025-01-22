# Lung Cancer Detection Web Application

## Overview

This repository contains a web application for detecting lung cancer using a trained deep learning model. Users can upload medical images through a user-friendly interface, and the application predicts the likelihood of lung cancer using a pre-trained Keras model. It integrates **Flask** for backend processing, **TensorFlow/Keras** for model inference, and a responsive front-end built with HTML, CSS, and JavaScript.

---

## Features

- **AI-Powered Prediction**: Utilizes a deep learning model (`Lungcancer.h5`) for accurate lung cancer detection.
- **User-Friendly Interface**: Allows users to upload images and receive real-time predictions.
- **Secure and Extensible**: Supports safe image uploads and can be extended for additional use cases.
- **Interactive Front-End**: Features dynamic image previews, loader animations, and responsive design.
- **Training and Testing Notebooks**: Includes Jupyter notebooks for model training and evaluation.

---

## Prerequisites

To run this project, ensure the following are installed on your system:

- **Python 3.8+**
- Required Python libraries:
  - Flask
  - TensorFlow
  - Keras
  - NumPy
  - Werkzeug

Install the dependencies using:
```bash
pip install flask tensorflow keras numpy werkzeug
