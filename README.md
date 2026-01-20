# Teeth Classification App
A Streamlit-based web application that uses a pre-trained deep learning model to classify teeth images. The app allows users to upload photos of teeth and receive predictions about their type or condition in real time.
This project can help build intuitive interfaces for dental image classification and is a foundation for future extensions like disease detection or mobile deployment.

## Overview
This app combines deep learning with an interactive web UI so users can classify teeth images without coding:
- Users upload teeth images (JPG, PNG)
- The model processes and predicts the label
- Results are shown instantly on the web page

The core of the system is a pre-trained neural network (the specific architecture can be TensorFlow, PyTorch, or another backend). The app is lightweight and runs locally or on hosted platforms like Streamlit Cloud.

## Features
- Image Upload – Upload one or more teeth images for analysis
- Deep Learning Inference – The model predicts the class of each uploaded image
- Interactive UI – User-friendly interface built with Streamlit

## Tech Stack
This project uses:
- Python – Core language
- Streamlit – Front end and web UI
- TensorFlow  – Deep learning model backend
- NumPy – Numerical computing

(The actual model can be replaced or improved with other architectures such as MobileNet, ResNet, Vision Transformers, etc., depending on the dataset and accuracy needs.)

## Quickstart (Run Locally)
1. Clone the repo:
```bash
git clone https://github.com/Mona1Tarek/Teeth-Classification-APP.git
cd Teeth-Classification-APP
```
2. Create a clean Python environment:
```bash
python -m venv venv
source venv/bin/activate     # macOS / Linux
venv\Scripts\activate        # Windows
```
3. Install dependencies:
```bash
pip install -r requirements.txt
```
4. Run the app:
```bash
streamlit run app.py
```
5. Open the browser:
- Navigate to the address shown in the terminal (usually http://localhost:8501)

## Project Structure
- `app.py` – Main Streamlit application logic
- `main.ipynb` – Notebook showing model exploration or testing workflows
- `requirements.txt` – Dependencies needed to run the app

Additional model files or data directories may be included once you integrate the trained model weights.

## How It Works
- User uploads an image via the UI
- The app loads the pre-trained model
- The image is preprocessed (resize, normalize) soon after uploading
- The model predicts the class label and confidence
- Results are displayed immediately on screen

## Contribution
Contributions are welcome! You can:
- Fork this repo
- Create a feature branch
- Submit a pull request

