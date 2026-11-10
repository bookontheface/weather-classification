**Klasifikasi Cuaca Menggunakan Deep Learning (MobileNetV2)**

**a. Deskripsi Proyek**

Proyek ini merupakan implementasi Deep Learning menggunakan Convolutional Neural Network (CNN) untuk melakukan klasifikasi kondisi cuaca berdasarkan gambar.
Model yang digunakan adalah MobileNetV2, yaitu arsitektur CNN yang ringan dan efisien dalam melakukan ekstraksi fitur serta klasifikasi gambar.
Sistem ini bertujuan untuk mengenali kondisi cuaca secara otomatis berdasarkan karakteristik visual pada gambar.
Website ini dibangun menggunakan Streamlit sehingga pengguna dapat mengunggah gambar cuaca dan mendapatkan hasil klasifikasi secara otomatis melalui antarmuka web yang interaktif dan mudah digunakan.

**b. Kategori Cuaca**

Model digunakan untuk mengklasifikasikan gambar ke dalam beberapa kategori cuaca:

1. Cloudy (Berawan)

2. Rainy (Hujan)

3. Shine (Cerah)

4. Sunrise (Matahari Terbit)

**c. Arsitektur Model**

MobileNetV2 digunakan sebagai arsitektur utama untuk mengekstraksi fitur dari gambar.

Tahapan klasifikasi:

1. Input Image: Memasukkan gambar cuaca.
2. Preprocessing: Resize dan normalisasi gambar.
3. Feature Extraction: Ekstraksi fitur menggunakan MobileNetV2.
4. Classification: Mengklasifikasikan fitur menggunakan layer Dense.
5. Prediction: Menghasilkan prediksi kategori cuaca menggunakan Softmax.

**d. Teknologi yang Digunakan:**

1. Python
2. TensorFlow / Keras
3. MobileNetV2
4. Streamlit
5. Pillow
6. Numpy
7. Jupyter Notebook
8. Matplotlib
9. Scikit-learn
