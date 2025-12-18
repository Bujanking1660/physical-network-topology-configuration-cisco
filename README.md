# Cisco Packet Tracer: Physical Network Topology & Configuration 🌐

Repositori ini berisi proyek simulasi jaringan menggunakan **Cisco Packet Tracer** yang berfokus pada implementasi topologi secara fisik (*Physical Mode*), konfigurasi perangkat melalui CLI, dan verifikasi konektivitas.

## 👤 Identitas
- **Nama** : Rizkya Gusnaldy Kalia
- **NIM** : 10124190
- **File Proyek** : `10124190_RizkyaGusnaldyKalia.pka`

## 📝 Deskripsi Tugas
Tugas ini mensimulasikan penyusunan perangkat jaringan di dalam rak (*wiring closet*) dan pengabelan antar perangkat sesuai dengan standar teknis.

### Bagian Utama Tugas:
1. **Set Up Topology**: Menyusun PC, Switch, dan Router ke dalam rak secara fisik.
2. **Device Cabling**: Melakukan koneksi kabel (Copper Straight-Through/Console) pada port yang tepat (misal: G0/0/0, G0/0/1).
3. **Configuration**: Mengonfigurasi IP Address (IPv4 & IPv6) serta Default Gateway pada setiap perangkat.
4. **Verification**: Menguji konektivitas antar perangkat dan menampilkan informasi perangkat menggunakan perintah IOS.

## 📊 Addressing Table (Tampilan Proyek)
| Device | Interface | IP Address | Subnet Mask / Prefix |
|--------|-----------|------------|----------------------|
| R1     | G0/0/0    | 172.20.0.1 | 255.255.255.0        |
| R1     | G0/0/1    | 172.10.0.1 | 255.255.255.0        |
| PC-A   | NIC       | 172.20.0.10| 255.255.255.0        |
| PC-B   | NIC       | 172.10.0.10| 255.255.255.0        |

## 🛠️ Cara Mempergunakan
1. Unduh file `.pka` di dalam repositori ini.
2. Buka menggunakan **Cisco Packet Tracer** (versi terbaru direkomendasikan).
3. Kamu dapat melihat konfigurasi melalui tab **CLI** pada router atau switch untuk melihat perintah `show ip interface brief` atau `show running-config`.

## 📸 Dokumentasi Fisik
<img width="1919" height="1079" alt="Screenshot 2025-12-19 000006" src="https://github.com/user-attachments/assets/1bb3896e-425f-4b89-bf05-e0a1cb6711d0" />

*(Catatan: Gambar di atas menunjukkan tata letak kabel dan perangkat di dalam rak server)*

---
© 2025 Rizkya Gusnaldy Kalia

