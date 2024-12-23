# Caloriest Burn Predictions

## Deskripsi
**Caloriest Burn Predictions** adalah sebuah aplikasi web yang dirancang untuk memprediksi jumlah kalori yang terbakar berdasarkan intensitas kegiatan melalui berbagai macam olahraga. Aplikasi ini memanfaatkan teknologi machine learning untuk memberikan prediksi yang akurat. Selain itu, aplikasi ini juga dilengkapi dengan fitur BMI check dan panduan nutrisi untuk membantu pengguna mencapai gaya hidup sehat.

---

## Showcase Aplikasi

Berikut adalah beberapa tampilan dari aplikasi Caloriest Burn Predictions:

1. **Landing Page**
![Landing Page](https://res.cloudinary.com/doypx7azh/image/upload/v1734921860/localhost_5173_landing_Nest_Hub_Max_iulonc.png)

2. **Login Page**
![Login Page](https://res.cloudinary.com/doypx7azh/image/upload/v1734921859/localhost_5173_landing_Nest_Hub_Max_1_vgzgsz.png)

3. **Register Page**
![Register Page](https://res.cloudinary.com/doypx7azh/image/upload/v1734921858/localhost_5173_landing_Nest_Hub_Max_2_nlotyx.png)

4. **Home Page**
![Home Page](https://res.cloudinary.com/doypx7azh/image/upload/v1734921859/home_sgpc7a.png)

5. **Predict Page**
![Predict Page](https://res.cloudinary.com/doypx7azh/image/upload/v1734921859/localhost_5173_record_Nest_Hub_Max_1_q2k7br.png)

6. **BMI Check Page**
![BMI Check Page](https://res.cloudinary.com/doypx7azh/image/upload/v1734921858/localhost_5173_record_Nest_Hub_Max_4_expn7g.png)

7. **Nutrition Guide Page**
![Nutrition Guide Page](https://res.cloudinary.com/doypx7azh/image/upload/v1734921858/localhost_5173_record_Nest_Hub_Max_5_n2c55r.png)
![Nutrition Guide Page dua](https://res.cloudinary.com/doypx7azh/image/upload/v1734921860/localhost_5173_record_Nest_Hub_Max_6_p9acc0.png)

---

## Cara Instalasi

Ikuti langkah-langkah berikut untuk menginstal aplikasi Caloriest Burn Predictions di lingkungan lokal Anda:

### 1. Clone Repository
```bash
git clone https://github.com/username/caloriest-burn-predictions.git
cd caloriest-burn-predictions
```

### 2. Instalasi Frontend
- Aplikasi frontend dibangun menggunakan **React + Vite**.
```bash
cd frontend
npm install
npm run dev
```

### 3. Instalasi Backend Server
- Backend server dibangun menggunakan **Express.js** dan **MongoDB** untuk database.

#### Mengatur File `.env`
Buat file `.env` di dalam folder `server` dan tambahkan konfigurasi berikut:
```
MONGO_URI=your_mongo_db_connection_string
PORT=5000
TOKEN_KEY=your-secret-key
```

- Setelah konfigurasi selesai, jalankan perintah berikut:
```bash
cd ../server
npm install
npm start
```

### 4. Instalasi Machine Learning API
- API untuk prediksi kalori dibangun menggunakan **Flask**.
```bash
cd ../ml
pip install -r requirements.txt
python app.py
```

### 5. Jalankan Aplikasi
Pastikan semua layanan (frontend, backend server, dan Flask API) berjalan dengan baik. Buka browser Anda dan akses aplikasi melalui URL yang diberikan oleh Vite.

---
