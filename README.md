
# Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Edutech (JJI)  
## Business Understanding

Jaya Jaya Institut adalah lembaga pendidikan tinggi yang memiliki rekam jejak yang baik dalam menghasilkan lulusan unggulan. Meski begitu, institusi ini menghadapi tantangan serius terkait tingginya jumlah mahasiswa yang tidak menyelesaikan studi atau mengalami dropout.

Sebagai upaya solusi, Jaya Jaya Institut ingin mendeteksi mahasiswa yang berisiko dropout sejak awal, agar bisa diberikan pendampingan secara khusus. Anda sebagai calon data scientist diminta untuk menganalisis data dan merancang solusi yang efektif untuk menurunkan tingkat dropout.

### Permasalahan Bisnis

1. Tingginya angka mahasiswa yang tidak menyelesaikan pendidikan atau mengalami dropout.  
2. Tidak adanya sistem prediksi dini untuk mengidentifikasi siswa yang berpotensi mengalami dropout.  
3. Terbatasnya pemanfaatan data analitik untuk memberi pendampingan kepada siswa yang memerlukan.  
4. Citra institusi yang bisa terdampak akibat tingginya angka dropout.  
5. Perlunya strategi yang efisien dan berbasis data dalam upaya menurunkan tingkat dropout.

### Cakupan Proyek

Proyek ini akan mencakup langkah-langkah berikut:

1. **Eksplorasi Data**: Melakukan pengumpulan serta analisis terhadap data siswa untuk memahami pola dan faktor yang berkaitan dengan dropout.  
2. **Pra-pemrosesan Data**: Menyiapkan dan membersihkan data agar layak untuk dianalisis lebih dalam.  
3. **Pengembangan Model Machine Learning**: Membangun model prediktif berbasis data historis guna mengidentifikasi siswa yang berpotensi dropout.  
4. **Evaluasi Model**: Menilai performa model dengan metrik evaluasi yang tepat agar model yang dihasilkan akurat dan andal.  
5. **Pembuatan Dashboard**: Mengembangkan dashboard interaktif yang menyajikan hasil analisis untuk membantu pengambilan keputusan.  
6. **Rekomendasi Solusi**: Menyampaikan rekomendasi strategis berdasarkan hasil analisis data untuk menurunkan angka dropout.  
7. **Dokumentasi dan Presentasi**: Menyusun laporan akhir dan menyampaikan hasil proyek secara sistematis.

### Persiapan

