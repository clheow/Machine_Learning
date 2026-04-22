📂 Dataset
Mohon maaf, dataset tidak disertakan dalam repository karena ukuran besar (>100MB) 🙏.

Dataset dapat diakses pada link berikut:
[https://link-dataset-kamu](https://www.kaggle.com/datasets/usdot/flight-delays?select=flights.csv)

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk membangun model Machine Learning yang dapat memprediksi keterlambatan penerbangan (flight delay) berdasarkan berbagai fitur seperti maskapai, bandara asal, bandara tujuan, jarak, dan waktu penerbangan.

---

## 🎯 Tujuan
- Memprediksi nilai keterlambatan penerbangan (arrival delay)
- Membandingkan performa beberapa algoritma Machine Learning
- Menentukan model terbaik berdasarkan evaluasi

---

## 📊 Dataset
Dataset yang digunakan berasal dari data penerbangan (flights dataset) dengan fitur seperti:
- AIRLINE
- ORIGIN_AIRPORT
- DESTINATION_AIRPORT
- DEPARTURE_DELAY
- DISTANCE
- AIR_TIME
- TAXI_OUT
- TAXI_IN
- SCHEDULED_DEPARTURE
- SCHEDULED_ARRIVAL
- DAY_OF_WEEK
- MONTH
- DAY
- ARRIVAL_DELAY (target)

---

## ⚙️ Data Preprocessing
Tahapan preprocessing yang dilakukan:
- Sampling data
- Menghapus missing value
- Handling outlier (clipping)
- Encoding data kategorikal (Label Encoding)

---

## 🤖 Algoritma yang Digunakan
Beberapa algoritma yang digunakan:
- Gradient Boosting Regressor
- Random Forest Regressor
- K-Nearest Neighbors (KNN)

---

## 🔍 Hyperparameter Tuning
Menggunakan:
- RandomizedSearchCV
Untuk mencari parameter terbaik pada setiap model.

---

## 📈 Evaluasi Model
Metode evaluasi yang digunakan:
- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- R² Score
