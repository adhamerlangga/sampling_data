# sampling_data

- line 3: baris untuk mendownload data, dengan menggunakan perintah wget
- line 5 dan line 6: konversi file menjadi csv melalui package csvkit dan menyimpannya pada file weather_2014 dan weather_2015. pada baris 5 konversi dilakukan pada sheet 1 dan baris 6 dilakukan pada sheet 2
- line 7: menggabungkan kedua file csv secara perbaris dengan command csvstack, dan menyimpannya pada output berupa file bernama weather.csv
- line 9: menghapus file yang telah didownload pada awal tahap (weather_data.xlsx)
- line 11: menulis isi file dari baris awal file csv, yakni mengambil header dan menyimpannya pada file sample_weather.csv
- line 12: menulis isi file dari file csv dengan melakukan sampling data sebesar 0.3 (30%) dari jumlah data dan menyimpannya (menambahkan) pada file sample_weather.csv
