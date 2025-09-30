---
title: Manual Penggunaan Tani Flow
layout: post
image: assets/images/CASE X5_122201.jpg
description: Panduan penggunaan produk sistem irigasi otomatis Tani Flow
date: 02-09-2025 20:40:00
categories: [Elektronika, Tani-Flow, Sistem-Kontrol]
tags: [Dokumentasi, Manual-Penggunaan]
---

# 🌱 MANUAL PENGGUNAAN
## 💧 PLANTERSENS - SISTEM IRIGASI OTOMATIS
### 🖥️ Interface Web Control Panel

---

## ℹ️ INFORMASI PRODUK

| Item            | Detail                                   |
| --------------- | ---------------------------------------- |
| **Nama Produk** | Plantersens - Sistem Irigasi Otomatis    |
| **Interface**   | Web Control Panel                        |
| **Versi Manual**| 2.0                                      |
| **Tanggal**     | September 2025                           |
| **Akses**       | `192.168.4.1` *(Hotspot Mode)*           |

---

## 1. 🌍 PENGENALAN SISTEM

### Tentang Plantersens
Plantersens adalah sistem kontrol irigasi otomatis berbasis web yang memungkinkan Anda mengatur jadwal penyiraman melalui smartphone, tablet, atau komputer. Sistem ini menggunakan teknologi WiFi untuk memberikan kontrol penuh atas sistem irigasi Anda.

### Keunggulan Sistem:
- **Interface Web Modern:** Akses melalui browser tanpa perlu aplikasi khusus
- **Real-time Monitoring:** Status sistem diperbarui setiap detik
- **Multi-jadwal:** Hingga 15 jadwal berbeda dapat diatur
- **Kontrol Manual:** Override sistem kapan saja
- **Responsive Design:** Optimal di semua perangkat
- **Otomatis:** Sistem berjalan tanpa perlu intervensi

### Cara Kerja Sistem:
1. **Plantersens** menciptakan hotspot WiFi sendiri
2. User terhubung ke hotspot dan mengakses panel kontrol
3. Semua pengaturan disimpan langsung di perangkat
4. Sistem menjalankan jadwal secara otomatis
5. Monitoring real-time melalui web interface

---

## 2. 🔗 AKSES PERTAMA KALI

### Langkah 1: Koneksi ke Sistem

1. **Nyalakan perangkat Plantersens:**
   - Pastikan LED indikator menyala
   - Tunggu hingga sistem boot (±30 detik)

2. **Hubungkan perangkat Anda:**
   - Buka WiFi Settings di HP/laptop
   - Cari jaringan dengan nama yang sesuai kode produk (misal: "TF-1901")
   - Connect ke jaringan tersebut
   - **Catatan:** Tidak perlu password

3. **Akses Control Panel:**
   - Buka browser (Chrome, Safari, Firefox)
   - Ketik alamat: `192.168.4.1`
   - Interface Plantersens akan terbuka

### Langkah 2: Verifikasi Koneksi

Pastikan elemen berikut tampil normal:
- **Header:** Menampilkan logo Plantersens dan waktu real-time
- **Navigation:** 4 menu utama (Waktu, Jadwal, Kontrol, Status)
- **Status Connection:** Indikator hijau "TERHUBUNG"
- **Footer:** Logo brand dan informasi versi

### Indikator Koneksi:
- **Hijau + "TERHUBUNG"** = Koneksi normal
- **Merah + "TIDAK TERHUBUNG"** = Ada masalah koneksi

---

## 3. 🧭 NAVIGASI INTERFACE

### Layout Utama

#### Header Section:
- **Logo Plantersens:** Brand identity
- **Real-time Clock:** Waktu sistem saat ini (format HH:MM:SS)
- **Date Display:** Tanggal sistem (format DD/MM/YYYY)

#### Navigation Menu:
Interface memiliki 4 menu utama yang dapat diakses dengan tap/klik:

1. **⏱️ Waktu** - Pengaturan tanggal dan waktu sistem
2. **📅 Jadwal** - Konfigurasi jadwal penyiraman otomatis  
3. **🎮 Kontrol** - Kontrol manual on/off irigasi
4. **📊 Status** - Monitoring status sistem dan jadwal

