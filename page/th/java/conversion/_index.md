---
translation: true
template: /_templates/_conversion-java.md
title: API การแปลง PDL | Java
url: /java/conversion/
description: แปลง PS, EPS และ XPS เป็น PDF และรูปภาพ รวมถึง BMP, JPG, PNG และ TIFF โดยใช้ไลบรารี Java ด้วยฟังก์ชันการแปลง Aspose.Page PDL
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: แปลง PS, EPS และ XPS
h2: โซลูชัน API ตัวแปลง PS, EPS และ XPS สำหรับ Java
---

{{<section overview>}}
---
p1: "เมื่อใดก็ตามที่จำเป็นต้องแปลงไฟล์ PostScript PS และ Encapsulated PostScript EPS รวมถึงเอกสาร XPS โดยทางโปรแกรม Java API สามารถทำได้อย่างราบรื่นและแปลงไฟล์หลายไฟล์ สำหรับ PS และ EPS นั้น API รองรับตัวดำเนินการ PostScript ระดับ 1-3 และความคิดเห็นส่วนหัวของ EPS ส่วนใหญ่ รวมถึงการแปลงเอกสาร PostScript ที่มีความสอดคล้องสูงสุด ยกเว้นกรณีแบบอักษรบางตัวและ API เกี่ยวข้องกับแบบอักษรเช่น Time New Roman"
p2: "ยิ่งไปกว่านั้น สำหรับการแปลงไฟล์ XPS นั้น API สามารถเพิ่มหรือลบหน้า จัดการกับแคนวาส เส้นทางและองค์ประกอบร่ายมนตร์ สร้างรูปร่างกราฟิกแบบเวกเตอร์ สตริงข้อความ แปลงรายการเค้าร่าง XPS และอื่นๆ"
p3: "โซลูชัน API สำหรับ Java ที่นี่ช่วยให้คุณแปลงไฟล์รูปแบบ PDL เช่น PS, EPS และ XPS โดยทางโปรแกรม แต่คุณอาจพบว่ามีประโยชน์ในการดูและลองใช้ข้ามแพลตฟอร์มที่พัฒนาบน API ดั้งเดิมเหล่านี้"
---

{{<section feature1>}}
---
title: การแปลง PostScript เป็น PDF ผ่าน Java
h3: "รหัส Java เพื่อแปลง PS EPS เป็น PDF"
item1: "ในการแปลงไฟล์ PostScript PS และ Encapsulated PostScript EPS เป็น PDF ผ่าน Java API คุณต้องทำตามขั้นตอนต่อไป:"
item2: "โหลดไฟล์ PS หรือ EPS โดยใช้ [*PsDocument Class*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument)"
item3: "ตั้งค่าตัวเลือกการบันทึก PDF โดยใช้ [*PdfSaveOptions Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfSaveOptions)"
item4: "ใช้ [*FileStream Class*](https://docs.oracle.com/javase/7/docs/api/java/io/FileOutputStream.html) สำหรับเอาต์พุตไฟล์ PDF"
item5: "ใช้ [*PdfDevice Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfDevice) ที่มีวัตถุ FileOutputStream เป็นพารามิเตอร์"
item6: "โทรไปที่ [*PsDocument.Save*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) เพื่อบันทึกเป็น PDF ไฟล์"
---

{{<section feature2>}}
---
title: การแปลง PostScript เป็นรูปภาพผ่าน Java
h3: "โค้ด Java สำหรับการแปลง PostScript เป็นรูปภาพ"
item1: "สำหรับแอพพลิเคชัน PostScript to image converter ของ EPS/PS โค้ด Java ต่อไปนี้ใช้งานได้ดี ดังนั้นให้ทำตามขั้นตอนต่อไป:"
item2: เริ่มต้นสตรีมอินพุตด้วยไฟล์ต้นฉบับ PS
item3: "สร้างวัตถุ [*PsDocument*](https://reference.aspose.com/page/java/com.aspose.eps/psdocument) ที่มีการสร้างสตรีมอินพุต PS เป็นพารามิเตอร์"
item4: "ใช้ [*ImageSaveOptions*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagesaveoptions) เพื่อระบุ AdditionalFontsFolder และ SuppressError เป็นต้น"
item5: "ใช้วัตถุ [*ImageDevice*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagedevice) เพื่อระบุประเภทและขนาดรูปภาพ หากจำเป็น"
item6: บันทึกไฟล์ PS/EPS เป็นและรูปภาพพร้อมตัวเลือกการบันทึกรูปภาพเป็นอาร์เรย์ของอาร์เรย์ไบต์ หนึ่งอาร์เรย์ของไบต์สำหรับหนึ่งหน้าของไฟล์อินพุต
---


{{<section feature3>}}
---
title: แปลง XPS เป็นรูปภาพ JPG, PNG, BMP ผ่าน Java
h3: รหัส Java สำหรับ XPS เป็นการแปลงรูปภาพ
item1: "Java API จัดการรูปแบบ XPS ที่ใช้สำหรับแสดงเค้าโครงหน้า ในทุกสถานการณ์ เมื่อใดก็ตามที่จำเป็นต้องแปลง XPS เป็นรูปภาพ BMP, JPG, PNG และ TIFF โดยทางโปรแกรม โค้ดต่อไปนี้สามารถรวมเข้ากับแอปพลิเคชัน Java ได้อย่างง่ายดาย"
item2: "ใช้ [*XpsDocument class*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument) เพื่อโหลดเอกสาร XPS"
item3: "ใช้คลาสตัวเลือกรูปภาพที่เกี่ยวข้อง เช่น [*PngSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PngSaveOptions), [*JpegSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/JpegSaveOptions), [*BmpSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/BmpSaveOptions) , [*TiffSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/TiffSaveOptions) สำหรับการตั้งค่าเพิ่มเติมของรูปภาพ"
item4: "สร้างอินสแตนซ์คลาส [*อุปกรณ์อิมเมจ*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/ImageDevice)"
item5: "โทร [*XpsDocument.save*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) เพื่อบันทึกภาพ JPEG ที่แปลงแล้วลงในวัตถุ ImageDevice จากนั้นใช้ ImageDevice เพื่อบันทึกภาพเป็น JPG"
---

{{<section feature4>}}
---
title: แปลง XPS เป็น PDF ผ่าน Java
h3: โค้ด Java สำหรับการแปลง XPS เป็น PDF
item1: ขั้นตอนการแปลงเอกสาร XPS เป็น PDF โดยทางโปรแกรมทำได้ง่ายโดยให้ผลลัพธ์ที่มีความเที่ยงตรงสูงระหว่างไฟล์อินพุตและเอาต์พุต
item2: "โหลดไฟล์โดยใช้คลาส XpsDocument เริ่มต้นวัตถุ [*PdfSaveOptions class*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PdfDevice)"
item3: สร้างวัตถุ PdfDevice สำหรับการเรนเดอร์และสุดท้ายบันทึกเอกสาร PDF ที่ส่งออก
---


