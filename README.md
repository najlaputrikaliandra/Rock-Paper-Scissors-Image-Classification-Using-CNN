🪨✋✌️ Rock Paper Scissors Image Classification

Proyek ini merupakan implementasi Image Classification menggunakan Convolutional Neural Network (CNN) untuk mengklasifikasikan gambar tangan menjadi tiga kategori: Rock, Paper, dan Scissors.

Model dikembangkan menggunakan TensorFlow & Keras, dilengkapi dengan teknik Data Augmentation untuk meningkatkan performa dan generalisasi model.

📌 Project Overview

📂 Dataset: Rock-Paper-Scissors Image Dataset

🧠 Model: Convolutional Neural Network (CNN)

🏷️ Klasifikasi: Multi-class (3 kelas)

📊 Target Akurasi: > 90%

⚙️ Framework: TensorFlow & Keras

Proyek ini mencakup seluruh pipeline machine learning mulai dari preprocessing data, training model, evaluasi, hingga prediksi gambar baru.

📁 Dataset Structure

Dataset terdiri dari tiga folder utama:

rockpaperscissors/
│
├── rock/
├── paper/
└── scissors/


Setiap folder berisi gambar tangan sesuai kategorinya.

🔍 Data Preprocessing

Beberapa teknik yang digunakan:

Image Rescaling (normalisasi pixel)

Data Augmentation:

Rotation

Width & Height Shift

Shear

Zoom

Horizontal Flip

Train–Validation Split (60% : 40%)

Tujuannya adalah untuk meningkatkan kemampuan generalisasi model dan mengurangi overfitting.

🧠 Model Architecture

Model dibangun menggunakan arsitektur CNN sederhana yang terdiri dari:

Convolutional Layers + ReLU Activation

MaxPooling Layers

Fully Connected (Dense) Layer

Dropout Layer

Output Layer (Softmax – 3 kelas)

Loss function yang digunakan adalah categorical_crossentropy dengan optimizer RMSprop.

📈 Model Performance

Model mampu mencapai akurasi validation lebih dari 90%

Training dihentikan secara otomatis menggunakan callback ketika akurasi validation telah memenuhi target

Visualisasi grafik akurasi training & validation digunakan untuk memantau performa model

🖼️ Prediction

Model dapat digunakan untuk memprediksi gambar baru dengan langkah:

Upload gambar

Resize & preprocessing

Prediksi menggunakan model terlatih

Output: Rock / Paper / Scissors

🛠️ Technologies Used

Python

TensorFlow

Keras

NumPy

Matplotlib

Scikit-learn

🎯 Project Goals

Menerapkan konsep dasar Convolutional Neural Network

Memahami alur kerja klasifikasi gambar

Mengimplementasikan data augmentation

Mencapai akurasi tinggi pada multi-class classification

Mengembangkan model yang dapat melakukan prediksi gambar secara real-time

🚀 How to Run

Clone repository ini

Install dependencies:

pip install tensorflow numpy matplotlib scikit-learn


Jalankan notebook:

Klasifikasi_Gambar_Najla.ipynb

👩‍💻 Author

Najla Putri Kaliandra Sabilillah