#### Footer Section:
- **Animated Logo:** Pergantian otomatis logo GNDRNG dan Dark Logic Labs
- **Copyright Info:** Informasi hak cipta dan versi
- **Product Code:** Kode produk berdasarkan SSID perangkat

> [!TIP]
> 💡 **Tips Navigasi:**
- **Active Tab:** Menu aktif ditandai dengan highlight warna hijau
- **Smooth Scrolling:** Otomatis scroll ke atas saat ganti menu
- **Auto Refresh:** Data diperbarui otomatis setiap detik
- **Toast Notifications:** Notifikasi pop-up untuk konfirmasi aksi

---

## 4. MENU WAKTU

### Fungsi Menu Waktu
Menu ini digunakan untuk mengatur tanggal dan waktu sistem yang akurat. Waktu yang tepat sangat penting untuk menjalankan jadwal irigasi sesuai rencana.

### Setting Waktu Manual

#### Form Pengaturan Tanggal:
```
Tanggal: [Hari] [Bulan] [Tahun]
Contoh: 22 09 2025
```

#### Form Pengaturan Waktu:
```
Waktu: [Jam] [Menit] [Detik]  
Contoh: 14 30 00 (untuk 14:30:00)
```

### Cara Setting Waktu:

#### Metode 1: Ambil Waktu HP (Otomatis)
1. Klik tombol **"Ambil Waktu HP"**
2. Form akan terisi otomatis dengan waktu perangkat Anda
3. Klik **"Atur Waktu Sistem"** untuk menyimpan

#### Metode 2: Input Manual
1. Isi field **Hari** (1-31)
2. Isi field **Bulan** (1-12)  
3. Isi field **Tahun** (2023-2099)
4. Isi field **Jam** (0-23, format 24 jam)
5. Isi field **Menit** (0-59)
6. Isi field **Detik** (0-59)
7. Klik **"Atur Waktu Sistem"**

### Status Perangkat

Menu ini juga menampilkan informasi real-time:

- **Waktu Saat Ini:** Waktu sistem yang berjalan
- **Tanggal:** Tanggal sistem aktif
- **Hari Ini:** Hari dalam seminggu (Minggu-Sabtu)
- **Alamat IP:** IP address perangkat (192.168.4.1)
- **Status Koneksi:** Status koneksi real-time

> [!NOTE]
> ⏰ **Tips Setting Waktu:**
- **Akurasi Penting:** Jadwal irigasi tergantung pada akurasi waktu
- **Format 24 Jam:** Gunakan format 24 jam (contoh: 14:30 bukan 2:30 PM)
- **Sinkronisasi Berkala:** Periksa waktu secara berkala dan sesuaikan jika perlu

---

## 5. 📅 MENU JADWAL

### Fungsi Menu Jadwal
Menu ini adalah inti dari sistem Plantersens. Anda dapat mengatur hingga 15 jadwal berbeda dengan pengaturan waktu, durasi, dan hari aktif yang fleksibel.

### Struktur Jadwal

Setiap jadwal memiliki komponen:

#### 1. Waktu Mulai
```
Jam: 0-23 (format 24 jam)
Menit: 0-59  
Detik: 0-59
Contoh: 06:00:00 (penyiraman jam 6 pagi)
```

#### 2. Durasi
```
Durasi: 1-240 menit
Contoh: 30 (penyiraman selama 30 menit)
```

#### 3. Hari Aktif
Pilih hari dalam seminggu kapan jadwal akan dijalankan:
- **Mg** = Minggu
- **Sn** = Senin  
- **Sl** = Selasa
- **Rb** = Rabu
- **Km** = Kamis
- **Jm** = Jumat
- **Sb** = Sabtu

#### 4. Status Aktif/Non-aktif
Toggle switch untuk mengaktifkan/menonaktifkan jadwal

### Cara Mengatur Jadwal:

#### Langkah 1: Pilih Jadwal
- Scroll ke jadwal yang ingin diatur (Jadwal 1 - 15)
- Setiap jadwal ditampilkan dalam card terpisah

#### Langkah 2: Set Waktu Mulai
1. Isi field **Jam** (0-23)
2. Isi field **Menit** (0-59)  
3. Isi field **Detik** (0-59, biasanya set 00)

#### Langkah 3: Set Durasi
- Isi field **Durasi** dalam menit
- Range: 1-240 menit (maksimal 4 jam)

