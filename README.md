# AutoBrand Identifier: Intelligent Car Brand Classification

### 📜 Overview <br>
AutoBrand Identifier is a fully functional web application that predicts the brand of a car based on user-provided images. By leveraging advanced deep learning techniques, the system ensures accurate and efficient brand classification. The application is powered by Flask and deployed on Render, providing seamless access and scalability.

This project demonstrates the integration of cutting-edge image recognition with a simple and intuitive user experience, making it ideal for practical and educational use cases.<br>

### 🚀 Features <br>
1. Automated Brand Classification: Input car-related image data and receive instant, accurate predictions.<br>
2. Deep Learning Model: Built using a CNN trained on a diverse dataset of images to enhance prediction performance.<br>
3. User-Friendly Interface: Upload images directly via the web app’s intuitive interface.<br>
4. Cloud Deployment: Hosted on Render, ensuring high availability and reliable performance.<br>
5. Real-Time Predictions: Minimal latency in processing inputs and delivering results.<br>

### 🛠️ Technology Stack<br>
1. Frontend: HTML, CSS<br>
2. Backend: Flask (Python-based micro web framework)<br>
3. Deep Learning Framework: TensorFlow/Keras for CNN modeling<br>
4. Hosting Platform: Render<br>
5. Programming Languages: Python (Backend and Model), HTML/CSS (Frontend)<br>

### 📊 Performance Highlights<br>
**Model Metrics:** <br>
Accuracy: Achieved a validation accuracy of 93%.<br>
Loss: Consistent reduction in loss during training, ensuring robustness.<br>
Optimizations: Applied data augmentation and hyperparameter tuning for enhanced performance.<br>

### 🏗️ Project Architecture<br>
Image Preprocessing: Resizes and normalizes images for uniform input to the model.<br>
Model Inference: Uses a trained CNN to process the input data and predict the car brand.<br>
Web Interface:<br>
Simple image upload functionality.<br>
Displays the predicted car brand with confidence scores.<br>
Deployment: Flask serves as the backend framework, hosted on Render for public accessibility.

![App Interface](./images/inter.png)

### 📋 Setup Instructions<br>
**Prerequisites** <br>
##### Ensure the following are installed on your system:<br>
1. Python 3.7+<br>
2. pip (Python package installer)<br>

### Steps<br>
**Clone this repository:** <br>
git clone https://github.com/nakkkul/Car-Brand-Classification.git  
cd AutoBrand-Identifier<br>

**Install dependencies:** <br>
pip install -r requirements.txt <br>

**Run the application locally:** <br>
python app.py  <br>
Open the application in your browser at http://127.0.0.1:5000.

### 🌐 Deployment Link <br>
The live version of the application can be accessed here: https://car-brand-classification.onrender.com

### 📂 Repository Structure <br>
Car-Brand-Classification/  
│  
├── app.py               # Main Flask application  
├── model/               # Trained model and preprocessing scripts  
├── static/              # CSS, JavaScript, and other static assets  
├── templates/           # HTML templates for Flask  
├── requirements.txt     # Required Python libraries  
└── README.md            # Project documentation  

### 📚 Future Enhancements
Expand the training dataset for improved generalizability.
Add multi-brand prediction functionality for complex inputs.
Implement API integration to support external applications.

### 🤝 Acknowledgments
Special thanks to open-source datasets and deep learning frameworks like TensorFlow/Keras for empowering this project.
