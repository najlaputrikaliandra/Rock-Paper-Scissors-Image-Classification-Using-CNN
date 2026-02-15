<h1>🪨✋✌️ Rock Paper Scissors Image Classification</h1>

<p>Proyek ini merupakan implementasi Image Classification menggunakan Convolutional Neural Network (CNN) untuk mengklasifikasikan gambar tangan menjadi tiga kategori: Rock, Paper, dan Scissors.</p>

<p>Model dikembangkan menggunakan TensorFlow & Keras, dilengkapi dengan teknik Data Augmentation untuk meningkatkan performa dan generalisasi model.</p>

<h2>📌 Project Overview</h2>

<p>📂 Dataset: Rock-Paper-Scissors Image Dataset</p>
<p>🧠 Model: Convolutional Neural Network (CNN)</p>
<p>🏷️ Klasifikasi: Multi-class (3 kelas)</p>
<p>⚙️ Framework: TensorFlow & Keras</p>

<p>Proyek ini mencakup seluruh pipeline machine learning mulai dari preprocessing data, training model, evaluasi, hingga prediksi gambar baru.</p>

<h2>📁 Dataset Structure</h2>

<p>Dataset terdiri dari tiga folder utama:</p>

<pre>
rockpaperscissors/
│
├── rock/
├── paper/
└── scissors/
</pre>

<p>Setiap folder berisi gambar tangan sesuai kategorinya.</p>

<h2>🔍 Data Preprocessing</h2>

<p>Beberapa teknik yang digunakan:</p>

<p>1. Image Rescaling (normalisasi pixel)</p>

<p>2. Data Augmentation:</p>

<p>- Rotation</p>
<p>- Width & Height Shift</p>
<p>- Shear</p>
<p>- Zoom</p>
<p- >Horizontal Flip</p>


<p>3. Train–Validation Split (60% : 40%)</p>

<p>Tujuannya adalah untuk meningkatkan kemampuan generalisasi model dan mengurangi overfitting.</p>

<h2>🧠 Model Architecture</h2>

<p>Model dibangun menggunakan arsitektur CNN sederhana yang terdiri dari:</p>

<p>- Convolutional Layers + ReLU Activation</p>
<p>- MaxPooling Layers</p>
<p>- Fully Connected (Dense) Layer</p>
<p>- Dropout Layer</p>
<p>- Output Layer (Softmax – 3 kelas)</p>

<p>Loss function yang digunakan adalah categorical_crossentropy dengan optimizer RMSprop.</p>

<h2>📈 Model Performance</h2>

<p>- Model mampu mencapai akurasi validation lebih dari 90%</p>

<p>- Training dihentikan secara otomatis menggunakan callback ketika akurasi validation telah memenuhi target</p>

<p>- Visualisasi grafik akurasi training & validation digunakan untuk memantau performa model</p>

<h2>🖼️ Prediction</h2>

<p>Model dapat digunakan untuk memprediksi gambar baru dengan langkah:</p>

<p>1. Upload gambar</p>
<p>2. Resize & preprocessing</p>
<p>3. Prediksi menggunakan model terlatih</p>
<p>4. Output: Rock / Paper / Scissors</p>

<h2>🛠️ Technologies Used</h2>

<p>- Python</p>
<p>- TensorFlow</p>
<p>- Keras</p>
<p>- NumPy</p>
<p>- Matplotlib</p>
<p>- Scikit-learn</p>

<h2>🎯 Project Goals</h2>

<p>- Menerapkan konsep dasar Convolutional Neural Network</p>
<p>- Memahami alur kerja klasifikasi gambar</p>
<p>- Mengimplementasikan data augmentation</p>
<p>- Mencapai akurasi tinggi pada multi-class classification</p>
<p>- Mengembangkan model yang dapat melakukan prediksi gambar secara real-time</p>

<h2>🚀 How to Run</h2>

<p>1. Clone repository ini</p>

<p>2. Install dependencies:</p>

<pre>
pip install tensorflow numpy matplotlib scikit-learn
</pre>

<p>3. Jalankan notebook:</p>

<pre>
Klasifikasi_Gambar_Najla.ipynb
</pre>

<h2>👩‍💻 Author</h2>

<p>Najla Putri Kaliandra Sabilillah</p>