#### Langkah 4: Pilih Hari Aktif
1. Klik tombol hari yang diinginkan
2. Tombol aktif akan berwarna hijau
3. Bisa memilih multiple hari
4. Klik lagi untuk membatalkan pemilihan

#### Langkah 5: Aktifkan Jadwal
- Toggle switch **"Aktifkan Jadwal"** ke posisi ON (hijau)
- Switch OFF (abu-abu) = jadwal tidak aktif

#### Langkah 6: Simpan
- Klik tombol **"Simpan Semua Jadwal"** di bawah
- Sistem akan menyimpan semua perubahan

### Contoh Konfigurasi Jadwal:

#### Jadwal Penyiraman Pagi:
```
Jadwal 1:
- Waktu: 06:00:00
- Durasi: 30 menit  
- Hari: Senin, Rabu, Jumat, Minggu
- Status: AKTIF
```

#### Jadwal Penyiraman Sore:
```
Jadwal 2:  
- Waktu: 17:30:00
- Durasi: 45 menit
- Hari: Selasa, Kamis, Sabtu  
- Status: AKTIF
```

> [!TIP]
> 📌 **Tips Pengaturan Jadwal:**
- **Hindari Overlapping:** Jangan buat jadwal yang waktunya bertabrakan
- **Sesuaikan Durasi:** Durasi tergantung kebutuhan air tanaman
- **Test Dulu:** Aktifkan satu jadwal dulu untuk testing
- **Backup Setting:** Catat konfigurasi jadwal sebagai backup

---

## 6. 🎮 MENU KONTROL

### Fungsi Menu Kontrol
Menu kontrol memberikan kemampuan untuk mengoperasikan sistem irigasi secara manual, mengabaikan jadwal otomatis yang sedang berjalan.

### Status Display

#### Status Irigasi:
Menampilkan kondisi sistem saat ini:

**Status AKTIF (Hijau):**
```
Status Irigasi: AKTIF
Durasi tersisa: Xm Ys
```

**Status MATI (Merah):**
```
Status Irigasi: MATI
```

### Kontrol Manual

#### Tombol Kontrol:
1. **"Nyalakan Irigasi"** (Biru)
   - Mengaktifkan irigasi secara manual
   - Akan berjalan hingga dimatikan manual

2. **"Matikan Irigasi"** (Merah)  
   - Mematikan irigasi secara paksa
   - Membatalkan jadwal yang sedang berjalan

### Cara Menggunakan Kontrol Manual:

#### Menjalankan Irigasi Manual:
1. Pastikan sistem dalam kondisi normal (terhubung)
2. Klik tombol **"Nyalakan Irigasi"**
3. Status akan berubah menjadi "AKTIF"
4. Irigasi akan berjalan hingga dimatikan manual

#### Menghentikan Irigasi:
1. Klik tombol **"Matikan Irigasi"**
2. Status akan berubah menjadi "MATI"
3. Sistem kembali ke mode otomatis

### Sistem Override

**Perhatian Penting:**
> Kontrol manual akan mengesampingkan jadwal yang sedang berjalan

#### Cara Kerja Override:
- **Manual ON:** Mengabaikan semua jadwal, irigasi terus menyala
- **Manual OFF:** Membatalkan jadwal yang sedang aktif
- **Kembali Otomatis:** Setelah kontrol manual, sistem kembali mengikuti jadwal

### Situasi Penggunaan Kontrol Manual:

#### Emergency Stop:
- Cuaca hujan mendadak
- Ada masalah pada sistem pipa  
- Maintenance sistem

#### Testing Sistem:
- Test fungsi solenoid valve
- Cek aliran air  
- Verifikasi instalasi

#### Override Sementara:
- Penyiraman tambahan saat cuaca panas
- Skip jadwal saat akan maintenance
- Adjustement kondisi khusus

> [!IMPORTANT]
> 🎯 **Tips Kontrol Manual:**
- **Jangan Lupa Matikan:** Kontrol manual tidak auto-off
- **Monitor Status:** Perhatikan indikator status real-time
- **Emergency Access:** Simpan bookmark 192.168.4.1 untuk akses cepat

---

## 7. 📊 MENU STATUS

