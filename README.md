# Klasifikasi Customer Churn Menggunakan Metode Support Vector Machine (SVM)
Customer churn merujuk pada persentase pelanggan yang berhenti menggunakan produk atau layanan dalam periode tertentu. Dalam konteks perbankan, customer churn dapat diartikan sebagai perpindahan pelanggan dari satu bank ke bank lain, yang mengakibatkan hilangnya pelanggan secara periodik. Fenomena ini dapat berpengaruh besar terhadap pendapatan perusahaan perbankan. Oleh karena itu, penggunaan model Support Vector Machine (SVM) untuk menganalisis data sampel dapat meningkatkan akurasi prediksi churn, sehingga membantu bank komersial memprediksi customer churn dengan lebih tepat dan efektif.

# Terdapat 12 atribut pada data yang digunakan, yaitu:
1. Customer ID
2. Credit Score
3. Country
4. Gender
5. Age
6. Tenure
7. Balance
8. Products Number
9. Credit Card
10. Active Member
11. Estimated Salary
12. Churn

# Kesimpulan
SVM adalah metode yang efektif untuk klasifikasi dan penyelesaian masalah yang sulit dilakukan secara manual. Dalam prediksi churn pelanggan bank, SVM dapat mengatasi masalah nonlinier dan dimensi tinggi dengan akurasi 86% menggunakan kernel RBF yang dioptimalkan. Variabel yang paling mempengaruhi churn adalah usia, pendapatan, saldo rekening, dan negara. Namun, dibandingkan dengan Random Forest Classifier yang mencapai akurasi 91%, SVM masih sedikit kalah. Walaupun Random Forest memberikan hasil yang lebih baik, prosesnya lebih lambat dan rawan overfitting karena melibatkan banyak data dan model pohon yang kompleks. Meskipun demikian, model SVM tetap efektif dalam memprediksi churn, memberikan wawasan penting untuk manajemen hubungan pelanggan, dan membantu bank meningkatkan keuntungan serta mencegah kehilangan nasabah.
