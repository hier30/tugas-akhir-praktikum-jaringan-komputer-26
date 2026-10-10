# Praktikum Jaringan Komputer - Pertemuan 2

## VLAN dan Trunking serta Crimping Kabel UTP (RJ-45)

**Nama:** Lutfiya Fakhira  
**NPM:** 2315061085  
**Kelas:** PJJK-A  

## Deskripsi

Pada praktikum ini dilakukan konfigurasi VLAN (Virtual Local Area Network) dan trunking antar-switch menggunakan Cisco Packet Tracer, mencakup pembuatan VLAN 10 (Operations) dan VLAN 99 (Management), konfigurasi access port pada perangkat pengguna, konfigurasi trunk antar-switch, serta pengujian konektivitas antar perangkat yang berada pada VLAN yang sama meskipun terhubung ke switch yang berbeda. Selain itu, pada praktikum ini juga dilakukan instalasi dan crimping kabel jaringan UTP menggunakan konektor RJ-45 dengan konfigurasi Straight-Through, yang kemudian diuji konektivitasnya menggunakan LAN Tester.

## Topologi

| Perangkat | Interface | IP Address      | Subnet Mask     |
|-----------|-----------|-----------------|------------------|
| PC-A      | NIC       | 192.168.10.3    | 255.255.255.0    |
| PC-B      | NIC       | 192.168.10.4    | 255.255.255.0    |
| S1        | VLAN 99   | 192.168.1.11    | 255.255.255.0    |
| S2        | VLAN 99   | 192.168.1.12    | 255.255.255.0    |

VLAN 10 (Operations) digunakan untuk PC-A dan PC-B. VLAN 99 (Management) digunakan untuk interface management S1 dan S2. Link S1-S2 (Fa0/1) dikonfigurasi sebagai trunk dengan native VLAN 99.

*(sisipkan screenshot topologi Packet Tracer di sini jika ada)*

## Video Praktikum

Link video:  
(https://youtu.be/DMYpN3iTj_M)

## File Packet Tracer

File Cisco Packet Tracer tersedia pada folder `packet-tracer`.

## Timestamp Video

00:00 Pembukaan  
01:30 Step 1: Membangun Topologi Jaringan  
03:18 Step 2: Konfigurasi IP Address PC-A dan PC-B  
04:03 Step 3: Membuat VLAN 10 dan VLAN 99 di S1 dan S2  
06:27 Step 4: Konfigurasi Access Port (Fa0/6 dan Fa0/18)  
08:33 Step 5: Konfigurasi VLAN Management (Interface VLAN 99)  
10:04 Step 6: Konfigurasi Trunk Antar-Switch (Fa0/1)  
12:39 Step 7: Verifikasi Konfigurasi  
14:42 Step 8: Pengujian Konektivitas (Ping)  
16:05 Jawaban Pertanyaan Evaluasi  
17:38 Kesimpulan VLAN & Trunking  
18:20 Cerita Praktikum Crimping Kabel UTP (RJ-45)  
