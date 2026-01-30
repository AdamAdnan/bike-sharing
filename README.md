# 🚲 Bike Sharing Dashboard

Dashboard interaktif untuk menganalisis data Bike Sharing menggunakan **Streamlit**.  
Dashboard ini menampilkan ringkasan metrik, pola waktu peminjaman, segmentasi pengguna, pengaruh cuaca dan musim, serta clustering permintaan.

## 📁 Struktur Folder

```
project/
│
├── dashboard.py
├── day.csv
├── hour.csv
├── requirements.txt
└── README.md
```

## Setup Environment - Anaconda
```
conda create --name bike-dashboard python=3.10
conda activate bike-dashboard
pip install -r requirements.txt
```

## Setup Environment - Shell/Terminal
```
mkdir proyek_analisis_data
cd proyek_analisis_data
pip install -r requirements.txt
```

## Run steamlit app
```
streamlit run dashboard/dashboard.py
```