### Fungsi Menu Status
Menu ini memberikan overview lengkap kondisi sistem, status irigasi, dan daftar semua jadwal yang telah dikonfigurasi.

### Status Sistem Real-time

#### Grid Status Utama:
Menampilkan 3 informasi penting:

**1. Status Irigasi:**
- **AKTIF** (hijau) = Irigasi sedang berjalan
- **MATI** (merah) = Irigasi dalam kondisi off

**2. Waktu Terakhir Update:**
- Menampilkan waktu sistem saat ini
- Update setiap detik untuk memastikan sistem responsif

**3. Perangkat Terhubung:**
- Jumlah perangkat yang terhubung ke sistem
- Biasanya 1-5 perangkat (smartphone, tablet, laptop)

### Daftar Jadwal

#### Informasi Setiap Jadwal:
Menu status menampilkan semua jadwal yang telah dikonfigurasi:

```
Jadwal X:
- Waktu: HH:MM:SS
- Durasi: XX menit  
- Hari: Daftar hari aktif
- Status: AKTIF/NON-AKTIF
- Trigger Hari Ini: SUDAH/BELUM
```

#### Status Trigger:
- **SUDAH:** Jadwal telah dijalankan hari ini
- **BELUM:** Jadwal belum dijalankan hari ini

### Interpretasi Status:

#### Status Normal:
```
Status Irigasi: MATI
Perangkat Terhubung: 1+
Trigger: Sesuai jadwal
```

#### Status Aktif:
```
Status Irigasi: AKTIF  
Durasi: Countdown timer
Jadwal yang berjalan: Teridentifikasi
```

#### Status Error:
```
Perangkat Terhubung: 0
Status: Disconnected
Action: Troubleshooting required
```

### Monitoring Real-time

#### Auto-refresh Data:
- Status diperbarui setiap 1 detik
- Tidak perlu refresh halaman manual
- Connection indicator menunjukkan status koneksi

#### Timestamp Info:
- **"Terakhir diperbarui"** menunjukkan berapa detik lalu data di-update
- Nilai normal: 0-3 detik
- Jika >10 detik: kemungkinan ada masalah koneksi

> [!TIP]
> 📡 **Tips Monitoring:**
- **Cek Rutin:** Periksa status minimal sekali sehari
- **Verifikasi Trigger:** Pastikan jadwal berjalan sesuai rencana  
- **Monitor Koneksi:** Perhatikan indikator connection status
- **Log Activity:** Catat waktu trigger untuk evaluasi

---

## 8.  TROUBLESHOOTING

### Masalah Umum dan Solusi

#### Problem 1: Tidak Bisa Akses 192.168.4.1

**Gejala:**
- Browser tidak bisa membuka alamat
- Error "This site can't be reached"
- Timeout saat loading

**Penyebab Mungkin:**
- Tidak terhubung ke WiFi sistem
- IP address salah
- Perangkat Plantersens mati

**Solusi:**
1. **Cek koneksi WiFi:**
   - Pastikan terhubung ke hotspot sistem (bukan WiFi rumah)
   - Nama WiFi sesuai kode produk

2. **Verifikasi IP address:**
   - Pastikan alamat: `192.168.4.1`
   - Jangan tambahkan http:// atau https://
   - Gunakan browser standard (Chrome/Safari/Firefox)

3. **Restart sistem:**
   - Matikan perangkat Plantersens 10 detik
   - Nyalakan kembali, tunggu 30 detik
   - Reconnect WiFi dan coba akses

#### Problem 2: Interface Loading Lambat

**Gejala:**
- Web interface lama terbuka
- Data tidak update real-time
- Toast notification tidak muncul

**Solusi:**
1. **Clear browser cache:**
   - Chrome: Ctrl+Shift+Del
   - Safari: Cmd+Alt+E
   - Firefox: Ctrl+Shift+Del

2. **Cek jarak perangkat:**
   - Dekatkan smartphone/laptop ke Plantersens
   - Jarak ideal <5 meter tanpa penghalang

3. **Restart browser:**
   - Tutup semua tab browser
   - Buka ulang dan akses 192.168.4.1

#### Problem 3: Jadwal Tidak Berjalan

**Gejala:**  
- Status "BELUM" trigger padahal sudah waktunya
- Irigasi tidak menyala otomatis
- Jadwal aktif tapi tidak execute

