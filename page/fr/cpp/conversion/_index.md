---
translation: true
template: /_templates/_conversion-cpp.md
title: API de conversion PDL | C++
url: /cpp/conversion/
description: Convertissez PS, EPS et XPS en PDF et en images, y compris BMP, JPG, PNG et TIFF à l'aide de la bibliothèque C++ avec la fonctionnalité de conversion Aspose.Page PDL.
family: page
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: Convertir PS, EPS et XPS
h2: Solution d'API de conversion PS, EPS et XPS pour C++.
---

{{<section overview>}}
---
p1: "Chaque fois qu'il est nécessaire de convertir des fichiers PostScript PS et PostScript EPS encapsulés ainsi que des documents XPS par programmation, l'API Java peut le faire en douceur et convertit plusieurs fichiers. Pour PS et EPS, l'API prend en charge les opérateurs PostScript de niveaux 1 à 3 et la plupart des commentaires d'en-tête EPS et transforme les documents PostScript ayant une conformité maximale à l'exception de quelques cas de polices et l'API traite des polices telles que Time New Roman."
p2: "Les programmeurs peuvent facilement l'utiliser pour le traitement par lots de documents PostScript et XPS, même manipuler des canevas, des chemins et des éléments de glyphes et gérer des formes graphiques vectorielles et des chaînes de texte."
p3: "La solution API pour Java ici vous permet de convertir par programme des fichiers de formats PDL tels que PS, EPS et XPS, mais il peut être utile de voir et d'essayer la multiplateforme développée sur ces API natives. Voici quelques scénarios de conversion tels que EPS en images, EPS en PDF, PostScript en PDF, PostScript en images, XPS en images et XPS en PDF"
---

{{<section feature1>}}
---
title: Convertir EPS en images via C++.
h3: Code C++ pour la conversion EPS en images
item1: "La bibliothèque C++ permet de convertir des fichiers PostScript Encapsulé (EPS) en images sur les plates-formes Windows et Linux. Le processus est :"
item2: "Utilisez FileStream pour créer le flux d'entrée pour le fichier EPS ainsi que pour créer un objet [*PsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.ps_document) ayant un flux d'entrée comme paramètre. Pour les paramètres spécifiques aux images, utilisez la [*classe ImageSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_save_options)."
item3: "Définissez le type et la taille de l'image à l'aide de [*ImageDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_device)."
item4: Enregistrez EPS sous forme d'images avec des options d'enregistrement d'image dans un tableau de tableaux d'octets en créant pour chaque tableau d'octets un nouveau flux de sortie de fichier.
---


{{<section feature2>}}
---
title: Conversion PostScript en PDF via Java.
h3: Code C++ pour la conversion PostScript en PDF
item1: "Le processus de conversion de PostScript en PDF est le même que celui d'EPS en Images, sauf que les développeurs utiliseront [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_save_options) pour définir des paramètres supplémentaires tels que AdditionalFontsFolder et la valeur SuppressError, etc.  De plus, utilisera [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_device) du flux de sortie créé."
---

{{<section feature3>}}
---
title: Convertissez XPS en PDF via C++.
h3: Code C++ pour la conversion XPS en PDF
item1: "L'API de traitement C++ XPS traite de la conversion de XPS en images, y compris BMP, JPG, TIFF, PNG, etc., ainsi que de la conversion XPS en PDF sur les systèmes Windows et Linux. Le processus de conversion de XPS en PDF est :"
item2: Définissez le flux de sortie ainsi que le flux d'entrée pour le document XPS d'entrée.
item3: "Passez-le en tant que paramètre à l'objet [*XpsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.xps_document)."
item4: "Spécifiez les options d'enregistrement spécifiques au PDF telles que TextCompression, ImageCompression et JpegQualityLevel à l'aide de [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_save_options)."
item5: "Créez une instance de [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_device) à partir du flux de sortie créé précédemment."
item6: Enfin, convertissez le document XPS en PDF avec les options d'enregistrement PDF.
---
