# Tugas AI – Linear Regression (SGD from Scratch)
Mata Kuliah Artificial Intelligence

### Topik 
- Linear Regression
- Linear Classifier
- Mean Squared Error (MSE)
- Cross-Entropy Loss
- Softmax
- Stochastic Gradient Descent (SGD)

## Modul 1 – Linear Regression 
Deskripsi:
Pada tugas ini, model Linear Regression dibangun untuk memprediksi biaya medis personal (charges) berdasarkan Body Mass Index (BMI).
Model diimplementasikan tanpa menggunakan scikit-learn, dan proses pembelajaran dilakukan menggunakan Stochastic Gradient Descent (SGD).

### Dataset 
Medical Cost Personal Datasets
https://www.kaggle.com/datasets/mirichoi0218/insurance

### Dasar Teori 
1. Model Linear Regression
2. Error Function
3. Mean Squared Error (MSE)

### Variabel yang digunakan: 
1. Fitur (x) : bmi
2. Target (y) : charges

### Implementasi dilakukan di Google Colab menggunakan: 
- pandas → membaca dataset
- numpy → perhitungan numerik
- matplotlib → visualisasi regresi
- Model dilatih menggunakan SGD tanpa library machine learning.

### Output Modul 1
- Final weight (w)
- Final bias (b)
- Final Mean Squared Error (MSE)
- Visualisasi garis regresi terhadap data BMI vs Charges

## MODUL 2 – Linear Classifier (Softmax + Cross Entropy)
Deskripsi: Membangun model klasifikasi harga ponsel berdasarkan:
- ram
- battery_power
Target:
- price_range (0–3)
Model diimplementasikan dari awal menggunakan:
- Softmax
- Cross-Entropy Loss
- SGD
Tanpa scikit-learn.

### Dataset
Mobile Price Classification
https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification

### Dasar Teori
1. Linear Classifier
2. Softmax
3. Cross-Entropy Loss
4. Update SGD

### Output Modul 2
- Implementasi fungsi softmax menggunakan numpy
- Implementasi cross-entropy loss
- Training menggunakan SGD
- Visualisasi decision boundary
- Evaluasi akurasi model
