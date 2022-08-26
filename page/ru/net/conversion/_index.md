---
translation: true
template: /_templates/_conversion-net.md
title: API преобразования PDL C# | .NET
url: /net/conversion/
description: Преобразование PS, EPS и XPS в PDF и изображения, включая BMP, JPG, PNG и TIFF, с помощью библиотеки .NET с функцией преобразования Aspose.Page PDL.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Преобразование PS, EPS и XPS
h2: PS, EPS и XPS Converter API Решение для .NET.
---

{{<section overview>}}
---
p1: "Всякий раз, когда возникает необходимость преобразовать файлы PostScript PS и Encapsulated PostScript EPS, а также документы XPS программным путем, .NET API может сделать это без проблем и преобразовать несколько файлов. Для PS и EPS API поддерживает операторы PostScript уровней 1-3 и большинство комментариев заголовков EPS, а также преобразует документы PostScript с максимальным соответствием, за исключением нескольких случаев шрифтов, а API работает с такими шрифтами, как Time New Roman."
p2: "Более того, для преобразования XPS-файлов API может добавлять или удалять страницы, работать с холстами, путями и элементами глифов, создавать фигуры векторной графики, текстовые строки, преобразовывать элементы схемы XPS и многое другое."
p3: "Представленное здесь решение API для .NET позволяет программно преобразовывать файлы таких форматов PDL, как PS, EPS и XPS, но вам может быть полезно посмотреть и попробовать кроссплатформенные решения, разработанные на основе этих собственных API."
---

{{<section feature1>}}
---
title: Преобразование PostScript в PDF через C# .NET.
h3: "Код C# для преобразования PS EPS в PDF"
item1: "Чтобы преобразовать файлы PostScript PS и Encapsulated PostScript EPS в PDF через .NET API, вам необходимо выполнить следующие шаги:"
item2: "Загрузите файл PS или EPS, используя [*PsDocument Class*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/)."
item3: "Установите сохранение PDF с помощью [*PdfSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfsaveoptions/)."
item4: "Используйте [*FileStream Class*](https://docs.microsoft.com/en-us/dotnet/api/system.io.filestream) для выходного файла PDF."
item5: "[*Класс PdfDevice*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfdevice/) путем инициализации с выходным объектом файлового потока PDF."
item6: "Вызовите [*PsDocument.Save*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/save/) для преобразования PDF."
---

{{<section feature2>}}
---
title: Преобразование PostScript в изображения через C# .NET.
h3: "Код C# для преобразования PostScript в изображения"
item1: "Для любого приложения конвертера EPS/PS PostScript в изображения хорошо работает следующий код C#, поэтому выполните следующие действия:"
item2: Загрузите документ, используя класс PsDocument, имеющий входной файловый поток в качестве параметра.
item3: "Создайте объект [*ImageSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/imagesaveoptions/) и инициализируйте его с необходимыми настройками."
item4: Сохраните каждую страницу входного файла в изображение PNG, JPG, TIFF, BMP и т. д.
---

{{<section feature3>}}
---
title: Преобразование XPS в изображения JPG, PNG, BMP через C# .NET.
h3: "Код C# для преобразования XPS в изображение"
item1: ".NET API также поддерживает преобразование XPS в изображения BMP, JPG, PNG, TIFF и т. д. и предоставляет класс XpsDocument для операций XPS. Чтобы преобразовать XPS в изображение, выполните следующие действия:"
item2: Загрузите файл XPS из потока.
item3: "Инициализируйте соответствующие параметры сохранения изображения, например, для **XPS в JPG** это [*JpegSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/) а для **XPS в PNG** — [*PngSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/). Вот список всех XPS в образ [*сохранить параметры*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/)."
item4: Определите соответствующие параметры рендеринга, такие как SmoothingMode, Resolution, PageNumbers и т. д. Наконец, пройдитесь по разделам документа, чтобы сохранить их в изображения.
---
