# CilacapTools QA Testing

Repository ini digunakan untuk mengelola laporan bug dan dokumentasi pengujian aplikasi CilacapTools.

## Objectives

- Menemukan dan mendokumentasikan bug pada aplikasi.
- Memastikan setiap laporan bug dapat direproduksi.
- Membandingkan hasil pengujian dengan aplikasi referensi.
- Menghubungkan laporan bug dengan hasil pengujian di Kiwi TCMS.

## Application Under Test

- **Application:** CilacapTools
- **Application URL:** https://with-bugs.practicesoftwaretesting.com
- **Reference Application:** https://practicesoftwaretesting.com

## Bug Reporting Guidelines

Setiap laporan bug wajib mencantumkan:

1. Ringkasan bug yang jelas.
2. Area aplikasi yang terdampak.
3. Lingkungan pengujian dan data yang digunakan.
4. Langkah-langkah untuk mereproduksi bug.
5. Actual Result dan Expected Result.
6. Bukti berupa screenshot, rekaman, atau console log jika diperlukan.
7. Kiwi TCMS Test Case ID dan tautan eksekusi dengan status FAIL.
8. Severity, Priority, dan alasan penentuannya.

Sebelum membuat laporan, pastikan bug belum pernah dilaporkan dan perilakunya sudah dibandingkan dengan aplikasi referensi.

## Severity Classification

| Severity | Description |
|---|---|
| Critical | Bug sangat serius yang berdampak besar pada fungsi utama aplikasi. |
| Major | Bug yang mengganggu fungsi penting aplikasi. |
| Minor | Bug dengan dampak terbatas pada fungsi tertentu. |
| Trivial | Bug kecil, seperti kesalahan teks atau tampilan. |

## Priority Classification

| Priority | Description |
|---|---|
| P1 | Harus segera ditangani. |
| P2 | Harus diperbaiki sebelum rilis. |
| P3 | Dapat ditangani setelah bug yang lebih mendesak. |
| P4 | Prioritas rendah dan dapat ditangani kemudian. |

## Issue Management

Semua laporan bug harus dibuat menggunakan **Bug Report Issue Template** yang tersedia di repository.

Label digunakan untuk mengelompokkan bug berdasarkan jenis, severity, priority, status, dan area aplikasi.

## Quality Gate

- Semua test case dengan prioritas P1 dan P2 harus berstatus PASS.
- Tidak boleh ada bug Critical atau Major yang masih terbuka.

## Team

Repository ini digunakan oleh tim pengujian perangkat lunak untuk kegiatan pengujian, pelaporan bug, dan pengelolaan defect.
