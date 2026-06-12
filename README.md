# Model  Perhitungan Mobil Berbasis YOLOv11 & Slicing Aided Hyper Inference (SAHI) dengan Perbandingan Gaussian Mixture Model (GMM) & Operasi Dilasi

Project ini bertujuan untuk menghitung jumlah slot parkir yang terisi secara otomatis menggunakan citra CCTV area parkir dengan membandingkan dua pendekatan berbeda, yaitu:
- YOLOv11n + SAHI sebagai metode berbasis Deep Learning.
- GMM + Dilasi sebagai metode Computer Vision konvensional.
Perbandingan dilakukan untuk mengetahui metode yang paling efektif dalam mendeteksi dan menghitung kendaraan pada area parkir.

# Dataset
Dataset yang digunakan adalah PKLot Dataset dari Roboflow yang terdiri dari 12.416 gambar area parkir dengan total 711.856 objek teranotasi. Dataset memiliki dua kelas, yaitu space-empty untuk slot parkir kosong dan space-occupied untuk slot parkir yang terisi kendaraan. Data dibagi menjadi 8.691 gambar training, 2.483 gambar validation, dan 1.242 gambar testing untuk proses pelatihan dan evaluasi model.
