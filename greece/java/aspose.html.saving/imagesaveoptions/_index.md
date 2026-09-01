---
title: "ImageSaveOptions Κλάση"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.saving.ImageSaveOptions κλάση. Συγκεκριμένη κλάση δεδομένων επιλογών. Παρέχει ιδιότητες για τη διαχείριση της ανάλυσης, εξομάλυνσης, ποιότητας, μορφής του αποτελέσματος εικόνας, καθώς και ρυθμίσεων σελίδας κ.λπ. Περισσότερες πληροφορίες μπορείτε να βρείτε στο άρθρο τεκμηρίωσης."
type: docs

url: /el/java/com.aspose.html.saving/imagesaveoptions/
---
## ImageSaveOptions class

Συγκεκριμένη κλάση δεδομένων επιλογών. Παρέχει ιδιότητες για τη διαχείριση της ανάλυσης του αποτελέσματος εικόνας, της ποιότητας εξομάλυνσης, της μορφής καθώς και των ρυθμίσεων σελίδας κ.ά. Περισσότερες πληροφορίες μπορείτε να βρείτε στην τεκμηρίωση [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#save-options).

```java
public class ImageSaveOptions : ImageRenderingOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `ImageSaveOptions`; το Png θα χρησιμοποιηθεί ως προεπιλεγμένη μορφή εικόνας. |
| [ImageSaveOptions](imagesaveoptions/#constructor_1)(ImageFormat) | Μορφή εικόνας [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/) βάσει αρχικοποίησης |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../../com.aspose.html.rendering.image/compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Λαμβάνει ένα αντικείμενο [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) που χρησιμοποιείται για τη διαμόρφωση της επεξεργασίας ιδιοτήτων css. |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Ορίζει ή λαμβάνει την οριζόντια ανάλυση για τις εξωτερικές και εσωτερικές (που χρησιμοποιούνται κατά την επεξεργασία φίλτρων) εικόνες, σε εικονοστοιχεία ανά ίντσα. Από προεπιλογή, αυτή η ιδιότητα είναι 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Λαμβάνει ένα αντικείμενο ρύθμισης σελίδας που χρησιμοποιείται για τη διαμόρφωση της εξόδου σελίδας. |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/) Λαμβάνει ένα αντικείμενο [`TextOptions`](../../com.aspose.html.rendering.image/textoptions/) που χρησιμοποιείται για τη διαμόρφωση της απόδοσης κειμένου. |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Ορίζει ή λαμβάνει την κάθετη ανάλυση για τις εξωτερικές και εσωτερικές (που χρησιμοποιούνται κατά την επεξεργασία φίλτρων) εικόνες, σε εικονοστοιχεία ανά ίντσα. Από προεπιλογή, αυτή η ιδιότητα είναι 300 dpi. |

## Παρατηρήσεις

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.rendering.image;
import com.aspose.html.saving;
...
      // Προετοιμάστε μια διαδρομή προς ένα πηγαίο αρχείο HTML
      String documentPath = Path.Combine(DataDir, "nature.html");

      // Προετοιμάστε μια διαδρομή για την αποθήκευση του μετατρεπόμενου αρχείου
      String savePath = Path.Combine(OutputDir, "nature-output-options.png");

      // Αρχικοποιήστε ένα έγγραφο HTML από το αρχείο
      using var document = new HTMLDocument(documentPath);

      // Αρχικοποιήστε το ImageSaveOptions       
      var options = new ImageSaveOptions()
      {
        SmoothingMode = SmoothingMode.Default,
        HorizontalResolution = 100,
        VerticalResolution = 100,
        BackgroundColor = Color.Beige
      };

      // Μετατροπή HTML σε PNG
      Converter.ConvertHTML(document, options, savePath);
```

### Δείτε επίσης

* class [ImageRenderingOptions](../../com.aspose.html.rendering.image/imagerenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
