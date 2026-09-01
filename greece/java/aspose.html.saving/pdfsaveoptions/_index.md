---
title: "PdfSaveOptions Κλάση"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.saving.PdfSaveOptions κλάση. Η συγκεκριμένη κλάση δεδομένων παρέχει λίγες ιδιότητες για τη διαχείριση του αποτελέσματος της μετατροπής. Για παράδειγμα PageSetup καθορίζει τα χαρακτηριστικά της σελίδας. Ανατρέξτε στο άρθρο τεκμηρίωσης."
type: docs

url: /el/java/com.aspose.html.saving/pdfsaveoptions/
---
## PdfSaveOptions class

Η συγκεκριμένη κλάση δεδομένων παρέχει λίγες ιδιότητες για τη διαχείριση του αποτελέσματος της μετατροπής. Για παράδειγμα [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) καθορίζει τα χαρακτηριστικά της σελίδας. Ανατρέξτε στην τεκμηρίωση [άρθρο](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions).

```java
public class PdfSaveOptions : PdfRenderingOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Λαμβάνει ένα αντικείμενο [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) που χρησιμοποιείται για τη διαμόρφωση της επεξεργασίας ιδιοτήτων css. |
| [getDocumentInfo](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/documentinfo/) Περιέχει πληροφορίες για το έγγραφο PDF εξόδου. |
[getEncryption]
[setEncryption] Gets or sets a encryption details. If not set, then no encryption will be performed. |
[getFormFieldBehaviour]
[setFormFieldBehaviour] Specifies the behavior of form fields in the output PDF document. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Ορίζει ή λαμβάνει την οριζόντια ανάλυση για εσωτερικές (που χρησιμοποιούνται κατά την επεξεργασία φίλτρων) εικόνες, σε pixel ανά ίντσα. Από προεπιλογή αυτή η ιδιότητα είναι 300 dpi. |
[getIsTaggedPdf]
[setIsTaggedPdf] Creates a tag structure if `true`. |
[getJpegQuality]
[setJpegQuality] Specifies the quality of JPEG compression for images (if JPEG compression is used). Default is 95. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Λαμβάνει ένα αντικείμενο ρύθμισης σελίδας που χρησιμοποιείται για τη διαμόρφωση της εξόδου σελίδας. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | Ορίζει ή λαμβάνει την κάθετη ανάλυση για εσωτερικές (που χρησιμοποιούνται κατά την επεξεργασία φίλτρων) εικόνες, σε pixel ανά ίντσα. Από προεπιλογή αυτή η ιδιότητα είναι 300 dpi. |

## Παρατηρήσεις

Μπορείτε να βρείτε πλήρη παραδείγματα και αρχεία δεδομένων στο [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
...
 	 // Προετοιμάστε μια διαδρομή προς ένα πηγαίο αρχείο HTML
      String documentPath = Path.Combine(DataDir, "drawing.html");

      // Προετοιμάστε μια διαδρομή για την αποθήκευση του μετατρεπόμενου αρχείου
      String savePath = Path.Combine(OutputDir, "drawing-options.pdf");

      // Αρχικοποιήστε ένα έγγραφο HTML από το αρχείο
      using var document = new HTMLDocument(documentPath);

      // Αρχικοποιήστε το PdfSaveOptions. Ορίστε το μέγεθος σελίδας 600x300 εικονοστοιχεία, περιθώρια, 
      // αναλύσεις και αλλάξτε το χρώμα φόντου σε AliceBlue 
      var options = new PdfSaveOptions()
      {         
        HorizontalResolution = 200,
        VerticalResolution = 200,
        BackgroundColor = Color.AliceBlue,
        JpegQuality = 100
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 300), new Margin(20, 10, 10, 10));      

      // Μετατρέψτε HTML σε PDF
      Converter.ConvertHTML(document, options, savePath);
```

### Δείτε επίσης

* class [PdfRenderingOptions](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
