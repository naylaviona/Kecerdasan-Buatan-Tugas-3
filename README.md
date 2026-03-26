# Kecerdasan Buatan Tugas 3

## Tugas AI – Linear Regression (SGD from Scratch) ##
Mata Kuliah Artificial Intelligence

## Topik ##
- Linear Regression
- Mean Squared Error (MSE)
- Gradient Descent
- Stochastic Gradient Descent (SGD)

## Modul 1 – Linear Regression ##
Deskripsi:
Pada tugas ini, model Linear Regression dibangun untuk memprediksi biaya medis personal (charges) berdasarkan Body Mass Index (BMI).
Model diimplementasikan tanpa menggunakan scikit-learn, dan proses pembelajaran dilakukan menggunakan Stochastic Gradient Descent (SGD).

## Dataset ##
Dataset yang digunakan:
Medical Cost Personal Datasets
https://www.kaggle.com/datasets/mirichoi0218/insurance

## Dasar Teori ##
1. Model Linear Regression
2. Error Function
3. Mean Squared Error (MSE)

## Variabel yang digunakan: ##
1. Fitur (x) : bmi
2. Target (y) : charges

## Implementasi dilakukan di Google Colab menggunakan: ##
- pandas → membaca dataset
- numpy → perhitungan numerik
- matplotlib → visualisasi regresi
- Model dilatih menggunakan SGD tanpa library machine learning.

## Hasil ##
Output yang ditampilkan:
- Final weight (w)
- Final bias (b)
- Final Mean Squared Error (MSE)
- Visualisasi garis regresi terhadap data BMI vs Charges
