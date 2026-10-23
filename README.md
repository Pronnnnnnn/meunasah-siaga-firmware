# MEUNASAH-SIAGA · Firmware ESP32

Lampu cadangan meunasah yang ditenagai aliran air wudhu.
Proyek Kelompok 07, mata kuliah Hardware-Software Co-Design, Program Studi Teknik Komputer, Fakultas Teknik, Universitas Syiah Kuala.

Anggota: M. Riza Yuriansyah, Raiyan Arief Ramadhan, Griselda Mustafa, Muhammad Ghufran.

## Status
Sprint 1 (19–23 Oktober 2026): repositori disiapkan. Kode firmware ESP32 mulai ditulis di sprint berikutnya.

## Pin ESP32 (rancangan)
| Fungsi | Pin |
|---|---|
| INA219 SDA / SCL | GPIO21 / GPIO22 |
| Tegangan generator (ADC1, lewat pembagi 68 kΩ / 10 kΩ) | GPIO34 |
| Deteksi PLN (PC817) | GPIO27 |
| Lampu 1 / lampu 2 (PWM) | GPIO25 / GPIO26 |
| Tombol BOOT / LED status | GPIO0 / GPIO2 |
