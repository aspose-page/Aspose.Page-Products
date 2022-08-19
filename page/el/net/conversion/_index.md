---
translation: true
template: /_templates/_conversion-net.md
title: PDL Conversion API C# | .NET
url: /net/conversion/
description: Μετατρέψτε τα PS, EPS και XPS σε PDF και εικόνες, συμπεριλαμβανομένων BMP, JPG, PNG και TIFF χρησιμοποιώντας τη βιβλιοθήκη .NET με τη λειτουργία μετατροπής Aspose.Page PDL.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Μετατροπή PS, EPS και XPS
h2: Λύση API μετατροπέα PS, EPS και XPS για .NET.
---

{{<section overview>}}
---
p1: "Κάθε φορά που χρειάζεται να μετατρέψετε αρχεία PostScript PS και Encapsulated PostScript EPS καθώς και έγγραφα XPS μέσω προγραμματισμού, το .NET API μπορεί να το κάνει ομαλά και μετατρέπει πολλαπλά αρχεία. Για PS και EPS, το API υποστηρίζει τελεστές PostScript Levels 1-3 και τα περισσότερα σχόλια κεφαλίδας EPS, καθώς και μετασχηματίζει έγγραφα PostScript με μέγιστη συμμόρφωση, με εξαίρεση λίγες περιπτώσεις γραμματοσειρών και το API ασχολείται με γραμματοσειρές όπως το Time New Roman."
p2: "Επιπλέον, για μετασχηματισμό αρχείων XPS, το API μπορεί να προσθέσει ή να αφαιρέσει σελίδες, να ασχοληθεί με καμβάδες, μονοπάτια και στοιχεία γλυφών, να δημιουργήσει σχήματα διανυσματικών γραφικών, συμβολοσειρές κειμένου, να μετατρέψει στοιχεία περιγράμματος XPS και πολλά άλλα."
p3: "Η λύση API για."
---

{{<section feature1>}}
---
title: Μετατροπή PostScript σε PDF μέσω C# .NET.
h3: "Κωδικός C# για μετατροπή PS EPS σε PDF"
item1: "Για να μετατρέψετε αρχεία PostScript PS και Encapsulated PostScript EPS σε PDF μέσω .NET API, πρέπει να ακολουθήσετε τα ακόλουθα βήματα:"
item2: "Φορτώστε το αρχείο PS ή EPS χρησιμοποιώντας το [*PsDocument Class*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/)."
item3: "Ρυθμίστε την αποθήκευση PDF χρησιμοποιώντας το [*PdfSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfsaveoptions/)."
item4: "Χρησιμοποιήστε το [*FileStream Class*](https://docs.microsoft.com/en-us/dotnet/api/system.io.filestream) για την έξοδο του αρχείου PDF."
item5: "[*PdfDevice Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfdevice/) με αρχικοποίηση με αντικείμενο ροής αρχείου PDF εξόδου."
item6: "Καλέστε το [*PsDocument.Save*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/save/) για μετατροπή PDF."
---

{{<section feature2>}}
---
title: Μετατροπή PostScript σε εικόνες μέσω C# .NET.
h3: "Κωδικός C# για μετατροπή PostScript σε εικόνες"
item1: "Για οποιαδήποτε εφαρμογή μετατροπής EPS/PS PostScript σε εικόνα, ο ακόλουθος κώδικας C# λειτουργεί καλά, επομένως ακολουθήστε τα ακόλουθα βήματα:"
item2: Φορτώστε το έγγραφο χρησιμοποιώντας την κλάση PsDocument έχοντας ως παράμετρο τη ροή αρχείου εισόδου.
item3: "Δημιουργήστε το αντικείμενο [*ImageSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/imagesaveoptions/) και αρχικοποιήστε το με τις απαιτούμενες ρυθμίσεις."
item4: Αποθηκεύστε κάθε σελίδα αρχείου εισόδου σε μια εικόνα PNG, JPG, TIFF, BMP κ.λπ.
---

{{<section feature3>}}
---
title: Μετατροπή XPS σε Εικόνες JPG, PNG, BMP μέσω C# .NET.
h3: "Κωδικός C# για μετατροπή XPS σε εικόνα"
item1: "Το .NET API υποστηρίζει επίσης τη μετατροπή XPS σε εικόνες BMP, JPG, PNG, TIFF κ.λπ. και παρέχει XpsDocument Class για λειτουργίες XPS. Για να μετατρέψετε το XPS σε Εικόνα, ακολουθήστε τα ακόλουθα βήματα:"
item2: Φορτώστε το αρχείο XPS από τη ροή.
item3: "Αρχικοποιήστε τις σχετικές επιλογές αποθήκευσης εικόνας, π.χ. για **XPS σε JPG** είναι [*JpegSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/) και για **XPS σε PNG** [*PngSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/). Ακολουθεί λίστα με όλα τα XPS σε Εικόνα [*επιλογές αποθήκευσης*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/)."
item4: Καθορίστε σχετικές ρυθμίσεις όπως SmoothingMode, Resolution και Page Numbers κ.λπ. για απόδοση. Τέλος, επαναλάβετε τα διαμερίσματα των εγγράφων για να τα αποθηκεύσετε σε εικόνες.
---
