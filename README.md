# faiz2306140_UTS-AI
Soal 1

Penjelasan Kasus
Seorang petani ingin bantuan sistem AI untuk menentukan jenis hama dari gejala berikut:

• Daun menguning
• Terdapat bercak hitam
• Daun berlubang
• Tanaman layu

Penjelasan Source Code
Kodenya dibagi dua bagian utama:

• Fungsi inferensi(gejala)
Ini fungsi untuk mencocokkan gejala yang diberikan pengguna dengan daftar aturan (rules) yang ada.
Aturan (rules) yang dibuat:
• Jika daun menguning dan terdapat bercak hitam → Hama Kutu Daun
• Jika daun berlubang dan terdapat bercak hitam → Hama Ulat Daun
• Jika tanaman layu dan daun menguning → Hama Nematoda
• Jika daun berlubang dan tanaman layu → Hama Penggerek Batang

Mekanisme:

• Program mengecek apakah gejala input mengandung semua gejala dalam salah satu rule.
• Kalau cocok, kembalikan nama hama.
• Kalau tidak ada yang cocok, kembalikan None.
• Fungsi main()
Ini bagian untuk:
• Mencetak judul sistem.
• Menampilkan gejala apa saja yang tersedia.
• Meminta input dari user (dipisah koma).
• Memanggil inferensi() dengan gejala yang diberikan.
• Menampilkan hasil: jenis hama yang terdeteksi atau pesan tidak bisa menentukan hama.

Soal 2

1. Memilih Jurnal / Artikel yang Relevan
Cari artikel atau jurnal tentang penerapan AI (sistem cerdas).
Dalam tugas ini, yang dipilih adalah:

• Judul: Sistem Pakar Identifikasi Hama Tanaman Buah Naga.
• Sumber: Universitas Mulawarman.

2. Membuat Ringkasan Jurnal
Setelah memilih artikel, buat ringkasan yang berisi:
• Tujuan:
Menjelaskan apa tujuan penelitian/sistem tersebut.
(Misal: membantu petani mengidentifikasi hama buah naga.)
• Metode AI yang Digunakan:
Menjelaskan metode kecerdasan buatan yang dipakai.
(Misal: menggunakan Certainty Factor untuk menangani ketidakpastian.)
• Manfaat:
Menjelaskan keuntungan dari penggunaan sistem pakar itu bagi pengguna.
(Misal: membantu petani mengenali 7 jenis hama, memberi informasi, mengurangi ketergantungan pada pakar.)

3. Membuat Ide Pengembangan Lanjutan
Setelah memahami jurnal, buat pengembangan ide lebih lanjut.
Ini bertujuan agar sistem pakar bisa lebih canggih dan berguna.
Beberapa contoh ide yang ditulis:
• Mobile Apps:
• Membuat aplikasi Android/iOS supaya bisa dipakai petani di lapangan.
• Pengolahan Citra:
• Menambahkan fitur supaya sistem bisa mengenali hama lewat foto tanaman.
• Machine Learning:
• Membuat sistem yang belajar otomatis dari data baru yang dikumpulkan.

4. Menciptakan Ide Penerapan di Lingkungan Sekitar
Langkah ini adalah membayangkan penerapan serupa di daerah lain, supaya lebih aplikatif.
Contohnya:
• Di Bandung, buat sistem untuk:
• Tanaman Stroberi (hama jamur, kutu daun).
• Tanaman Sayuran (ulat grayak, penyakit fusarium).
• Tanaman Hias (serangan kutu putih, jamur daun).
