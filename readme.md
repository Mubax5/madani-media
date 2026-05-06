# Workflow Operasional Guru - Madani Montessori Islamic School

**Unit:** Kelompok Bermain dan Taman Kanak Kanak Islam Terpadu MADANI MONTESSORI Islamic School  
**Tim:** 5 orang total: 1 Founder/Kepala Sekolah + 4 guru  
**Murid:** 32 anak KB, TK A, TK B, TK C (distribusi per jenjang belum final)  
**Program:** Reguler, Half Day, rencana Full Day, dan Bimbel SD sore

## 1. Struktur Tim

```mermaid
flowchart TB
    KS[Founder / Kepala Sekolah\nArah akademik, supervisi, orang tua, keputusan teknis]
    K1[Kelas 1\nKB + TK A]
    K2[Kelas 2\nTK B + TK C]
    G1[Guru 1\nWali Kelas KB-A]
    G2[Guru 2\nPendamping KB-A]
    G3[Guru 3\nWali Kelas B-C]
    G4[Guru 4\nPendamping B-C / Rotasi Bimbel]
    S[Sistem Akademik\nLaporan harian, mingguan, bulanan, semester]
    B[Bimbel SD Sore\n1 guru per hari bergantian]
    KS --> K1
    KS --> K2
    KS --> S
    K1 --> G1
    K1 --> G2
    K2 --> G3
    K2 --> G4
    G1 --> S
    G2 --> S
    G3 --> S
    G4 --> S
    G1 -.-> B
    G2 -.-> B
    G3 -.-> B
    G4 -.-> B
```

## 2. Timeline Harian

```mermaid
flowchart LR
    A[07.00-07.30\nBriefing + Persiapan]
    B[07.30-08.00\nPenyambutan Anak]
    C[08.00-09.30\nKegiatan Inti Montessori-Islamic]
    D[09.30-10.00\nSnack, Toilet, Transisi]
    E[10.00/10.30\nClosing Reguler]
    F[10.30-13.00\nHalf Day]
    G[13.00-14.00\nInput Laporan + Lesson Prep]
    H[14.00-17.00\nBimbel SD]
    I[Future Full Day\nSampai 16.00 / Jumat 15.30]
    A --> B --> C --> D --> E --> F --> G --> H
    D -. jika full day .-> I
```

## 3. Workflow Pelaporan Tumbuh Kembang

```mermaid
flowchart LR
    A[Observasi di kelas]
    B[Catatan cepat]
    C[Input harian ke sistem]
    D[Review Kepala Sekolah]
    E[Ringkasan Mingguan]
    F[Evaluasi Bulanan]
    G[Portofolio dan Laporan Semester]
    H[Rencana Stimulasi]
    A --> B --> C --> D --> E --> F --> G
    F --> H
    H -. siklus perbaikan .-> A
```

## 4. Rotasi Bimbel

| Hari | Guru Piket Bimbel | Catatan |
|---|---|---|
| Senin | Guru 1 | Sampai sekitar 17.00 |
| Selasa | Guru 2 | Sampai sekitar 17.00 |
| Rabu | Guru 3 | Sampai sekitar 17.00 |
| Kamis | Guru 4 | Sampai sekitar 17.00 |
| Jumat | Rotasi ringan / opsional | Sesuaikan pendaftar dan beban guru |

## 5. Jam Program

| Program | Senin-Kamis | Jumat |
|---|---:|---:|
| Reguler | 07.30-10.30 | 07.30-10.00 |
| Half Day | 07.30-13.00 | 07.30-12.30 |
| Full Day (rencana) | 07.30-16.00 | 07.30-15.30 |
| Bimbel SD | setelah TK selesai - 17.00 | menyesuaikan |

## 6. Aturan Kunci

1. Guru yang piket bimbel tidak diberi tugas administrasi berat pada hari yang sama.
2. Founder/Kepala Sekolah memegang quality control dan keputusan teknis, bukan semua tugas operasional kecil.
3. Laporan harian harus ringkas, sedangkan analisis panjang dipindah ke mingguan/bulanan.
4. Saat Full Day mulai berjalan, minimal harus ada 2 orang dewasa yang tetap tersedia untuk anak full day jika bimbel berjalan bersamaan.
