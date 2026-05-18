---
title: "XpsSaveOptions Κλάση"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.saving.XpsSaveOptions κλάση. Συγκεκριμένη κλάση δεδομένων επιλογών παρέχει μερικές ιδιότητες για τη διαχείριση του αποτελέσματος μετατροπής. Για παράδειγμα, το PageSetup καθορίζει τα χαρακτηριστικά της σελίδας. Ανατρέξτε στο άρθρο τεκμηρίωσης."
type: docs

url: /el/java/com.aspose.html.saving/xpssaveoptions/
---
## XpsSaveOptions class

Η συγκεκριμένη κλάση δεδομένων επιλογών παρέχει μερικές ιδιότητες για τη διαχείριση του αποτελέσματος μετατροπής. Για παράδειγμα, το [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) καθορίζει τα χαρακτηριστικά της σελίδας. Ανατρέξτε στην τεκμηρίωση [άρθρο](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#save-options).

```java
public class XpsSaveOptions : XpsRenderingOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Λαμβάνει ένα αντικείμενο [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) που χρησιμοποιείται για τη διαμόρφωση της επεξεργασίας ιδιοτήτων css. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Ορίζει ή λαμβάνει την οριζόντια ανάλυση για εσωτερικές (που χρησιμοποιούνται κατά την επεξεργασία φίλτρων) εικόνες, σε pixel ανά ίντσα. Από προεπιλογή αυτή η ιδιότητα είναι 300 dpi. |
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
	  String documentPath = Path.Combine(OutputDir, "save-options.html");
      String savePath = Path.Combine(OutputDir, "save-options-output.xps");

      // Προετοιμάστε κώδικα HTML και αποθηκεύστε τον σε ένα αρχείο
      var code = "<h1> XpsSaveOptions Class</h1>\r\n" +
            "<p>Using XpsSaveOptions Class, you can programmatically apply a wide range of conversion parameters such as BackgroundColor, PageSetup, etc.</p>\r\n";

      File.WriteAllText(documentPath, code);

      // Αρχικοποιήστε ένα έγγραφο HTML από το αρχείο html
      using var document = new HTMLDocument(documentPath);
       
      // Ορίστε το μέγεθος σελίδας, τα περιθώρια και αλλάξτε το χρώμα φόντου σε AntiqueWhite
      var options = new XpsSaveOptions()
      {
        BackgroundColor = Color.AntiqueWhite
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(Length.FromInches(4.9f), Length.FromInches(3.5f)), new Margin(30, 20, 10, 10));

      // Μετατροπή HTML σε XPS
      Converter.ConvertHTML(document, options, savePath); 
```

### Δείτε επίσης

* class [XpsRenderingOptions](../../com.aspose.html.rendering.xps/xpsrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
