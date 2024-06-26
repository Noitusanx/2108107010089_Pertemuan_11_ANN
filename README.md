# Artificial Neural Network (ANN)

Pada tugas pertama yaitu menggunakan dataset [Data_bank_churn](https://www.megabagus.id/download/data-ann/) bertujuan untuk memecahkan masalah bank yang berupa tingkat keluarnya nasabah yang meningkat secara drastis berdasarkan data-data yang diberikan. Setelah diuji ternyata tingkat akurasi dari artificial neural networknya cukup tinggi yaitu sebesar 86.43%.

Pada tugas kedua, kasusnya berupa diabetes dan health insurance. Pada kasus diabetes, dataset yang digunakan adalah [diabetes_prediction_dataset](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset?resource=download) yang bertujuan untuk mengetahui apakah orang tersebut terkena diabetes atau tidak berdasarkan age dan blood glucose level. Pada kasus health insurance data yang digunakan adalah [Health_insurance](https://www.kaggle.com/code/shubhamptrivedi/health-insurance-price-predict-linear-regression/input) yang bertujuan untuk memprediksi charges asuransi kesehatan berdasarkan age seseorang. Kedua kasus tersebut dibandingkan hasil akurasi SVM dan ANN-nya.

## Langkah-Langkah

1. **Install libraries**

```bash
    pip install -r requirements.txt
```

2. **Download Datasets**

   > Pastikan dataset yang di download berada di directory yang sesuai.

3. **Jalankan Code**
   > Jalankan kode cell satu persatu dengan menekan `Shift+Enter` atau dengan `Run All` untuk menjalankan semua kode sekaligus.

## Hasil Akurasi dari Metode SVM (Klasifikasi)

![alt text](images/image.png)

![alt text](images/image_accuracy.png)
​
Akurasi = 23586/25000 <br>
Akurasi = 0.94344

Sehingga hasil akurasi yang diperoleh sebesar 94.34%

## Hasil Akurasi dari Metode ANN (Klasifikasi)

![alt text](images/accuracy_ann_classification.png)

Hasil yang diperoleh sebesar 94.74%

> Berdasarkan hasil tersebut, maka akurasi yang diperoleh oleh ANN lebih baik dibandingkan dengan akurasi SVM berdasarkan studi kasus diabetes tersebut.

## Hasil Mean Squared Error (MSE) dari Metode SVM (Regresi)

![alt text](images/acc_svm_regresi.png)

Hasil Mean Squared Error (MSE) menggunakan metode SVM (Regresi) pada dataset health insurance yaitu sebesar = 1.1

## Hasil Mean Squared Error (MSE) dari Metode ANN (Regresi)

![alt text](images/acc_ann_regresi.png)

Hasil Mean Squared Error (MSE) menggunakan metode ANN (Regresi) pada dataset health insurance yaitu sebesar = .90

> Berdasarkan hasil tersebut, maka metode ANN (Regresi) memiliki nilai error lebih kecil sehingga lebih baik dibandingkan dengan metode SVM (Regresi) berdasarkan studi kasus health insurance tersebut.
