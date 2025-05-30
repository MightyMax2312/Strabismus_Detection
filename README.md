# Strabismus Detection using Deep Learning

This project contains a deep learning pipeline to detect **strabismus** (eye misalignment) from images using a trained neural network. It includes a dataset, preprocessing pipeline, training code and an h5 model with ready deployment on a Jetson Nano/Windows with potential input from an ESP32-CAM. The accuracy of the model is 77%, and has the following features:-
- CNN-based model to detect strabismus from eye images
- Dataset and preprocessing pipeline included
- Training scripts and a pretrained `.h5` model
- Docker support for deployment
- Designed to run on:
  - **Jetson Nano**
  - **Windows**
  - Linux systems
  - Potential ESP32-CAM input

---

## 📦 Installation guide

```bash
# Clone the repository
git clone https://github.com/MightyMax2312/Strabismus_Detection.git
cd Strabismus_Detection

#Use a Python virtual environment
python3 -m venv venv
source venv/bin/activate

# Install required packages
pip install -r requirements.txt
