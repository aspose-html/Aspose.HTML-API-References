---
title: "ResourceHandler.HandleResourceReference"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος ResourceHandler. Αυτή η μέθοδος είναι υπεύθυνη για τη διαχείριση της αναφοράς του πόρου. Σε αυτή τη μέθοδο μπορείτε να ορίσετε πώς θα φαίνεται η αναφορά στον πόρο που διαχειρίζεται."
type: docs

url: /el/java/com.aspose.html.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

Αυτή η μέθοδος είναι υπεύθυνη για τη διαχείριση της αναφοράς του πόρου. Σε αυτή τη μέθοδο, μπορείτε να ορίσετε πώς θα φαίνεται η αναφορά στον πόρο που διαχειρίζεται.

```java
public String HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| resource | Resource | Το [`Resource`](../../../com.aspose.html.saving/resource/) που θα διαχειριστείται. |
| πλαίσιο | ResourceHandlingContext | Πλαίσιο διαχείρισης πόρων. |

### Τιμή Επιστροφής

Μια συμβολοσειρά που θα γραφτεί στον γονικό πόρο και που αντιπροσωπεύει μια αναφορά στον πόρο που διαχειρίζεται αυτή τη στιγμή.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| InvalidOperationException | Εγείρεται εάν το [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) είναι `null` και το [`Status`](../../../com.aspose.html.saving/resource/status/) είναι Saved. Το [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) πρέπει να καθοριστεί για αποθηκευμένο πόρο, επειδή διαφορετικά είναι αδύνατο να καθοριστεί η σωστή αναφορά στους πόρους που αναφέρονται σε αυτόν. |

### Δείτε επίσης

* class [Resource](../../../com.aspose.html.saving/resource/)
* class [ResourceHandlingContext](../../../com.aspose.html.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* package [com.aspose.html.saving.ResourceHandlers](../../../com.aspose.html.saving.resourcehandlers/)
* package [Aspose.HTML](../../../)
