---
title: Manual Penggunaan Tani Flow
layout: post
image: assets/images/title/taniflow.png
description: Panduan penggunaan produk sistem irigasi otomatis Tani Flow
date: 02-09-2025 20:40:00
categories: [Elektronika, Tani-Flow, Sistem-Kontrol]
tags: [Dokumentasi, Manual-Penggunaan]
---

# Manual Penggunaan TaniFlow
## Sistem Irigasi Otomatis

![TaniFLow-Product](/assets/images/flyer.png){: width="900" height="589" .w-50 .center}

---

## ℹ️ INFORMASI PRODUK

| Item            | Detail                                   |
| --------------- | ---------------------------------------- |
| **Nama Produk** | TANIFLOW - Sistem Irigasi Otomatis       |
| **Interface**   | Web Control Panel                        |
| **Versi Manual**| 2.0                                      |
| **Tanggal**     | September 2025                           |
| **Akses**       | `192.168.4.1` *(Hotspot Mode)*           |
| **Versi**       | 1.2                                      |

---

## **1. Pengenalan Singkat**

TaniFlow adalah sistem irigasi otomatis yang dirancang untuk memudahkan pengelolaan irigasi tanaman secara terjadwal. Sistem ini dapat:

- Mengatur jadwal irigasi hingga 15 slot waktu berbeda
- Kontrol durasi irigasi per jadwal (1-60 menit). **Maksimal 60 Menit**
- Pengaturan hari aktif untuk setiap jadwal
- Kontrol manual kapan saja (Limit waktu durasi aktif selama 1 menit.)
- Monitoring real-time status sistem
- Antarmuka web yang mudah digunakan

---

## **2. Spesifikasi Teknis**

![TaniFLow-Product](/assets/images/product.png)
_Produk TaniFlow_

### Hardware
- **Kode Produksi**
   -  Kode ini digunakan untuk nama hotspot `TF-MGT1902`
- **Indikator**
   - Power: Sebagai penanda bahwa sistem siap digunakan `Led Merah`
   - Active: Sebagai penanda bahwa sistem irigasi sudah aktif `Led Kuning`
   - Connect: Sebagai penanda bahwa sistem sedang berkoneksi dengan HP atau Laptop `Led Biru`
- **Catu Daya**: 220V AC
- **Konektor Aktuator Kran** `sebelah kiri product`
   - Berfungsi sebagai koneksi ke aktuator kran

### Software
- **WiFi Mode**: Access Point (AP) 
- **Wifi Default**: TF-MGT1902 `nama hostpsot sesuai kode produksi yang tertera pada kemasan`
- **Password WiFi Default**: 12345678
- **IP Address**: 192.168.4.1

### Fitur Kontrol
- **Maksimal Jadwal**: 15 jadwal aktif
- **Durasi Irigasi**: 1-60 menit per jadwal `maksimal 60 menit, lebih dari itu tidak disarankan, karena memperpendek umur pakai aktuator kran`
- **Pengaturan Hari**: Tersedia pilihan hari aktif `Senin-Minggu` 
   - Terdiri dari singkatan pada sistem:
      - Senin= Sn
      - Selasa= Sl
      - Rabu= Rb
      - Kamis= Km
      - Jumat= Jm
      - Sabtu= Sb
      - Minggu= Mg



---

## **3. Persiapan Awal**

### Langkah 1: Persiapan Perangkat
1. Pastikan aktuator kran terpasang dengan benar pada pipa air
2. Pastikan alat kontrol TaniFlow sudah terhubung dengan **aktuator kran** 
3. Jauhkan alat kontrol TaniFlow dengan air secara langsung

### Langkah 2: Nyalakan Perangkat
1. Colokkan kabel AC ke stopkontak listrik
2. Lampu indikator power akan menyala dan anda akan mendengar 2x bunyi "beep" pendek yang menandakan sistem siap

---

## **4. Cara Mengakses Sistem**

### Melalui Smartphone/Tablet

1. **Buka Pengaturan WiFi** di perangkat Anda
2. **Cari jaringan WiFi** dengan nama: **TF-MGT1902** `sesuai kode produk pada kemasan`
3. **Hubungkan** dengan password: **12345678**
4. **Matikan** data seluler hp
4. **Buka browser** (Chrome, Firefox, Safari, dll)
5. **Ketik alamat**: `192.168.4.1` atau `http://192.168.4.1`
6. **Halaman TaniFlow** akan muncul otomatis

### Melalui Laptop/PC

1. **Klik icon WiFi** di taskbar
2. **Cari jaringan WiFi** dengan nama: **TF-MGT1902** `sesuai kode produk pada kemasan`
3. **Hubungkan** dengan password: **12345678**
4. **Buka browser** favorit Anda
5. **Ketik alamat**: `192.168.4.1` atau `http://192.168.4.1`
6. **Halaman TaniFlow** akan muncul otomatis

