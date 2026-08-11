---
title: 'Sistem Informasi Administrasi Kependudukan (SIAK)'
lastmod: 2026-08-11
date: 2025-09-25
draft: false
description: 'Technical Case Study - Sistem Informasi Administrasi Kependudukan'
tags: ['Laravel', 'Filament', 'NativePHP', 'Leaflet', 'GIS', 'Docker']
categories: ['Projects']
weight: 1
---

## Technical Overview

**SIAK** adalah aplikasi manajemen administrasi kependudukan berbasis Laravel yang dikembangkan untuk Kantor Kelurahan Kalicari. Project ini mengelola data penduduk, keluarga, RT/RW, fasilitas umum, dan usaha warga dengan integrasi GIS serta adaptasi desktop offline menggunakan NativePHP.

---

## Technology Stack

| **Category** | **Technology**      | **Purpose**             |
| ------------ | ------------------- | ----------------------- |
| Framework    | Laravel             | Backend MVC             |
| Admin Panel  | Filament            | CRUD, UI                |
| Database     | MySQL / PostgreSQL  | Data storage            |
| ORM          | Eloquent            | Database abstraction    |
| GIS          | Leaflet.js + Geoman | Map & polygon           |
| Desktop      | NativePHP           | Offline app             |
| Container    | Docker              | Environment consistency |
| CI/CD        | GitHub Actions      | Automated deployment    |
| Proxy        | Traefik             | Reverse proxy, SSL      |
| Tunnel       | Cloudflare Tunnel   | Public access           |

---

## Evidence

- **Repository**: [github.com/ibrammalik/SIAK](https://github.com/ibrammalik/SIAK)
- **Demo**: [siak.ibra.im](https://siak.ibra.im)
- **Manual Book**: [bit.ly/3TRtKno](https://bit.ly/3TRtKno)

---

## Screenshots

### Dashboard

![Dashboard](content/project/siak/dashboard.png)

Dashboard utama menampilkan ringkasan informasi dan statistik administrasi kependudukan untuk memberikan gambaran kondisi data secara cepat.

### Manajemen Layer GIS

![GIS Layer](content/project/siak/gis-layer-crud-1.png)

![GIS Layer Form](content/project/siak/gis-layer-crud-2.png)
Halaman ini digunakan untuk mengelola layer pada peta GIS, termasuk melihat, menambahkan, mengubah, dan menghapus data layer.

Form pengelolaan layer digunakan untuk memasukkan maupun memperbarui informasi layer yang akan digunakan pada peta.

### Laporan Monografi

![Generate Monografi](content/project/siak/monografi-generate.png)

Fitur generate monografi digunakan untuk menentukan parameter dan menghasilkan laporan monografi berdasarkan data administrasi kependudukan.

![Preview Monografi](content/project/siak/monografi-preview.png)

Preview menampilkan hasil laporan monografi sebelum pengguna melakukan proses pencetakan atau pengunduhan dokumen.

### Notifikasi

![Notifikasi](content/project/siak/notification.png)

Panel notifikasi digunakan untuk menyampaikan informasi dan pemberitahuan kepada pengguna terkait aktivitas atau kondisi tertentu dalam sistem.

### Data Penduduk

![Export Penduduk](content/project/siak/penduduk-export.png)

Fitur export memungkinkan data penduduk diekspor ke dalam format yang dapat digunakan untuk pengolahan atau dokumentasi lebih lanjut.

![Import Penduduk](content/project/siak/penduduk-import.png)

Fitur import digunakan untuk memasukkan data penduduk secara massal dari berkas ke dalam sistem.

![Resource Penduduk](content/project/siak/penduduk-resource.png)

Halaman resource penduduk menyediakan antarmuka untuk melihat, mencari, memfilter, dan mengelola data penduduk.

### Pengaturan Profil

![Profile Settings](content/project/siak/profile-settings-1.png)

![Profile Settings Form](content/project/siak/profile-settings-2.png)

Halaman pengaturan profil kelurahan menyediakan informasi kelurahan serta opsi untuk mengelola data profil kelurahan.

Form pengaturan profil digunakan untuk memperbarui informasi akun pengguna.

![Edit Profile Image](content/project/siak/profile-settings-edit-img.png)

Pengguna dapat mengedit (crop, zoom, drag) latar belakang halaman sambutan melalui fitur pengelolaan gambar pada halaman pengaturan profil kelurahan.

### Pencarian

![Search](content/project/siak/search.png)

Fitur pencarian digunakan untuk menemukan data tertentu dengan lebih cepat berdasarkan kata kunci yang dimasukkan pengguna.

---
