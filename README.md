# Amazon Kindle Books Sales Analysis 2023

Ini merupakan GitHub Repository untuk Project Amazon Kindle Books Sales Analysis 2023

## Background Project

Dalam project ini, diberikan skenario portal marketplace Amazon ingin melihat *review* penjualan untuk *Kindle e-books* tahun 2023. Amazon juga ingin mencari tahu faktor yang berpotensi untuk meningkatkan penjualan dan akan menerapkannya di tahun depan. Terdapat enam *file* dalam repository, yaitu sebagai berikut:

1. Amazon Kindle Books Sales Analysis 2023.pdf
   File PDF yang berisi detail penjelasan dari project ini, mulai dari proses *data cleansing*, *exploration*, *insights*, dan *recommendations*
2. Kindle Dashboard.twb
   File visualsasi dari Tableau yang membantu pembuatan grafik dan KPI dalam *project* ini.
3. kindle_analysis.ipynb
   Notebook yang berisi proses analisis *project*. Proses analisis yang dijalankan, yakni:
   - Analisis model regresi menggunakan OLS
   - *Plotting* grafik menggunakan matplotlib dan seaborn
   - Komputasi matematika menggunakan numpy.
5. kindle_data.ipynb
   Notebook ini berisi proses *data cleansing* dari *file* data mentah yang di dapatkan. Proses *data cleansing* ini meliputi:
   - Identifikasi *missing value*
   - *Handling duplicate*
   - *Handling inconsistent format*
   - Hapus *outlier*.
7. Kindle_Data_Cleaned_2.csv
   File *export* hasil pembersihan data dari  kindle_data.ipynb
8. kindle_data-v2.csv
   File data mentah. Data diambil dari portal *free data source*, kaggle