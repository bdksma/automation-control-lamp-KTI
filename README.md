# **IoT-Based Automation Control Room at PT Krakatau Tirta Industri**  

## **📌 Deskripsi Proyek**  
Proyek ini merupakan **simulasi IoT sederhana** yang dikembangkan selama magang di **PT Krakatau Tirta Industri (PT KTI)**. Sistem ini bertujuan untuk **mengotomatiskan kontrol lampu dan AC di dalam ruangan** menggunakan sensor **Passive Infra Red (PIR) untuk mendeteksi keberadaan manusia**.  

Dengan sistem ini, lampu dan AC akan **menyala otomatis ketika ada orang di dalam ruangan** dan akan **mati ketika ruangan kosong** untuk menghemat energi serta meningkatkan efisiensi operasional.  

## **🔧 Teknologi & Perangkat yang Digunakan**  
- **Microcontroller:** ESP32 / Arduino  
- **Sensor:** PIR Motion Sensor (Passive Infrared)  
- **Relay:** 2-Channel Relay Module (untuk mengontrol lampu & AC)  
- **Komunikasi:** MQTT (Mosquitto) & HTTP  
- **Cloud Platform:** Blynk  
- **Power Supply:** 5V & 220V untuk kontrol beban listrik  

## **⚙️ Fitur Utama**  
✅ **Deteksi Kehadiran Otomatis** – Lampu dan AC menyala ketika ada orang dan mati saat ruangan kosong.  
✅ **Kontrol Jarak Jauh** – Pengguna dapat menyalakan/mematikan perangkat melalui dashboard web.  
✅ **Notifikasi & Monitoring** – Sistem dapat memberikan notifikasi saat perangkat dinyalakan/dimatikan.  
✅ **Hemat Energi** – Mengurangi konsumsi listrik dengan mematikan perangkat saat tidak digunakan.  
✅ **Log Aktivitas** – Menyimpan data penggunaan perangkat untuk analisis lebih lanjut.  

## **📡 Arsitektur Sistem**  
terlampir

## **📊 Hasil & Dampak Implementasi**  
Implementasi sistem ini memberikan dampak yang dapat diukur, antara lain:  

🚀 **Efisiensi Konsumsi Energi**  
- **Penghematan listrik hingga 20-30%** dengan mengurangi pemborosan pemakaian listrik saat ruangan kosong.  
- **Pengurangan beban AC** yang bekerja terus-menerus tanpa ada orang di ruangan.  

📉 **Otomatisasi & Kenyamanan**  
- Tidak perlu lagi menyalakan dan mematikan perangkat secara manual.  
- Mengurangi kelalaian dalam pemakaian listrik berlebih.  

📡 **Monitoring & Aksesibilitas**  
- Dapat dikontrol melalui **dashboard berbasis web** di komputer atau smartphone.  
- Sistem menyimpan data untuk analisis pola penggunaan listrik.  

## **🛠️ Instalasi & Konfigurasi**  
### **1️⃣ Persiapan Hardware**  
- Hubungkan **PIR Sensor** ke ESP32/Arduino.  
- Hubungkan **relay** untuk mengontrol AC & lampu.  
- Pastikan koneksi listrik aman dengan **isolasi & fuse**.  

### **2️⃣ Instalasi Software**  
```bash
# Clone repositori ini
git clone https://github.com/bdiksma/automation-control-lamp-KTI.git
cd IoT-Control-Room

# Install dependensi (untuk Python)
pip install -r requirements.txt

# Atur konfigurasi di .env
cp .env.example .env
nano .env

# Jalankan server
python app.py
```

### **3️⃣ Deployment (Opsional)**  
- **Gunakan Raspberry Pi** untuk menjalankan sistem di ruangan nyata.  
- **Gunakan MQTT Broker (Mosquitto)** untuk komunikasi data antar perangkat.  

## **📊 Dashboard & Tampilan**  
terlampir

## **📞 Kontak**  
Jika ada pertanyaan atau ingin berkolaborasi, hubungi saya di:  
📧 Email: kussumabuddi369@gmail.com  
🔗 LinkedIn: [linkedin.com/in/username](https://linkedin.com/in/yusuf-budi-kusuma)  
