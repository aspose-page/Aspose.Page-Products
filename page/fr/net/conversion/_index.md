---
translation: true
template: /_templates/_conversion-net.md
title: API de conversion PDL C# | .NET
url: /net/conversion/
description: Convertissez PS, EPS et XPS en PDF et en images, y compris BMP, JPG, PNG et TIFF à l'aide de la bibliothèque .NET avec la fonctionnalité de conversion Aspose.Page PDL.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Convertir PS, EPS et XPS
h2: Solution API de conversion PS, EPS et XPS pour .NET.
---

{{<section overview>}}
---
p1: "Chaque fois qu'il est nécessaire de convertir des fichiers PostScript PS et PostScript EPS encapsulés ainsi que des documents XPS par programmation, l'API .NET peut le faire en douceur et convertit plusieurs fichiers. Pour PS et EPS, l'API prend en charge les opérateurs PostScript de niveaux 1 à 3 et la plupart des commentaires d'en-tête EPS et transforme les documents PostScript ayant une conformité maximale à l'exception de quelques cas de polices et l'API traite des polices telles que Time New Roman."
p2: "De plus, pour la transformation de fichiers XPS, l'API peut ajouter ou supprimer des pages, traiter des éléments de canevas, de chemins et de glyphes, créer des formes graphiques vectorielles, des chaînes de texte, convertir des éléments de plan XPS, etc."
p3: "La solution API pour .NET ici vous permet de convertir par programmation des fichiers de formats PDL tels que PS, EPS et XPS, mais il peut être utile de voir et d'essayer la multiplateforme développée sur ces API natives."
---

{{<section feature1>}}
---
title: Conversion PostScript en PDF via C# .NET.
h3: "Code C# pour la conversion PS EPS en PDF"
item1: "Pour convertir des fichiers PostScript PS et Encapsulated PostScript EPS en PDF via l'API .NET, vous devez suivre les étapes suivantes :"
item2: "Chargez le fichier PS ou EPS à l'aide de [*PsDocument Class*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/)."
item3: "Définissez l'enregistrement PDF à l'aide de [*Classe PdfSaveOptions*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfsaveoptions/)."
item4: "Utilisez [*FileStream Class*](https://docs.microsoft.com/en-us/dotnet/api/system.io.filestream) pour le fichier PDF de sortie."
item5: "[*PdfDevice Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfdevice/) en initialisant avec l'objet filestream PDF de sortie."
item6: "Appelez [*PsDocument.Save*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/save/) pour la conversion PDF."
---

{{<section feature2>}}
---
title: Conversion PostScript en Images via C# .NET.
h3: "Code C# pour la conversion PostScript en images"
item1: "Pour toute application de conversion EPS/PS PostScript en image, le code C# suivant fonctionne bien, alors suivez les étapes suivantes :"
item2: Chargez le document à l'aide de la classe PsDocument ayant le flux de fichier d'entrée comme paramètre.
item3: "Créez l'objet [*ImageSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/imagesaveoptions/) et initialisez-le avec les paramètres requis."
item4: Enregistrez chaque page de fichier d'entrée dans une image PNG, JPG, TIFF, BMP, etc.
---

{{<section feature3>}}
---
title: Convertissez XPS en images JPG, PNG, BMP via C# .NET.
h3: "Code C# pour la conversion XPS en image"
item1: "L'API .NET prend également en charge la conversion XPS en images BMP, JPG, PNG, TIFF, etc., et fournit la classe XpsDocument pour les opérations XPS. Pour convertir XPS en image, procédez comme suit :"
item2: Chargez le fichier XPS à partir du flux.
item3: "Initialisez les options d'enregistrement d'image pertinentes, par exemple pour **XPS vers JPG**, il s'agit de [*JpegSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/) et pour **XPS vers PNG** ses [*PngSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/). Voici la liste de tous les XPS vers Image [*options de sauvegarde*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/)."
item4: Définissez les paramètres pertinents tels que SmoothingMode, Resolution et PageNumbers, etc. pour le rendu. Enfin, parcourez les partitions de documents pour les enregistrer dans des images.
---