**Troubleshooting:**
1. **Cek setting waktu:**
   - Pastikan waktu sistem akurat
   - Bandingkan dengan waktu sebenarnya
   - Set ulang jika berbeda

2. **Verifikasi konfigurasi jadwal:**
   - Pastikan toggle status "AKTIF" (hijau)
   - Cek hari aktif sudah dipilih
   - Verifikasi waktu dan durasi

3. **Test manual:**
   - Coba kontrol manual dulu
   - Jika manual tidak work = masalah hardware
   - Jika manual work = masalah setting jadwal

#### Problem 4: Koneksi Terputus-putus

**Gejala:**
- Status connection merah-hijau bergantian  
- Data tidak real-time
- Control tidak responsif

**Solusi:**
1. **Stabilkan koneksi:**
   - Posisi perangkat lebih dekat
   - Hindari interferensi WiFi lain
   - Matikan WiFi rumah sementara

2. **Cek power supply:**
   - Pastikan tegangan listrik stabil
   - Gunakan UPS jika perlu
   - Cek kabel power tidak longgar

#### Problem 5: Kontrol Manual Tidak Respon

**Gejala:**
- Klik tombol tidak ada efek
- Status tidak berubah
- Error message muncul

**Solusi:**
1. **Refresh halaman:**
   - F5 atau pull-to-refresh
   - Clear cache browser
   - Reconnect WiFi

2. **Cek hardware:**
   - Pastikan solenoid valve tidak macet
   - Cek koneksi kabel ke valve
   - Test continuity dengan multimeter

### Error Messages dan Artinya:

#### "Gagal mengirim perintah!"
- **Penyebab:** Koneksi terputus saat kirim command
- **Solusi:** Cek koneksi, coba lagi

#### "Gagal mengambil data dari perangkat"  
- **Penyebab:** Communication timeout
- **Solusi:** Refresh halaman, cek koneksi

#### "Gagal mengambil jadwal"
- **Penyebab:** Error saat load konfigurasi jadwal
- **Solusi:** Restart sistem, load ulang halaman

> [!NOTE]
> 🧾 **Tips Troubleshooting Umum:**
1. **Restart First:** 80% masalah selesai dengan restart
2. **Check Connection:** Pastikan WiFi connection stable
3. **Clear Cache:** Browser cache sering menyebabkan masalah
4. **Note Down Settings:** Catat konfigurasi sebelum troubleshoot
5. **One Problem at a Time:** Selesaikan satu masalah dulu

---

## 9. ❓ FAQ (Frequently Asked Questions) (Frequently Asked Questions)

### Q1: Berapa perangkat yang bisa terhubung bersamaan?
**A:** Sistem dapat menangani hingga 5 perangkat secara bersamaan. Lebih dari itu mungkin akan mengalami slowdown.

### Q2: Apakah data hilang jika listrik mati?  
**A:** Tidak. Semua pengaturan jadwal dan konfigurasi disimpan di memory internal yang tahan terhadap power outage.

### Q3: Bisakah mengakses dari luar rumah?
**A:** Tidak. Sistem menggunakan hotspot lokal, hanya bisa diakses dalam range WiFi (±10-15 meter).

### Q4: Maksimal berapa lama durasi penyiraman?
**A:** Maksimal 240 menit (4 jam) per jadwal. Jika butuh lebih lama, buat multiple jadwal.

### Q5: Bagaimana jika lupa password WiFi?
**A:** Sistem tidak menggunakan password. Langsung connect ke hotspot dan akses 192.168.4.1.

### Q6: Bisakah menjalankan 2 jadwal bersamaan?
**A:** Tidak disarankan. Sistem dirancang untuk 1 jadwal aktif dalam satu waktu untuk mencegah conflict.

### Q7: Apakah bisa otomatis mati jika hujan?
**A:** Tidak ada sensor hujan built-in. Gunakan kontrol manual untuk mematikan saat hujan.

### Q8: Bagaimana cara factory reset?
**A:** Tekan dan tahan tombol reset di perangkat selama 10 detik hingga LED berkedip.

### Q9: Apakah interface bisa dibuka di iOS dan Android?
**A:** Ya. Interface web kompatibel dengan semua browser modern di iOS, Android, Windows, dan Mac.

