# Laporan Tugas Sistem Pakar  
**Nama:** Zaki Muhamad  
**NIM:** 2306094  

## Judul  
Implementasi Metode Forward Chaining dan Backward Chaining pada Sistem Pakar  

## Deskripsi Repositori  
Repositori ini berisi implementasi dari dua metode inferensi dalam sistem pakar, yaitu **Forward Chaining** dan **Backward Chaining**. Kedua metode digunakan untuk pengambilan keputusan berdasarkan fakta dan aturan yang ada.

### Bahasa Pemrograman  
- Python

### Struktur Utama  
Repositori ini terdiri dari dua file utama:
- `ForwardChaining.py`
- `BackwardChaining.py`

## Penjelasan Metode

### 1. Forward Chaining (Penelusuran Maju)
Forward Chaining merupakan metode inferensi yang dimulai dari fakta-fakta awal untuk mencari kesimpulan.

#### Cara Kerja:
1. Sistem mengevaluasi fakta-fakta yang tersedia.
2. Aturan-aturan yang memiliki premis yang sesuai akan dijalankan.
3. Jika kesimpulan dari aturan terpenuhi, maka ditambahkan ke dalam basis fakta.
4. Proses ini berulang hingga kesimpulan akhir ditemukan atau tidak ada lagi aturan yang bisa diterapkan.

#### Contoh Output:
Program akan menampilkan langkah-langkah penelusuran dan memberikan kesimpulan berdasarkan fakta yang diberikan.

### 2. Backward Chaining (Penelusuran Mundur)
Backward Chaining merupakan metode inferensi yang dimulai dari hipotesis (tujuan) dan mencoba memverifikasi kebenarannya melalui aturan dan fakta yang ada.

#### Cara Kerja:
1. Sistem memulai dari kesimpulan yang ingin dibuktikan.
2. Sistem mencari aturan yang dapat mendukung kesimpulan tersebut.
3. Premis dari aturan tersebut akan diperiksa apakah terdapat dalam basis fakta.
4. Jika tidak, sistem akan mundur untuk membuktikan premis tersebut terlebih dahulu.
5. Proses ini berulang hingga kesimpulan dapat dibuktikan atau terbukti salah.

#### Contoh Output:
Program akan menelusuri dari kesimpulan ke fakta-fakta dan memberikan hasil apakah kesimpulan tersebut valid berdasarkan fakta.

## Kelebihan dan Kekurangan
| Metode             | Kelebihan                                           | Kekurangan                                         |
|--------------------|----------------------------------------------------|---------------------------------------------------|
| Forward Chaining   | Baik untuk kasus dengan banyak data awal           | Tidak efisien jika banyak aturan yang tidak relevan |
| Backward Chaining  | Efisien untuk membuktikan satu hipotesis spesifik | Kurang efektif untuk menemukan semua kemungkinan   |

## Kesimpulan
Repositori ini merupakan contoh implementasi sederhana namun efektif dari dua metode inferensi dalam sistem pakar. Dengan memahami cara kerja Forward dan Backward Chaining, kita dapat membangun sistem pakar yang lebih kompleks dan adaptif terhadap berbagai kasus.

## Referensi
- [Link Repositori GitHub](https://github.com/mrzack18/Forward-Chaining_-_Backward-Chaining)
