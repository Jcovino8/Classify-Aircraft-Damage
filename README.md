# Intro-DeepLearning-NeuralNetworks-With-Keras

The 'Labs' folder contains my labs associated with course 2/13 from my IBM Professional certificate titled 'Intro to Deep Learning & Neural Networks with Keras' My final project for this course is an Aircraft Damage Classifier and Captioning tool.

# FINAL PROJECT: Aircraft Damage Classification & Captioning

This project combines **deep learning-based image classification** with **transformer-powered image captioning** to analyze and describe aircraft damage. It leverages transfer learning via VGG16 to classify damage types (crack vs dent), and uses the BLIP (Bootstrapped Language-Image Pretraining) model to generate descriptive captions for each image.

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- PyTorch
- Hugging Face Transformers (BLIP model)
- Matplotlib
- PIL (Pillow)

---

## 📂 Project Structure

```bash
aircraft-damage-project/
├── Final_Project.py           # Main script
├── README.md
├── requirements.txt
├── predictions/               # Sample labeled predictions
│   └── crack_example.png
├── model_plot.png             # Training/validation loss or accuracy curves
└── .gitignore

