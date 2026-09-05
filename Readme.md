# Task 1 — Smart Object Classifier 🤖📱

An AI-powered smart object classification project built using **Google Teachable Machine** for the **AI Ambassadors Competition** in collaboration with **NTI**.

---

## 🔗 Live Demo Model
You can test the trained model directly via your webcam using the link below:
👉 **[Teachable Machine Model Link](https://teachablemachine.withgoogle.com/models/mojvi29Mgy/)**

---

## 🎯 Dataset & Classes
The model was trained to classify 3 distinct object classes, optimized with varying angles, distance variation, and background isolation:

1. **Cup:** 25+ image samples across multiple angles.
2. **Pen:** 26 image samples.
3. **Ear pod:** 32 image samples.

---

## 📋 Short Evaluation Report

### ⚠️ Identified Challenges
* **Hand Interference:** Potential model bias toward recognizing human hands if included excessively in training frames.
* **Lighting & Background Sensitivity:** Accuracy variance caused by changing ambient lighting or background clutter relative to initial training conditions.
* **Feature Overlap:** Visual similarities between small items (e.g., pens and ear pods) at specific tight angles.

### ✅ Accuracy Optimization Strategies
* **Hands-Free Capture:** Positioned objects directly on a flat surface and rotated them to capture isolated object features.
* **Multi-Angle & Distance Variation:** Captured image samples across diverse perspectives, distances, and orientations.
* **Dataset Expansion:** Exceeded the minimum requirement (20 samples per class) to improve model generalization.

---

## 📁 Repository Structure
* `index.html`: JavaScript integration code exported from Teachable Machine.
* `smart_object_classifier_report.pdf`: Comprehensive project evaluation report.
