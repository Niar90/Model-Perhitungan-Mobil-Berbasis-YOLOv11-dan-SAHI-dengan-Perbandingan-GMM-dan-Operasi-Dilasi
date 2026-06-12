# Model  Perhitungan Mobil Berbasis YOLOv11 & Slicing Aided Hyper Inference (SAHI) dengan Perbandingan Gaussian Mixture Model (GMM) & Operasi Dilasi

Project ini dibuat untuk memenuhi tugas akhir Mata Kuliah Pengolahan Citra Digital, Semester Genap 2025/2026, Kelas 2024D, Universitas Negeri Surabaya. Project ini membandingkan performa metode Deep Learning berbasis YOLOv11n + SAHI dengan metode Computer Vision konvensional GMM + Dilasi dalam mendeteksi dan menghitung kendaraan pada area parkir menggunakan dataset PKLot.

Project ini membandingkan performa YOLOv11n + SAHI dan GMM + Dilasi dalam mendeteksi serta menghitung kendaraan pada area parkir menggunakan dataset PKLot. Pada metode pertama, YOLOv11n digunakan sebagai model deteksi objek, sementara SAHI diterapkan untuk meningkatkan kemampuan deteksi kendaraan berukuran kecil melalui proses slicing gambar. Sebagai pembanding, digunakan metode konvensional GMM + Dilasi yang melakukan segmentasi kendaraan berdasarkan distribusi intensitas piksel setelah melalui tahap preprocessing. Hasil pengujian menunjukkan bahwa YOLOv11n + SAHI memberikan performa terbaik dengan Precision 99,77%, Recall 99,69%, F1-Score 99,73%, dan mAP@50 99,43%, serta waktu inferensi 5,84 ms per gambar. Sementara itu, GMM + Dilasi memperoleh Precision 14,98%, Recall 76,82%, dan F1-Score 23,82% dengan waktu inferensi 54,86 ms per gambar. Hasil tersebut menunjukkan bahwa pendekatan berbasis Deep Learning lebih akurat, lebih cepat, dan lebih efektif dibandingkan metode segmentasi konvensional untuk tugas car park counting.

# Dataset
Dataset yang digunakan adalah PKLot Dataset dari Roboflow yang terdiri dari 12.416 gambar area parkir dengan total 711.856 objek teranotasi. Dataset memiliki dua kelas, yaitu space-empty untuk slot parkir kosong dan space-occupied untuk slot parkir yang terisi kendaraan. Data dibagi menjadi 8.691 gambar training, 2.483 gambar validation, dan 1.242 gambar testing untuk proses pelatihan dan evaluasi model.

# Anggota
Nia Ayu Agustin (24031554081)
Aulia Aziza (24031554102)
Audy Alycia (24031554179)

