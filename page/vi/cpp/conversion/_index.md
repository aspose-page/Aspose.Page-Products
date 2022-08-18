---
translation: true
template: /_templates/_conversion-cpp.md
title: API chuyển đổi PDL | C ++
url: /cpp/conversion/
description: Chuyển đổi PS, EPS và XPS sang PDF và Hình ảnh bao gồm BMP, JPG, PNG và TIFF bằng cách sử dụng thư viện C ++ với chức năng chuyển đổi Aspose.Page PDL.
family: page
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: Chuyển đổi PS, EPS và XPS
h2: Giải pháp API chuyển đổi PS, EPS và XPS cho C ++.
---

{{<section overview>}}
---
p1: "Bất cứ khi nào có nhu cầu chuyển đổi các tệp PostScript PS và PostScript EPS được đóng gói cũng như các tài liệu XPS theo chương trình, Java API có thể thực hiện điều đó một cách suôn sẻ và chuyển đổi nhiều tệp. Đối với PS và EPS, API hỗ trợ các toán tử PostScript Cấp 1-3 và hầu hết các nhận xét tiêu đề EPS cũng như biến đổi các tài liệu PostScript có sự phù hợp tối đa với ngoại lệ một số phông chữ và giao dịch API như phông chữ Time New Roman."
p2: "Các lập trình viên có thể dễ dàng sử dụng nó để xử lý hàng loạt các tài liệu PostScript và XPS, thậm chí thao tác các phần tử canvas, đường dẫn và glyphs cũng như xử lý các hình dạng đồ họa vector và chuỗi văn bản."
p3: "Giải pháp API cho Java ở đây cho phép bạn chuyển đổi các tệp có định dạng PDL như PS, EPS và XPS theo lập trình, nhưng bạn có thể thấy hữu ích khi xem và thử đa nền tảng được phát triển trên các API gốc này. Dưới đây là một số kịch bản chuyển đổi như EPS sang Hình ảnh, EPS sang PDF, PostScript sang PDF, PostScript sang Hình ảnh, XPS sang Hình ảnh và XPS sang PDF"
---

{{<section feature1>}}
---
title: Chuyển đổi EPS sang hình ảnh thông qua C ++.
h3: Mã C ++ để chuyển đổi EPS sang hình ảnh
item1: "Thư viện C ++ cho phép chuyển đổi các tệp PostScript (EPS) được đóng gói thành hình ảnh trên nền tảng Windows và Linux. Quá trình này là:"
item2: "Sử dụng FileStream để tạo luồng đầu vào cho tệp EPS cũng như để tạo đối tượng [*PsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.ps_document) có luồng đầu vào như một tham số. Đối với các cài đặt dành riêng cho Hình ảnh, hãy sử dụng [*ImageSaveOptions Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_save_options)."
item3: "Xác định loại và kích thước hình ảnh bằng [*ImageDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_device)."
item4: Lưu EPS dưới dạng hình ảnh với các tùy chọn lưu hình ảnh vào một mảng các mảng byte tạo cho mỗi mảng byte một luồng đầu ra tệp mới.
---


{{<section feature2>}}
---
title: Chuyển đổi PostScript sang PDF qua Java.
h3: Mã C ++ cho Chuyển đổi PostScript sang PDF
item1: "Quá trình chuyển đổi PostScript sang PDF cũng giống như EPS thành Hình ảnh, ngoại trừ việc các nhà phát triển sẽ sử dụng [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_save_options) để xác định các cài đặt bổ sung như giá trị ExtraFontsFolder và SuppressError, v.v. Hơn nữa, sẽ sử dụng [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_device) từ luồng đầu ra đã tạo."
---

{{<section feature3>}}
---
title: Chuyển đổi XPS sang PDF qua C ++.
h3: Mã C ++ để chuyển đổi XPS sang PDF
item1: "API xử lý XPS của C ++ giải quyết việc chuyển đổi XPS thành Hình ảnh bao gồm BMP, JPG, TIFF, PNG, v.v., cũng như chuyển đổi XPS sang PDF trên các hệ thống chạy Windows và Linux. Quá trình chuyển đổi XPS sang PDF là:"
item2: Xác định luồng đầu ra cũng như xác định luồng đầu vào cho tài liệu XPS đầu vào.
item3: "Chuyển nó dưới dạng tham số cho Đối tượng [*XpsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.xps_document)."
item4: "Chỉ định các tùy chọn lưu cụ thể cho PDF như TextCompression, ImageCompression và JpegQualityLevel bằng [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_save_options)."
item5: "Tạo một bản sao của [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_device) từ luồng đầu ra đã tạo trước đó."
item6: Cuối cùng chuyển đổi tài liệu XPS dưới dạng PDF với các tùy chọn lưu PDF.
---
