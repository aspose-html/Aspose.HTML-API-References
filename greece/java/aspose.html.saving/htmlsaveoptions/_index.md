---
title: "HTMLSaveOptions Τάξη"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.saving.HTMLSaveOptions class. Αντιπροσωπεύει τις επιλογές αποθήκευσης HTML. Αναθέτοντας συγκεκριμένες ιδιότητες μπορείτε να διαχειριστείτε την επεξεργασία πόρων όπως το μέγιστο βάθος διαχείρισης κ.λπ. Περισσότερες πληροφορίες στο άρθρο τεκμηρίωσης"
type: docs

url: /el/java/com.aspose.html.saving/htmlsaveoptions/
---
## HTMLSaveOptions class

Αναπαριστά τις επιλογές αποθήκευσης HTML. Αναθέτοντας συγκεκριμένες ιδιότητες, μπορείτε να διαχειριστείτε την επεξεργασία πόρων όπως το μέγιστο βάθος διαχείρισης κ.λπ. Περισσότερες πληροφορίες στη τεκμηρίωση [article](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

```java
public class HTMLSaveOptions : SaveOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [HTMLSaveOptions](htmlsaveoptions/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
[getDocumentType]
[setDocumentType] Gets or sets the output document type. |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) Λαμβάνει ένα αντικείμενο [`ResourceHandlingOptions`](../resourcehandlingoptions/) που χρησιμοποιείται για τη διαμόρφωση της διαχείρισης πόρων. |
[getSerializeInputValue]
[setSerializeInputValue] This option controls whether to serialize the value of the [`HTMLInputElement`](../../com.aspose.html/htmlinputelement/)'s or the [`HTMLTextAreaElement`](../../com.aspose.html/htmltextareaelement/)'s "value" property into the "value" attribute. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [AUTO](../../com.aspose.html.saving/htmlsaveoptions/auto/) | Ο τύπος του εξαγόμενου εγγράφου θα επιλεγεί αυτόματα. |
| const [HTML](../../com.aspose.html.saving/htmlsaveoptions/html/) | Το έγγραφο θα αποθηκευτεί ως HTML. |
| const [XHTML](../../com.aspose.html.saving/htmlsaveoptions/xhtml/) | Το έγγραφο θα αποθηκευτεί ως XHTML. |

## Παρατηρήσεις

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Παραδείγματα

```java
import Aspose.Html;
import com.aspose.html.dom.svg;
import com.aspose.html.saving;
import System;
...
     // Προετοιμάστε μια διαδρομή εξόδου για ένα έγγραφο HTML 
      String documentPath = Path.Combine(OutputDir, "save-with-linked-file.html");

      // Προετοιμάστε ένα απλό αρχείο HTML με ένα συνδεδεμένο έγγραφο
      File.WriteAllText(documentPath, "<p>Hello World!</p>" +
                      "<a href='linked.html'>linked file</a>");

      // Προετοιμάστε ένα απλό συνδεδεμένο αρχείο HTML
      File.WriteAllText(Path.Combine(OutputDir, "linked.html"), "<p>Hello linked file!</p>");

      // Φορτώστε το "save-with-linked-file.html" στη μνήμη
      using (var document = new HTMLDocument(documentPath))
      {
        // Δημιουργήστε ένα στιγμιότυπο επιλογών αποθήκευσης
        var options = new HTMLSaveOptions();

        // Η ακόλουθη γραμμή με τιμή '0' αποκόπτει όλα τα άλλα συνδεδεμένα αρχεία HTML κατά την αποθήκευση αυτού του αντικειμένου
        // Εάν αφαιρέσετε αυτή τη γραμμή ή αλλάξετε την τιμή σε '1', το αρχείο 'linked.html' θα αποθηκευτεί επίσης στον φάκελο εξόδου
        options.ResourceHandlingOptions.MaxHandlingDepth = 1;

        // Αποθηκεύστε το έγγραφο με τις επιλογές αποθήκευσης
        document.Save(Path.Combine(OutputDir, "save-with-linked-file_out.html"), options);
      }
```

*OutputDir - user output folder.

### Δείτε επίσης

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
