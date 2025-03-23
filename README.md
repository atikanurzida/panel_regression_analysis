# Analisis Pengaruh Pendidikan dan Gini Coefficient terhadap Kemiskinan


### **Latar Belakang**

Pembangunan ekonomi yang inklusif dan berkelanjutan merupakan salah satu tujuan utama dari pencapaian Tujuan Pembangunan Berkelanjutan (SDGs), khususnya dalam hal pengentasan kemiskinan. Namun, kemiskinan tetap menjadi masalah struktural yang menghambat pencapaian tujuan tersebut. Menurut penelitian Perwitasari et al. (2023) tingkat pendidikan, koefisien Gini, dan Produk Domestik Regional Bruto (PDRB) merupakan indikator utama yang berperan dalam mengukur ketimpangan pendapatan dan akses terhadap kesempatan ekonomi.

Meskipun data empiris menunjukkan hubungan kausal dari faktor pendidikan dan gini coefficient yang signifikan terhadap kemiskinan, masih belum jelas sejauh mana kedua faktor ini secara simultan berkontribusi terhadap pengurangan kemiskinan dalam jangka panjang. Oleh karena itu, penelitian ini bertujuan untuk menganalisis pengaruh pendidikan dan Gini coefficient terhadap tingkat kemiskinan di beberapa provinsi di Indonesia dari tahun 2007 hingga 2020 menggunakan pendekatan regresi data panel.

Hasil dari penelitian ini diharapkan dapat memberikan pemahaman yang lebih komprehensif tentang peran pendidikan dan distribusi pendapatan dalam mengurangi kemiskinan serta menjadi dasar dalam perumusan kebijakan pembangunan ekonomi yang lebih inklusif.

### **Tujuan Analisis**

   - Menganalisis efek jangka panjang dari pendidikan terhadap kemiskinan. 
   - Melihat apakah perubahan Gini coefficient mempengaruhi penurunan kemiskinan secara signifikan dalam rentang waktu tertentu.

### **Regresi Data Panel**
Regresi data panel adalah metode analisis statistik yang digunakan untuk menganalisis data yang memiliki dimensi lintas individu (cross-section) dan dimensi waktu (time series). Dengan kata lain, data panel menggabungkan observasi dari beberapa entitas (misalnya, negara, perusahaan, rumah tangga) yang diamati selama beberapa periode waktu.

##### **Model dalam Regresi Data Panel**

###### **Common Effect Model (CEM) / Pooled OLS**
  Model yang mengasumsikan bahwa hubungan antar variabel independen dan dependen sama untuk semua individu dan waktu.
   - Tidak mempertimbangkan perbedaan antar individu atau waktu.
   - Asumsinya semua entitas memiliki intercept yang sama.
   - Modelnya sama dengan regresi OLS biasa

###### **Fixed Effect Model (FEM)**
   Fixed Effect Model (FEM) adalah salah satu metode dalam regresi data panel yang digunakan untuk menganalisis hubungan antara variabel dengan mempertimbangkan perbedaan yang tetap dari masing-masing individu atau kelompok dalam dataset.
   - Mengasumsikan adanya perbedaan spesifik antar individu yang tetap (fixed) selama periode waktu tertentu.
   - Efek tetap ini dikontrol dengan menambahkan variabel dummy untuk setiap individu atau dengan pendekatan transformasi (within transformation).

##### **Pemilihan model yang tepat**
###### **Uji Chow**
   Uji Chow adalah metode statistik yang digunakan untuk menentukan apakah dua kelompok data memiliki struktur regresi yang sama atau berbeda. Dalam analisis data panel, uji ini digunakan untuk membandingkan Common Effect Model (CEM) dan Fixed Effect Model (FEM).
   - Common Effect Model (CEM) → Mengasumsikan bahwa semua individu (misalnya, provinsi) memiliki hubungan yang sama tanpa adanya efek spesifik.
   - Fixed Effect Model (FEM) → Mengasumsikan bahwa setiap individu memiliki perbedaan tetap yang harus diperhitungkan.

#### **Kesimpulan**
Dari perbandingan metode Common Effect Model dan Fixed Effect Model, dapat disimpulkan bahwa model terbaik dengan menggunakan Fixed Effect Model. Hal tersebut karena p-value pada F-Poolability < 0.00 menunjukkan bahwa ada perbedaan karakteristik antarprovinsi yang harus diperhitungkan dalam model. Selain itu nilai R-Squared pada Fixed Effect Model lebih besar yaitu 77.19%
