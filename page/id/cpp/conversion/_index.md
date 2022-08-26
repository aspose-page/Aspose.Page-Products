---
translation: true
template: /_templates/_conversion-cpp.md
title: API Konversi PDL | C++
url: /cpp/conversion/
description: Konversikan PS, EPS, dan XPS ke PDF dan Gambar termasuk BMP, JPG, PNG, dan TIFF menggunakan pustaka C++ dengan fungsi konversi Aspose.Page PDL.
family: page
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: Konversi PS, EPS, dan XPS
h2: Solusi API konverter PS, EPS, dan XPS untuk C++.
---

{{<section overview>}}
---
p1: "Setiap kali ada kebutuhan untuk mengonversi File PostScript PS dan Encapsulated PostScript EPS serta dokumen XPS secara terprogram, Java API dapat melakukannya dengan lancar dan mengonversi banyak file. Untuk PS dan EPS, API mendukung operator PostScript Level 1-3 dan sebagian besar komentar header EPS serta mengubah dokumen PostScript yang memiliki kesesuaian maksimum dengan pengecualian beberapa kasus font dan API menangani font seperti Time New Roman."
p2: "Pemrogram dapat dengan mudah menggunakannya untuk pemrosesan batch dokumen PostScript dan XPS, bahkan memanipulasi elemen kanvas, jalur dan mesin terbang dan menangani bentuk grafik vektor dan string teks."
p3: "Solusi API untuk Java di sini memungkinkan Anda mengonversi file format PDL seperti PS, EPS, dan XPS secara terprogram, tetapi Anda mungkin merasa berguna untuk melihat dan mencoba lintas platform yang dikembangkan pada API asli ini. Berikut adalah beberapa skenario konversi seperti EPS ke Gambar, EPS ke PDF, PostScript ke PDF, PostScript ke Gambar, XPS ke Gambar dan XPS ke PDF"
---

{{<section feature1>}}
---
title: Konversi EPS ke Gambar melalui C++.
h3: Kode C++ untuk Konversi EPS ke Gambar
item1: "Pustaka C++ memungkinkan konversi file Encapsulated PostScript (EPS) menjadi gambar pada platform Windows dan Linux. Prosesnya adalah:"
item2: "Gunakan FileStream untuk membuat aliran input untuk file EPS serta untuk membuat objek [*PsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.ps_document) yang memiliki aliran input sebagai parameter. Untuk pengaturan khusus Gambar, gunakan [*ImageSaveOptions Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_save_options)."
item3: "Tentukan jenis dan ukuran gambar menggunakan [*ImageDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_device)."
item4: Simpan EPS sebagai gambar dengan opsi penyimpanan gambar ke larik larik byte yang membuat untuk setiap byte larik aliran keluaran file baru.
---


{{<section feature2>}}
---
title: Konversi PostScript ke PDF melalui Java.
h3: Kode C++ untuk Konversi PostScript ke PDF
item1: "Proses mengonversi PostScript ke PDF sama dengan EPS ke Gambar, kecuali pengembang akan menggunakan [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_save_options) untuk menentukan pengaturan tambahan seperti AdditionalFontsFolder dan nilai SuppressError dll. Selain itu, akan menggunakan [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_device) dari aliran keluaran yang dibuat."
---

{{<section feature3>}}
---
title: Konversi XPS ke PDF melalui C++.
h3: Kode C++ untuk Konversi XPS ke PDF
item1: "C++ XPS Processing API menangani konversi XPS ke Gambar termasuk BMP, JPG, TIFF, PNG, dan lainnya, serta konversi XPS ke PDF pada sistem berbasis Windows dan Linux. Proses mengonversi XPS ke PDF adalah:"
item2: Tentukan aliran output serta tentukan aliran input untuk dokumen input XPS.
item3: "Berikan sebagai parameter ke [*XpsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.xps_document) Object."
item4: "Tentukan opsi penyimpanan khusus PDF seperti TextCompression, ImageCompression, dan JpegQualityLevel menggunakan [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_save_options)."
item5: "Buat instance [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_device) dari aliran keluaran yang dibuat sebelumnya."
item6: Terakhir, konversikan dokumen XPS sebagai PDF dengan opsi penyimpanan PDF.
---
