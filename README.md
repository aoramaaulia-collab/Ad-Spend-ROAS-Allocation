# Belanja yang Hampir Sama Besar Membeli Hasil 2,4 Kali Berbeda

Analisis efisiensi belanja iklan (ROAS) di tiga platform, Facebook, TikTok, dan Instagram, untuk membagi anggaran kampanye Lebaran Rp 200 juta. Lingkupnya 975 kampanye bersih dari 1.012 baris mentah, dengan posisi data 1 April 2026.

**[Baca portofolio lengkapnya](https://aoramaaulia-collab.github.io/NAMA-REPO/)**

> Dataset dirancang meniru pola belanja iklan digital. Ini bukan data perusahaan sungguhan, dan tidak disajikan sebagai pengalaman kerja di perusahaan mana pun.

## Pertanyaan dan jawabannya

Manajer pemasaran klien meminta satu hal: platform mana yang paling efisien. Jawabannya Facebook, dengan ROAS 3,65, lawan TikTok 2,58 dan Instagram 1,54. Tetapi kolom jenis kampanye, yang tidak disebut dalam permintaan, memisahkan hasil 4,0 kali, sekitar 1,7 kali lebih tajam daripada platform. Selisih antar-platform ternyata bukan soal iklan yang kurang diklik, melainkan nilai tiap pembelian.

| Platform | ROAS | Porsi berjalan | Usulan |
|---|---|---|---|
| Facebook | 3,65 | 31,5% | Rp 84 juta (42%) |
| TikTok | 2,58 | 37,0% | Rp 68 juta (34%) |
| Instagram | 1,54 | 31,5% | Rp 48 juta (24%) |

Pembagiannya sengaja tidak sebanding lurus dengan ROAS. Pembagian sebanding akan memberi Facebook 47,0%, padahal titik jenuhnya tidak tercatat di data.

## Temuan utama

1. **Data yang lengkap belum tentu benar.** Berkas ini tidak punya satu pun sel kosong, tetapi 37 dari 1.012 baris mustahil secara logika bisnis.
2. **Instagram menyerap belanja sebesar Facebook, tetapi tiap rupiahnya menghasilkan kurang dari separuh.** Urutan ini sama di 64 dari 64 kombinasi pembersihan.
3. **Jenis kampanye memisahkan lebih tajam daripada platform**, dan keunggulan Facebook tetap bertahan setelah jenis kampanye disamakan.
4. **Selisih Facebook dan Instagram sebagian besar datang dari nilai tiap pembelian.** Faktor itu menyumbang 86% selisih ROAS.
5. **Seluruh baris bermasalah berasal dari satu rentang ID**, CMP-0971 sampai CMP-1000, jadi sumbernya satu kiriman data.

## Isi repositori

| Berkas | Isi |
|---|---|
| `index.html` | Portofolio lengkap: temuan, empat gambar dengan cara membacanya, tujuh rekomendasi beserta alasannya, dan batas analisis |
| [Workbook analisis](https://docs.google.com/spreadsheets/d/1EphG44ue-JMlh1FTlysmtqbrnUZVzPB1XsyCvxv4QOE/edit?usp=sharing) | Sepuluh lembar dengan seluruh rumus terbuka: data mentah, pembersihan, ringkasan, tabel silang, tren, rekomendasi, dan tujuh gerbang validasi |
| [Memo keputusan](https://docs.google.com/document/d/1qYVfpW4vTL67juZlftEPW93j8HJxQFItmEge57pDE84/edit?usp=sharing) | Satu halaman untuk manajer: rekomendasi, dasar, batas, dan syarat pembatal |
| [Catatan keputusan](https://docs.google.com/document/d/1mNocLxlSkZnZLWH22pw6ZJ8LmYaNc5mvUBfEAZvEu4g/edit?usp=sharing) | Setiap aturan, pilihan yang ditolak, uji, dan alasannya, untuk pemeriksa |

## Cara memeriksa ulang

Buka [workbook](https://docs.google.com/spreadsheets/d/1EphG44ue-JMlh1FTlysmtqbrnUZVzPB1XsyCvxv4QOE/edit?usp=sharing) di Google Sheets, lalu lihat lembar **Validasi**. Tujuh gerbang menghitung ulang angka kunci: jumlah baris tiap tahap (1.012, 37, 975), pemeriksaan bernilai nol, ROAS per platform dan per jenis kampanye, tabel silang, dan cakupan periode. Empat belas baris berstatus LOLOS dan satu DICATAT apa adanya.

## Alat

Spreadsheet (Google Sheets). Seluruh angka dihitung lewat rumus, tidak ada yang diketik dari gambar.

## Batas

ROAS membandingkan pendapatan dengan belanja iklan saja, jadi ini bukan ukuran keuntungan. Seluruh angka mengukur hasil pada tingkat belanja yang sudah terjadi, tidak ada data atribusi, dan data tidak menandai kampanye mana yang termasuk musim Lebaran.

---

Dibuat oleh **Aulia Aorama**, September 2026. Hubungi lewat [aoramaaulia@gmail.com](mailto:aoramaaulia@gmail.com) atau lihat proyek lain di [GitHub](https://github.com/aoramaaulia-collab).
