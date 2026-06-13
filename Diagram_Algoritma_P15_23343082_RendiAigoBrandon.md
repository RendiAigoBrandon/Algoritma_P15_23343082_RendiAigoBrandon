# Diagram_Algoritma_P15_23343082_RendiAigoBrandon

Dokumen ini berisi diagram untuk tugas **Aktivitas Algoritma - Kerangka Analisis Tren, Persiapan Future Tech Talk, dan Pohon Keputusan Karier**.

---

## 1. Diagram Kerangka Analisis Tren

```mermaid
flowchart TD
    A[Mulai: Pilih tren teknologi mobile] --> B[Identifikasi tren]
    B --> C[Cari bukti adopsi]
    C --> D[Analisis pendorong dan hambatan]
    D --> E[Identifikasi peluang untuk Flutter developer]
    E --> F[Rumuskan rekomendasi]
    F --> G[Ambil keputusan: pelajari sekarang, nanti, atau abaikan sementara]

    B --> B1[Definisi, sejarah singkat, dan masalah yang diselesaikan]
    C --> C1[Sumber primer, studi kasus, perusahaan pengguna, package pendukung]
    D --> D1[Faktor teknis, bisnis, regulasi, infrastruktur, dan SDM]
    E --> E1[Package Flutter, jenis aplikasi, peluang portofolio, peluang kerja]
    F --> F1[Prioritas belajar, proyek latihan, risiko, dan target 3-6 bulan]
```

---

## 2. Diagram Algoritma Persiapan Future Tech Talk

```mermaid
flowchart TD
    A[Mulai] --> B[Pilih topik tren]
    B --> C[Tentukan sudut pandang presentasi]
    C --> D[Riset sumber primer]
    D --> E[Catat data penting dan contoh implementasi]
    E --> F[Susun narasi presentasi]
    F --> G[Buat slide visual]
    G --> H[Tambahkan contoh kode atau demo Flutter]
    H --> I[Latihan presentasi 2-3 kali]
    I --> J[Rekam dengan Loom atau OBS]
    J --> K[Review hasil rekaman]
    K --> L{Sudah jelas dan durasi sesuai?}
    L -- Belum --> I
    L -- Sudah --> M[Upload ke YouTube unlisted atau Google Drive]
    M --> N[Bagikan link dan poin diskusi di forum]
    N --> O[Selesai]
```

---

## 3. Diagram Pohon Keputusan Karier

```mermaid
flowchart TD
    A[Mulai: Tentukan spesialisasi karier] --> B{Apa kekuatan teknis saya saat ini?}

    B -->|UI Flutter, API, kamera, logika aplikasi| C{Tertarik fitur cerdas dan machine learning?}
    B -->|Koneksi perangkat, sensor, hardware| D{Tertarik kontrol perangkat fisik?}
    B -->|Web, deployment cepat, akses lintas platform| E{Tertarik aplikasi web-mobile?}
    B -->|Fintech, payment, platform besar| F{Tertarik ekosistem layanan skala besar?}

    C -->|Ya| G[Spesialisasi: Flutter + AI on-device]
    C -->|Belum| H[Perkuat Flutter dasar dan API terlebih dahulu]

    D -->|Ya| I[Spesialisasi: Flutter + IoT]
    D -->|Belum| H

    E -->|Ya| J[Spesialisasi: Flutter Web / PWA]
    E -->|Belum| H

    F -->|Ya| K[Spesialisasi: Flutter + FinTech / Super Apps]
    F -->|Belum| H

    G --> L{Peluang pasar terbesar di daerah saya?}
    I --> L
    J --> L
    K --> L

    L -->|Kesehatan, pendidikan, UMKM, pertanian| M[Prioritas: AI on-device]
    L -->|Smart city, pertanian presisi, manufaktur| N[Prioritas: IoT]
    L -->|Bisnis lokal, sekolah, UMKM butuh akses web| O[Prioritas: PWA]
    L -->|Fintech, transportasi, marketplace, layanan digital| P[Prioritas: Super Apps / FinTech]

    M --> Q[Buat portofolio OCR scanner, image classifier, AI notes]
    N --> R[Buat portofolio smart home MQTT/BLE]
    O --> S[Buat portofolio Flutter Web PWA offline-first]
    P --> T[Buat portofolio e-wallet mockup, booking, payment integration]

    Q --> U[Selesai: pilih spesialisasi dan mulai roadmap 3 bulan]
    R --> U
    S --> U
    T --> U
```
