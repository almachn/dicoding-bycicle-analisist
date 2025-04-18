# dicoding-bycicle-analisist 🚲

## Project Description

Proyek ini mengeksplorasi tren penyewaan sepeda berdasarkan kondisi cuaca, musim, dan hari kerja/libur. 

## Dataset Description

Dataset yang digunakan dalam analisis ini adalah [bike sharing dataset](https://www.kaggle.com/datasets/lakshmi25npathi/bike-sharing-dataset)

## Installation Instructions

1. **Clone the project repository:**

   ```
   git clone https://github.com/almachn/dicoding-bycicle-analisist
   ```
2. **Create a virtual environment:**
   Menggunakan venv:
   ```
   python -m venv venv
   ```
   atau menggunakan virtualenv:
   ```
   virtualenv venv
   ```
3. **Enable the virtual environment and install dependencies:**

   Windows:
   ```
   venv\Scripts\activate
   pip install -r requirements.txt
   ```
   MacOS/Linux:
   ```
   source venv/bin/activate
   pip install -r requirements.txt
   ```
## Usage Instructions
- Untuk menggunakan proyek ini, lihat dokumentasi di notebook.ipynb.
- Untuk menjalankan dasbor Streamlit, jalankan perintah berikut:
```
streamlit run dashboard/dashboard.py
```
[Streamlit App](https://almachn-bicycle-analysis.streamlit.app/)
## Main Features

📅 **Analisis Penyewaan Bulanan**
Melihat tren naik-turun jumlah penyewaan sepeda per bulan.

🌤️ **Analisis Musim & Cuaca**
    Mengetahui musim atau kondisi cuaca apa yang paling mendukung aktivitas bersepeda.

🧑‍💼 **Perbandingan Hari Kerja vs Hari Libur**
    Mengeksplorasi pola perilaku pengguna antara weekday dan weekend.

📊 **Analisis RFM**
    Menggunakan Recency, Frequency, dan Monetary untuk menemukan jam-jam dengan performa terbaik.

🖼️ **Dashboard Interaktif**
    Disajikan secara visual menggunakan Streamlit.
   
## Creator
Alma Choerunisa
✉️ MC367D50927@student.devacademy.id