---

![UI Menu Waktu](/assets/images/menu-waktu.jpg)
_Menu Pengaturan Waktu Sistem_

## **5. Pengaturan Waktu Sistem**

Sebelum menggunakan jadwal otomatis, Anda **harus** mengatur waktu sistem terlebih dahulu.

### Cara Mengatur Waktu

1. **Buka Tab "Waktu"** di menu navigasi
2. Anda akan melihat form pengaturan waktu dengan isian:
   - **Tanggal**: Hari, Bulan, Tahun
   - **Waktu**: Jam, Menit, Detik

### Opsi Pengaturan

#### Opsi 1: Gunakan Waktu HP (Otomatis)
1. Klik tombol **"Ambil Waktu HP"**
2. Form akan terisi otomatis dengan waktu perangkat Anda
3. Klik tombol **"Atur Waktu Sistem"**
4. Tunggu notifikasi berhasil

#### Opsi 2: Input Manual
1. Isi manual setiap isian:
   - Hari: 1-31
   - Bulan: 1-12
   - Tahun: 2023-2099
   - Jam: 0-23 (format 24 jam)
   - Menit: 0-59
   - Detik: 0-59
2. Klik tombol **"Atur Waktu Sistem"**

### Verifikasi Waktu

Setelah pengaturan, cek **"Status Perangkat"** di bawah form untuk memastikan:
- Waktu sudah sesuai
- Tanggal sudah benar
- Hari sudah tepat

> **⚠️ Penting**: Waktu yang akurat sangat penting untuk jadwal berjalan dengan tepat!

---

![UI Menu Jadwal](/assets/images/menu-jadwal.jpg)
_Menu Pengaturan Jadwal_

## **6. Pengaturan Jadwal Irigasi**

TaniFlow mendukung hingga **15 jadwal** berbeda yang dapat dikonfigurasi secara praktis.

### Cara Mengatur Jadwal

1. **Buka Tab "Jadwal"** di menu navigasi
2. Anda akan melihat 15 kartu jadwal (Jadwal 1 - Jadwal 15)

### Konfigurasi Setiap Jadwal

Setiap jadwal memiliki pengaturan:

#### 1. Waktu Mulai
- **Jam**: 0-23 (format 24 jam)
- **Menit**: 0-59
- **Detik**: 0-59

Contoh: Untuk irigasi jam 6 pagi, set: `06:00:00`

#### 2. Durasi Irigasi
- **Range**: 1-60 menit
- **Input**: Masukkan angka durasi dalam menit

Contoh: Untuk irigasi 15 menit, masukkan: `15`

#### 3. Hari Aktif
Pilih hari-hari kapan jadwal ini akan berjalan:
- **Mg** = Minggu
- **Sn** = Senin
- **Sl** = Selasa
- **Rb** = Rabu
- **Km** = Kamis
- **Jm** = Jumat
- **Sb** = Sabtu

**Cara memilih**:
- Klik tombol hari untuk mengaktifkan (tombol akan berubah warna)
- Klik lagi untuk menonaktifkan
- Anda bisa memilih satu atau lebih hari

#### 4. Status Aktif/Non-aktif
- **Toggle Switch**: Geser untuk aktifkan/nonaktifkan jadwal
- Hijau = Aktif
- Abu-abu = Non-aktif

> Jadwal yang non-aktif tidak akan berjalan meskipun sudah waktunya

### Contoh Pengaturan Jadwal

**Contoh 1: Irigasi Pagi Setiap Hari**
- Waktu: `06:00:00`
- Durasi: `15` menit
- Hari: Semua hari dipilih (Mg, Sn, Sl, Rb, Km, Jm, Sb)
- Status: Aktif ✅

**Contoh 2: Irigasi Sore Hari Kerja**
- Waktu: `17:00:00`
- Durasi: `20` menit
- Hari: Senin sampai Jumat (Sn, Sl, Rb, Km, Jm)
- Status: Aktif ✅

**Contoh 3: Irigasi Tambahan Weekend**
- Waktu: `14:00:00`
- Durasi: `30` menit
- Hari: Sabtu dan Minggu (Sb, Mg)
- Status: Aktif ✅

### Menyimpan Jadwal

1. Setelah semua jadwal dikonfigurasi
2. Scroll ke bawah
3. Klik tombol **"Simpan Semua Jadwal"**
4. Tunggu notifikasi berhasil
5. Anda akan mendengar bunyi "beep" sebagai konfirmasi

> **💡 Tips**: Semua jadwal akan tersimpan di memori internal dan tidak akan hilang meskipun listrik mati!

---

![UI Menu Manual](/assets/images/menu-manual.jpg)
_Menu Kontrol Manual_

