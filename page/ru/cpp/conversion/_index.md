---
translation: true
template: /_templates/_conversion-cpp.md
title: API преобразования PDL | С++
url: /cpp/conversion/
description: Преобразование PS, EPS и XPS в PDF и изображения, включая BMP, JPG, PNG и TIFF, с помощью библиотеки C++ с функцией преобразования Aspose.Page PDL.
family: page
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: Преобразование PS, EPS и XPS
h2: Решение API конвертера PS, EPS и XPS для C++.
---

{{<section overview>}}
---
p1: "Всякий раз, когда возникает необходимость программно преобразовать файлы PostScript PS и Encapsulated PostScript EPS, а также документы XPS, API Java может сделать это без проблем и преобразовать несколько файлов. Для PS и EPS API поддерживает операторы PostScript уровней 1-3 и большинство комментариев заголовка EPS, а также преобразует документы PostScript с максимальным соответствием, за исключением нескольких случаев шрифтов, а API работает с такими шрифтами, как Time New Roman."
p2: "Программисты могут легко использовать его для пакетной обработки документов PostScript и XPS, даже для управления холстами, путями и элементами глифов, а также для обработки фигур векторной графики и текстовых строк."
p3: "Предлагаемое API-решение для Java позволяет вам программно преобразовывать файлы таких форматов PDL, как PS, EPS и XPS, но вам может быть полезно увидеть и попробовать кросс-платформенные решения, разработанные на основе этих собственных API-интерфейсов. Вот несколько сценариев преобразования, таких как EPS в изображения, EPS в PDF, PostScript в PDF, PostScript в изображения, XPS в изображения и XPS в PDF."
---

{{<section feature1>}}
---
title: Преобразование EPS в изображения с помощью C++.
h3: Код C++ для преобразования EPS в изображения
item1: "Библиотека C++ позволяет преобразовывать файлы Encapsulated PostScript (EPS) в изображения на платформах Windows и Linux. Процесс:"
item2: "Используйте FileStream для создания входного потока для файла EPS, а также для создания объекта [*PsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.ps_document) с входным потоком как параметр. Для конкретных настроек изображений используйте [*класс ImageSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_save_options)."
item3: "Определите тип и размер изображения, используя [*ImageDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_device)."
item4: Сохраняйте EPS в виде изображений с параметрами сохранения изображений в массив массивов байтов, создавая для каждого массива байтов новый поток вывода файла.
---


{{<section feature2>}}
---
title: Преобразование PostScript в PDF через Java.
h3: Код C++ для преобразования PostScript в PDF
item1: "Процесс преобразования PostScript в PDF такой же, как и преобразования EPS в изображения, за исключением того, что разработчики будут использовать [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_save_options) для определения дополнительных настроек, таких как AdditionalFontsFolder, значение SuppressError и т. д. Кроме того, будет использоваться [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_device) из созданного выходного потока."
---

{{<section feature3>}}
---
title: Конвертируйте XPS в PDF через C++.
h3: Код C++ для преобразования XPS в PDF
item1: "C++ XPS Processing API предназначен для конверсии XPS в изображения, включая BMP, JPG, TIFF, PNG и т. д., а также для преобразования XPS в PDF в системах на базе Windows и Linux. Процесс преобразования XPS в PDF:"
item2: Определите выходной поток, а также определите входной поток для входного документа XPS.
item3: "Передайте его как параметр объекту [*XpsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.xps_document)."
item4: "Укажите специальные параметры сохранения PDF, такие как TextCompression, ImageCompression и JpegQualityLevel, используя [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_save_options)."
item5: "Создайте экземпляр [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_device) из ранее созданного выходного потока."
item6: Наконец, конвертируйте XPS-документ в PDF с помощью параметров сохранения PDF.
---
