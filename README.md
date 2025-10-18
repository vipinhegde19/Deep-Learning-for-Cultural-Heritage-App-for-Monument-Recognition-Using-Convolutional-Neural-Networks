# Deep-Learning-for-Cultural-Heritage-App-for-Monument-Recognition-Using-Convolutional-Neural-Networks
# 🏛️ Deep Learning for Cultural Heritage: Monument Recognition Using Convolutional Neural Networks

## 📘 Overview

This project presents a **Deep Learning–based Cultural Heritage App** designed to recognize and classify **Indian monuments** using **Convolutional Neural Networks (CNNs)**.
It leverages image recognition techniques to preserve cultural heritage by accurately identifying monuments from photographs.
The application can be extended for educational, tourism, or heritage documentation purposes.

---

## 🚀 Features

* 🧠 Custom CNN model trained on Indian monument images
* 🏗️ Support for 24+ monument categories
* 🖼️ Real-time image classification and monument prediction
* 📊 Visualization of model training performance (accuracy & loss)
* 📱 Streamlit interface for user-friendly interaction
* 🧾 Automatic report generation with evaluation metrics (MSE, RMSE, PSNR)

---

## 🧩 Dataset

The dataset used for training and testing is the **Indian Monuments Image Dataset**, containing diverse images across multiple monument categories such as:

* Taj Mahal
* Qutub Minar
* Charminar
* Gateway of India
* Hampi Temple
* India Gate
* Red Fort, and more.

Each class includes approximately **50 images**, resized and normalized for model training.

---

## 🧠 Model Architecture

A **Convolutional Neural Network (CNN)** was implemented from scratch with:

* Input layer: 300×300×3
* Multiple Conv2D + MaxPooling layers
* Fully Connected (Dense) layers
* Softmax output for multi-class prediction

Additional experiments were conducted using **ResNet50** for performance comparison.

---

## 📈 Model Evaluation

Key metrics used:

* **Training & Validation Accuracy/Loss plots**
* **Confusion Matrix** for class-level analysis
* **RMSE, MSE, and PSNR** for performance validation

The CNN model achieved strong classification accuracy and generalized well across unseen monument images.

---

## 🧰 Technologies Used

* **Python 3.10+**
* **TensorFlow / Keras** – Deep Learning framework
* **NumPy, OpenCV, Matplotlib, Seaborn** – Data handling and visualization
* **Streamlit** – Frontend web interface
* **ReportLab** – PDF report generation

---

## 🧪 How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/<your-username>/Deep-Learning-for-Cultural-Heritage-App-for-Monument-Recognition-Using-Convolutional-Neural-Networks.git
   cd Deep-Learning-for-Cultural-Heritage-App-for-Monument-Recognition-Using-Convolutional-Neural-Networks
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:

   ```bash
   streamlit run app.py
   ```
4. Upload an image and get the predicted monument name along with analysis metrics.

---

## 📊 Results

| Model                 | Training Accuracy | Validation Accuracy |
| --------------------- | ----------------: | ------------------: |
| Custom CNN            |              ~94% |                ~91% |
| ResNet50 (Fine-tuned) |              ~97% |                ~95% |

---

## 📜 Future Enhancements

* Incorporate **transfer learning** with EfficientNet and Vision Transformers
* Expand dataset with **global monuments**
* Add **geo-tagging and historical data** integration
* Deploy model as a **mobile-friendly web app**

---

## 👨‍💻 Author

**Vipin Hegde**
Software Developer & Machine Learning Enthusiast
📧 [Your Email Address]
🔗 [LinkedIn Profile or Portfolio Link]

---

## 🪪 License

This project is licensed under the **MIT License** — feel free to use, modify, and distribute with attribution.

---

## 🌍 Acknowledgments

Special thanks to the open-source community and dataset contributors for enabling cultural preservation through technology.

