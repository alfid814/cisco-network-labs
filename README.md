# cisco-network-labs
"Kumpulan simulasi jaringan dan keamanan menggunakan Cisco Packet Tracer."
# Network Security & Cisco Packet Tracer Portfolio

Halo! Saya **Dimas Alfiansyah**, mahasiswa Teknik Informatika Universitas Islam Sultan Agung (Unissula). Repositori ini berisi kumpulan simulasi jaringan yang saya bangun menggunakan Cisco Packet Tracer, dengan fokus pada **segmentasi jaringan, routing, dan penerapan kebijakan keamanan (ACL, Port Security)**.

## 📂 Daftar Proyek

### 1. [Simulasi Jaringan Perusahaan Multi-Departemen](./01-company-network)
*   **Deskripsi**: Membangun jaringan perusahaan yang tersegmentasi untuk departemen Perpustakaan, Lab, TU, dan Guru.
*   **Fitur Keamanan**: VLAN Segmentation, Inter-VLAN Routing, ACL untuk membatasi akses antar departemen.
*   **Teknologi**: Cisco Packet Tracer, 3 Router, 5 Switch.

### 2. [Simulasi Layanan Jaringan: DHCP, DNS, dan Web Server](./02-network-services)
*   **Deskripsi**: Membangun jaringan LAN dengan dua switch yang menyediakan layanan DHCP, DNS, dan Web Server untuk klien dinamis dan statis.
*   **Fitur**:
    *   Konfigurasi DHCP Server (IP Pool: 172.16.0.0/16) untuk PC Dynamic.
    *   Konfigurasi DNS Server untuk menerjemahkan domain `www.internal.com` dan `www.cabillo.edu`.
    *   Konfigurasi Web Server dengan IP statis (172.16.0.20 dan 172.16.0.30).
    *   Pengujian akses web dari PC klien menggunakan domain name.
*   **Teknologi**: Cisco Packet Tracer, 2 Switch, 3 PC, 4 Server (DHCP, DNS, 2 Web).

### 3. [Simulasi Topologi Mesh dengan Redundansi dan Keamanan STP](./03-mesh-topology-redundancy)
*   **Deskripsi**: Membangun jaringan mesh kompleks yang menghubungkan 12 switch untuk memastikan ketersediaan tinggi (*high availability*) dan menganalisis perilaku Spanning Tree Protocol (STP) dalam mencegah *looping*.
*   **Fitur**:
    *   Konfigurasi redundant links antar switch.
    *   Analisis Root Bridge Election pada STP.
    *   Penerapan fitur keamanan STP: **BPDU Guard** dan **PortFast** pada port yang terhubung ke PC.
*   **Teknologi**: Cisco Packet Tracer, 12 Switch (2950 & 2960), 8 PC.

### 4. [Konfigurasi Switch & Port Security](./04-switch-port-security)
*   **Deskripsi**: Konfigurasi dasar switch 2950-24 untuk menghubungkan 6 PC (PC0-PC5) dengan pengalamatan IP statis (192.168.1.66 - 192.168.1.71), serta penerapan fitur keamanan *Port Security* untuk mencegah akses tidak sah.
*   **Fitur**:
    *   Konfigurasi VLAN dasar dan pengalamatan IP statis pada klien.
    *   Penerapan **Port Security** pada semua port aktif (fa0/18 hingga fa0/23).
    *   Pembatasan maksimal 1 MAC address per port.
    *   Konfigurasi *violation mode* menjadi `shutdown` sebagai bentuk mitigasi serangan fisik.
    *   Penonaktifan port yang tidak digunakan (unused ports).
*   **Teknologi**: Cisco Packet Tracer, 1 Switch (2950-24), 6 PC.

## 🛡️ Fokus Keahlian
*   **Networking**: Cisco Packet Tracer, VLAN, Routing (Static/OSPF), ACL, STP.
*   **Cybersecurity**: Network Segmentation, Port Security, Prinsip Least Privilege.

## 📫 Kontak
*   **LinkedIn**: https://www.linkedin.com/in/dimas-alfiansyah-3036643a3/
*   **Email**: Alfid814@gmail.com