### Q10: Bagaimana cara update firmware?
**A:** Saat ini belum ada fitur OTA update. Hubungi technical support untuk update manual.

---

## 10. 🧑‍💻 TECHNICAL SUPPORT

### Informasi Kontak

**Customer Service:**
- **Telepon:** 0800-PLANTERSENS (0800-7526-8377)
- **WhatsApp:** +62-812-PLANTERS (+62-812-7526-8377)
- **Email:** support@plantersens.com

**Technical Support:**
- **Email:** technical@plantersens.com
- **Telegram:** @PlantersensSupport
- **Website:** www.plantersens.com/support

### Jam Operasional:
- **Senin - Jumat:** 08:00 - 17:00 WIB
- **Sabtu:** 08:00 - 14:00 WIB  
- **Minggu:** Libur (Emergency support available)

### Informasi yang Perlu Disiapkan Saat Menghubungi Support:

1. **Product Code:** (Tampil di footer web interface)
2. **Firmware Version:** (Tampil di footer)
3. **Problem Description:** Jelaskan masalah secara detail
4. **Error Messages:** Screenshot jika ada error
5. **Network Info:** Jumlah perangkat terhubung
6. **Environment:** Kondisi instalasi (indoor/outdoor)

### Remote Support:

Tim technical support dapat memberikan bantuan melalui:
- **Screen sharing:** TeamViewer, AnyDesk
- **Video call:** WhatsApp, Zoom, Google Meet
- **Email support:** Screenshot dan deskripsi masalah

### Garansi dan Layanan:

#### Garansi Produk:
- **Hardware:** 2 tahun dari tanggal pembelian
- **Software:** Lifetime support dan bug fixes
- **Technical Support:** Gratis selama masa garansi

#### Layanan Purna Jual:
- **Installation Support:** Bantuan instalasi jarak jauh
- **Configuration Help:** Setup jadwal dan optimasi
- **Maintenance Guide:** Panduan perawatan berkala
- **Upgrade Consultation:** Saran untuk upgrade sistem

### Website Resources:

**Knowledge Base:**
- www.plantersens.com/kb
- Tutorial video
- FAQ extended
- Download center

**Community Forum:**
- www.plantersens.com/forum
- User discussion
- Tips and tricks
- Troubleshooting community

---

## 📎 LAMPIRAN

### Spesifikasi Teknis Web Interface:

**Browser Support:**
- Chrome 80+
- Safari 13+  
- Firefox 75+
- Edge 80+

**Device Compatibility:**
- iOS 12+
- Android 7+
- Windows 10+
- macOS 10.14+

**Network Requirements:**
- WiFi 802.11 b/g/n
- Frequency: 2.4 GHz
- Range: 10-15 meter
- Bandwidth: 1 Mbps minimum

### Default Configuration:

**Network Settings:**
```
SSID: [Product Code] (contoh: TF-1901)
IP Address: 192.168.4.1
Subnet: 255.255.255.0  
Gateway: 192.168.4.1
DNS: 192.168.4.1
```

**Default Schedules:**
```
Jadwal 1-15: 
- Waktu: 08:00 + index jam
- Durasi: 5 menit
- Hari: Semua hari (Mg-Sb)
- Status: AKTIF
```

### Keyboard Shortcuts:

**Navigation:**
- Tab key: Pindah antar form fields
- Enter: Submit form/konfirmasi
- Esc: Cancel/kembali
- F5: Refresh halaman

**Mobile Gestures:**
- Swipe down: Refresh halaman
- Double tap: Zoom in/out
- Pinch: Zoom control
- Long press: Context menu

---

**© 2025 Plantersens - Sistem Irigasi Otomatis**  
**Manual Penggunaan Web Interface v2.0**

*Simpan manual ini sebagai bookmark browser untuk referensi cepat*

---

### Quick Reference Card:

**Akses Sistem:** 192.168.4.1  
**Emergency Stop:** Menu Kontrol → Matikan Irigasi  
**Support:** 0800-PLANTERSENS  
**Factory Reset:** Tekan tombol reset 10 detik  

**Menu Shortcuts:**
- ⏱️ Waktu: Setting tanggal/waktu
- 📅 Jadwal: Konfigurasi penyiraman  
- 🎮 Kontrol: Manual on/off

- 📊 Status: Monitor sistem







