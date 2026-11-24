
# TUGAS PRAKTIK IoT SENSOR API

## Dokumentasi Proyek Node-RED

Proyek ini merupakan implementasi IoT Sensor API menggunakan Node-RED.

### 1. Dokumentasi Flow Node-RED

![Flow Node-RED](<dokumentasi/WhatsApp Image 2026-11-24 at 22.31.19.jpeg>)

### 2. Pengujian Sistem

![Pengujian Sistem](<dokumentasi/WhatsApp Image 2026-11-24 at 22.31.30.jpeg>)

### 3. Dashboard Monitoring

![Dashboard Monitoring](<dokumentasi/WhatsApp Image 2026-11-24 at 22.31.45.jpeg>)

### 4. Hasil Pengujian

![Hasil Pengujian](<dokumentasi/WhatsApp Image 2026-11-24 at 22.32.12.jpeg>)

## Teknologi yang Digunakan
- Node-RED
- REST API
- MQTT
- Dashboard 2.0
- Chart.js

# IoT Sensor API - Node-RED

## Deskripsi
Proyek IoT Sensor API menggunakan Node-RED
untuk monitoring suhu dan pengelolaan data sensor.

## Fitur
- Subscribe sensor menggunakan MQTT
- REST API GET /api/suhu
- REST API GET /api/history
- REST API POST /api/kontrol
- Endpoint PUT /api/threshold
- Notifikasi ketika suhu melewati batas
- Dashboard Monitoring
- Grafik suhu real-time (pengembangan)

## Pengujian Threshold
Batas suhu: 30°C
Suhu pengujian: 35°C

Hasil:
{
  "success": true,
  "message": "Batas suhu berhasil diperbarui",
  "threshold": 30
}

Notifikasi:
Suhu melewati batas yang ditentukan!

## Teknologi
- Node-RED
- MQTT
- REST API
- Dashboard 2.0
- JavaScript

## Cara Menjalankan
1. Instal Node-RED.
2. Import file IoT_Sensor_API.json.
3. Deploy flow.
4. Buka Dashboard Monitoring.
