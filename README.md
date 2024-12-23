# Caloriest Burn Predictions

## Deskripsi
**Caloriest Burn Predictions** adalah sebuah aplikasi web yang dirancang untuk memprediksi jumlah kalori yang terbakar berdasarkan intensitas kegiatan melalui berbagai macam olahraga. Aplikasi ini memanfaatkan teknologi machine learning untuk memberikan prediksi yang akurat. Selain itu, aplikasi ini juga dilengkapi dengan fitur BMI check dan panduan nutrisi untuk membantu pengguna mencapai gaya hidup sehat.

---

## Showcase Aplikasi

Berikut adalah beberapa tampilan dari aplikasi Caloriest Burn Predictions:

1. **Landing Page**
![Landing Page](https://res.cloudinary.com/doypx7azh/image/upload/v1734921860/localhost_5173_landing_Nest_Hub_Max_iulonc.png)

2. **Login Page**
![Login Page](./showcase/login-page.png)

3. **Register Page**
![Register Page](./showcase/register-page.png)

4. **Home Page**
![Home Page](./showcase/home-page.png)

5. **Predict Page**
![Predict Page](./showcase/predict-page.png)

6. **BMI Check Page**
![BMI Check Page](./showcase/bmi-check-page.png)

7. **Nutrition Guide Page**
![Nutrition Guide Page](./showcase/nutrition-guide-page.png)

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
JWT_SECRET=your_jwt_secret_key
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
flask run
```

### 5. Jalankan Aplikasi
Pastikan semua layanan (frontend, backend server, dan Flask API) berjalan dengan baik. Buka browser Anda dan akses aplikasi melalui URL yang diberikan oleh Vite.

---
