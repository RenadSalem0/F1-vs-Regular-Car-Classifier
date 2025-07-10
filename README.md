# 🏎️ Formula 1 vs Regular Car Classifier

This project uses a machine learning model trained using **Teachable Machine** to classify images into:

- 🏁 Formula 1 Cars  
- 🚗 Regular Cars

The model was tested using **Google Colab**, and also directly through Teachable Machine’s interface before export.

---

## 📷 Training Samples

| Formula 1 Car | Regular Car |
|---------------|-------------|
| ![](F1car.jpg) | ![](Regular_car.jpg) |

> Sample images used to train the model.

---

## 🧪 Teachable Machine Test Output

The image below shows the prediction result from **Teachable Machine** after giving it a sample image (before exporting the model):

![](Test1.png)

---

## 🧪 Google Colab Test Output

After exporting the model and testing it in **Google Colab**, the following output was generated when predicting an image:

![](Colab_test.png)

---

## 🛠️ Tools Used

- [Teachable Machine by Google](https://teachablemachine.withgoogle.com/)
- Google Colab
- Python 3
- TensorFlow / Keras

---

## 📁 Project Files

├── F1car.jpg # Sample training image - Formula 1 car
├── Regular_car.jpg # Sample training image - Regular car
├── Test1.png # Prediction result from Teachable Machine
├── Colab_test.png # Prediction result from Google Colab
├── keras_model.h5 # Trained Keras model
├── labels.txt # Class labels
└── README.md # Project documentation


---

## ✅ Summary

This image classifier was developed as part of a machine learning task using **Teachable Machine**. It accurately distinguishes between Formula 1 and regular cars. The model was tested both on **Teachable Machine** and in **Google Colab** using an exported Keras model.






