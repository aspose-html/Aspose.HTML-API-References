---
title: "DocSaveOptions Κλάση"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.saving.DocSaveOptions κλάση. Συγκεκριμένη κλάση δεδομένων επιλογών. Αναθέτοντας ιδιότητες μπορείτε να διαχειριστείτε χαρακτηριστικά απόδοσης όπως ανάλυση, μέγεθος σελίδας, χρώμα φόντου, καθώς και επιλογές ειδικές για το έγγραφο όπως ενσωμάτωση γραμματοσειρών. Περισσότερες πληροφορίες στο άρθρο τεκμηρίωσης."
type: docs

url: /el/java/com.aspose.html.saving/docsaveoptions/
---
## DocSaveOptions class

Συγκεκριμένη κλάση δεδομένων επιλογών. Αναθέτοντας ιδιότητες, μπορείτε να διαχειριστείτε χαρακτηριστικά απόδοσης όπως ανάλυση, μέγεθος σελίδας, χρώμα φόντου καθώς και ειδικές επιλογές εγγράφου όπως η ενσωμάτωση γραμματοσειρών. Περισσότερες πληροφορίες στη τεκμηρίωση [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#save-options).

```java
public class DocSaveOptions : DocRenderingOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Λαμβάνει ένα αντικείμενο [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) που χρησιμοποιείται για τη διαμόρφωση της επεξεργασίας ιδιοτήτων css. |
[getDocumentFormat]
[setDocumentFormat] Gets or sets the file format of the output document. The default value is DOCX. |
[getFontEmbeddingRule]
[setFontEmbeddingRule] Gets or sets the font embedding rule. The default value is None. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Ορίζει ή λαμβάνει την οριζόντια ανάλυση για εσωτερικές (που χρησιμοποιούνται κατά την επεξεργασία φίλτρων) εικόνες, σε pixel ανά ίντσα. Από προεπιλογή αυτή η ιδιότητα είναι 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Λαμβάνει ένα αντικείμενο ρύθμισης σελίδας που χρησιμοποιείται για τη διαμόρφωση της εξόδου σελίδας. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | Ορίζει ή λαμβάνει την κάθετη ανάλυση για εσωτερικές (που χρησιμοποιούνται κατά την επεξεργασία φίλτρων) εικόνες, σε pixel ανά ίντσα. Από προεπιλογή αυτή η ιδιότητα είναι 300 dpi. |

## Παρατηρήσεις

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.saving;
import System;
...
 // Προετοιμάστε μια διαδρομή προς ένα πηγαίο αρχείο HTML
      String documentPath = Path.Combine(DataDir, "canvas.html");

      // Προετοιμάστε μια διαδρομή για την αποθήκευση του μετατρεπόμενου αρχείου 
      String savePath = Path.Combine(OutputDir, "canvas-output-options.docx");

      // Αρχικοποιήστε ένα έγγραφο HTML από το αρχείο
      using var document = new HTMLDocument(documentPath);

      // Αρχικοποιήστε το DocSaveOptions. Ορίστε το μέγεθος σελίδας 600x400 εικονοστοιχεία και τα περιθώρια
      var options = new DocSaveOptions();
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 400), new Margin(10, 10, 10, 10));

      // Μετατροπή HTML σε DOCX
      Converter.ConvertHTML(document, options, savePath);
```

*OutputDir - custom output folder path.

### Δείτε επίσης

* class [DocRenderingOptions](../../com.aspose.html.rendering.doc/docrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
