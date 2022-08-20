---
translation: true
template: /_templates/_conversion-net.md
title: API chuyển đổi PDL C# | .NET
url: /net/conversion/
description: Chuyển đổi PS, EPS và XPS sang PDF và Hình ảnh bao gồm BMP, JPG, PNG và TIFF bằng cách sử dụng thư viện .NET với chức năng chuyển đổi Aspose.Page PDL.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Chuyển đổi PS, EPS và XPS
h2: Giải pháp API chuyển đổi PS, EPS và XPS cho .NET.
---

{{<section overview>}}
---
p1: "Bất cứ khi nào cần chuyển đổi các tệp PostScript PS và PostScript EPS được đóng gói cũng như các tài liệu XPS theo chương trình, .NET API có thể thực hiện điều đó một cách suôn sẻ và chuyển đổi nhiều tệp. Đối với PS và EPS, API hỗ trợ các toán tử PostScript Cấp 1-3 và hầu hết các nhận xét tiêu đề EPS cũng như biến đổi các tài liệu PostScript có sự phù hợp tối đa với ngoại lệ một số phông chữ và giao dịch API như phông chữ Time New Roman."
p2: "Hơn nữa, để chuyển đổi tệp XPS, API có thể thêm hoặc xóa các trang, xử lý các bức tranh sơn dầu, đường dẫn và các phần tử glyphs, tạo hình dạng đồ họa vector, chuỗi văn bản, chuyển đổi các mục phác thảo XPS và hơn thế nữa."
p3: "Giải pháp API cho .NET ở đây cho phép bạn chuyển đổi các tệp có định dạng PDL như PS, EPS và XPS theo lập trình, nhưng bạn có thể thấy hữu ích khi xem và thử đa nền tảng được phát triển trên các API gốc này."
---

{{<section feature1>}}
---
title: "Chuyển đổi PostScript sang PDF qua C# .NET."
h3: "Mã C# cho PS EPS chuyển đổi sang PDF"
item1: "Để chuyển đổi các tệp PostScript PS và PostScript EPS được đóng gói sang PDF thông qua .NET API, bạn cần thực hiện các bước tiếp theo:"
item2: "Tải tệp PS hoặc EPS bằng [*PsDocument Class*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/)."
item3: "Đặt lưu PDF bằng [*PdfSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfsaveoptions/)."
item4: "Sử dụng [*FileStream Class*](https://docs.microsoft.com/en-us/dotnet/api/system.io.filestream) cho tệp PDF đầu ra."
item5: "[*PdfDevice Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfdevice/) bằng cách khởi tạo với đối tượng đầu ra PDF filestream."
item6: "Gọi [*PsDocument.Save*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/save/) để chuyển đổi PDF."
---

{{<section feature2>}}
---
title: "Chuyển đổi PostScript sang Hình ảnh qua C# .NET."
h3: "Mã C# cho Chuyển đổi PostScript sang Hình ảnh"
item1: "Đối với bất kỳ ứng dụng chuyển đổi EPS / PS PostScript sang hình ảnh nào, mã C# sau hoạt động tốt, vì vậy hãy thực hiện các bước tiếp theo:"
item2: Tải tài liệu bằng cách sử dụng lớp PsDocument có luồng tệp đầu vào dưới dạng tham số.
item3: "Tạo đối tượng [*ImageSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/imagesaveoptions/) và khởi tạo nó với các cài đặt cần thiết."
item4: Lưu từng trang tệp đầu vào thành hình ảnh PNG, JPG, TIFF, BMP, v.v.
---

{{<section feature3>}}
---
title: Chuyển đổi XPS sang Hình ảnh JPG, PNG, BMP thông qua C# .NET.'
h3: "Mã C# để chuyển đổi XPS sang hình ảnh"
item1: ".NET API cũng hỗ trợ Chuyển đổi XPS sang Hình ảnh BMP, JPG, PNG, TIFF, v.v. và cung cấp Lớp XpsDocument cho các hoạt động XPS. Để chuyển đổi XPS thành Hình ảnh, hãy thực hiện các bước tiếp theo:"
item2: Tải tệp XPS từ luồng.
item3: "Khởi tạo các tùy chọn lưu hình ảnh có liên quan, ví dụ: cho ** XPS sang JPG ** nó là [*JpegSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/) và cho ** XPS thành PNG ** [*PngSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/)của nó. Đây là danh sách tất cả XPS sang Hình ảnh [*tùy chọn lưu*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/)."
item4: Xác định các cài đặt có liên quan như SmoothingMode, Độ phân giải và Số trang, v.v. để kết xuất. Cuối cùng, lặp qua các phân vùng tài liệu để lưu chúng thành hình ảnh.
---
