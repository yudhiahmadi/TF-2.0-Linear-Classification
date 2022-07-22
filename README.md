# TF 2.0 Linear Classification
![image](https://user-images.githubusercontent.com/87703066/180477833-a9cc47bd-33c2-4519-a90f-aeca2c3104f4.png)

Pembuatan model klasifikasi dengan menggunakan tensorflow v2

Langkah-langkah :
1. Import data yang digunakan (Kali ini saya menggunakan data publik dari sklearn)
2. Bagi data menjadi data train dan data test. Untuk proporsinya bebas ingin berapa saja, asal data trainnya lebih tinggi
3. Standarisasi menggunakan standardscaler, hal ini ditujukan untuk standarisasi data ke skala atau range yang sama
![image](https://user-images.githubusercontent.com/87703066/180411881-8151810d-cb54-4cc8-b2bd-1aaec40b3497.png)

4. Buat model
- 2 Layer : input dan dense sigmoid
Penggunaan sigmoid bertujuan untuk mengklasifikasikan ke 2 kelas yaitu 0 dan 1
![image](https://user-images.githubusercontent.com/87703066/180412025-314c1cb1-30ef-48f1-8990-229ed55829cf.png)

- Optimizer menggunakan adam

- Adam adalah algoritma optimasi pengganti untuk stochastic gradient descent untuk training model deep learning. Adam menggabungkan sifat-sifat terbaik dari algoritma AdaGrad dan RMSProp untuk memberikan optimization algorithm yang dapat menangani sparse gradients pada noisy problem.
(https://lms.onnocenter.or.id)

![image](https://user-images.githubusercontent.com/87703066/180413480-16d25454-5c9a-480a-9581-4a600790349e.png)

Source (https://towardsdatascience.com/)





- Pengukuran loss (kesalahan deteksi) menggunakan binary_crossentropy
![image](https://user-images.githubusercontent.com/87703066/180413102-754afd75-5296-4c93-bf14-aa0dc2bb6c9a.png)

Source (https://towardsdatascience.com/)

5. Plot loss dan accuracy
