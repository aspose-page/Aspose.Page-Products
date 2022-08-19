---
translation: true
template: /_templates/_conversion-java.md
title: API для преобразования PDL | Java
url: /java/conversion/
description: Преобразование PS, EPS и XPS в PDF и изображения, включая BMP, JPG, PNG и TIFF, с помощью библиотеки Java с функцией преобразования Aspose.Page PDL.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Конвертировать PS, EPS и XPS
h2: Решение API конвертера PS, EPS и XPS для Java
---

{{<section overview>}}
---
p1: "Всякий раз, когда возникает необходимость программно конвертировать файлы PostScript PS и Encapsulated PostScript EPS, а также документы XPS, API Java может сделать это без проблем и преобразовать несколько файлов. Для PS и EPS API поддерживает операторы PostScript уровней 1-3 и большинство комментариев заголовков EPS, а также преобразует документы PostScript с максимальным соответствием, за исключением нескольких случаев шрифтов, а API работает с такими шрифтами, как Time New Roman."
p2: "Более того, для преобразования XPS-файлов API может добавлять или удалять страницы, работать с холстами, путями и элементами глифов, создавать фигуры векторной графики, текстовые строки, конвертироватьь элементы схемы XPS и многое другое."
p3: "Предлагаемое API-решение для Java позволяет вам программно преобразовывать файлы таких форматов PDL, как PS, EPS и XPS, но вам может быть полезно увидеть и попробовать кросс-платформенные решения, разработанные на основе этих собственных API-интерфейсов."
---

{{<section feature1>}}
---
title: Конвертировать PostScript в PDF через Java.
h3: "Код Java для преобразования PS EPS в PDF"
item1: "Чтобы преобразовать файлы PostScript PS и Encapsulated PostScript EPS в PDF через Java API, вам необходимо выполнить следующие шаги:"
item2: "Загрузите файл PS или EPS, используя [*PsDocument Class*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument)."
item3: "Установите параметры сохранения PDF с помощью [*PdfSaveOptions Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfSaveOptions)."
item4: "Используйте [*FileStream Class*](https://docs.oracle.com/javase/7/docs/api/java/io/FileOutputStream.html) для выходного файла PDF."
item5: "Используйте [*PdfDevice Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfDevice) с объектом FileOutputStream в качестве параметра."
item6: "Вызовите [*PsDocument.Save*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) для сохранения в PDF файл."
---

{{<section feature2>}}
---
title: Конвертировать PostScript в изображения через Java.
h3: "Код Java для преобразования PostScript в изображения"
item1: "Для любого приложения конвертера EPS/PS PostScript в изображения хорошо работает следующий код Java, поэтому выполните следующие действия:"
item2: Инициализируйте входной поток исходным файлом PS.
item3: "Создайте объект [*PsDocument*](https://reference.aspose.com/page/java/com.aspose.eps/psdocument) с созданным входным потоком PS в качестве параметра"
item4: "Используйте [*ImageSaveOptions*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagesaveoptions), чтобы указать AdditionalFontsFolder и SuppressError и т. д."
item5: "Используйте объект [*ImageDevice*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagedevice) для указания типа и размера изображения, если это необходимо."
item6: Сохранить файл PS/EPS как и изображение с параметрами сохранения изображения в виде массива массивов байтов. Один массив байтов для одной страницы входного файла.
---


{{<section feature3>}}
---
title: Конвертировать XPS в изображения JPG, PNG, BMP через Java.
h3: Код Java для преобразования XPS в изображение
item1: "Java API имеет дело с форматом XPS, который используется для представления макета страницы. В любом случае, когда возникает необходимость программно преобразовать XPS в изображения BMP, JPG, PNG и TIFF, следующий код можно легко интегрировать в приложение Java."
item2: "Используйте [*класс XpsDocument*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument) для загрузки документа XPS."
item3: "Используйте соответствующий класс параметров изображения, например [*PngSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PngSaveOptions), [*JpegSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/JpegSaveOptions), [*BmpSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/BmpSaveOptions) , [*TiffSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/TiffSaveOptions) для дополнительных настроек изображения."
item4: "Создайте экземпляр класса [*устройство изображения*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/ImageDevice)."
item5: "Вызовите [*XpsDocument.save*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-), чтобы сохранить преобразованное изображение JPEG в объект ImageDevice, а затем использовать ImageDevice для сохранения изображения в формате JPG."
---

{{<section feature4>}}
---
title: Конвертируйте XPS в PDF через Java.
h3: Код Java для преобразования XPS в PDF
item1: Процесс конвертации документов XPS в PDF программным путем прост и обеспечивает высокую точность результатов среди входных и выходных файлов.
item2: "Загрузите файл с помощью класса XpsDocument. Инициализировать объект [*PdfSaveOptions class*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PdfDevice)."
item3: Создайте объект PdfDevice для рендеринга и, наконец, сохраните выходной PDF-документ.
---


