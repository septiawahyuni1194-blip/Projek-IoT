# Projek-IoT
Projek-Kapasitas Tempat Sampah 
# Komponen Utama Sistem
1. Mikrokontroler ESP32
ESP32 berfungsi sebagai pusat pengendali seluruh sistem. Mikrokontroler ini bertugas untuk:
- Membaca data dari sensor ultrasonik
- Mengolah data kapasitas tempat sampah
- Mengirim data ke platform monitoring melalui internet
2. Sensor Ultrasonik
Sensor ultrasonik dipasang pada bagian atas tempat sampah dengan posisi menghadap ke dasar tong sampah. Sensor ini digunakan untuk:
- Mengukur jarak antara sensor dan permukaan sampah
- Menentukan tingkat kepenuhan tempat sampah berdasarkan hasil pengukuran jarak
3. LCD Display
Layar LCD digunakan untuk menampilkan informasi kapasitas tempat sampah secara langsung kepada pengguna, seperti:
- Persentase kepenuhan sampah
- Status kondisi tempat sampah
4. Casing dan Rangkaian Elektronik
Pada bagian belakang tempat sampah terdapat casing yang berfungsi sebagai tempat penyimpanan:
- PCB
- Modul ESP32
- Catu daya
- Komponen elektronik pendukung lainnya
# Cara Kerja Sistem
1. Sensor ultrasonik membaca jarak antara sensor dan permukaan sampah.
2. Data jarak dikirim ke ESP32 untuk diproses.
3. ESP32 menghitung persentase kapasitas tempat sampah.
4. Hasil perhitungan ditampilkan pada LCD.
5. Data kapasitas dikirim melalui internet ke platform monitoring IoT.
6. Pengguna dapat memantau kondisi tempat sampah secara real-time dari jarak jauh.
# Tujuan dan Manfaat
Sistem monitoring tempat sampah ini dibuat untuk:
- Meningkatkan efisiensi pengelolaan sampah
- Mengurangi keterlambatan pengangkutan sampah
- Mempermudah proses pemantauan kondisi tempat sampah
- Mendukung terciptanya lingkungan yang lebih bersih dan modern
# Team Members
1. Septia Wahyuni  
2. Ayyum Firdayni 
3. Lusi Ramadhani
4. Kenny Ibrahim
5. Ahmad Raif = frotend
6. Putra Valen 
# Project Structure
Hardware > Schematic and Wiring
Firmware > Esp32 code
Backend > API and database
Frontend > dashboard website
UI/UX > Figma and design
docs > flowchart and dokumentasi

