# 🛡️ AI Surveillance Robot – Final Project Robotika

Proyek ini merupakan tugas akhir dari mata kuliah **Robotika** yang menggabungkan **Artificial Intelligence (AI)** untuk pendeteksian objek secara real-time dengan perangkat keras berbasis **Arduino**. Sistem ini dirancang untuk **robot Bela Negara University 5 (BNU5) untuk pengawasan otomatis (AI Surveillance)** dengan model deteksi berbasis **YOLOv8** yang dijalankan pada kamera laptop yang dihubungkan dengan robot BNU5.

## 📌 Tujuan Proyek

Membangun sistem robotik cerdas pada robot BNU5 yang mampu melakukan:

* **Deteksi objek manusia** secara real-time.
* **Menggerakkan robot** sesuai logika pengawasan (melalui kontrol Arduino).

## 🧠 Teknologi yang Digunakan

| Komponen               | Deskripsi                                |
| ---------------------- | ---------------------------------------- |
| `YOLOv8`               | Model deep learning untuk deteksi objek. |
| `OpenCV`               | Untuk pengambilan dan pemrosesan video.  |
| `Arduino Uno`          | Mengendalikan motor/aktuator robot.      |
| `Serial Communication` | Komunikasi antara Python dan Arduino.    |
| `Python`               | Mengendalikan logika AI dan komunikasi.  |

## 📂 Struktur File

* `main.ipynb` – Notebook utama yang memuat skrip deteksi dan komunikasi ke Arduino.
* `BNU5.ino` – Program Arduino untuk mengendalikan motor robot BNU5 berdasarkan input dari Python.
* `yolov8n.pt` – Model YOLOv8 kecil yang digunakan untuk deteksi manusia.

## 🚀 Cara Menjalankan

1. Hubungkan Mikrokontroller robot BNU5 ke Laptop.
2. **Compile dan Upload** file `BNU5.ino` ke Mikrokontroller robot **BNU5**.
3. **Jalankan** Jupyter Notebook `main.ipynb`.
4. Pastikan kamera berfungsi dan terhubung ke Mikrokontroller BNU5.
5. Sistem akan mulai mendeteksi objek dan mengirim sinyal perintah ke Arduino.

## 🔧 Dependensi

Dependensi yang perlu di-install:

```bash
pip install ultralytics opencv-python pyserial
```

## 📽️ Video Demo

> *https://drive.google.com/drive/folders/1HayTDdwoYTi72so7CHPkwnWIxDgeYM-f*

## 👥 Tim Pengembang

Proyek ini dikembangkan oleh: 
- Irsyad Fadhil Makarim
- Kalfin Syah Kilau Mayya
- Albi Akhsanul Hakim
- Mikhail Shams Afzal Karim
- Muhamad Vicky Oktafrian
