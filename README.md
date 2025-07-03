
# 🚦 Traffic Sign Recognition


## 🧠 Overview

This project implements a **Convolutional Neural Network (CNN)** to classify traffic signs from the German Traffic Sign Recognition Benchmark (GTSRB) dataset with high accuracy. Developed as part of a university project at **Ajeenkya D Y Patil University**, it includes data preprocessing, training, evaluation, and a Tkinter-based GUI for visual classification.

## 🔍 Highlights

- 🧠 **CNN Model**: Trained on ~50,000 images for classifying over 40 types of traffic signs.
- 🎯 **Performance**: Achieved **~95% accuracy** on test data.
- 📈 **Metrics Evaluation**: Accuracy and loss plotted and tracked across epochs.
- 🖥️ **GUI**: Built a simple **Tkinter**-based GUI to load and classify images interactively.

## 🗂️ Repository Structure

```
📦traffic-sign-detection/
 ┣ 📜Meta.csv                 # Metadata about traffic signs
 ┣ 📜Train.csv                # Training dataset
 ┣ 📜Test.csv                 # Test dataset
 ┣ 📜proj.py                  # Python script for training/testing
 ┣ 📜traffic_signs.ipynb      # Jupyter notebook for full model workflow
 ┣ 📜traffic_classifier.h5    # Trained CNN model
 ┣ 📜cudart64_110.dll         # CUDA runtime (optional)
 ┗ 📜README.md                # This file
```

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/mayuragrawal21/Trafic-Sign-Detection.git
   cd Trafic-Sign-Detection
   ```

2. **Install dependencies**:
   ```bash
   pip install tensorflow numpy pandas matplotlib opencv-python scikit-learn pillow
   ```

3. **Run the notebook**:
   - Open `traffic_signs.ipynb` in Jupyter or VS Code to explore training, evaluation, and visualizations.

4. **Launch the GUI**:
   ```bash
   python proj.py
   ```

   Upload an image to classify traffic signs using the trained model.

## 📊 Model Performance

| Metric     | Value       |
|------------|-------------|
| Accuracy   | ~95%        |
| Loss       | Monitored across epochs |
| Classes    | 40+ Traffic Sign Types |

## 🛠 Technologies Used

- Python
- TensorFlow / Keras
- Tkinter (for GUI)
- NumPy, OpenCV, Pandas
- Matplotlib, Seaborn

## 👤 Author

**Mayur Agrawal**  
📍 India  
🔗 [GitHub](https://github.com/mayuragrawal21) | [LinkedIn](https://www.linkedin.com/in/mayur-agrawal21/)  
📧 [agrawalmayur2001@gmail.com](mailto:agrawalmayur2001@gmail.com)

---

> 🛑 *For educational and research purposes only.*
