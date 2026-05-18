---
title: "Configuration Κλάση"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.Configuration class. Αντιπροσωπεύει το αντικείμενο πλαισίου διαμόρφωσης που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Διαχειριζόμενοι τη διαμόρφωση, μπορείτε να παρακάμψετε το στυλ του εγγράφου εφαρμόζοντας ένα προσαρμοσμένο φύλλο στυλ χρήστη ή να διαχειριστείτε τυχόν αιτήματα web από την εφαρμογή, καθώς και να διαμορφώσετε την πολιτική σεναρίων. Οι λεπτομέρειες βρίσκονται στον οδηγό Περιβάλλον Διαμόρφωσης"
type: docs

url: /el/java/com.aspose.html/configuration/
---
## Configuration class

Αντιπροσωπεύει το αντικείμενο περιβάλλοντος διαμόρφωσης που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Διαχειριζόμενοι τη διαμόρφωση, μπορείτε να παρακάμψετε το στυλ του εγγράφου εφαρμόζοντας ένα προσαρμοσμένο φύλλο στυλ χρήστη, ή να διαχειριστείτε τυχόν αιτήματα web από την εφαρμογή, καθώς και να διαμορφώσετε την πολιτική των σεναρίων. Λεπτομέρειες βρίσκονται στον [Environment Configuration guide](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/).

```java
public class Configuration : IDisposable, IServiceProvider
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Configuration](configuration/)() | Αρχικοποιεί μια νέα παρουσία του `class`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
[getSecurity]
[setSecurity] Gets or sets the sandboxing flag of the configuration. Refer to article about [sandboxing](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/#sandboxing). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [Create](../../com.aspose.html/configuration/create/#create)() | Δημιουργήστε και διαμορφώστε την παρουσία του αντικειμένου Configuration. |
| static [Create](../../com.aspose.html/configuration/create/#create_1)(Action&lt;IConfigurationBuilder&gt;) | Δημιουργήστε και διαμορφώστε την παρουσία του αντικειμένου Configuration. |
| [dispose](../../com.aspose.html/configuration/dispose/)() | Εκτελεί εργασίες που ορίζονται από την εφαρμογή και σχετίζονται με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων. |
| [getService](../../com.aspose.html/configuration/getservice/#getservice)(Type) | Λαμβάνει την ζητούμενη υπηρεσία. |
| [GetService&lt;T&gt;](../../com.aspose.html/configuration/getservice/#getservice_1)() | Λαμβάνει την ζητούμενη υπηρεσία. |

## Παρατηρήσεις

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Παραδείγματα

```java
import System;
import System.Diagnostics;
import System.IO;
import Aspose.Html;
import com.aspose.html.net;
import com.aspose.html.services;

    // Αυτός ο διαχειριστής μηνυμάτων εκτυπώνει ένα μήνυμα σχετικά με την έναρξη και το τέλος της επεξεργασίας του αιτήματος
    public class LogMessageHandler : MessageHandler
    {
      // Παρακάμψτε τη μέθοδο Invoke()
      public void Invoke(INetworkOperationContext context)
      {
        Debug.WriteLine("Start processing request: " + context.Request.RequestUri);

        // Καλεί τον επόμενο διαχειριστή μηνυμάτων στην αλυσίδα
        Next(context);

        Debug.WriteLine("Finish processing request: " + context.Request.RequestUri);
      }
    }
```

```java
    public void CreateACustomMessageHandlerTest()
    {
      // Δημιουργήστε μια παρουσία της κλάσης Configuration
      using var configuration = new Configuration();

      // Προσθέστε το LogMessageHandler στην αλυσίδα των υπάρχοντων χειριστών μηνυμάτων
      var service = configuration.GetService<INetworkService>();
      var handlers = service.MessageHandlers;
           
      handlers.Insert(0, new LogMessageHandler());

      // Ετοιμάστε τη διαδρομή προς ένα αρχείο πηγαίου εγγράφου
      String documentPath = Path.Combine(DataDir, "input.htm");

      // Αρχικοποιήστε ένα έγγραφο HTML με την καθορισμένη διαμόρφωση
      using var document = new HTMLDocument(documentPath, configuration);
    }
```

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.net;
import com.aspose.html.saving;
import com.aspose.html.services;
import System;
import System.Collections.Generic;
import System.IO;
import System.Net;
import System.Text;

public void SandboxingSample()
    {
      // Προετοιμάστε κώδικα HTML και αποθηκεύστε τον σε ένα αρχείο
      var code = "<span>Hello World!!</span> " +
            "<script>document.write('Have a nice day!');</script>";

      File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

      // Δημιουργήστε μια παρουσία της Configuration
      using (var configuration = new Configuration())
      {
        // Σημειώστε το 'scripts' ως μη αξιόπιστο πόρο
        configuration.Security |= Sandbox.Scripts;

        // Αρχικοποιήστε ένα έγγραφο HTML με την καθορισμένη διαμόρφωση
        using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
        {
          // Μετατρέψτε HTML σε PDF
          Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
        }
      }       
    }
```

*OutputDir - user output folder path.

### Δείτε επίσης

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
