# Project_IoT_Kelompok22

### Kelompok 22: Aku dan 3 Anak Jenius

### Tema Project: Smart Helmet Security System

### Nama Anggota Kelompok:
1. Cantika Zahra P. M  (123240091)
2. Reza Putri Awalia   (123240095)
3. Safna Recyfa Naqiya (123240115)
4. Ilyas Jamil         (123240180)

### Smart Helmet Security System

Sistem pengaman helm pintar berbasis IoT menggunakan ESP32. Jika pengait helm dibuka secara paksa saat mode kunci aktif, sistem akan langsung membunyikan buzzer di lokasi dan mengirimkan notifikasi bahaya beserta lokasi Google Maps ke bot Telegram pengguna.

### Fitur Utama
1. Alarm: Buzzer langsung berbunyi di helm tanpa jeda saat pengait dibuka paksa
2. Koneksi (MQTT): Mengirim data status helm via broker agar hemat daya dan respon cepat
3. Pengolahan Data (Node-RED): Mengolah logika keamanan dan status lokasi secara otomatis di background
4. Notifikasi Telegram & Maps: Menerima pesan peringatan di HP beserta tautan lokasi Google Maps jika GPS valid
5. Baterai: Menggunakan baterai 2200 mAh yang tahan dipakai hingga 12-15 jam
