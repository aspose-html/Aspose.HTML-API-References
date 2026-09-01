---
title: "Κλάση MarkdownSaveOptions"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Η κλάση com.aspose.html.saving.MarkdownSaveOptions. Αντιπροσωπεύει τις επιλογές αποθήκευσης Markdown. Για παράδειγμα, μπορείτε να ορίσετε το στυλ μορφοποίησης markdown, να χρησιμοποιήσετε προ-ορισμένες συμβατές επιλογές GitLab Flavored Markdown και να διαμορφώσετε τη διαχείριση πόρων. Ανατρέξτε σε περισσότερες πληροφορίες στο άρθρο."
type: docs

url: /el/java/com.aspose.html.saving/markdownsaveoptions/
---
## MarkdownSaveOptions class

Αναπαριστά τις επιλογές αποθήκευσης Markdown. Για παράδειγμα, μπορείτε να ορίσετε το στυλ μορφοποίησης markdown, να χρησιμοποιήσετε προκαθορισμένες συμβατές επιλογές GitLab Flavored Markdown και να διαμορφώσετε τη διαχείριση πόρων. Ανατρέξτε σε περισσότερες πληροφορίες στο [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options).

```java
public class MarkdownSaveOptions : SaveOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `MarkdownSaveOptions`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| static [getDefault](../../com.aspose.html.saving/markdownsaveoptions/default/) Επιστρέφει ένα σύνολο επιλογών που είναι συμβατές με την προεπιλεγμένη τεκμηρίωση Markdown. |
| static [getGit](../../com.aspose.html.saving/markdownsaveoptions/git/) Επιστρέφει ένα σύνολο επιλογών που είναι συμβατές με το GitLab Flavored Markdown. |
[getFeatures]
[setFeatures] Flag set that controls which elements are converted to markdown. |
[getFormatter]
[setFormatter] Gets or sets the markdown formatting style. |
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
	 // Προετοιμάστε μια διαδρομή για την αποθήκευση του μετατρεπόμενου αρχείου
      String savePath = Path.Combine(OutputDir, "options-output.md");

      // Προετοιμάστε κώδικα HTML και αποθηκεύστε τον στο αρχείο.
      var code = "<h1>Header 1</h1>" +
            "<h2>Header 2</h2>" +
            "<p>Hello, World!!</p>" +
            "<a href='aspose.com'>aspose</a>";
      File.WriteAllText(Path.Combine(OutputDir, "options.html"), code);

      // Δημιουργήστε μια παρουσία του SaveOptions και ορίστε τον κανόνα: 
      // - μόνο τα στοιχεία <a> και <p> θα μετατραπούν σε Markdown
      var options = new MarkdownSaveOptions();
      options.Features = MarkdownFeatures.Link | MarkdownFeatures.AutomaticParagraph;

      // Καλέστε τη μέθοδο ConvertHTML για να μετατρέψετε το HTML σε Markdown.
      Converter.ConvertHTML(Path.Combine(OutputDir, "options.html"), options, savePath);
```

### Δείτε επίσης

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