## **7. Kontrol Manual**

Anda dapat mengontrol irigasi secara manual kapan saja, terlepas dari jadwal yang sudah diatur.

### Cara Menggunakan Kontrol Manual

1. **Buka Tab "Kontrol"** di menu navigasi
2. Anda akan melihat:
   - Status irigasi saat ini (AKTIF/MATI)
   - Durasi tersisa (jika sedang aktif)
   - Tombol kontrol

### Tombol Kontrol

#### Nyalakan Irigasi
- Klik tombol **"Nyalakan Irigasi"** (biru)
- Irigasi akan berjalan selama **1 menit** (default)
- Status akan berubah menjadi "AKTIF"

#### Matikan Irigasi
- Klik tombol **"Matikan Irigasi"** (merah)
- Irigasi akan langsung berhenti
- Status akan berubah menjadi "MATI"

### Monitoring Real-time

Saat irigasi aktif, Anda dapat melihat:
- **Status**: Menampilkan "Status Irigasi: AKTIF" dengan warna hijau
- **Durasi Tersisa**: Countdown waktu tersisa dalam format "Xm Ys"

Contoh: `Durasi tersisa: 0m 45s` artinya masih ada 45 detik lagi

### Perilaku Kontrol Manual

> **⚠️ Perhatian**: 
> - Kontrol manual akan **mengesampingkan jadwal otomatis** yang sedang berjalan
> - Jika Anda menyalakan manual, lalu ada jadwal otomatis yang waktunya tiba, jadwal otomatis **tidak akan** berjalan hingga kontrol manual selesai
> - Setelah kontrol manual selesai, sistem akan kembali mengikuti jadwal otomatis

---

![UI Menu Status Sistem](/assets/images/menu-status.jpg)
_Menu Status Sistem_

## **8. Monitoring Status Sistem**

Menu Status membantu Anda memantau kondisi sistem secara keseluruhan.

### Cara Mengakses

1. **Buka Tab "Status"** di menu navigasi
2. Anda akan melihat beberapa informasi penting

### Informasi Status Sistem

#### 1. Status Irigasi
- **AKTIF**: Irigasi sedang berjalan (warna hijau)
- **MATI**: Irigasi tidak berjalan (warna abu-abu)

#### 2. Waktu Terakhir Update
Menampilkan waktu terakhir sistem mengirim data ke antarmuka web

#### 3. Perangkat Terhubung
Menampilkan jumlah perangkat (smartphone/laptop) yang terhubung ke WiFi TaniFlow

### Daftar Jadwal

Di bagian bawah menu Status, terdapat **Daftar Jadwal** yang menampilkan:

#### Untuk Setiap Jadwal:
- **Waktu**: Kapan irigasi akan dimulai
- **Durasi**: Berapa lama irigasi akan berjalan
- **Hari**: Hari-hari apa saja jadwal ini aktif
- **Status**: AKTIF/NON-AKTIF
- **Trigger Hari Ini**: SUDAH/BELUM
  - SUDAH: Jadwal ini sudah dijalankan hari ini
  - BELUM: Jadwal ini belum dijalankan hari ini

### Status Koneksi (Header)

Di bagian atas halaman (semua tab), terdapat indikator koneksi:
- **Lingkaran Hijau + "TERHUBUNG"**: Sistem aktif dan perangkat terhubung
- **Lingkaran Merah + "TIDAK TERHUBUNG"**: Tidak ada perangkat terhubung

### Auto-refresh

Status sistem akan **otomatis diperbarui** setiap 1 detik untuk menampilkan informasi terkini.

---

## **9. Troubleshooting**

### Masalah Umum dan Solusi

#### 1. Tidak Bisa Terhubung ke WiFi TaniFlow

**Gejala**: SSID TF-MGT1902 tidak muncul di daftar WiFi

**Solusi**:
- Pastikan alat sudah menyala (cek LED indikator)
- Restart perangkat TaniFlow (cabut-pasang adaptor)
- Tunggu 10-20 detik sampai sistem booting
- Coba scan ulang WiFi di perangkat Anda
- Pastikan Anda berada dalam jangkauan WiFi (maksimal 10-15 meter)

#### 2. Halaman Web Tidak Muncul

**Gejala**: Sudah terhubung WiFi tapi halaman tidak terbuka

**Solusi**:
- Pastikan sudah mengetik alamat yang benar: `192.168.4.1`
- Coba tambahkan `http://` di depan: `http://192.168.4.1`
- Clear cache browser
- Coba browser lain
- Restart smartphone/laptop Anda
- Disconnect dan connect ulang WiFi

#### 3. Waktu Tidak Akurat

**Gejala**: Waktu sistem tidak sesuai dengan waktu sebenarnya

