---
title: "Κλάση MHTMLSaveOptions"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Κλάση com.aspose.html.saving.MHTMLSaveOptions. Αντιπροσωπεύει τις επιλογές αποθήκευσης MHTML. Αναθέτοντας συγκεκριμένες ιδιότητες μπορείτε να διαχειριστείτε την επεξεργασία πόρων όπως το μέγιστο βάθος διαχείρισης κ.λπ. Περισσότερες πληροφορίες στο άρθρο τεκμηρίωσης."
type: docs

url: /el/java/com.aspose.html.saving/mhtmlsaveoptions/
---
## MHTMLSaveOptions class

Αναπαριστά τις επιλογές αποθήκευσης MHTML. Αναθέτοντας συγκεκριμένες ιδιότητες, μπορείτε να διαχειριστείτε την επεξεργασία πόρων όπως το μέγιστο βάθος διαχείρισης κ.λπ. Περισσότερες πληροφορίες στη τεκμηρίωση [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options).

```java
public class MHTMLSaveOptions : SaveOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MHTMLSaveOptions](mhtmlsaveoptions/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) Λαμβάνει ένα αντικείμενο [`ResourceHandlingOptions`](../resourcehandlingoptions/) που χρησιμοποιείται για τη διαμόρφωση της διαχείρισης πόρων. |

## Παρατηρήσεις

Μπορείτε να βρείτε πλήρη παραδείγματα και αρχεία δεδομένων στο [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
import System.IO;
...
	 // Προετοιμάστε κώδικα HTML με σύνδεσμο σε άλλο αρχείο και αποθηκεύστε το στο αρχείο ως 'document.html'
      var code = "<span>Hello, World!!</span> " +
            "<a href='document2.html'>click</a>";
      File.WriteAllText("document.html", code);

      // Προετοιμάστε κώδικα HTML και αποθηκεύστε το στο αρχείο ως 'document2.html'
      code = @"<span>Hello, World!!</span>";
      File.WriteAllText("document2.html", code);
       
      String savePath = Path.Combine(OutputDir, "output-options.mht");

      // Αλλάξτε την τιμή του βάθους σύνδεσης πόρων σε 1 για να μετατρέψετε το έγγραφο με άμεσα συνδεδεμένους πόρους
      var options = new MHTMLSaveOptions()
      {
        ResourceHandlingOptions =
        {
          MaxHandlingDepth = 1
        }
      };

      // Μετατρέψτε HTML σε MHTML
      Converter.ConvertHTML("document.html", options, savePath);  
```

### Δείτε επίσης

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
