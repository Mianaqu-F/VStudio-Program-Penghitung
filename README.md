# Penghitung Biaya Pengiriman
## Deskripsi 
Program ini adalah skrip Python sederhana yang digunakan untuk menghitung biaya pengiriman berdasarkan berat paket, jarak pengiriman, jenis pengiriman, dan status keanggotaan (member atau non-member). Program ini juga menampilkan rincian perhitungan biaya secara terstruktur.

## Fitur
1. Input Nama dan NIM: Menampilkan nama dan NIM pengguna.
2. Hitung Biaya Pengiriman:
- Biaya dasar: Rp 10.000
- Tambahan biaya jika berat melebihi 5 kg: Rp 5.000
- Tambahan biaya jika jarak melebihi 10 km: Rp 8.000
- Tambahan biaya untuk pengiriman express: Rp 20.000
- Diskon 10% untuk member.
3. Penanganan Error: Menampilkan pesan error jika input tidak valid.

## Cara Menggunakan
1. Jalankan skrip Python:
```
python penghitung.py
```
2. Masukkan data yang diminta:
- Berat paket (kg)
- Jarak pengiriman (km)
- Jenis pengiriman (biasa/express)
- Status member (member/non-member)

3. Program akan menampilkan rincian biaya pengiriman secara terperinci.

## Contoh Output
```
===========================================
Nama: Michael Andrea Aquino
NIM: 312310703
===========================================
Masukkan berat paket (kg): 6
Masukkan jarak pengiriman (km): 15
Masukkan jenis pengiriman (biasa/express): express
Apakah Anda member? (member/non-member): member

Keterangan                 Biaya (Rp)
========================================
Biaya Dasar                10000
Biaya Berat > 5 kg          5000
Biaya Jarak > 10 km         8000
Biaya Pengiriman Express   20000
Diskon Member (10%)        -4300.0
========================================
Total Biaya Pengiriman     37700.00
```
## Penanganan Error
Jika input tidak valid, program akan menampilkan pesan berikut:
```
Input yang Anda masukkan tidak valid. Pastikan menggunakan angka untuk berat dan jarak.
```
## Teknologi
- Python 3.x
## Kontribusi
Pull request dipersilakan. Untuk perubahan besar, harap buka issue terlebih dahulu untuk mendiskusikan apa yang ingin Anda ubah.

---
[Instagram](https://www.instagram.com/mianaqu/)

## Penulis
- Nama: **[Michael Andrea Aquino]**
- NIM: **[312310703]**

