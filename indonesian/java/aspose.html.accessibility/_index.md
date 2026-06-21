---
title: "com.aspose.html.accessibility"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Paket com.aspose.html.accessibility untuk semua manipulasi terkait Aksesibilitas Web. Mematuhi standar internasional W3C Web Accessibility Initiative"
type: docs

url: /id/java/com.aspose.html.accessibility/
---
Paket **com.aspose.html.accessibility** digunakan untuk semua manipulasi terkait Aksesibilitas Web. Mematuhi standar internasional Inisiatif Aksesibilitas Web W3C.

## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [AccessibilityRules](./accessibilityrules/) | Referensi cepat ke Pedoman Aksesibilitas Konten Web (WCAG) 2 persyaratan (kriteria keberhasilan) dan teknik. Berisi daftar Prinsip. https://www.w3.org/WAI/WCAG21/quickref/ |
| [AccessibilityValidator](./accessibilityvalidator/) | Kelas validator menangani aturan referensi cepat. Berisi metode Validate untuk memeriksa aksesibilitas. |
| [Criterion](./criterion/) | Kriteria keberhasilan yang dapat diverifikasi disediakan untuk setiap rekomendasi, sehingga WCAG 2.0 dapat diterapkan di area yang memerlukan pengujian kepatuhan. https://www.w3.org/WAI/WCAG21/Understanding/understanding-techniques |
| [Guideline](./guideline/) | Pedoman - tingkat berikutnya setelah prinsip. Tidak dapat diuji, tetapi menggambarkan kerangka kerja dan tujuan umum yang membantu penulis memahami kriteria keberhasilan dan lebih baik menerapkan teknik. Pedoman adalah daftar kriteria penerimaan dengan tipe RuleDirectory{Criterion}. |
| [Principle](./principle/) | Prinsip Aksesibilitas - Tingkat tertinggi yang menyediakan fondasi aksesibilitas web, berisi daftar Pedoman dengan tipe RuleCollection{Guideline}. Objek tidak diizinkan dibuat di luar assembly. https://www.w3.org/WAI/fundamentals/accessibility-principles/ |
| [Rule](./rule/) | Kelas abstrak yang mendefinisikan karakteristik sebuah Aturan dan mengimplementasikan antarmuka IRule |
| [Target](./target/) | Kelas berisi item elemen html atau css tempat kesalahan ditemukan. |
| [ValidationBuilder](./validationbuilder/) | Kelas ValidationBuilder menyediakan implementasi konkret dari langkah-langkah konfigurasi. Mendefinisikan metode dan pengaturan untuk kelas ValidationSettings. |
| [WebAccessibility](./webaccessibility/) | Objek untuk Pedoman Aksesibilitas Konten Web (WCAG) 2 persyaratan (kriteria keberhasilan) dan teknik. https://www.w3.org/WAI/WCAG21/quickref/ |
## Antarmuka

| Antarmuka | Deskripsi |
| --- | --- |
| [IError](./ierror/) | Antarmuka menjelaskan kesalahan validasi |
| [IRule](./irule/) | Antarmuka yang menjelaskan properti utama dari aturan. |
| [ITechniqueResult](./itechniqueresult/) | Menjelaskan hasil validasi teknik. |
## Enumerasi

| Enumerasi | Deskripsi |
| --- | --- |
| [TargetTypes](./targettypes/) | Enum tipe objek hasil dari dokumen html yang berisi kesalahan.. |
