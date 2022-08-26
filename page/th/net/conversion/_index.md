---
translation: true
template: /_templates/_conversion-net.md
title: API การแปลง PDL C# | .NET
url: /net/conversion/
description: แปลง PS, EPS และ XPS เป็น PDF และรูปภาพ รวมถึง BMP, JPG, PNG และ TIFF โดยใช้ไลบรารี .NET ด้วยฟังก์ชันการแปลง Aspose.Page PDL
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: แปลง PS, EPS และ XPS
h2: โซลูชัน API ตัวแปลง PS, EPS และ XPS สำหรับ .NET
---

{{<section overview>}}
---
p1: "เมื่อใดก็ตามที่จำเป็นต้องแปลงไฟล์ PostScript PS และ Encapsulated PostScript EPS ตลอดจนเอกสาร XPS โดยทางโปรแกรม .NET API สามารถทำได้อย่างราบรื่นและแปลงไฟล์หลายไฟล์ สำหรับ PS และ EPS นั้น API รองรับตัวดำเนินการ PostScript ระดับ 1-3 และความคิดเห็นส่วนหัวของ EPS ส่วนใหญ่ รวมถึงการแปลงเอกสาร PostScript ที่มีความสอดคล้องสูงสุด ยกเว้นกรณีแบบอักษรบางตัวและ API เกี่ยวข้องกับแบบอักษรเช่น Time New Roman"
p2: "นอกจากนี้ สำหรับการแปลงไฟล์ XPS นั้น API สามารถเพิ่มหรือลบหน้า จัดการกับผืนผ้าใบ เส้นทางและองค์ประกอบร่ายมนตร์ สร้างรูปร่างกราฟิกแบบเวกเตอร์ สตริงข้อความ แปลงรายการเค้าร่าง XPS และอื่นๆ"
p3: "โซลูชัน API สำหรับ .NET ที่นี่ให้คุณแปลงไฟล์รูปแบบ PDL เช่น PS, EPS และ XPS โดยทางโปรแกรม แต่คุณอาจพบว่ามีประโยชน์ในการดูและลองใช้ข้ามแพลตฟอร์มที่พัฒนาบน API ดั้งเดิมเหล่านี้"
---

{{<section feature1>}}
---
title: การแปลง PostScript เป็น PDF ผ่าน C# .NET
h3: "รหัส C# สำหรับการแปลง PS EPS เป็น PDF"
item1: "ในการแปลงไฟล์ PostScript PS และ Encapsulated PostScript EPS เป็น PDF ผ่าน .NET API คุณต้องทำตามขั้นตอนต่อไป:"
item2: "โหลดไฟล์ PS หรือ EPS โดยใช้ [*PsDocument Class*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/)"
item3: "ตั้งค่าการบันทึก PDF โดยใช้ [*PdfSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfsaveoptions/)"
item4: "ใช้ [*FileStream Class*](https://docs.microsoft.com/en-us/dotnet/api/system.io.filestream) สำหรับเอาต์พุตไฟล์ PDF"
item5: "[*PdfDevice Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfdevice/) โดยเริ่มต้นด้วยออบเจกต์ไฟล์สตรีม PDF เอาต์พุต"
item6: "โทร [*PsDocument.Save*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/save/) เพื่อแปลงไฟล์ PDF"
---

{{<section feature2>}}
---
title: การแปลง PostScript เป็นรูปภาพผ่าน C# .NET
h3: "รหัส C# สำหรับการแปลง PostScript เป็นรูปภาพ"
item1: "สำหรับโปรแกรม PostScript to image converter ของ EPS/PS โค้ด C# ต่อไปนี้ใช้งานได้ดี ดังนั้นให้ทำตามขั้นตอนต่อไป:"
item2: โหลดเอกสารโดยใช้คลาส PsDocument ที่มีสตรีมไฟล์อินพุตเป็นพารามิเตอร์
item3: "สร้าง [*ImageSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/imagesaveoptions/) ออบเจ็กต์และเริ่มต้นใช้งานด้วยการตั้งค่าที่จำเป็น"
item4: บันทึกแต่ละหน้าไฟล์อินพุตเป็นรูปภาพ PNG, JPG, TIFF, BMP เป็นต้น
---

{{<section feature3>}}
---
title: แปลง XPS เป็นรูปภาพ JPG, PNG, BMP ผ่าน C# .NET
h3: "รหัส C# สำหรับ XPS เป็นการแปลงรูปภาพ"
item1: ".NET API ยังรองรับการแปลง XPS เป็นรูปภาพ BMP, JPG, PNG, TIFF เป็นต้น และให้บริการ XpsDocument Class สำหรับการดำเนินการ XPS ในการแปลง XPS เป็น Image ให้ทำตามขั้นตอนต่อไปนี้:"
item2: โหลดไฟล์ XPS จากสตรีม
item3: "เริ่มต้นตัวเลือกการบันทึกรูปภาพที่เกี่ยวข้อง เช่น **XPS เป็น JPG** คือ [*JpegSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/) และสำหรับ **XPS เป็น PNG** [*PngSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/) นี่คือรายการของ XPS เป็นอิมเมจทั้งหมด [*บันทึกตัวเลือก*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/)"
item4: กำหนดการตั้งค่าที่เกี่ยวข้อง เช่น SmoothingMode, Resolution และ PageNumbers เป็นต้น สำหรับการแสดงผล ในที่สุดก็วนซ้ำผ่านพาร์ติชั่นเอกสารเพื่อบันทึกลงในรูปภาพ
---
