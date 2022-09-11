# Klasifikasi Rambu Lalu Lintas - Husnan

## Domain Proyek

Beberapa penerapan computer vision yang paling penting untuk self-driving cars adalah kemampuan mendeteksi, mengklasifikasikan, dan melokalisasi berbagai jenis objek. Objek-objek ini bisa berupa kendaraan lain, pejalan kaki, rambu lalu lintas, atau hal aneh lain yang mungkin kita lihat saat mengemudi.
Pada kesempatan kali ini, saya membuat model machine learning terkait dengan penerapan computer vision pada self-driving cars. Saya membuat model klasifikasi gambar dengan data berupa rambu-rambu lalu lintas.

## Business Understanding

### Problem Statements
- Bagaimana self-driving cars memahami peringatan, larangan, perintah, atau petunjuk pada jalan?

### Goals
- Membuat model klasifikasi gambar dengan data berupa rambu-rambu lalu lintas.

## Data Understanding
[German Traffic Sign Dataset](https://www.kaggle.com/datasets/saadhaxxan/germantrafficsigns) merupakan benchmark dataset untuk klasifikasi gambar multi kelas. Terdapat satu rambu lalu lintas pada masing-masing gambar, sehingga dataset ini disebut juga sebagai single-image atau gambar tunggal.

### Variabel-variabel pada German Traffic Sign Dataset adalah sebagai berikut:
|Kelas |Label                                        |Kelas   |Label                                         | 
|------|---------------------------------------------|--------|----------------------------------------------|
|0   	 |Speed limit (20km/h)   	                     |22   	  |Bumpy road   	                               |
|1   	 |Speed limit (30km/h)   	                     |23   	  |Slippery road   	                             |
|2   	 |Speed limit (50km/h)   	                     |24   	  |Road narrows on the right   	                 |
|3   	 |Speed limit (60km/h)   	                     |25   	  |Road work   	                                 |
|4   	 |Speed limit (70km/h)   	                     |26   	  |Traffic signals   	                           |
|5   	 |Speed limit (80km/h)   	                     |27   	  |Pedestrians   	                               |
|6   	 |End of speed limit (80km/h)                  |28   	  |Children crossing   	                         |
|7   	 |Speed limit (100km/h)   	                   |29   	  |Bicycles crossing   	                         |
|8   	 |Speed limit (120km/h)   	                   |30   	  |Beware of ice/snow   	                       |
|9   	 |No passing   	                               |31   	  |Wild animals crossing   	                     |
|10    |No passing for vehicles over 3.5 metric tons |32   	  |End of all speed and passing limits   	       |
|11    |Right-of-way at the next intersection   	   |33   	  |Turn right ahead   	                         |
|12    |Priority road   	                           |34   	  |Turn left ahead   	                           |
|13    |Yield   	                                   |35   	  |Ahead only   	                               |
|14    |Stop   	                                     |36   	  |Go straight or right   	                     |
|15    |No vehicles   	                             |37   	  |Go straight or left   	                       |
|16    |Vehicles over 3.5 metric tons prohibited   	 |38   	  |Keep right   	                               |
|17    |No entry   	                                 |39   	  |Keep left   	                                 |
|18    |General caution   	                         |40   	  |Roundabout mandatory   	                     |
|19    |Dangerous curve to the left   	             |41   	  |End of no passing   	                         |
|20    |Dangerous curve to the right   	             |42   	  |End of no passing by vehicles over 3.5 metric |
|21    |Double curve   	                             |   	    |   	                                         |


## Data Preparation
Pada bagian ini Anda menerapkan dan menyebutkan teknik data preparation yang dilakukan. Teknik yang digunakan pada notebook dan laporan harus berurutan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan proses data preparation yang dilakukan
- Menjelaskan alasan mengapa diperlukan tahapan data preparation tersebut.

## Modeling
Tahapan ini membahas mengenai model machine learning yang digunakan untuk menyelesaikan permasalahan. Anda perlu menjelaskan tahapan dan parameter yang digunakan pada proses pemodelan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan kelebihan dan kekurangan dari setiap algoritma yang digunakan.
- Jika menggunakan satu algoritma pada solution statement, lakukan proses improvement terhadap model dengan hyperparameter tuning. **Jelaskan proses improvement yang dilakukan**.
- Jika menggunakan dua atau lebih algoritma pada solution statement, maka pilih model terbaik sebagai solusi. **Jelaskan mengapa memilih model tersebut sebagai model terbaik**.

## Evaluation
Pada bagian ini anda perlu menyebutkan metrik evaluasi yang digunakan. Lalu anda perlu menjelaskan hasil proyek berdasarkan metrik evaluasi yang digunakan.

Sebagai contoh, Anda memiih kasus klasifikasi dan menggunakan metrik **akurasi, precision, recall, dan F1 score**. Jelaskan mengenai beberapa hal berikut:
- Penjelasan mengenai metrik yang digunakan
- Menjelaskan hasil proyek berdasarkan metrik evaluasi

Ingatlah, metrik evaluasi yang digunakan harus sesuai dengan konteks data, problem statement, dan solusi yang diinginkan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan formula metrik dan bagaimana metrik tersebut bekerja.

**---Ini adalah bagian akhir laporan---**

_Catatan:_
- _Anda dapat menambahkan gambar, kode, atau tabel ke dalam laporan jika diperlukan. Temukan caranya pada contoh dokumen markdown di situs editor [Dillinger](https://dillinger.io/), [Github Guides: Mastering markdown](https://guides.github.com/features/mastering-markdown/), atau sumber lain di internet. Semangat!_
- Jika terdapat penjelasan yang harus menyertakan code snippet, tuliskan dengan sewajarnya. Tidak perlu menuliskan keseluruhan kode project, cukup bagian yang ingin dijelaskan saja.
