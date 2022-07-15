<img width="154" alt="Step Processing" src="...\Gambar\Readme">
# Clustering with K-Medoids
<table>
<tr>
<td>
  Analisis Clustering Ayat-Ayat Al-Qur'an Menggunakan Algoritma K-Medoids ditujukan sebagai salah satu syarat untuk mendapatkan gelar Sarjana Teknik
</td>
</tr>
</table>

### Development
Penjelasan Detail :

* Preprocessing :
    * Cleaning Data : Untuk membersihkan data dari numerik, special characters, coma, dot.
    * Text Processing : Memproses data untuk mempersiapkan agar bisa diproses pada saat modelling
        - Case Folding : Untuk merubah seluruh kata menjadi huruf kecil semua
        - Tokenizing : Untuk menguraikan kalimat menjadi beberapa kata atau "token"
        - Stopwords : Menghilangkan kata yang dianggap kurang perlu. Menggunakan Package dari NLTK
        - Stemming : Merubah Kata menjadi kata dasar menggunakan algoritma Nazief dan Adriani by Sastrawi
        - Pembobotan TF-IDF : Konversi setiap kata yang muncul menjadi integer berdasarkan nilai bobotnya
        - Reduksi Dimensi : Mengurangi kolom untuk meningkatkan kualitas hasil klaster dan kinerja algoritma
* Modelling :
    * K-Medoids Algorithm : Klasterisasi Menggunakan Algoritma K-Medoids
* Evaluasi : 
    * Silhouette Coefficient : Mengevaluasi Hasil Klaster menggunakan metode Silhouette Coefficient

## Built with Package

- Pandas
- Numpy
- NLTK
- Sastrawi
- Sklearn
- Matplotlib
- Seaborn

## Contact

Linkedin : https://www.linkedin.com/in/ridhaginanjar/
Github : https://github.com/ridhaginanjar
Email : ridhaginanjar7@gmail.com

