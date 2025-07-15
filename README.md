# 📸 CIFAR-10 Image Classifier Web App

A lightweight web application built with **Streamlit** that classifies images into one of the 10 CIFAR-10 categories using a custom-trained TensorFlow model. Simply upload a `.jpg` or `.png` image, and get instant prediction probabilities displayed as a horizontal bar chart.

---

## ✅ Features

* Upload any image and predict its CIFAR-10 class.
* Interactive bar chart visualization of prediction probabilities.
* Simple and intuitive web interface.
* Pre-trained model included for quick use.

---

## 📂 Project Structure

```
Cifar10Classifier/
│
├── app.py              # Streamlit web application
├── model.py            # TensorFlow model training script
├── cifar10_model.h5    # Pre-trained Keras model
├── requirements.txt    # Python dependencies
├── LICENSE             # License information
└── README.md           # Project documentation
```

---

## ⚙️ Installation & Usage

### 1️⃣ Prerequisites

* Python 3.8+
* Pip package manager

### 2️⃣ Clone the Repository

```bash
git clone https://github.com/shivkumar005/Cifar10Classifier.git
cd Cifar10Classifier
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the App

Make sure `cifar10_model.h5` exists in the same directory. Then launch:

```bash
streamlit run app.py
```

### 5️⃣ Training (Optional)

If you'd like to train a fresh model:

```bash
python model.py
```

This generates a new `cifar10_model.h5` file.

---

## 🖼️ CIFAR-10 Classes

* Airplane ✈️
* Automobile 🚗
* Bird 🐦
* Cat 🐱
* Deer 🦌
* Dog 🐶
* Frog 🐸
* Horse 🐴
* Ship 🚢
* Truck 🚚

---

## 💡 Notes

* The model is a simple fully connected neural network and is not state-of-the-art for CIFAR-10. It’s designed for demonstration purposes.
* Images are resized to `32x32` pixels automatically during upload.
* For larger-scale or production systems, consider using more advanced architectures like CNNs.

---

## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for full details.

---

## 🙏 Acknowledgements

* The CIFAR-10 Dataset

--- 

## 📫 Connect

[Mail](mailto:shivakumarsouta18@gmail.com) | [LinkedIn](https://linkedin.com/in/shivakumarsouta) | [Portfolio](https://shivakumarsouta-portfolio.vercel.app)

---

