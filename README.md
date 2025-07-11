# Asynchronous Time Series Data Pipeline for Weather and Meteorology
Sistem ini dirancang agar dapat berjalan secara otomatis dan efisien, mengintegrasikan berbagai tahapan pemrosesan data dalam arsitektur yang terstruktur dan scalable.

## 🛠️ Features

- **Data Ingestion**: Menarik data cuaca dan meteorologi dari sumber tertentu.
- **Data Preparation & Cleaning**: Membersihkan dan menyiapkan data agar siap diproses.
- **Feature Engineering**: Membuat fitur baru yang relevan untuk proses modeling.
- **Modeling**:
  - Clustering (untuk segmentasi data)
  - Regresi (untuk prediksi nilai cuaca/meteorologi)
- **Visualization**: Menyediakan grafik dan visualisasi data yang mudah dipahami.
- **Storage**: Menyimpan hasil akhir ke dalam database untuk keperluan lanjutan.

## ⚙️ Tech Stack

- **Python**
- **Celery** - untuk eksekusi task secara parallel
- **RabbitMQ** - message broker untuk manajemen antrean
- **Pandas, Scikit-learn, Matplotlib** - untuk analisis dan visualisasi data
- **PostgreSQL** - untuk penyimpanan data akhir (opsional)

## 🧩 Architecture

Sistem dibangun dengan pendekatan modular dan asynchronous pipeline, memungkinkan setiap proses berjalan secara paralel dan efisien:

