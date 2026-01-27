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
conda create --name main-ds python=3.9
conda activate main-ds
pip install -r requirements.txt
```

## Setup Environment - Shell/Terminal
```
mkdir proyek_analisis_data
cd proyek_analisis_data
pipenv install
pipenv shell
pip install -r requirements.txt
```

## Run steamlit app
```
streamlit run dashboard.py
```
