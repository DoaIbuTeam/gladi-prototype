# Gladi

**Lakukan gladi resik sebelum hari-H karier!**

Gladi adalah _website_ untuk latihan masuk ke satu perusahaan tujuan. _User_ dapat memilih perusahaan dan posisi yang diincar, cek di mana dia masih kurang, _mock_-_up_ wawancara dan situasi kerja, serta ngobrol langsung dengan alumni yang sudah bekerja di sana. Dibuat untuk mahasiswa tingkat akhir, _fresh graduate_, dan pencari kerja pertama.

🔗 **_Link prototype_** `https://doaibuteam.github.io/gladi-prototype/`

---
## Latar Belakang

Banyak lulusan sudah berusaha melamar, tetapi tersisih di tahap seleksi atau keluar tidak lama setelah diterima. Hal ini dapat dilatar belakangi oleh tiga sebab:

1. **Kemampuan dan pengalaman belum cukup**, dan tidak ada tempat latihan yang mirip kondisi kerja sungguhan.
2. **Jawaban terlalu umum**, tidak disesuaikan dengan karakter perusahaan, dan bahasa tubuh tidak pernah dilatih.
3. **Budaya kerja baru kelihatan setelah masuk**, karena informasinya cuma dari materi employer branding.

Tiga hal ini nyambung satu sama lain, jadi Gladi dibuat sebagai satu alur latihan, bukan fitur yang berdiri sendiri.

## Tiga fitur utama

**Gavi Konsul**
Kamu isi perusahaan dan posisi target, lalu unggah CV. Gavi membandingkannya dengan kebutuhan posisi itu dan menyusun peta kesenjangan (keterampilan, pengalaman, pengetahuan tentang perusahaan) plus rencana 30 hari. Kamu juga bisa ngobrol bebas soal kerjaan dan karier.

**Gavi Role Play**
Ceritakan masalah atau situasi yang mau dilatih. Gavi memerankan lawan bicara yang relevan, sesuai gaya komunikasi perusahaan tujuan. Setelah sesi ada umpan balik soal isi jawaban, gaya bicara, dan isyarat nonverbal.

**Mentoring Alumni**
Sesi 60 menit, satu mentor satu peserta, dengan alumni dari perusahaan yang kamu tuju. Mentor membahas ritme kerja sehari-hari, 90 hari pertama, dan hal-hal yang tidak tertulis di situs karier. Mentor menerima ringkasan hasil simulasimu sebelum sesi.

Semua berujung di **Readiness Report**: rangkuman posisimu terhadap perusahaan tujuan, perkembangan dari sesi ke sesi, dan langkah berikutnya.

## Alur pakai

1. Daftar, pilih perusahaan dan posisi target, unggah CV (portofolio opsional)
2. Gavi Konsul membuat peta kesenjangan dan rencana 30 hari
3. Latihan di Gavi Role Play dan baca umpan baliknya
4. Cocokkan dan jadwalkan mentor
5. Sesi mentoring dan bahas hasil simulasi
6. Baca Readiness Report dan tentukan tindak lanjut

## Paket

| Paket | Isi | Harga |
|---|---|---|
| Gladi Basic | Gavi Konsul lengkap tanpa limit, 3 sesi Role Play, recognition, Readiness Report (30 hari) | Rp49.000 |
| Gladi Plus | Semua isi Basic, career framework, 4 sesi mentoring 1-on-1 (30 hari) | Rp299.000 |
| Gladi Intensif | Role Play tanpa batas, 7 sesi mentoring, feedback berkelanjutan dari mentor di luar sesi, Readiness Report akhir (30 hari) | Rp499.000 |

Versi dasar Gavi Konsul gratis sebagai pintu masuk. Teman yang memakai kode referral mendapat diskon 10% di ketiga paket.

## Status prototipe

Yang sudah ada di demo ini:

- Halaman awal, login/daftar dengan persetujuan Syarat & Ketentuan dan Kebijakan Privasi
- Halaman Home: profil target, alur 6 langkah, jadwal mentoring, langganan, referral
- Gavi Konsul (ngobrol bebas dan peta kesenjangan), Gavi Role Play, alur booking mentoring, ruang sesi, dan Readiness Report
- Batas fitur per paket (gratis, terbatas, berbayar)

Yang masih simulasi atau belum ada:

- Login, pembayaran, kode referral, dan email konfirmasi hanya tampilan. Tidak ada akun atau transaksi sungguhan, dan data hilang kalau halaman di-refresh.
- Data mentor adalah contoh, bukan alumni asli.
- Di versi GitHub Pages, jawaban Role Play dan Konsul memakai jawaban cadangan sederhana. AI yang menyesuaikan dengan masalah pengguna butuh server terpisah.
- Analisis nonverbal lewat kamera belum aktif.
- Readiness Report masih berbentuk demo, dihitung dari aktivitas di sesi yang sedang berjalan.

## Privasi dan etika

Rencananya Gladi mengikuti UU No. 27 Tahun 2022 tentang Pelindungan Data Pribadi: persetujuan eksplisit sebelum rekaman suara atau video diproses, data bisa dihapus kapan saja, dan tidak dijual. Persona perusahaan disusun dari informasi publik dan wawancara terstandar dengan alumni. Mentor dilarang membocorkan soal atau informasi rahasia perusahaan.

Teks Syarat & Ketentuan dan Kebijakan Privasi di prototipe ini masih ringkasan dan belum ditinjau ahli hukum.

## Menjalankan sendiri

Tidak ada instalasi. Website ini satu file, `index.html`. Download, lalu buka di browser. Untuk menayangkan lewat GitHub Pages: **Settings → Pages → Deploy from a branch → main / (root)**.

## Tim

- Izzah Zahra Answar, Universitas Indonesia
- Salma Muthia, Universitas Gadjah Mada
- Suci Ramadhani, Universitas Gadjah Mada

Edubiz Competition 2026
