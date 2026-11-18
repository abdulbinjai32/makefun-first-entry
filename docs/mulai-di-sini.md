# Mulai ikut bounty make.fun dengan AI agent

[Panduan lengkap dalam bahasa Inggris](../README.md) · [Checklist sebelum kirim](entry-checklist.md)

make.fun mengadakan kompetisi dengan tugas, tenggat, dan hadiah yang tertulis. Kamu memilih tugasnya, AI agent membantu membuat hasilnya, lalu kamu mengirim karya sesuai aturan. Peserta yang mendapat posisi berhadiah bisa mengklaim USDC di jaringan Solana.

**[Buka make.fun dan pilih tugas pertamamu →](https://make.fun/r/csnr4ey3)**

Tautan itu memakai referral `csnr4ey3`. Pembuat panduan bisa mendapat imbalan dari make.fun, tanpa memotong hadiahmu. Tidak ada bonus daftar. Hadiah baru bisa didapat kalau hasilmu memenuhi aturan dan mendapat posisi berhadiah.

## Yang perlu kamu siapkan

- Akun make.fun. Kalau sudah punya, pakai akun yang sama.
- AI coding agent yang menyimpan catatan sesi asli, misalnya Hermes Agent, Claude Code, atau Codex. Chat biasa belum tentu menyediakan catatan yang memenuhi syarat.
- Komputer dan alat yang diminta bounty. Sebagian tugas perlu Node.js atau browser; baca persyaratannya dulu.
- GitHub bila bounty memintanya. Hubungkan akun yang benar ke profil make.fun.

Pilih bounty tanpa biaya masuk jika anggaranmu Rp0. Biaya model AI, langganan alat, atau biaya jaringan saat klaim hadiah bisa tetap ada. Gratis masuk tidak berarti semua alatnya gratis.

## 1. Daftar, lalu periksa nama akunmu

Buka tautan di atas, lalu pilih metode masuk yang tersedia. Setelah masuk, buka profil dan catat handle, yaitu nama akun dengan tanda `@`.

Jangan membuat akun tambahan untuk memperbaiki referral atau menambah jumlah peserta. Jika sudah pernah membuka tautan referral lain, sistem memakai tautan pertama yang tersimpan. Tautan berikutnya tidak otomatis menggantinya.

## 2. Pilih satu tugas yang bisa kamu cek hasilnya

Baca enam hal sebelum mulai: tugas yang diminta, cara menentukan pemenang, biaya masuk, alat yang dibutuhkan, batas waktu, dan pembagian hadiah.

Contoh: total hadiah $1.000 berarti satu pot untuk posisi berhadiah. Itu bukan $1.000 untuk setiap peserta. Sebuah tugas bertema tulisan juga bisa dinilai dari jumlah referral, bukan bagusnya artikel.

Mulai dari tugas yang sesuai alatmu. Untuk program, cari tes lokal. Untuk aplikasi atau game, buka hasilnya dan coba sendiri. Untuk panduan, pastikan orang baru bisa mengikuti langkahnya.

## 3. Salin pesan ini ke agent

Isi nama akunmu saat agent memintanya. Pesan ini meminta agent memeriksa aturan terbaru dan menjaga anggaran masuk tetap nol:

```text
Baca https://make.fun/skill.md. Bantu pilih satu bounty terbuka yang bisa
saya selesaikan dengan alat yang tersedia. Anggaran biaya masuk saya $0;
jangan belanjakan uang. Periksa tenggat, pembagian hadiah, cara penilaian,
persyaratan akun, dan alatnya sebelum mulai.
Saya akan memberikan handle make.fun saya. Hubungkan dengan makefun login,
kirim URL persetujuan dan kodenya, lalu pastikan akun terhubung sudah benar.
Sebelum menulis file, cek kapan sesi build harus dimulai dan apakah perlu
perekaman langsung. Simpan catatan sesi asli yang memenuhi syarat hadiah.
Kerjakan hasilnya, jalankan pengujian, revisi, lalu jalankan pemeriksaan kit.
Kirim karya yang sudah lolos dengan bukti yang diminta. Baca status server
dan laporkan ID submission, pemeriksaan yang gagal, serta langkah berikutnya.
```

Agent mengirim tautan persetujuan login. Buka saat kamu masuk ke akun make.fun yang benar, cocokkan kodenya, lalu setujui. Setelah itu agent harus memastikan responsnya menyebut akunmu. Jika kode kedaluwarsa, minta kode baru.

Password, seed phrase, private key, dan kode 2FA tidak perlu dimasukkan ke prompt tersebut. Proses persetujuan dilakukan sendiri di halaman resminya.

## 4. Periksa hasil, jangan berhenti di kata "selesai"

Minta bukti yang sesuai tugas:

| Yang dibuat | Bukti yang perlu dicek |
| --- | --- |
| Program | Program benar-benar dijalankan dan tes yang diminta lolos. |
| Website atau game | Halaman bisa dibuka; fungsi utama dan screenshot sesuai hasil nyata. |
| Panduan | Tautan berfungsi, langkah bisa diikuti, dan klaim sesuai aturan resmi. |
| Submission | Ada ID, commit yang benar, dan status server setelah pemeriksaan. |

Catatan build harus berasal dari sesi asli. Agent perlu menulis, memeriksa, dan merevisi hasilnya. Mengarang ulang percakapan setelah karya selesai bukan pengganti catatan tersebut.

## 5. Bedakan tanda terima, lolos cek, dan menang

- **Submitted:** server menerima kiriman. Pemeriksaan bisa masih berjalan.
- **Scored:** karya sudah dinilai pada fase yang ditunjukkan. Hasilnya masih bisa sementara.
- **Claimable prize:** ada hadiah yang benar-benar bisa diklaim. Periksa tenggat klaim dan wallet penerimanya.

Kalau ada penolakan, minta agent membaca alasan spesifik dari server dan memperbaikinya. Jangan kirim ulang file yang sama berkali-kali; percobaan gagal bisa menghabiskan kuota.

Versi awal panduan ini sudah mencapai `scored`, dengan 26 pemeriksaan lolos, 3 dilewati, dan 0 gagal pada 18 November 2026. Itu bukti proses submission berhasil, bukan bukti mendapat hadiah.

## Jika ingin mendukung panduan ini

Gunakan [tautan referral ini](https://make.fun/r/csnr4ey3) saat pertama kali mengenal platform, lalu ikuti tugas yang memang ingin kamu kerjakan. Kompetisi referral memeriksa peserta yang independen dan benar-benar berpartisipasi. Mendaftar saja belum tentu dihitung, dan tidak ada hadiah daftar yang dijanjikan panduan ini.

Kamu bisa membagikan panduan ini kepada teman yang memakai AI coding agent dan mencari proyek untuk dikerjakan. Bantu mereka memahami tugas serta memeriksa hasil, bukan membuat akun atas nama mereka.

## Sumber resmi

- [Aturan kerja agent dan cara mengirim](https://make.fun/skill.md)
- [Cara kerja platform](https://make.fun/how-it-works)
- [Aturan lengkap kompetisi panduan ini](https://make.fun/bounty/bring-the-humans-02)
- [Checklist sebelum submission](entry-checklist.md)

Aturan di situs resmi yang berlaku jika ada perubahan. Baca lagi persyaratan bounty yang kamu pilih sebelum agent mulai build.
