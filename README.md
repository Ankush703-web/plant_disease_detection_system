# 🌿 Plant Disease Detection System for Sustainable Agriculture

A web-based application powered by deep learning to detect plant diseases from leaf images. This tool supports sustainable agriculture by helping farmers and agronomists identify diseases early and accurately.

## 🧠 Features

- 🔍 **Image-based Plant Disease Detection** using a trained CNN model
- 📊 Built with **Streamlit** for a user-friendly web interface
- 🌱 Supports **38 classes** of plant diseases and healthy conditions
- 📷 Upload a leaf image and get real-time predictions
- ❄️ Interactive UI with visual feedback and result display

## 🚀 How to Run

1. Clone the repository:

   git clone https://github.com/Ankush703-web/plant-disease-detection.git

   cd plant-disease-detection
   
3. Install the dependencies:

    pip install -r requirements.txt

3. Place your trained model file in the project directory:

   trained_plant_disease_model.keras
   
5. Run the app:
   
   streamlit run model.py

🖼️ Demo
The app has two pages:

HOME: Introduction and overview

DISEASE RECOGNITION: Upload an image and get disease predictions


📁 Project Structure

├── model.py                  # Streamlit app and model inference logic

├── trained_plant_disease_model.keras  # Trained Keras model (not included)

├── Diseases.png              # Illustration used on the homepage

├── requirements.txt          # Python dependencies

└── README.md                 # You're reading it!

🧬 Model Details

Architecture: Convolutional Neural Network (CNN)

Input size: 128x128 pixels

Output: 38 class probabilities

Framework: TensorFlow / Keras

🖥️ Tech Stack
Python

TensorFlow / Keras

Streamlit

NumPy

PIL

📌 Future Improvements
Add mobile-friendly UI

Extend to more plant species and diseases

Integrate with Rasa for conversational predictions
