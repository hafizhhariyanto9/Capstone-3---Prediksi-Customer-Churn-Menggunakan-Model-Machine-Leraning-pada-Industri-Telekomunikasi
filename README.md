# Prediksi Customer Churn Menggunakan Model Machine Learning pada Industri Telekomunikasi

## Pendahuluan
Churn pelanggan merupakan tantangan utama dalam industri telekomunikasi karena berdampak langsung pada pendapatan dan profitabilitas perusahaan. Oleh karena itu, prediksi churn menjadi aspek krusial dalam strategi retensi pelanggan. Proyek ini bertujuan untuk mengembangkan model machine learning yang dapat memprediksi kemungkinan pelanggan akan berhenti berlangganan layanan telekomunikasi. Dataset yang digunakan berasal dari ABC Telco dan terdiri dari berbagai fitur yang mencerminkan perilaku pelanggan, termasuk lama berlangganan, jenis kontrak, layanan yang digunakan, dan tagihan bulanan.

Dalam penelitian ini, diterapkan beberapa teknik pemodelan machine learning, yaitu Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, XGBoost, LightGBM, Extra Trees, CatBoost, dan Bagging. Selain itu, dilakukan proses seleksi fitur, resampling data menggunakan SMOTE untuk menangani ketidakseimbangan kelas, serta optimasi hiperparameter dan threshold guna meningkatkan performa model. Model dievaluasi menggunakan metrik F2-score untuk memastikan bobot yang lebih besar pada Recall dalam mendeteksi pelanggan yang berisiko churn.

Hasil eksperimen menunjukkan bahwa model Logistic Regression dengan SMOTE memberikan performa terbaik dengan F2-score sebesar 0.757 pada data test setelah threshold dioptimalkan menjadi 0.25, mengungguli model lainnya. Temuan ini mengindikasikan bahwa kombinasi teknik oversampling, pemilihan threshold yang tepat, dan interpretabilitas model dapat meningkatkan efektivitas prediksi churn. Implementasi model ini membantu perusahaan mengidentifikasi pelanggan berisiko lebih awal, sehingga memungkinkan pengambilan keputusan yang lebih proaktif dalam strategi retensi dan menghemat biaya operasional sebesar $5,142 (9.7%) dibandingkan pendekatan rule-based.

**Kata Kunci:** Churn Prediction, Machine Learning, Telekomunikasi, Logistic Regression, SMOTE, F2-score, Threshold Optimization

**Streamlit:** [https://2dnrllhbjrryvan6ga9fys.streamlit.app/](https://deploychurnpredicttelco-hyrwakbbmxydu6zgc82kfr.streamlit.app/)
