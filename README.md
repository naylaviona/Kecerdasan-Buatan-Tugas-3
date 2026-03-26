# Kecerdasan-Buatan-Tugas-3

📊 Tugas AI – Linear Regression (SGD from Scratch)
👩‍💻 Mata Kuliah

Artificial Intelligence

📌 Topik
Linear Regression
Mean Squared Error (MSE)
Gradient Descent
Stochastic Gradient Descent (SGD)

📘 Modul 1 – Linear Regression
🎯 Deskripsi

Pada tugas ini, model Linear Regression dibangun untuk memprediksi biaya medis personal (charges) berdasarkan Body Mass Index (BMI).

Model diimplementasikan tanpa menggunakan scikit-learn, dan proses pembelajaran dilakukan menggunakan Stochastic Gradient Descent (SGD) sesuai materi Lecture 7.

📂 Dataset

Dataset yang digunakan:

Medical Cost Personal Datasets
https://www.kaggle.com/datasets/mirichoi0218/insurance

Variabel yang digunakan:

Fitur (x) : bmi
Target (y) : charges
🧮 Dasar Teori
1️⃣ Model Linear Regression

Sesuai materi lec07:

𝑓
(
𝑥
)
=
𝑏
+
𝑤
@
𝑥
f(x)=b+w@x

Untuk satu variabel:

𝑓
(
𝑥
)
=
𝑤
𝑥
+
𝑏
f(x)=wx+b
2️⃣ Error Function
𝜖
𝑖
=
𝑤
𝑥
𝑖
+
𝑏
−
𝑦
𝑖
ϵ
i
	​

=wx
i
	​

+b−y
i
	​

3️⃣ Mean Squared Error (MSE)
𝑀
𝑆
𝐸
=
1
𝑛
∑
𝑖
=
1
𝑛
𝜖
𝑖
2
MSE=
n
1
	​

i=1
∑
n
	​

ϵ
i
2
	​


MSE merupakan rata-rata kuadrat error untuk mengukur seberapa baik model memprediksi data.

4️⃣ Stochastic Gradient Descent (SGD)

Update parameter sesuai lec07:

𝑤
←
𝑤
−
𝜂
𝜖
𝑖
𝑥
𝑖
w←w−ηϵ
i
	​

x
i
	​

𝑏
←
𝑏
−
𝜂
𝜖
𝑖
b←b−ηϵ
i
	​


Dimana:

𝜂
η = learning rate
𝜖
𝑖
ϵ
i
	​

 = error pada data ke-i
🧪 Simulasi Perhitungan Manual

Diberikan:

x = 30
y = 16000
w = 100
b = 100
learning rate = 0.001

Hasil:

Prediksi = 3100
Error = -12900
w baru = 487
b baru = 112.9
💻 Implementasi

Implementasi dilakukan di Google Colab menggunakan:

pandas → membaca dataset
numpy → perhitungan numerik
matplotlib → visualisasi regresi

Model dilatih menggunakan SGD tanpa library machine learning.

📊 Hasil

Output yang ditampilkan:

Final weight (w)
Final bias (b)
Final Mean Squared Error (MSE)
Visualisasi garis regresi terhadap data BMI vs Charges
