# RakitWeb - Tulis Skripmu, Lihat Webmu. Buat Laman Sesuka Hatimu!

> Made by | Rizky Daffy [About Me](https://rizkydaffy.github.io/)

---
## Apa sih itu RakitWeb?

RakitWeb adalah proyek revolusioner yang memberdayakan Anda untuk mengkustomisasi dan memublikasikan konten web langsung dari terminal atau skrip. Lupakan antarmuka yang rumit atau dashboard yang membingungkan. Dengan RakitWeb, Anda punya kontrol penuh untuk membangun halaman web personal dengan cara yang cepat, efisien, dan menyenangkan.

---

## Fitur Dari RakitWeb
  1. <b>Kontrol Penuh via Skrip/Terminal</b>: Unggah file HTML, CSS, JavaScript, atau aset lainnya langsung dari command line Anda.
  2. <b>Publikasi Instan</b>: Setelah diunggah, file Anda akan langsung tersedia di URL yang mudah diingat, misalnya /nama_file_anda.html.
  3. <b>Fleksibilitas Tanpa Batas</b>: Mulai dari halaman statis sederhana hingga tata letak yang kompleks, semua ada di tangan Anda (<b>asal jangan di taruh page judol ajg</b>).
  4. Pengalaman Defacing: Dirancang untuk semua orang (terkecuali judi) untuk bisa berkreasi dengan kreativitas tanpa batas

---

### Bagaimana RakitWeb Bekerja?
RakitWeb terdiri dari dua komponen utama:
  1. Aplikasi Web (RakitWeb Server): Aplikasi ini akan menerima file yang Anda kirimkan. Setelah diterima, file tersebut akan langsung dipublikasikan dan bisa diakses melalui URL [<a href="rakitweb.my.id">rakitweb.my.id</a>].
  2. Skrip Klien (RWCLI/Script): Ini adalah alat yang Anda gunakan di terminal atau skrip Anda untuk mengirim file ke server RakitWeb. Cukup tentukan file mana yang ingin Anda unggah, dan RakitWeb akan mengurus sisanya. butuh bantuan? [<a href="rakitweb.my.id/tutorial">Baca Instruksi nya disini</a>]
Contoh Alur Kerja:
Seorang developer menjalankan rakitweb upload rizkyganteng.html dari terminalnya. RakitWeb CLI akan mengirimkan rizkyganteng.html ke RakitWeb Server. Dalam hitungan detik, file tersebut akan tersedia untuk publik di https://rakitweb.my.id/rizkyganteng.html.
---

### Panduan Memulai Cepat

Bagian ini akan memandu Anda melalui langkah-langkah esensial untuk mulai menggunakan RakitWeb atau mengirim file kamu sendiri.
Prasyarat<br>
  1. [<b>Jangan ngirim laman berbau vulgar atau laman judol</b>]
  2. [Waras, iya tau bebas tapi ya ga upload shell juga dong ajg]
```bash
# Ambil repo dari RWCLI
git clone https://github.com/rizkydaffy/rwcli.git
cd rwcli
# Instalasi dependensi server
npm install # atau pip install -r requirements.txt, dsb.
# Jalanin script (perhatikan: file .html nya harus berada di folder yg sama dengan script nya)

Upload: python rwcli whenyh.html <= berada di folder yg sama
List: python rwcli list <= menampilkan semua halaman yg terkirim
[PERHATIAN: Konten yang Anda unggah akan disimpan di server kami. Mengunggah file dengan nama yang sama akan menimpa versi sebelumnya]

```
---

### Keamanan

Keamanan adalah prioritas utama kami. RakitWeb dirancang dengan mempertimbangkan praktik keamanan terbaik. Informasi lebih lanjut tentang arsitektur keamanan dan pedoman pelaporan kerentanan dapat ditemukan di SECURITY.md

---

### Lisensi

Proyek ini dilisensikan di bawah [MIT LICENSE]. Lihat berkas LICENSE untuk detail lengkap.

---
### ⚠️ | STOP JUDOL 

Sebagai bagian dari komitmen terhadap lingkungan yang positif dan konstruktif, kami mengajak seluruh pihak untuk secara tegas menggaungkan semangat <b style="color: red">#ANTIJUDI</b>. Ini bukan hanya tentang mematuhi regulasi, tetapi juga tentang membangun fondasi masyarakat yang kuat, cerdas, dan produktif, bebas dari dampak negatif praktik-praktik yang tidak bertanggung jawab.

---
### Dukungan

Untuk pertanyaan, laporan bug, atau feedback, silakan buka issue di repositori GitHub ini atau hubungi saya di facebook :)
```
GitHub: @rizkydaffy
Website: rizkydaffy.github.io
Facebook: RizkyDaffy
```
