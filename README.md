# CNNect-Classifier 🚀  
**Abdul Rafay** | BS Software Engineering

CNNect-Classifier is a deep learning-powered web application that performs real-time image classification on the CIFAR-10 dataset. Built as part of my Machine Learning Internship at Intern Intelligence, this project represents a complete end-to-end pipeline — from model training to deployment — wrapped inside a user-friendly interface.

This project started as a task but turned into something much bigger. Inspired by a post that said Streamlit is the fastest way to build AI apps and impress future employers, I took that challenge seriously. I moved beyond notebooks and built a fully functional deep learning app.

## What It Does

- Takes an input image via upload  
- Runs it through a custom-trained CNN model  
- Outputs predicted class with probability scores  
- Provides a clean, mobile-friendly UI for interaction  

## Behind the Scenes

- Built a CNN from scratch using PyTorch for image classification  
- Used convolutional layers, pooling, dropout, and fully connected layers  
- Trained and fine-tuned the model on CIFAR-10 for optimal accuracy  
- Switched from TensorFlow to PyTorch for smoother experimentation  
- Deployed using Streamlit to create a real-time web interface  

## Tech Stack

- PyTorch  
- Torchvision  
- Streamlit  
- PIL  
- NumPy  
- HTML/CSS  

## Features

- 📷 Image Upload Interface  
- ⚡ Real-Time Predictions  
- 📊 Class-wise Confidence Breakdown  
- 💻 Mobile-Responsive, Minimalist UI  

## Installation

To run the app locally, follow these steps:

```bash
git clone https://github.com/YourGitHubUsername/CNNect-Classifier.git
cd CNNect-Classifier
streamlit run app.py
```

Make sure you have the trained model file `cifar10_model.pt` in the same directory as `app.py`.

## File Structure

- `app.py` – Streamlit frontend with prediction logic  
- `task.ipynb` – Model building and training notebook  
- `cifar10_model.pt` – Saved PyTorch model weights (not included in repo)  

## Classes Predicted

- Airplane  
- Automobile  
- Bird  
- Cat  
- Deer  
- Dog  
- Frog  
- Horse  
- Ship  
- Truck  

## Why This Project Matters

This wasn’t just about training a model — it was about making machine learning usable. I learned how to bridge the gap between model performance and user experience. CNNect-Classifier represents my journey into real-world AI application development, with hands-on deployment and user-facing design.

## Connect with Me

📌 [LinkedIn – Abdul Rafay](https://www.linkedin.com/in/abdul-rafay19)
