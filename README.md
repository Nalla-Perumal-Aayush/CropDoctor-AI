# 🌿 CropDoctor AI

**A Hybrid AI System for Plant Disease Detection and Treatment Consultation.**

CropDoctor AI combines **Computer Vision** (to see the disease) and **Large Language Models** (to explain the cure). It empowers farmers with instant, expert-level agronomy advice.

## 🚀 Features
- **Visual Diagnosis:** Detects 38 different plant diseases across 14 species using a fine-tuned **MobileNetV3**.
- **Expert Consultation:** Integrated **Gemma-2B LLM** to provide detailed reports on symptoms, treatment steps, and prevention.
- **User-Friendly UI:** Built with **Gradio** for easy image uploading and instant analysis.
- **Efficient:** Optimized to run entirely within the free tier of Google Colab.

## 🛠️ Tech Stack
- **Deep Learning:** TensorFlow (Keras), PyTorch
- **Models:** MobileNetV3 (Vision), Google Gemma-2B-IT (LLM)
- **Interface:** Gradio
- **Dataset:** PlantVillage (Augmented)

## 📊 Performance
- **Vision Model Accuracy:** ~95% (on Validation Set)
- **Supported Crops:** Apple, Tomato, Corn, Potato, Grape, Pepper, etc.

## 🤝 Acknowledgements
- Dataset sourced from [PlantVillage](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset).
- LLM powered by Google's [Gemma](https://huggingface.co/google/gemma-2b-it).

---
*Created by Nalla Perumal Aayush*
