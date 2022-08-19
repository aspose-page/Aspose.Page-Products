---
translation: true
template: /_templates/_conversion-java.md
title: API de conversion PDL | Java
url: /java/conversion/
description: Convertissez PS, EPS et XPS en PDF et en images, y compris BMP, JPG, PNG et TIFF à l'aide de la bibliothèque Java avec la fonctionnalité de conversion Aspose.Page PDL.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Convertir PS, EPS et XPS
h2: Solution d'API de conversion PS, EPS et XPS pour Java
---

{{<section overview>}}
---
p1: "Chaque fois qu'il est nécessaire de convertir des fichiers PostScript PS et PostScript EPS encapsulés ainsi que des documents XPS par programmation, l'API Java peut le faire en douceur et convertit plusieurs fichiers. Pour PS et EPS, l'API prend en charge les opérateurs PostScript de niveaux 1 à 3 et la plupart des commentaires d'en-tête EPS et transforme les documents PostScript ayant une conformité maximale à l'exception de quelques cas de polices et l'API traite des polices telles que Time New Roman."
p2: "De plus, pour la transformation de fichiers XPS, l'API peut ajouter ou supprimer des pages, traiter des éléments de canevas, de chemins et de glyphes, créer des formes graphiques vectorielles, des chaînes de texte, convertir des éléments de plan XPS, etc."
p3: "La solution API pour Java ici vous permet de convertir par programme des fichiers de formats PDL tels que PS, EPS et XPS, mais il peut être utile de voir et d'essayer la multiplateforme développée sur ces API natives."
---

{{<section feature1>}}
---
title: Conversion PostScript en PDF via Java.
h3: "Code Java pour convertir PS EPS en PDF"
item1: "Pour convertir des fichiers PostScript PS et Encapsulated PostScript EPS en PDF via l'API Java, vous devez suivre les étapes suivantes :"
item2: "Chargez le fichier PS ou EPS à l'aide de [*PsDocument Class*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument)."
item3: "Définissez les options d'enregistrement PDF à l'aide de [*Classe PdfSaveOptions*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfSaveOptions)."
item4: "Utilisez [*FileStream Class*](https://docs.oracle.com/javase/7/docs/api/java/io/FileOutputStream.html) pour le fichier PDF de sortie."
item5: "Utilisez [*PdfDevice Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfDevice) ayant l'objet FileOutputStream comme paramètre."
item6: "Appelez [*PsDocument.Save*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) pour enregistrer le fichier au format PDF."
---

{{<section feature2>}}
---
title: Conversion PostScript en images via Java.
h3: "Code Java pour la conversion PostScript en images"
item1: "Pour toute application de conversion EPS/PS PostScript vers image, le code Java suivant fonctionne bien, alors suivez les étapes suivantes :"
item2: Initialiser le flux d'entrée avec le fichier source PS.
item3: "Créer un objet [*PsDocument*](https://reference.aspose.com/page/java/com.aspose.eps/psdocument) avec le flux d'entrée PS créé comme paramètre"
item4: "Utilisez [*ImageSaveOptions*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagesaveoptions) pour spécifier AdditionalFontsFolder et SuppressError, etc."
item5: "Utilisez l'objet [*ImageDevice*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagedevice) pour spécifier un type et une taille d'image si nécessaire."
item6: Enregistrer le fichier PS/EPS sous et l'image avec des options d'enregistrement d'image sous la forme d'un tableau de tableaux d'octets. Un tableau d'octets pour une page d'un fichier d'entrée.
---


{{<section feature3>}}
---
title: Convertissez XPS en images JPG, PNG, BMP via Java.
h3: Code Java pour la conversion XPS en image
item1: "L'API Java traite le format XPS utilisé pour représenter la mise en page. Dans n'importe quel scénario, chaque fois qu'il est nécessaire de convertir XPS en images BMP, JPG, PNG et TIFF par programme, le code suivant peut facilement être intégré dans l'application Java."
item2: "Utilisez [*classe XpsDocument*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument) pour charger le document XPS."
item3: "Utilisez la classe d'options d'image appropriée telle que [*PngSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PngSaveOptions), [*JpegSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/JpegSaveOptions), [*BmpSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/BmpSaveOptions) , [*TiffSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/TiffSaveOptions) pour les paramètres d'image supplémentaires."
item4: "Créez l'instance de classe [*image device*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/ImageDevice)."
item5: "Appelez [*XpsDocument.save*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) pour enregistrer l'image JPEG convertie dans l'objet ImageDevice, puis utilisez ImageDevice pour enregistrer l'image au format JPG."
---

{{<section feature4>}}
---
title: Convertir XPS en PDF via Java.
h3: Code Java pour la conversion XPS en PDF
item1: Le processus de conversion de documents XPS en PDF par programme est simple, avec des résultats haute fidélité parmi les fichiers d'entrée et de sortie.
item2: "Chargez le fichier à l'aide de la classe XpsDocument. Initialisez l'objet [*PdfSaveOptions class*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PdfDevice)."
item3: Créez un objet PdfDevice pour le rendu et enregistrez enfin le document PDF de sortie.
---


