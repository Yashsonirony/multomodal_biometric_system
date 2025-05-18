# Multimodal Biometric Authentication System

## 🔐 Overview

This project implements a **Multimodal Biometric Authentication System** that enhances security and accuracy by combining two or more biometric modalities. By integrating biometric traits such as **facial recognition** and **fingerprint recognition**, the system improves identity verification reliability in comparison to unimodal systems.

## 🎯 Objectives

- Improve authentication accuracy and reduce false acceptance/rejection rates.
- Integrate multiple biometric traits (e.g., Face + Fingerprint).
- Provide a scalable and secure authentication solution.

## 💡 Features

- Multimodal authentication (Face and Fingerprint).
- User enrollment and verification.
- Liveness detection to prevent spoofing (optional).
- GUI for user interaction (optional).
- Real-time matching and feedback.

## 🛠️ Tech Stack

- **Programming Language:** Python
- **Libraries:** OpenCV, NumPy, TensorFlow/PyTorch, scikit-learn, Pillow
- **Face Recognition:** dlib or FaceNet
- **Fingerprint Recognition:** OpenCV, image processing techniques, or biometric SDKs
- **Database:** SQLite / Firebase / MongoDB
- **GUI:** Tkinter / Streamlit / Flask (optional)

## 🗃️ Dataset

- **Face Dataset:** [LFW](http://vis-www.cs.umass.edu/lfw/) / custom images
- **Fingerprint Dataset:** [FVC2004](https://bias.csr.unibo.it/fvc2004/) / [SOCOFing](https://www.kaggle.com/datasets/ruizgara/socofing)

> You can replace these with your own dataset or live image capture.

## 📦 Installation

```bash
git clone https://github.com/your-username/multimodal-biometric-system.git
cd multimodal-biometric-system
pip install -r requirements.txt
