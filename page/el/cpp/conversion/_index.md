---
translation: true
template: /_templates/_conversion-cpp.md
title: API μετατροπής PDL | C++
url: /cpp/conversion/
description: Μετατρέψτε PS, EPS και XPS σε PDF και εικόνες, συμπεριλαμβανομένων BMP, JPG, PNG και TIFF χρησιμοποιώντας τη βιβλιοθήκη C++ με τη λειτουργία μετατροπής Aspose.Page PDL.
family: page
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: Μετατροπή PS, EPS και XPS
h2: Λύση API μετατροπέα PS, EPS και XPS για C++.
---

{{<section overview>}}
---
p1: "Όποτε χρειάζεται να μετατρέψετε αρχεία PostScript PS και Encapsulated PostScript EPS καθώς και έγγραφα XPS μέσω προγραμματισμού, το Java API μπορεί να το κάνει ομαλά και μετατρέπει πολλαπλά αρχεία. Για PS και EPS, το API υποστηρίζει τελεστές PostScript Levels 1-3 και τα περισσότερα σχόλια κεφαλίδας EPS, καθώς και μετασχηματίζει έγγραφα PostScript με μέγιστη συμμόρφωση, με εξαίρεση λίγες περιπτώσεις γραμματοσειρών και το API ασχολείται με γραμματοσειρές όπως το Time New Roman."
p2: "Οι προγραμματιστές μπορούν εύκολα να το χρησιμοποιήσουν για ομαδική επεξεργασία εγγράφων PostScript και XPS, ακόμη και να χειριστούν καμβάδες, μονοπάτια και στοιχεία γλυφών και να χειριστούν σχήματα διανυσματικών γραφικών και συμβολοσειρές κειμένου."
p3: "Η λύση API για Java εδώ σάς επιτρέπει να μετατρέπετε αρχεία μορφών PDL όπως PS, EPS και XPS μέσω προγραμματισμού, αλλά μπορεί να σας φανεί χρήσιμο να δείτε και να δοκιμάσετε cross-platform που έχουν αναπτυχθεί σε αυτά τα εγγενή API. Ακολουθούν μερικά σενάρια μετατροπής όπως EPS σε Εικόνες, EPS σε PDF, PostScript σε PDF, PostScript σε Εικόνες, XPS σε Εικόνες και XPS σε PDF"
---

{{<section feature1>}}
---
title: Μετατροπή EPS σε Εικόνες μέσω C++.
h3: Κωδικός C++ για μετατροπή EPS σε εικόνες
item1: "Η βιβλιοθήκη C++ επιτρέπει τη μετατροπή αρχείων Encapsulated PostScript (EPS) σε εικόνες σε πλατφόρμες Windows και Linux. Η διαδικασία είναι:"
item2: "Χρησιμοποιήστε το FileStream για να δημιουργήσετε τη ροή εισόδου για το αρχείο EPS καθώς και για να δημιουργήσετε αντικείμενο [*PsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.ps_document) με ροή εισόδου ως παράμετρος. Για ρυθμίσεις συγκεκριμένες για τις εικόνες, χρησιμοποιήστε την [*ImageSaveOptions Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_save_options)."
item3: "Καθορίστε τον τύπο και το μέγεθος της εικόνας χρησιμοποιώντας το [*ImageDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_device)."
item4: Αποθηκεύστε το EPS ως εικόνες με επιλογές αποθήκευσης εικόνας σε μια σειρά συστοιχιών byte δημιουργώντας για κάθε πίνακα byte μια νέα ροή εξόδου αρχείου.
---


{{<section feature2>}}
---
title: Μετατροπή PostScript σε PDF μέσω Java.
h3: Κώδικας C++ για μετατροπή PostScript σε PDF
item1: "Η διαδικασία μετατροπής του PostScript σε PDF είναι η ίδια με του EPS σε Εικόνες, με τη διαφορά ότι οι προγραμματιστές θα χρησιμοποιήσουν το [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_save_options) για τον καθορισμό πρόσθετων ρυθμίσεων, όπως την τιμή AdditionalFontsFolder και SuppressError κ.λπ. Επιπλέον, θα χρησιμοποιήσει το [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_device) από τη ροή εξόδου που δημιουργήθηκε."
---

{{<section feature3>}}
---
title: Μετατροπή XPS σε PDF μέσω C++.
h3: Κώδικας C++ για μετατροπή XPS σε PDF
item1: "Το C++ XPS Processing API ασχολείται με τη μετατροπή XPS σε Εικόνες, όπως BMP, JPG, TIFF, PNG και άλλα, καθώς και με τη μετατροπή XPS σε PDF σε συστήματα που βασίζονται σε Windows και Linux. Η διαδικασία μετατροπής XPS σε PDF είναι:"
item2: Καθορίστε τη ροή εξόδου καθώς και τη ροή εισόδου για το έγγραφο εισόδου XPS.
item3: "Μεταβιβάστε την ως παράμετρο στο αντικείμενο [*XpsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.xps_document)."
item4: "Καθορίστε τις συγκεκριμένες επιλογές αποθήκευσης για το PDF, όπως το TextCompression, το ImageCompression και το JpegQualityLevel χρησιμοποιώντας το [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_save_options)."
item5: "Δημιουργήστε μια παρουσία του [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_device) από την προηγούμενη ροή εξόδου που δημιουργήθηκε."
item6: Τέλος, μετατρέψτε το έγγραφο XPS ως PDF με τις επιλογές αποθήκευσης PDF.
---
