# Emotion-Recognition-using-CNN-and-OpenCV

This project implements a **real-time facial emotion detection system** using a Convolutional Neural Network (CNN) trained on facial expression data.  
It detects faces from a webcam stream, classifies the emotion, and displays the result live.

---

##  Features
- Detects faces using **OpenCV Haar Cascades**
- Classifies emotions with a **CNN model (Keras/TensorFlow)**
- Supports 7 emotion categories:  
  `Angry, Disgust, Fear, Happy, Neutral, Sad, Surprise`
- Real-time webcam demo

---

##  Tech Stack
- **Python 3.8+**
- **TensorFlow / Keras**
- **OpenCV**
- **NumPy**

---


##  Dataset
This project was trained on the **FER-2013 dataset** (Facial Expression Recognition), available on [Kaggle](https://www.kaggle.com/datasets/msambare/fer2013).  
It contains 48x48 grayscale face images categorized into 7 emotions.

---

### 1. Clone the repository

```bash
git clone https://github.com/LOAI-TK/emotion-detection-cnn.git
cd emotion-detection-cnn
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```


### 3. Training (optional)

If you want to train your own model:

jupyter notebook notebooks/emotion-classification-cnn-using-keras.ipynb

### 4. Run real-time detection

Make sure you have a trained model (model.h5) in the models/ folder, then run:

```bash
python src/EDCNN.py
```

---

## Credits

- Inspired by a YouTube tutorial [](https://youtu.be/Bb4Wvl57LIk?si=MLUSaOuokTS7nIdB)

- Dataset: FER-2013 Kaggle Dataset


## Future Improvements

- Use deep learning face detectors (e.g., MTCNN, Dlib) instead of Haar Cascades

- Improve accuracy with deeper CNN/ResNet models

- Add probability bars for each emotion in real time

- Deploy as a simple web app using Streamlit/Flask

## License

This project is for educational purposes. You are free to use and modify it with attribution.
