

# Analisis Sentimen dengan Bidirectional LSTM  

Proyek ini bertujuan untuk mempelajari model Natural Language Processing (NLP) sederhana menggunakan arsitektur **Bidirectional LSTM** untuk analisis sentimen. Dataset yang digunakan adalah **IMDB Review Dataset** dengan total 22.000 baris data untuk pelatihan. Model ini menghasilkan probabilitas antara dua kelas:  
- **Negatif**  
- **Positif**  

Probabilitas dihitung dalam rentang 0 sampai 1, dan kelas dengan probabilitas terbesar akan menjadi prediksi sentimen dari komentar/review tersebut.

---

## Cara Menjalankan Model  

Proyek ini dapat dijalankan dengan dua cara:  

### 1. Menjalankan Model dengan File **.h5**  
**Langkah-langkah:**  
1. Pastikan Anda menggunakan **TensorFlow** versi **2.14**.  
2. Gunakan Python versi **3.10**, karena runtime ini kompatibel dengan TensorFlow 2.14.  
3. Pastikan **NumPy** yang terpasang memiliki versi di bawah **2.0** (contoh: `1.24.x`).  
4. Unduh file model **.h5** yang telah disediakan.  
5. Jalankan script Python untuk memuat dan menggunakan model tersebut.  

### 2. Menjalankan dengan **Streamlit**  
**Langkah-langkah:**  
1. Unduh file berikut:  
   - File model **.h5**.  
   - File tokenizer dalam format **.pickle**.  
2. Buka terminal, navigasikan ke folder proyek, dan jalankan perintah berikut:  
   ```bash
   streamlit run .
   ```  
3. Harap diperhatikan bahwa metode ini menggunakan endpoint IBM untuk beberapa fungsi tambahan. Namun, tidak ada jaminan bahwa endpoint tersebut masih aktif sehingga metode ini **tidak disarankan**.  

---

## Catatan  
- Proyek ini ditujukan untuk **pembelajaran** dan **eksperimen** model NLP sederhana.  
- Output dari model berupa probabilitas untuk setiap kelas sentimen (**negatif** atau **positif**).  
- Gunakan proyek ini sebagai referensi untuk memahami arsitektur Bidirectional LSTM dan penerapannya pada analisis sentimen.  

---

**Selamat mencoba dan belajar!**  