**Solusi**:
- Buka tab "Waktu"
- Klik "Ambil Waktu HP"
- Klik "Atur Waktu Sistem"
- Jika masalah berlanjut, coba input manual
- Periksa baterai backup RTC (mungkin perlu diganti)

#### 4. Jadwal Tidak Berjalan

**Gejala**: Sudah waktunya tapi irigasi tidak jalan

**Cek hal berikut**:
1. Apakah waktu sistem sudah benar?
2. Apakah jadwal sudah dalam status AKTIF? (toggle switch hijau)
3. Apakah hari ini termasuk dalam hari aktif jadwal tersebut?
4. Apakah jadwal sudah "Trigger Hari Ini: SUDAH"? (setiap jadwal hanya jalan 1x per hari)
5. Cek tab "Status" untuk melihat detail jadwal

#### 5. Irigasi Tidak Berhenti

**Gejala**: Irigasi terus berjalan melewati durasi yang ditentukan

**Solusi**:
- Buka tab "Kontrol"
- Klik tombol "Matikan Irigasi"
- Jika masih tidak berhenti, restart perangkat TaniFlow
- Cek koneksi solenoid valve

#### 6. Solenoid Tidak Berfungsi

**Gejala**: Sistem menunjukkan AKTIF tapi air tidak mengalir

**Cek**:
- Apakah solenoid valve terpasang dengan benar?
- Apakah ada tekanan air?
- Apakah kabel solenoid terhubung ke pin yang benar (D7)?
- Coba kontrol manual untuk tes
- Cek power supply 12V

#### 7. LED WiFi Tidak Berkedip

**Gejala**: LED tidak berkedip meskipun sudah terhubung

**Info**: 
- LED akan berkedip (2 detik nyala, 1 detik mati) hanya jika ada perangkat yang terhubung
- Jika tidak ada yang terhubung, LED akan mati (normal)
- Jika masalah berlanjut, cek koneksi LED ke pin D5

#### 8. Buzzer Tidak Bunyi

**Gejala**: Tidak ada bunyi beep saat startup atau saat menyimpan

**Info**:
- Ini bukan masalah kritis, sistem tetap berfungsi normal
- Jika perlu, cek koneksi buzzer ke pin D6

---

## **10. Perawatan dan Tips**

### Perawatan Rutin

#### Mingguan
1. **Cek Status Sistem**
   - Buka tab "Status" untuk memastikan semua berjalan normal
   - Verifikasi jadwal yang sudah dijalankan

2. **Uji Kontrol Manual**
   - Test nyalakan dan matikan manual untuk memastikan responsif

#### Bulanan
1. **Cek Waktu Sistem**
   - Bandingkan dengan waktu sebenarnya
   - Atur ulang jika ada perbedaan signifikan

2. **Bersihkan Perangkat**
   - Lap dengan kain lembut untuk membersihkan debu
   - Jangan gunakan air untuk membersihkan

3. **Cek Koneksi Fisik**
   - Pastikan semua kabel terhubung dengan baik
   - Cek kondisi solenoid valve

#### 6 Bulan Sekali

- **Kalibrasi Jadwal**
   - Review dan sesuaikan jadwal dengan kebutuhan tanaman


### Tips Penggunaan Optimal

#### 💡 Efisiensi Irigasi
- **Pagi Hari**: Set jadwal pagi (05:00-07:00) untuk efisiensi air
- **Malam Hari**: Alternatif baik untuk menghindari penguapan (18:00-20:00)
- **Hindari Siang**: Irigasi siang hari (11:00-15:00) kurang efisien karena penguapan tinggi

#### 💡 Durasi Irigasi
- **Tanaman Kecil**: 5-10 menit
- **Tanaman Sedang**: 15-20 menit
- **Tanaman Besar/Pohon**: 30-60 menit
- **Sesuaikan** dengan jenis tanah (tanah liat lebih lama, berpasir lebih cepat)

#### 💡 Pengaturan Jadwal Cerdas
- **Musim Kemarau**: Tingkatkan frekuensi (2-3x sehari)
- **Musim Hujan**: Kurangi frekuensi atau non-aktifkan beberapa jadwal
- **Weekday vs Weekend**: Buat jadwal berbeda untuk hari kerja dan akhir pekan

### Informasi Kontak
Jika mengalami masalah teknis yang tidak dapat diatasi:

**Produk**: TaniFlow - Sistem Irigasi Otomatis  
**Versi**: 1.2  
**Hubungi** : 
   - Whatsapp: 08817145425
   - Instagram: gindring.labs

---

## **11. Lampiran: Spesifikasi**

### Konsumsi Daya
- **Standby**: ~2W
- **Saat Irigasi Aktif**: 12-15W


---

**Terima kasih telah menggunakan TaniFlow!**  
Irigasi otomatis, tanaman sehat, panen melimpah! 🌱💧








