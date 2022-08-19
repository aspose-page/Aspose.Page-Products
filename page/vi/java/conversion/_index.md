---
translation: true
template: /_templates/_conversion-java.md
title: API chuyển đổi PDL | Java
url: /java/conversion/
description: Chuyển đổi PS, EPS và XPS sang PDF và Hình ảnh bao gồm BMP, JPG, PNG và TIFF bằng cách sử dụng thư viện Java với chức năng chuyển đổi Aspose.Page PDL.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Chuyển đổi PS, EPS và XPS
h2: Giải pháp API chuyển đổi PS, EPS và XPS cho Java
---

{{<section overview>}}
---
p1: "Bất cứ khi nào có nhu cầu chuyển đổi các tệp PostScript PS và PostScript EPS được đóng gói cũng như các tài liệu XPS theo chương trình, Java API có thể thực hiện điều đó một cách suôn sẻ và chuyển đổi nhiều tệp. Đối với PS và EPS, API hỗ trợ các toán tử PostScript Cấp 1-3 và hầu hết các nhận xét tiêu đề EPS cũng như biến đổi các tài liệu PostScript có sự phù hợp tối đa với ngoại lệ một số phông chữ và giao dịch API như phông chữ Time New Roman."
p2: "Hơn nữa, để chuyển đổi tệp XPS, API có thể thêm hoặc xóa các trang, xử lý các bức tranh sơn dầu, đường dẫn và các phần tử glyphs, tạo hình dạng đồ họa vector, chuỗi văn bản, chuyển đổi các mục phác thảo XPS và hơn thế nữa."
p3: "Giải pháp API cho Java ở đây cho phép bạn chuyển đổi các tệp có định dạng PDL như PS, EPS và XPS theo lập trình, nhưng bạn có thể thấy hữu ích khi xem và thử đa nền tảng được phát triển trên các API gốc này."
---

{{<section feature1>}}
---
title: Chuyển đổi PostScript sang PDF qua Java.
h3: "Mã Java để chuyển đổi PS EPS sang PDF"
item1: "Để chuyển đổi các tệp PostScript PS và PostScript EPS được đóng gói thành PDF thông qua Java API, bạn cần thực hiện các bước tiếp theo:"
item2: "Tải tệp PS hoặc EPS bằng [*PsDocument Class*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument)."
item3: "Đặt các tùy chọn lưu PDF bằng [*PdfSaveOptions Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfSaveOptions)."
item4: "Sử dụng [*FileStream Class*](https://docs.oracle.com/javase/7/docs/api/java/io/FileOutputStream.html) cho tệp PDF đầu ra."
item5: "Sử dụng [*PdfDevice Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfDevice) có đối tượng FileOutputStream làm tham số."
item6: "Gọi [*PsDocument.Save*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) để lưu thành tệp PDF."
---

{{<section feature2>}}
---
title: Chuyển đổi PostScript sang Hình ảnh qua Java.
h3: "Mã Java cho Chuyển đổi PostScript sang Hình ảnh"
item1: "Đối với bất kỳ ứng dụng chuyển đổi EPS / PS PostScript sang hình ảnh nào, mã Java sau đây hoạt động tốt, vì vậy hãy thực hiện các bước tiếp theo:"
item2: Khởi tạo luồng đầu vào bằng tệp nguồn PS.
item3: "Tạo đối tượng [*PsDocument*](https://reference.aspose.com/page/java/com.aspose.eps/psdocument) với luồng đầu vào PS đã tạo làm tham số"
item4: "Sử dụng [*ImageSaveOptions*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagesaveoptions) để chỉ định ExtraFontsFolder và SuppressError, v.v."
item5: "Sử dụng đối tượng [*ImageDevice*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagedevice) để chỉ định loại và kích thước hình ảnh nếu cần."
item6: Lưu tệp PS / EPS dưới dạng và hình ảnh với tùy chọn lưu hình ảnh dưới dạng một mảng các mảng byte. Một mảng byte cho một trang của tệp đầu vào.
---


{{<section feature3>}}
---
title: Chuyển đổi XPS sang Hình ảnh JPG, PNG, BMP qua Java.
h3: Mã Java để chuyển đổi XPS sang hình ảnh
item1: "Java API đề cập đến định dạng XPS được sử dụng để trình bày bố cục trang. Trong bất kỳ trường hợp nào, bất cứ khi nào có nhu cầu chuyển đổi XPS sang hình ảnh BMP, JPG, PNG và TIFF theo lập trình, đoạn mã sau có thể dễ dàng được tích hợp trong ứng dụng Java."
item2: "Sử dụng [*lớp XpsDocument*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument) để tải tài liệu XPS."
item3: "Sử dụng lớp tùy chọn hình ảnh có liên quan như [*PngSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PngSaveOptions), [*JpegSaveOptions*](https: // tham chiếu .aspose.com / page / java / com.aspose.xps.rendering / JpegSaveOptions), [*BmpSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/BmpSaveOptions) , [*TiffSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/TiffSaveOptions) cho các cài đặt bổ sung hình ảnh."
item4: "Tạo phiên bản Lớp [*image device*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/ImageDevice)."
item5: "Gọi [*XpsDocument.save*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) để lưu hình ảnh JPEG đã chuyển đổi vào đối tượng ImageDevice và sau đó sử dụng ImageDevice để lưu hình ảnh dưới dạng JPG."
---

{{<section feature4>}}
---
title: Chuyển đổi XPS sang PDF qua Java.
h3: Mã Java để chuyển đổi XPS sang PDF
item1: Quá trình chuyển đổi tài liệu XPS sang PDF theo chương trình rất đơn giản với kết quả độ trung thực cao giữa các tệp đầu vào và đầu ra.
item2: "Tải tệp bằng lớp XpsDocument. Khởi tạo đối tượng [*PdfSaveOptions class*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PdfDevice)."
item3: Tạo đối tượng PdfDevice để kết xuất và cuối cùng lưu tài liệu PDF đầu ra.
---


