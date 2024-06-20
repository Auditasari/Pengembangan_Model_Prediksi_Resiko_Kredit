# Pengembangan_Model_Prediksi_Resiko_Kredit
## Rakamin Virtual Intership ID/X Patners
### Final Project

#### Problem 
Bank meminjamkan dana kepada peminjam, namun 49,8 % peminjam mengalami kredit macet. Hal ini menyebabkan kerugian. Sehingga bank menginginkanmodel untuk memprediksi resiko kredit, untukmeminimalisir kerugian dimasa depan. <br>

#### Goal / Business Matriks 
Mengurangi rasio kredit macet sebesar 10%

#### Objective 
1. Mengembangkan model machine learning untuk memprediksi apakah peminjam meiliki resiko tinggi atau rendah
2. Memberikan rekomendasi, berupa segmentasi peminjam yang berpotensi kredit macet atau kredit lancar.

#### Data Overview 
Dataset tersusun dari : <br>

1. Total Baris : 466.285
2. Total kolom : 75 Kolom
   
Terdiri dari : <br>
1. kolom target : loan_status
2. 53 kolom numerik
3. 20 kolom kategorik

#### Proses 
1. Data Collecting
2. Exploratory Data Analysis
3. Data Pre Procesing
4. Machine Learning Model
5. Simulasi Bisnis

#### Machine Learning Model 
Project ini melihat 5 model machine learning yaitu :
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. AdaBosst Classifier
5. XGBoist Classifier

Dari kelima model yang diuji, model machine learning XGBoost Classifier memiliki nilai Rou_auc dan F1-Score yang paling baik diantara lainnya, Berikut hasil dari XGBoost Classifier : <br>
| Model | Presisi | Recall | F1-Score | Rou_Auc|
| ------| --------| -------| ---------| -------|
| XGB Classifier (Sebelum Hyperparameter Tuning)| 0.66| 0.79 |0.71 | 0.78|
| XGB Classifier (Sesudah Hyperparameter Tuning)| 0.66| 0.79 |0.71 | 0.78|

#### Simulasi Bisnis
1. Jumlah Nasabah Yang Terindikasi High Risk Sebelum Model: 77.682
2. Jumlah Nasabah Yang Terindikasi High Risk Setelah Model: 68.915

Jumlah nasabah sesudah model dengan nasabah yang terindikasi high risk berkurang sekitar 11 %. 
