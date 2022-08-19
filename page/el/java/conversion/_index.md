---
translation: true
template: /_templates/_conversion-java.md
title: API μετατροπής PDL | Java
url: /java/conversion/
description: Μετατρέψτε PS, EPS και XPS σε PDF και εικόνες, συμπεριλαμβανομένων BMP, JPG, PNG και TIFF χρησιμοποιώντας τη βιβλιοθήκη Java με τη λειτουργία μετατροπής Aspose.Page PDL.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Μετατροπή PS, EPS και XPS
h2: Λύση API μετατροπέα PS, EPS και XPS για Java
---

{{<section overview>}}
---
p1: "Όποτε χρειάζεται να μετατρέψετε αρχεία PostScript PS και Encapsulated PostScript EPS καθώς και έγγραφα XPS μέσω προγραμματισμού, το Java API μπορεί να το κάνει ομαλά και μετατρέπει πολλαπλά αρχεία. Για PS και EPS, το API υποστηρίζει τελεστές PostScript Levels 1-3 και τα περισσότερα σχόλια κεφαλίδας EPS, καθώς και μετασχηματίζει έγγραφα PostScript με μέγιστη συμμόρφωση, με εξαίρεση λίγες περιπτώσεις γραμματοσειρών και το API ασχολείται με γραμματοσειρές όπως το Time New Roman."
p2: "Επιπλέον, για μετασχηματισμό αρχείων XPS, το API μπορεί να προσθέσει ή να αφαιρέσει σελίδες, να ασχοληθεί με καμβάδες, μονοπάτια και στοιχεία γλυφών, να δημιουργήσει σχήματα διανυσματικών γραφικών, συμβολοσειρές κειμένου, να μετατρέψει στοιχεία περιγράμματος XPS και πολλά άλλα."
p3: "Η λύση API για Java εδώ σάς επιτρέπει να μετατρέπετε αρχεία μορφών PDL όπως PS, EPS και XPS μέσω προγραμματισμού, αλλά μπορεί να σας φανεί χρήσιμο να δείτε και να δοκιμάσετε cross-platform που έχουν αναπτυχθεί σε αυτά τα εγγενή API."
---

{{<section feature1>}}
---
title: Μετατροπή PostScript σε PDF μέσω Java.
h3: "Java Code για μετατροπή PS EPS σε PDF"
item1: "Για να μετατρέψετε αρχεία PostScript PS και Encapsulated PostScript EPS σε PDF μέσω Java API, πρέπει να ακολουθήσετε τα ακόλουθα βήματα:"
item2: "Φορτώστε το αρχείο PS ή EPS χρησιμοποιώντας το [*PsDocument Class*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument)."
item3: "Ορίστε τις επιλογές αποθήκευσης PDF χρησιμοποιώντας το [*PdfSaveOptions Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfSaveOptions)."
item4: "Χρησιμοποιήστε το [*FileStream Class*](https://docs.oracle.com/javase/7/docs/api/java/io/FileOutputStream.html) για την έξοδο του αρχείου PDF."
item5: "Χρησιμοποιήστε το [*PdfDevice Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfDevice) έχοντας ως παράμετρο το αντικείμενο FileOutputStream."
item6: "Καλέστε το [*PsDocument.Save*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) για αποθήκευση του αρχείου σε PDF."
---

{{<section feature2>}}
---
title: Μετατροπή PostScript σε εικόνες μέσω Java.
h3: "Κώδικας Java για μετατροπή PostScript σε εικόνες"
item1: "Για οποιαδήποτε εφαρμογή μετατροπής EPS/PS PostScript σε εικόνα, ο ακόλουθος κώδικας Java λειτουργεί καλά, επομένως ακολουθήστε τα ακόλουθα βήματα:"
item2: Εκκινήστε τη ροή εισόδου με το αρχείο πηγής PS.
item3: "Δημιουργία αντικειμένου [*PsDocument*](https://reference.aspose.com/page/java/com.aspose.eps/psdocument) με δημιουργημένη ροή εισόδου PS ως παράμετρο"
item4: "Χρησιμοποιήστε το [*ImageSaveOptions*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagesaveoptions) για να καθορίσετε AdditionalFontsFolder και SuppressError κ.λπ."
item5: "Χρησιμοποιήστε το αντικείμενο [*ImageDevice*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagedevice) για να καθορίσετε έναν τύπο και μέγεθος εικόνας, εάν χρειάζεται."
item6: Αποθήκευση αρχείου PS/EPS ως και εικόνα με επιλογές αποθήκευσης εικόνας ως συστοιχία συστοιχιών byte. Ένας πίνακας byte για μια σελίδα ενός αρχείου εισόδου.
---


{{<section feature3>}}
---
title: Μετατροπή XPS σε Εικόνες JPG, PNG, BMP μέσω Java.
h3: Κώδικας Java για μετατροπή XPS σε εικόνα
item1: "Το Java API προσφέρει μορφή XPS που χρησιμοποιείται για την αναπαράσταση της διάταξης σελίδας. Σε οποιοδήποτε σενάριο, όποτε υπάρχει ανάγκη μετατροπής XPS σε εικόνες BMP, JPG, PNG και TIFF μέσω προγραμματισμού, ο ακόλουθος κώδικας μπορεί εύκολα να ενσωματωθεί στην εφαρμογή Java."
item2: "Χρησιμοποιήστε το [*XpsDocument class*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument) για να φορτώσετε το έγγραφο XPS."
item3: "Χρησιμοποιήστε τη σχετική κατηγορία επιλογών εικόνας, όπως [*PngSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PngSaveOptions), [*JpegSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/JpegSaveOptions), [*BmpSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/BmpSaveOptions) , [*TiffSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/TiffSaveOptions) για πρόσθετες ρυθμίσεις εικόνας."
item4: "Δημιουργήστε την παρουσία κλάσης [*συσκευή εικόνας*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/ImageDevice)."
item5: "Καλέστε το [*XpsDocument.save*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) για να αποθηκεύσετε την εικόνα JPEG που έχει μετατραπεί σε αντικείμενο ImageDevice και στη συνέχεια χρησιμοποιήστε το ImageDevice για να αποθηκεύσετε την εικόνα ως JPG."
---

{{<section feature4>}}
---
title: Μετατροπή XPS σε PDF μέσω Java.
h3: Κώδικας Java για μετατροπή XPS σε PDF
item1: Η διαδικασία μετατροπής εγγράφων XPS σε PDF μέσω προγραμματισμού είναι απλή, έχοντας αποτελέσματα υψηλής πιστότητας μεταξύ των αρχείων εισόδου και εξόδου.
item2: "Φορτώστε το αρχείο χρησιμοποιώντας την κλάση XpsDocument. Αρχικοποιήστε το αντικείμενο [*PdfSaveOptions class*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PdfDevice)."
item3: Δημιουργήστε αντικείμενο PdfDevice για απόδοση και, τέλος, αποθηκεύστε το έγγραφο PDF εξόδου.
---


