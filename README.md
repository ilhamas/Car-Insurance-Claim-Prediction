# Car-Insurance-Claim-Prediction
## Background
Pada tahun 2018 di Amerika tercatat sekitar 12 juta kecelakaan terjadi, sekitar 42% atau 5 juta diantara nya adalah kecelakaan mobil dan kecelakaan itu mengakibatkan sekitar 1.8 juta orang mengalami luka. Tentunya hal ini menimbulkan kerugian materi maupun non materi bagi para korban.
Asuransi mobil tentunya sangat bermanfaat untuk menanggung kerugian berupa kerusakan mobil karena kecelakaan, dana yang digunakan perusahaan asuransi untuk memperbaiki kerusakan mobil tersebut bersumber dari premi yang di bayarkan customer setiap tahun nya. Disisi lain premi juga merupakan salah satu sumber pendapatan bagi perusahaan asuransi yang nanti nya akan di manfaatkan perusahaan untuk mendapatkan keuntungan lain nya seperti investasi sehingga sangat penting bagi perusahaan untuk menentukan premi yang tepat bagi customer sehingga revenue perusahaan meningkat.
Ini merupakan sebual project Machine Learning yang dikerjakan secara kolaborasi untuk memprediksi customer yang berpotensi melakukan claim dan mencari kriteria customer yang memiliki potensi claim rendah sehingga perusahaan dapat membuat kebijakan premi yang tepat. Model yang akan di buat adalah Supervised Machine Learning dengan tipe Classification.

## Problem Statement
Bagaimana cara mengetahui customer yang akan melakukan claim agar perusahaan bisa membuat kebijakan premi untuk meningkatkan revenue

## Goals
- Mengetahui tahu customer yang akan melakukan claim
- Mengetahui tahu kriteria customer yang memiliki potensi tidak melakukan claim

## Objective
- Membuat model Machine Learning untuk memprediksi customer yang akan melakukan claim dan tidak
- Menganalisa kriteria customer yang tidak melakukan claim

Data yang di gunakan bersumber dari https://www.kaggle.com/mukuljh2/car-insurance-claim.

## Insight
- Sebesar 32 % customer yang memiliki mobil usia muda melakukan klaim, mengingat kondisi mobil yang masih prima customer tersebut cenderung mengendarai mobil nya lebih cepat sehingga tingkat kecelakaan meningkat.

- Sebesar 45.12 % customer yang lisensi berkendara nya dicabut melakukan klaim, hal ini menunjukan customer tersebut kurang memiliki kesadaran safety driving sehingga potensi kecelakaan meningkat.

- Dibandingkan kelompok umur lainnya,  persentase customer Gen X 
yang melakukan claim paling rendah (21.6 %), hal ini disebabkan usia tersebut cenderung lebih safety dalam berkendara sehingga potensi kecelakaan lebih rendah dari yang lain

- Sebesar 75 % customer yang tidak memiliki anak yang mengendarai mobil tidak melakukan klaim. Pengemudi yang berusia muda cenderung kurang waspada dalam berkendara sehingga lebih sering melakukan klaim.

- Sebesar 83 % (2229) customer yang memiliki kendaraan jenis minivan tidak melakukan klaim. Hal ini dikarenakan pengemudi mobil minivan cenderung membawa anak dalam berkendara sehingga pengemudi berkendara lebih berhati-hati sehingga kemungkinan untuk melakukan klaim lebih rendah.

- Sebesar 78 % customer yang telah bergabung selama lebih dari 10 tahun tidak melakukan klaim, hal ini menunjukan customer yang sudah lama bergabung memiliki tingkat kecelakaan yang rendah karena umur yang semakin matang dan mobil yang semakin tua.

## Recommendation
### Berdasarkan Model
- Menggunakan Logistic Regression model

- Model digunakan untuk memprediksi potential customer

- Secara proporsional menaikkan premi asuransi bagi existing customer 

### Kriteria customer yang cenderung tidak melakukan claim:
- No license revoked (lisensi SIM-nya tidak pernah dicabut)
- memiliki Minivan
- No kids driving at home (tidak memiliki anak yang berkendara)
- Car age more then 5 years (usia kendaraan diatas 5 tahun)
- Gen X

### Menaikkan premi asuransi bagi existing customer yang:
- frekuensi claim tinggi 
- claim point tinggi
 




