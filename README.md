# Driver Drowsiness Detection  

A real-time system to detect driver drowsiness using computer vision and deep learning. This project uses **TensorFlow**, **OpenCV**, and **Python** to classify drowsy and non-drowsy states and provide alerts during live video monitoring.  

## Features  
- Real-time video feed monitoring with OpenCV.  
- Custom-trained deep learning model for drowsiness detection.  
- Displays detection results in real-time.  

## Technologies Used  
- **Python**  
- **TensorFlow**  
- **OpenCV**  

## Setup and Installation  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/Virendra69/Driver-Drowsiness-Detection.git  
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the detection script:
   ```bash
   python detect_drowsiness.py

## How It Works
1. Captures live video feed using OpenCV's VideoCapture.
2. The custom-trained model classifies frames as drowsy or non-drowsy.
3. Detection results are displayed on the video feed in real-time.

## Project Structure
* train_model.ipynb: Jupyter notebook for model training.
* detect_drowsiness.py: Script for real-time detection.
* requirements.txt: Dependency file for setup.

## Future Enhancements
* Integrate audio alerts for drowsiness detection.
* Deploy as a mobile or web application.
