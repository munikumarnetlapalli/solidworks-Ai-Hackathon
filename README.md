# solidworks-Ai-Hackathon
SOLIDWORKS AI Hackathon – Part Counting Model
This repository contains code and resources for the SOLIDWORKS AI Hackathon (IIT Madras), where the goal is to build a machine learning model that can correctly identify and count which mechanical parts appear in synthetic images.

Each image may contain any combination of the following parts:

Bolt
Locating Pin
Nut
Washer
Your task:
For every image, predict how many of each part type are present.

✨ Key Features
🧠 Deep Learning–based Detection & Counting
Model(s) to detect and count mechanical parts (bolts, locating pins, nuts, washers) in synthetic images.

🗂 Kaggle-Ready Pipeline
Scripts to preprocess data, train models, run inference, and generate submission CSV files in the required format.

🧪 Configurable Experiments
Easy configuration of model hyperparameters, training options, and image augmentations.

📊 Submission & Evaluation Support
Automatically produces Kaggle-compatible submission files and helps you debug predictions.

🏁 Competition Overview
Host: SOLIDWORKS AI Hackathon @ IIT Madras
Task: Count the number of each mechanical part in an image
Parts: bolt, locatingpin, nut, washer
🧮 Evaluation
The competition uses exact-match accuracy:

For each test image:
You output four integers: bolt, locatingpin, nut, washer
You get 1 point if all four counts are exactly correct
Otherwise, you get 0 for that image
Your final score is the mean exact-match accuracy over all test images.
🔧 Requirements
Python: 3.8+
Recommended:
PyTorch or TensorFlow (depending on this repo’s implementation)
CUDA-capable GPU (for faster training)
Libraries:
numpy, pandas, opencv-python or Pillow, scikit-learn, etc.
