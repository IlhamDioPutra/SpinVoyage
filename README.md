# Submission Dicoding "Belajar Analisis Data dengan Python"

## Project Analisis Data

Repository ini berisi proyek data analytics yang saya kerjakan. Deployment in **Streamlit** 
## Deskripsi

Proyek ini bertujuan untuk menganalisis data pada Bike Sharing Dataset. Tujuan akhirnya adalah untuk menghasilkan wawasan dan informasi yang berguna dari data yang dianalisis.

## Struktur File dan Direktori

- **/data**: Direktori ini berisi data yang digunakan dalam proyek, dalam format .csv yang marupakan data mentah.
- **/dashboard**: Direktori ini berisi main.py yang digunakan untuk membuat dashboard hasil analisis data dan 2 file .csv yang sudah dikelola sebelumnya sehingga menjadi data .csv yang bersih yaitu day_clean.csv dan hour_clean.csv
- **notebook.ipynb**: File ini yang digunakan untuk melakukan analisis data.
- **README.md**: File yang berisi cara menjalankan dashboard dan informasi dari project ini.
- **requirement.txt**: File yang berisikan informasi berbagai library yang digunakan dalam proses analisis data.
- **url.txt**: File yang berisi tautan untuk menuju website ini di deploy.
## Setup Environment

    
    conda create --name main-ds python=3.9
    conda activate main-ds
    pip install streamlit
    pip install -r requirements.txt
    

## Run Streamlit App

    
    streamlit run dashboard.py
    
## Run Streamlit APP via Browser
    Link : https://ilhamdioputra-spin-voyage.streamlit.app

## Deskripsi App
Aplikasi sudah mampu dengan baik dan bekerja secara dinamis, hanya saja Ada beberapa hal yang perlu dikembangkan yaitu Diagram Pie Chart Untuk Melihat Perbandingan Pengguna Registered dan Pengguna Casual masih bersifat statik. Kemudian untuk Histogram Jam paling banyak disewakan dan paling sedikit disewakan sepeda sudah bekerja dengan baik secara dinamis,  **namun ketika menggunakan fitur dinamis waktu maka warna khusus yang berbeda untuk menampilkan mana data histogram yang paling banyak dan paling sedikit tidak bekerja dengan baik . Oleh karena itu saya membuat semua warna Sama di histogram tersebut agar tidak membuat kebingungan kedepannya**
