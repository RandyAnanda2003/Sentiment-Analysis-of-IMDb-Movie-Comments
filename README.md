ada dua cara untuk mencoba run model analisis sentiment ini.

jika kamu ingin menjalankan model ini langsung menggunakan model h5, maka harus menggunakan tensorflow dengan versi 2.14. runtime python yang kompatibel dengan tf 2.14 adalah py 3.10 sehingga anda juga diminta untuk mendownload python versi 3.10. depedensi lain yang mungkin harus diperhatikan adalah versi numpy harus dibawah 2. 

jika langsung menjalakan dari file streamlit, jangan lupa unduh file tokenizee pickle dan file h5 nya lalu jalankan promp di terminal streamlit run <nama file.py>. dalam cara ini tidak dapat dipastikan bahwa link endpoint ibm masih berlaku. sehingga tidak disarankan.

kode ini hanya untuk belajar model NLP sederhana menggunakan biderctional LSTM dengan datset review imdb sederhana yang berjumlah 22 ribu row dataset train
output dari kode ini adalah sebuah probabilitas antara 2 kelas dari komentar/review yang dianalisis, yaitu [negatif,positif] dimana probabilitas bernilai 0<=p(x)<=1. probabilitas terbesar itulah sentimennya
