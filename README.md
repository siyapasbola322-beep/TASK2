# Long Hair Identification

## 🔍 Project Description

This project is part of an internship task to build a deep learning model that identifies whether a person in an image has long hair or short hair and predicts gender accordingly.

### 📌 Task Requirements

- If the person is **between 20 and 30 years old**:
  - Predict **gender based on hair length**.
    - Long hair ➝ Female
    - Short hair ➝ Male
- If the person is **below 20 or above 30 years old**:
  - Predict **gender using traditional classification**, ignoring hair length.

---

## 🧠 Model Architecture

- CNN (Convolutional Neural Network) built using TensorFlow/Keras
- Trained on the **UTKFace Dataset**
- Age range filter applied during preprocessing
- Hair length determined using morphological image processing / edge-based segmentation

---

## 📁 Folder Structure
