
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
