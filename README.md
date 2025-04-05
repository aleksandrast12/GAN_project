#  GAN – Face Generation from CelebA Dataset

This project implements a Generative Adversarial Network (GAN) that learns to generate realistic human face images based on the CelebA dataset. It was developed using Python, TensorFlow, and Keras in a Google Colab environment.

##  Project Goal
The main objective was to build a GAN from scratch, train it on real-world face images, and produce synthetic face outputs that resemble the original dataset. The project served both as a machine learning experiment and a deep learning portfolio piece.

##  Technologies Used
- Python
- TensorFlow 2.13 / Keras
- NumPy
- Matplotlib
- PIL
- Google Colab

##  Dataset
- **CelebA** – Large-scale CelebFaces Attributes Dataset  
  [Kaggle link](https://www.kaggle.com/datasets/jessicali9530/celeba-dataset)

Note: To download the dataset from Kaggle in Colab, you need to upload your `kaggle.json` API key.

##  Features

- 📦 Data loading and preprocessing (resize to 64x64, normalization)
- 🧠 Custom generator and discriminator architecture
- 🎯 GAN training with loss visualization
- 🖼️ Face samples saved every few epochs to monitor progress
- 💾 Model and results saved for reuse

##  Example Output (after N epochs)

![output_faces](https://github.com/user-attachments/assets/38061511-fb91-4269-9d78-f5cbfc3f41dd)

##  How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Install dependencies (TensorFlow 2.13 is recommended)
3. Upload your `kaggle.json` file and download the dataset
4. Run all cells and monitor training progress

##  License
Educational / non-commercial use only.
