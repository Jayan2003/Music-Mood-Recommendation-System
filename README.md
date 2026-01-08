
# 🎵 Music Mood Recommendation System


## 📌 Overview

The **Music Mood Recommendation System** is an AI-based application that analyzes a user’s facial expression from an uploaded image, predicts the emotional state, generates a natural language description of the emotion, and recommends a suitable song that matches the detected mood.

This project demonstrates the integration of **computer vision**, **deep learning**, and **emotion-aware recommendation systems**.

---

## 🖼️ System Interface

The following screenshot shows the full system pipeline, including emotion prediction, probability scores, emotion description generation, and music recommendation.

![System Interface](Interface.png)

---

## 🎯 Project Objectives

* Detect and crop faces from uploaded images
* Classify facial emotions into:

  * Happy
  * Sad
  * Neutral
* Display emotion probability scores
* Generate a textual description of the detected emotion
* Recommend a mood-based song using an embedded YouTube player

---

## 🧠 System Workflow

```
Image Upload
   ↓
Face Detection & Cropping
   ↓
CNN Emotion Classification (Happy / Sad / Neutral)
   ↓
Emotion Probability Estimation
   ↓
Emotion Description Generation
   ↓
Music Recommendation
```

---

## 🧪 Dataset

* **RAF-DB (Real-world Affective Faces Database)**
* Used for training the emotion recognition model
* Simplified to three emotion classes for robustness and clarity

---

## 🧠 Model Description

### Emotion Recognition

* Convolutional Neural Network (CNN)
* Extracts facial features and predicts emotion class probabilities

### Emotion Description Generation

* Decoder-only neural model
* Produces a short natural language description of the detected emotion

### Music Recommendation

* Each emotion is mapped to a predefined set of songs
* Recommended song is displayed using a YouTube embedded player

---

## 🛠️ Technologies Used

* Python
* Convolutional Neural Networks (CNN)
* OpenCV
* Decoder-only text generation model
* Gradio (Web Interface)
* NumPy, Pandas
* YouTube Embed

---

## ▶️ How to Run the Project

1. Open the notebook:

   ```
   Music_Mood.ipynb
   ```
2. Install required Python libraries if needed
3. Run all notebook cells
4. Upload a face image using the interface

---

## 📊 Output Example

* **Predicted Emotion:** Happy
* **Emotion Probabilities:** Displayed numerically
* **Generated Description:** Textual explanation of facial expression
* **Music Recommendation:** Mood-matching song

---

## 🎓 Academic Context

* **Topics Covered:**

  * Computer Vision
  * Neural Networks
  * Emotion Recognition
  * Recommendation Systems

---

## 🔮 Future Improvements

* Real-time webcam emotion detection
* Additional emotion categories
* Personalized music recommendations
* Spotify API integration

---

## 👤 Authors
- **Salma Yasser Galal** — 211006565  
- **Jayan Ahmed Samer** — 211005353  
- **Zeina Ahmed ElShenawy** — 211007926  


---


