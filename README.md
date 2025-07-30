# Barbershop Management System

## Aplikasi ini adalah sistem manajemen antrian dan transaksi untuk barbershop yang memungkinkan:

Pendaftaran pelanggan dengan berbagai layanan
Manajemen antrian pelanggan
Pelacakan status kursi
Pembuatan struk dengan QR code
Update status transaksi melalui scan QR code

## Fitur Utama
Manajemen Layanan:
8 jenis layanan dengan harga berbeda
Kemampuan memilih multiple layanan

Sistem Antrian:
Antrian FIFO (First In First Out)
Tampilan status antrian dan kursi

Transaksi:
Penyimpanan data transaksi ke Excel
Pembuatan struk digital dengan QR code
QR Code Integration:
Generate QR code di struk
Scan QR code untuk update status transaksi

Kursi Barber:
Sistem tracking 2 kursi barber
Auto-kosongkan kursi setelah transaksi selesai

### Instalasi
Pastikan Python 3.x terinstall
Install dependencies:
bash
```bash
pip install opencv-python openpyxl pillow qrcode
```

Clone repository atau copy file barbershop.py

## Penggunaan
Jalankan program:

bash
```bash
python barbershop.py
```

Menu utama:
text
1. Tambah Pelanggan
2. Tampilkan Antrian
3. Layani Pelanggan
4. Scan QR Pelanggan
5. Keluar
Struktur File
transaksi_barbershop.xlsx: File Excel untuk menyimpan data transaksi

struk_TRXxxxx.png: File struk dengan format PNG

Dependencies
Python 3.x

OpenCV (opencv-python)

OpenPyXL (openpyxl)

Pillow (Pillow)

QRCode (qrcode)

Kontribusi
Pull request dipersilakan. Untuk perubahan besar, buka issue terlebih dahulu.
