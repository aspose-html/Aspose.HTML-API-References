---
title: "FontMatcher.MatchFontFallback"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος FontMatcher. Αυτή η μέθοδος καλείται εάν δεν βρεθεί κατάλληλη γραμματοσειρά στους φακέλους αναζήτησης γραμματοσειρών. Θα πρέπει να επιστρέφει γραμματοσειρά τύπου true βάσει των fontMatchingProperties που μπορεί να αποδώσει charCode ή null εάν τέτοια γραμματοσειρά δεν είναι διαθέσιμη."
type: docs

url: /el/java/com.aspose.html.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

Αυτή η μέθοδος καλείται εάν δεν βρεθεί κατάλληλη γραμματοσειρά στους φακέλους αναζήτησης γραμματοσειρών. Θα πρέπει να επιστρέφει γραμματοσειρά πραγματικού τύπου βάσει των *fontMatchingProperties* που μπορεί να αποδώσει το *charCode*, ή `null` εάν τέτοια γραμματοσειρά δεν είναι διαθέσιμη.

```java
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | Ιδιότητες της ταιριαστής γραμματοσειράς. |
| charCode | UInt32 | Κώδικας του χαρακτήρα που θα αποδοθεί χρησιμοποιώντας την ταιριαστή γραμματοσειρά. |

### Τιμή επιστροφής

Ένας πίνακας byte που περιέχει τα δεδομένα των γραμματοσειρών ή `null`.

### Δείτε επίσης

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* package [com.aspose.html.rendering.fonts](../../../com.aspose.html.rendering.fonts/)
* package [Aspose.HTML](../../../)
