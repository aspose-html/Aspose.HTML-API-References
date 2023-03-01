---
title: Interface ITrueTypeFont
second_title: Aspose.HTML για Αναφορά API .NET
description: Aspose.Html.Drawing.ITrueTypeFont διεπαφή. Δηλώνει μεθόδους εργασίας με γραμματοσειρά TrueType.
type: docs
weight: 2760
url: /el/net/aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

Δηλώνει μεθόδους εργασίας με γραμματοσειρά TrueType.

```csharp
public interface ITrueTypeFont
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [DataSize](../../aspose.html.drawing/itruetypefont/datasize/) { get; } | Επιστρέφει το μέγεθος των δεδομένων γραμματοσειράς σε bytes |
| [FamilyName](../../aspose.html.drawing/itruetypefont/familyname/) { get; } | Λάβετε το όνομα της οικογένειας γραμματοσειρών. |
| [FullFontName](../../aspose.html.drawing/itruetypefont/fullfontname/) { get; } | Αυτό θα πρέπει να είναι ένας συνδυασμός του "FamilyName" και του "SubFamilyName". Εξαίρεση: εάν η γραμματοσειρά είναι "Κανονική" όπως υποδεικνύεται στο "SubFamilyName", τότε χρησιμοποιήστε μόνο το οικογενειακό όνομα που περιέχεται στο "FamilyName". Μια εξαίρεση στον παραπάνω ορισμό του ονόματος πλήρους γραμματοσειράς είναι για τις συμβολοσειρές πλατφόρμας Microsoft για γραμματοσειρές CFF OpenType: σε αυτήν την περίπτωση, η συμβολοσειρά ονόματος πλήρους γραμματοσειράς πρέπει να είναι πανομοιότυπη με τη συμβολοσειρά ονόματος γραμματοσειράς PostScript στο Όνομα CFF INDEX.. |
| [SubFamilyName](../../aspose.html.drawing/itruetypefont/subfamilyname/) { get; } | Το όνομα της υποοικογένειας γραμματοσειράς διακρίνει τη γραμματοσειρά σε μια ομάδα με το ίδιο όνομα οικογένειας γραμματοσειράς. Υποτίθεται ότι αφορά το στυλ (πλάγια, πλάγια) και το βάρος (ανοιχτό, τολμηρό, μαύρο, κ.λπ.). Μια γραμματοσειρά χωρίς ιδιαίτερες διαφορές στο βάρος ή το στυλ (π.χ. μεσαίο βάρος, όχι πλάγιο και σύνολο fsSelection bit 6) θα πρέπει να έχει αποθηκευμένη τη συμβολοσειρά "Regular" σε αυτή τη θέση. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [GetAscent](../../aspose.html.drawing/itruetypefont/getascent/)(float) | Επιστρέφει την ανάβαση, σε πόντους. |
| [GetData](../../aspose.html.drawing/itruetypefont/getdata/)() | Ανοίξτε τη ροή με δεδομένα γραμματοσειράς. Ο καλών είναι υπεύθυνος για την απόρριψη της ροής. |
| [GetDescent](../../aspose.html.drawing/itruetypefont/getdescent/)(float) | Επιστρέφει την κάθοδο, σε πόντους. |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.Html.Drawing](../../aspose.html.drawing/)
* συνέλευση [Aspose.HTML](../../)


