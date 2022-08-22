---
translation: true
template: /_templates/_conversion-cpp.md
title: API การแปลง PDL | C++
url: /cpp/conversion/
description: แปลง PS, EPS และ XPS เป็น PDF และรูปภาพ รวมถึง BMP, JPG, PNG และ TIFF โดยใช้ไลบรารี C++ ด้วยฟังก์ชันการแปลง Aspose.Page PDL
family: page
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: แปลง PS, EPS และ XPS
h2: โซลูชัน API ตัวแปลง PS, EPS และ XPS สำหรับ C++
---

{{<section overview>}}
---
p1: "เมื่อใดก็ตามที่จำเป็นต้องแปลงไฟล์ PostScript PS และ Encapsulated PostScript EPS ตลอดจนเอกสาร XPS โดยทางโปรแกรม Java API สามารถทำได้อย่างราบรื่นและแปลงไฟล์หลายไฟล์ สำหรับ PS และ EPS นั้น API รองรับตัวดำเนินการ PostScript ระดับ 1-3 และความคิดเห็นส่วนหัวของ EPS ส่วนใหญ่ รวมถึงการแปลงเอกสาร PostScript ที่มีความสอดคล้องสูงสุด ยกเว้นกรณีแบบอักษรบางตัวและ API เกี่ยวข้องกับแบบอักษรเช่น Time New Roman"
p2: "โปรแกรมเมอร์สามารถใช้มันสำหรับการประมวลผลแบบกลุ่มของเอกสาร PostScript และ XPS ได้อย่างง่ายดาย แม้กระทั่งจัดการผืนผ้าใบ เส้นทาง และองค์ประกอบร่ายมนตร์ และจัดการรูปร่างกราฟิกแบบเวกเตอร์และสตริงข้อความ"
p3: "โซลูชัน API สำหรับ Java ที่นี่ช่วยให้คุณแปลงไฟล์ในรูปแบบ PDL เช่น PS, EPS และ XPS โดยทางโปรแกรม แต่คุณอาจพบว่ามีประโยชน์ในการดูและลองใช้ข้ามแพลตฟอร์มที่พัฒนาบน API ดั้งเดิมเหล่านี้ ต่อไปนี้เป็นบางสถานการณ์ของการแปลง เช่น EPS เป็นรูปภาพ, EPS เป็น PDF, PostScript เป็น PDF, PostScript เป็นรูปภาพ, XPS เป็นรูปภาพ และ XPS เป็น PDF"
---

{{<section feature1>}}
---
title: แปลง EPS เป็นรูปภาพผ่าน C++
h3: รหัส C++ สำหรับการแปลง EPS เป็นรูปภาพ
item1: "ไลบรารี C++ อนุญาตให้แปลงไฟล์ Encapsulated PostScript (EPS) เป็นรูปภาพบนแพลตฟอร์ม Windows และ Linux กระบวนการคือ:"
item2: "ใช้ FileStream เพื่อสร้างสตรีมอินพุตสำหรับไฟล์ EPS รวมถึงสร้างวัตถุ [*PsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.ps_document) ที่มีอินพุตสตรีม เป็นพารามิเตอร์ สำหรับการตั้งค่าเฉพาะรูปภาพ ให้ใช้ [*ImageSaveOptions Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_save_options)"
item3: "กำหนดประเภทและขนาดของรูปภาพโดยใช้ [*ImageDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_device)"
item4: บันทึก EPS เป็นรูปภาพพร้อมตัวเลือกการบันทึกรูปภาพไปยังอาร์เรย์ของอาร์เรย์ไบต์ที่สร้างสตรีมเอาต์พุตไฟล์ใหม่ให้กับอาร์เรย์ทุกไบต์
---


{{<section feature2>}}
---
title: การแปลง PostScript เป็น PDF ผ่าน Java
h3: โค้ด C++ สำหรับการแปลง PostScript เป็น PDF
item1: "ขั้นตอนการแปลง PostScript เป็น PDF จะเหมือนกับ EPS เป็น Images ยกเว้นนักพัฒนาจะใช้ [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_save_options) เพื่อกำหนดการตั้งค่าเพิ่มเติม เช่น ค่า AdditionalFontsFolder และ SuppressError เป็นต้น นอกจากนี้ จะใช้ [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_device) จากสตรีมเอาต์พุตที่สร้างขึ้น"
---

{{<section feature3>}}
---
title: แปลง XPS เป็น PDF ผ่าน C++
h3: โค้ด C++ สำหรับการแปลง XPS เป็น PDF
item1: "API การประมวลผล C++ XPS เกี่ยวข้องกับการแปลง XPS เป็นรูปภาพ รวมถึง BMP, JPG, TIFF, PNG และอื่นๆ ตลอดจนการแปลง XPS เป็น PDF บนระบบที่ใช้ Windows และ Linux ขั้นตอนการแปลง XPS เป็น PDF คือ:"
item2: กำหนดกระแสข้อมูลขาออกและกำหนดกระแสข้อมูลขาเข้าสำหรับเอกสาร XPS อินพุต
item3: "ส่งผ่านเป็นพารามิเตอร์ไปยังวัตถุ [*XpsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.xps_document)"
item4: "ระบุตัวเลือกการบันทึกเฉพาะ PDF เช่น TextCompression, ImageCompression และ JpegQualityLevel โดยใช้ [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_save_options)"
item5: "สร้างอินสแตนซ์ของ [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_device) จากสตรีมเอาต์พุตที่สร้างก่อนหน้า"
item6: สุดท้ายแปลงเอกสาร XPS เป็น PDF ด้วยตัวเลือกการบันทึก PDF
---
