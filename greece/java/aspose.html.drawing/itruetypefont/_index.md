---
title: "Διεπαφή ITrueTypeFont"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Διεπαφή com.aspose.html.drawing.ITrueTypeFont. Δηλώνει μεθόδους για εργασία με γραμματοσειρά TrueType."
type: docs

url: /el/java/com.aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

Δηλώνει μεθόδους για εργασία με γραμματοσειρά TrueType.

```java
public interface ITrueTypeFont
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getDataSize](../../com.aspose.html.drawing/itruetypefont/datasize/) Επιστρέφει το μέγεθος των δεδομένων της γραμματοσειράς σε bytes. |
| [getFamilyName](../../com.aspose.html.drawing/itruetypefont/familyname/) Λαμβάνει το όνομα της οικογένειας γραμματοσειράς. |
| [getFullFontName](../../com.aspose.html.drawing/itruetypefont/fullfontname/) Αυτό πρέπει να είναι ένας συνδυασμός των \"FamilyName\" και \"SubFamilyName\". Εξαίρεση: εάν η γραμματοσειρά είναι \"Regular\" όπως υποδεικνύεται στο \"SubFamilyName\", τότε χρησιμοποιήστε μόνο το όνομα οικογένειας που περιέχεται στο \"FamilyName\". Μια εξαίρεση στον παραπάνω ορισμό του πλήρους ονόματος γραμματοσειράς ισχύει για τις συμβολοσειρές της πλατφόρμας Microsoft για γραμματοσειρές CFF OpenType: σε αυτήν την περίπτωση, η συμβολοσειρά Full font name πρέπει να είναι ταυτοτική με το PostScript FontName στο CFF Name INDEX. |
| [getSubFamilyName](../../com.aspose.html.drawing/itruetypefont/subfamilyname/) Το όνομα SubFamily της γραμματοσειράς διακρίνει τη γραμματοσειρά σε μια ομάδα με το ίδιο όνομα Font Family. Θεωρείται ότι καλύπτει το στυλ (italic, oblique) και το βάρος (light, bold, black, κλπ.). Μια γραμματοσειρά χωρίς ιδιαίτερες διαφορές στο βάρος ή το στυλ (π.χ. μεσαίο βάρος, χωρίς italic και με το bit 6 του fsSelection ενεργό) θα πρέπει να έχει τη συμβολοσειρά \"Regular\" αποθηκευμένη σε αυτή τη θέση. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getAscent](../../com.aspose.html.drawing/itruetypefont/getascent/)(float) | Επιστρέφει το ύψος ανόδου (ascent), σε points. |
| [getData](../../com.aspose.html.drawing/itruetypefont/getdata/)() | Ανοίξτε τη ροή με τα δεδομένα της γραμματοσειράς. Ο καλών είναι υπεύθυνος για την απελευθέρωση της ροής. |
| [getDescent](../../com.aspose.html.drawing/itruetypefont/getdescent/)(float) | Επιστρέφει το ύψος καθόδου (descent), σε points. |

### Δείτε επίσης

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
