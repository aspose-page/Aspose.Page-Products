---
translation: true
template: /_templates/_conversion-java.md
title: API Konversi PDL | Java
url: /java/conversion/
description: Konversikan PS, EPS, dan XPS ke PDF dan Gambar termasuk BMP, JPG, PNG, dan TIFF menggunakan perpustakaan Java dengan fungsi konversi Aspose.Page PDL.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Konversi PS, EPS, dan XPS
h2: Solusi API konverter PS, EPS, dan XPS untuk Java
---

{{<section overview>}}
---
p1: "Setiap kali ada kebutuhan untuk mengonversi File PostScript PS dan Encapsulated PostScript EPS serta dokumen XPS secara terprogram, Java API dapat melakukannya dengan lancar dan mengonversi banyak file. Untuk PS dan EPS, API mendukung operator PostScript Level 1-3 dan sebagian besar komentar header EPS serta mengubah dokumen PostScript yang memiliki kesesuaian maksimum dengan pengecualian beberapa kasus font dan API menangani font seperti Time New Roman."
p2: "Selain itu, untuk transformasi file XPS, API dapat menambah atau menghapus halaman, menangani elemen kanvas, jalur, dan mesin terbang, membuat bentuk grafik vektor, string teks, mengonversi item garis besar XPS, dan banyak lagi."
p3: "Solusi API untuk Java di sini memungkinkan Anda mengonversi file format PDL seperti PS, EPS, dan XPS secara terprogram, tetapi Anda mungkin merasa berguna untuk melihat dan mencoba lintas platform yang dikembangkan pada API asli ini."
---

{{<section feature1>}}
---
title: Konversi PostScript ke PDF melalui Java.
h3: "Kode Java untuk mengonversi PS EPS ke PDF"
item1: "Untuk mengonversi file PostScript PS dan Encapsulated PostScript EPS ke PDF melalui Java API, Anda perlu melakukan langkah-langkah berikut:"
item2: "Muat file PS atau EPS menggunakan [*PsDocument Class*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument)."
item3: "Setel opsi penyimpanan PDF menggunakan [*PdfSaveOptions Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfSaveOptions)."
item4: "Gunakan [*FileStream Class*](https://docs.Oracle.com/javase/7/docs/api/java/io/FileOutputStream.html) untuk file PDF keluaran."
item5: "Gunakan [*PdfDevice Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfDevice) yang memiliki objek FileOutputStream sebagai parameter."
item6: "Hubungi [*PsDocument.Save*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) untuk menyimpan file ke dalam PDF."
---

{{<section feature2>}}
---
title: Konversi PostScript ke Gambar melalui Java.
h3: "Kode Java untuk Konversi PostScript ke Gambar"
item1: "Untuk aplikasi EPS/PS PostScript to image converter, kode Java berikut berfungsi dengan baik, jadi ikuti langkah-langkah selanjutnya:"
item2: Inisialisasi aliran input dengan file sumber PS.
item3: "Buat objek [*PsDocument*](https://reference.aspose.com/page/java/com.aspose.eps/psdocument) dengan aliran input PS yang dibuat sebagai parameter"
item4: "Gunakan [*ImageSaveOptions*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagesaveoptions) untuk menentukan AdditionalFontsFolder dan SuppressError dll."
item5: "Gunakan objek [*ImageDevice*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagedevice) untuk menentukan jenis dan ukuran gambar jika diperlukan."
item6: Simpan file PS/EPS sebagai dan gambar dengan opsi penyimpanan gambar sebagai larik array byte. Satu array byte untuk satu halaman file input.
---


{{<section feature3>}}
---
title: Konversi XPS ke Gambar JPG, PNG, BMP melalui Java.
h3: Kode Java untuk XPS ke Konversi Gambar
item1: "Java API menangani format XPS yang digunakan untuk merepresentasikan tata letak halaman. Dalam skenario apa pun, setiap kali ada kebutuhan untuk mengonversi XPS ke gambar BMP, JPG, PNG, dan TIFF secara terprogram, kode berikut dapat dengan mudah diintegrasikan dalam aplikasi Java."
item2: "Gunakan [*XpsDocument class*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument) untuk memuat dokumen XPS."
item3: "Gunakan kelas opsi gambar yang relevan seperti [*PngSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PngSaveOptions), [*JpegSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/JpegSaveOptions), [*BmpSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/BmpSaveOptions) , [*TiffSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/TiffSaveOptions) untuk pengaturan tambahan gambar."
item4: "Buat instance Kelas [*image device*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/ImageDevice)."
item5: "Hubungi [*XpsDocument.save*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) untuk menyimpan gambar JPEG yang dikonversi ke objek ImageDevice dan kemudian gunakan ImageDevice untuk menyimpan gambar sebagai JPG."
---

{{<section feature4>}}
---
title: Konversi XPS ke PDF melalui Java.
h3: Kode Java untuk Konversi XPS ke PDF
item1: Proses mengonversi XPS ke dokumen PDF secara terprogram sederhana dengan hasil fidelitas tinggi di antara file input dan output.
item2: "Muat file menggunakan kelas XpsDocument. Inisialisasi objek [*PdfSaveOptions class*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PdfDevice)."
item3: Buat objek PdfDevice untuk rendering dan terakhir simpan dokumen PDF keluaran.
---


