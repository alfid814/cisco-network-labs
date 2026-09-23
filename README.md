# Network Security & Cisco Packet Tracer Portfolio

Halo! Saya **Dimas Alfiansyah**, mahasiswa undergraduate Teknik Informatika Universitas Islam Sultan Agung (Unissula).

Repositori ini berisi kumpulan simulasi jaringan yang saya bangun menggunakan **Cisco Packet Tracer**, dengan fokus pada segmentasi jaringan, routing, layanan jaringan, dan penerapan kebijakan keamanan (*Access Control List*, *Port Security*, *BPDU Guard*).

Repositori ini saya susun sebagai bukti praktik dari pembelajaran saya di **Cisco Networking Academy** dan **RIPE NCC Academy**.

---

## 📂 Daftar Proyek

### 1. Simulasi Jaringan Perusahaan Multi-Departemen

![Topologi Jaringan Perusahaan](./company-network-security/topology.png)

*   **Deskripsi**: Membangun jaringan perusahaan yang tersegmentasi untuk departemen Perpustakaan, Lab 1-3, TU, dan Guru menggunakan 3 router dan 5 switch.
*   **Fitur Keamanan**: Segmentasi VLAN, Inter-VLAN Routing, Access Control List (ACL) untuk membatasi akses antar departemen.
*   **Teknologi**: Cisco Packet Tracer, 3 Router, 5 Switch, 6 PC.
*   **File Proyek**: [Download File .pkt](./company-network-security/company-network.pkt)

---

### 2. Simulasi Layanan Jaringan: DHCP, DNS, dan Web Server

![Topologi Layanan Jaringan](./network-services/topology.png)

*   **Deskripsi**: Membangun jaringan LAN dengan dua switch yang menyediakan layanan DHCP, DNS, dan Web Server untuk klien dinamis dan statis.
*   **Fitur**:
    *   Konfigurasi DHCP Server (IP Pool: 172.16.0.0/16) untuk PC Dynamic.
    *   Konfigurasi DNS Server untuk menerjemahkan domain `www.internal.com` dan `www.cabillo.edu`.
    *   Konfigurasi Web Server dengan IP statis (172.16.0.20 dan 172.16.0.30).
    *   Pengujian akses web dari PC klien menggunakan domain name.
*   **Teknologi**: Cisco Packet Tracer, 2 Switch, 3 PC, 4 Server (DHCP, DNS, 2 Web).
*   **File Proyek**: [Download File .pkt](./network-services/network-services.pkt)

---

### 3. Simulasi Topologi Mesh dengan Redundansi dan Keamanan STP

![Topologi Mesh](./mesh-topology-redundancy/topology.png)

*   **Deskripsi**: Membangun jaringan mesh kompleks yang menghubungkan 12 switch untuk memastikan ketersediaan tinggi (*high availability*) dan menganalisis perilaku Spanning Tree Protocol (STP) dalam mencegah *looping*.
*   **Fitur**:
    *   Konfigurasi redundant links antar switch.
    *   Analisis Root Bridge Election pada STP.
    *   Penerapan fitur keamanan STP: **BPDU Guard** dan **PortFast** pada port yang terhubung ke PC.
*   **Teknologi**: Cisco Packet Tracer, 12 Switch (2950 & 2960), 8 PC.
*   **File Proyek**: [Download File .pkt](./mesh-topology-redundancy/mesh-topology.pkt)

---

### 4. Konfigurasi Switch & Port Security

![Topologi Switch Security](./switch-port-security/topology.png)

*   **Deskripsi**: Konfigurasi dasar switch 2950-24 untuk menghubungkan 6 PC (PC0-PC5) dengan pengalamatan IP statis (192.168.1.66 - 192.168.1.71), serta penerapan fitur keamanan *Port Security* untuk mencegah akses tidak sah.
*   **Fitur**:
    *   Konfigurasi VLAN dasar dan pengalamatan IP statis pada klien.
    *   Penerapan **Port Security** pada semua port aktif (fa0/18 hingga fa0/23).
    *   Pembatasan maksimal 1 MAC address per port.
    *   Konfigurasi *violation mode* menjadi `shutdown` sebagai bentuk mitigasi serangan fisik.
    *   Penonaktifan port yang tidak digunakan (*unused ports*).
*   **Teknologi**: Cisco Packet Tracer, 1 Switch (2950-24), 6 PC.
*   **File Proyek**: [Download File .pkt](./switch-port-security/switch-port-security.pkt)

---

## 🛡️ Fokus Keahlian

*   **Networking**: Cisco Packet Tracer, VLAN, Inter-VLAN Routing, DHCP, DNS, STP, ACL.
*   **Cybersecurity**: Network Segmentation, Port Security, BPDU Guard, Hardening Perangkat.
*   **Tools**: Cisco Packet Tracer, Git, GitHub, Linux (dasar).
*   **Sertifikasi (In Progress)**: Cisco Networking Academy, RIPE NCC Academy.

---

## 🎓 Pendidikan

**Universitas Islam Sultan Agung (Unissula)** — Teknik Informatika
Mata kuliah relevan: Jaringan Komputer, Keamanan Informasi, Sistem Operasi, Basis Data.

---

## 📫 Kontak

*   **Email**: alfid814@gmail.com
*   **LinkedIn**: https://www.linkedin.com/in/dimas-alfiansyah-3036643a3/
*   **GitHub**: [github.com/alfid814](https://github.com/alfid814)
*   **Lokasi**: Semarang, Indonesia

---

*Repositori ini terus diperbarui seiring pembelajaran saya di bidang Network Security.*
