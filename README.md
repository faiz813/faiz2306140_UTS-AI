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