#### Sumber Data  
Dataset yang digunakan dalam proyek ini tersedia di repositori berikut: [Dataset](https://github.com/dicodingacademy/dicoding_dataset/tree/main/students_performance). Dataset tersebut mencakup informasi tentang performa siswa, termasuk data akademik, demografi, serta faktor lainnya yang relevan untuk keperluan analisis. Beberapa kolom yang terdapat dalam dataset antara lain:

- **Marital_status**: Status perkawinan siswa.  
- **Application_mode**: Jenis pendaftaran saat mendaftar.  
- **Application_order**: Urutan pengajuan pendaftaran.  
- **Course**: Program studi yang diambil oleh siswa.  
- **Daytime_evening_attendance**: Jenis kehadiran (siang/malam).  
- **Previous_qualification**: Pendidikan terakhir yang dimiliki.  
- **Previous_qualification_grade**: Nilai dari pendidikan terakhir.  
- **Nacionality**: Kewarganegaraan siswa.  
- **Mothers_qualification**: Tingkat pendidikan ibu.  
- **Fathers_qualification**: Tingkat pendidikan ayah.  
- **Mothers_occupation**: Pekerjaan ibu.  
- **Fathers_occupation**: Pekerjaan ayah.  
- **Admission_grade**: Nilai saat masuk ke institusi.  
- **Displaced**: Status apakah siswa berpindah tempat tinggal.  
- **Educational_special_needs**: Status kebutuhan pendidikan khusus.  
- **Debtor**: Status apakah siswa memiliki utang.  
- **Tuition_fees_up_to_date**: Status pelunasan biaya kuliah.  
- **Gender**: Jenis kelamin siswa.  
- **Scholarship_holder**: Status penerima beasiswa.  
- **Age_at_enrollment**: Usia saat pendaftaran.  
- **International**: Apakah siswa berasal dari luar negeri.  
- **Curricular_units_1st_sem_credited**: Jumlah SKS semester pertama yang diakui.  
- **Curricular_units_1st_sem_enrolled**: Jumlah SKS semester pertama yang diambil.  
- **Curricular_units_1st_sem_evaluations**: Jumlah evaluasi yang dilakukan di semester pertama.  
- **Curricular_units_1st_sem_approved**: Jumlah mata kuliah semester pertama yang lulus.  
- **Curricular_units_1st_sem_grade**: Rata-rata nilai pada semester pertama.  
- **Curricular_units_1st_sem_without_evaluations**: Jumlah mata kuliah tanpa evaluasi di semester pertama.  
- **Curricular_units_2nd_sem_credited**: SKS semester kedua yang diakui.  
- **Curricular_units_2nd_sem_enrolled**: SKS semester kedua yang diambil.  
- **Curricular_units_2nd_sem_evaluations**: Evaluasi pada semester kedua.  
- **Curricular_units_2nd_sem_approved**: Mata kuliah semester kedua yang lulus.  
- **Curricular_units_2nd_sem_grade**: Rata-rata nilai semester kedua.  
- **Curricular_units_2nd_sem_without_evaluations**: Jumlah mata kuliah semester kedua tanpa evaluasi.  
- **Unemployment_rate**: Tingkat pengangguran.  
- **Inflation_rate**: Tingkat inflasi.  
- **GDP**: Produk Domestik Bruto.  
- **Status**: Status akhir siswa (dropout, lulus, dll.).

Kolom-kolom di atas memberikan informasi penting yang dapat digunakan dalam analisis dan pembuatan model prediktif.

#### Setup Environment

1. **Instalasi Dependensi**  
   Instal seluruh dependensi yang diperlukan melalui file `requirements.txt` dengan menjalankan perintah berikut:  
   ```bash  
   pip install -r requirements.txt  
   ```

2. **Mengunduh Dataset**  
   Unduh dataset dari tautan yang disediakan dan simpan dalam direktori proyek Anda.

3. **Menjalankan Jupyter Notebook**  
   Gunakan Jupyter Notebook untuk proses eksplorasi data dan pengembangan model machine learning.

## Business Dashboard

### Penjelasan Dashboard  
Dashboard dibuat menggunakan Metabase dengan tujuan menyajikan data siswa secara interaktif kepada pemangku kepentingan. Di dalamnya terdapat berbagai visualisasi seperti angka dropout, sebaran nilai, serta faktor-faktor yang mempengaruhi performa siswa. Dashboard ini memungkinkan pengguna untuk memahami pola serta tren yang relevan untuk mendukung pengambilan keputusan.

### Cara Mengakses Dashboard  
Berikut adalah langkah-langkah untuk mengakses dashboard melalui Metabase:

1. Buka browser dan kunjungi tautan berikut: [Metabase Dashboard](http://localhost:3000).  
2. Masukkan kredensial berikut untuk masuk:  
   - **Email**: `aliakbarsaid@gmail.com`  
   - **Password**: `akbar123`  
3. Setelah berhasil masuk, Anda akan diarahkan ke beranda dashboard. Pilih tampilan dashboard yang diinginkan untuk melihat visualisasi data.

## Menjalankan Sistem Machine Learning

Untuk menjalankan prototipe sistem machine learning yang dikembangkan, ikuti langkah-langkah berikut:

1. **Pastikan dependensi telah terinstal**  
   Gunakan file `requirements.txt` untuk menginstal seluruh dependensi:  
   ```bash  
   pip install -r requirements.txt  
   ```

2. **Menjalankan aplikasi Streamlit**  
   Prototipe ini memanfaatkan Streamlit sebagai antarmuka pengguna. Jalankan aplikasi dengan perintah berikut:  
   ```bash  
   streamlit run app.py  
   ```

3. **Mengakses aplikasi di browser**  
   Aplikasi akan berjalan secara lokal dan bisa diakses melalui browser di alamat berikut:  
   [http://localhost:8501](http://localhost:8501)  
   Selain itu, versi aplikasi yang telah di-deploy dapat diakses di tautan berikut:  
   [https://students-performance-dicoding.streamlit.app/](https://edutechjji.streamlit.app)

4. **Menggunakan antarmuka aplikasi**  
   - Isi formulir yang tersedia dengan data siswa, seperti status pernikahan, program studi, nilai masuk, dan informasi lainnya.  
   - Klik tombol **"🔍 Prediksi"** untuk melihat hasil prediksi.

5. **Menafsirkan hasil prediksi**  
   - Jika hasil menunjukkan **"BERISIKO DROPOUT"**, maka aplikasi akan menampilkan probabilitas serta indikator visual dari risiko tersebut.  
   - Jika hasil menunjukkan **"TIDAK BERISIKO"**, maka ditampilkan probabilitas bertahan serta indikator visual yang relevan.

Prototipe ini dirancang untuk membantu institusi pendidikan dalam mengenali siswa berisiko sejak awal dan memberikan langkah intervensi yang sesuai.

## Conclusion

Berdasarkan hasil analisis melalui dashboard “Performance Students” di Jaya Jaya Institut, terungkap bahwa tingginya tingkat dropout dipengaruhi oleh beberapa faktor utama. Di antaranya adalah keterlambatan dalam membayar biaya kuliah, prestasi akademik yang rendah di semester awal, kurangnya dukungan dalam bentuk beasiswa, serta tingginya tingkat dropout di program studi tertentu seperti Biofuel Production Technologies dan Informatics Engineering. Selain itu, mahasiswa yang mendaftar di usia muda, berjenis kelamin laki-laki, serta memiliki status debitur, juga cenderung lebih rentan untuk mengalami dropout.  
Dengan memanfaatkan dashboard interaktif serta model prediktif berbasis machine learning, institusi dapat lebih cepat mengidentifikasi siswa berisiko dan memberikan intervensi yang tepat, sehingga diharapkan angka dropout dapat ditekan dan reputasi institusi dapat meningkat dalam jangka panjang.

### Rekomendasi Action Items

Berikut beberapa tindakan strategis yang dapat diterapkan oleh Jaya Jaya Institut untuk menurunkan angka dropout dan meningkatkan retensi mahasiswa:

- Membangun sistem deteksi dini berbasis machine learning untuk mengenali mahasiswa dengan risiko tinggi dropout, berdasarkan data akademik, keuangan, dan demografi.  
- Menyediakan dukungan finansial yang lebih luas dengan memperluas akses beasiswa dan keringanan biaya, khususnya bagi mahasiswa dengan latar belakang ekonomi rentan atau yang belum melunasi pembayaran.  
- Meningkatkan kualitas proses pembelajaran serta bimbingan akademik di semester awal, termasuk program mentoring dan tutoring bagi mahasiswa baru agar mereka dapat beradaptasi dan berprestasi.  
- Melakukan evaluasi terhadap kurikulum serta metode pembelajaran di program studi dengan tingkat dropout tinggi, dan menyediakan opsi belajar yang lebih fleksibel seperti kelas malam.  
- Mengadakan layanan konseling dan program pengembangan karakter guna memberikan dukungan psikologis dan sosial, khususnya kepada mahasiswa baru yang lebih rentan menghadapi tekanan akademik maupun pribadi.
