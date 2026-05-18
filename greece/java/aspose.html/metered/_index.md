---
title: "Κλάση Metered"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Κλάση com.aspose.html.Metered. Παρέχει μεθόδους για ορισμό κλειδιού μετρητή"
type: docs

url: /el/java/com.aspose.html/metered/
---
## Metered class

Παρέχει μεθόδους για τον ορισμό κλειδιού με μέτρηση.

```java
public class Metered
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Metered](metered/)() | Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [setMeteredKey](../../com.aspose.html/metered/setmeteredkey/)(String, String) | Ορίζει το δημόσιο και ιδιωτικό κλειδί του μετρητή. Εάν αγοράσετε άδεια μετρητή, κατά την εκκίνηση της εφαρμογής, αυτό το API πρέπει να κληθεί· συνήθως αυτό είναι επαρκές. Ωστόσο, εάν αποτυγχάνει συνεχώς η μεταφόρτωση δεδομένων κατανάλωσης και υπερβεί τις 24 ώρες, η άδεια θα μετατραπεί σε κατάσταση αξιολόγησης· για να αποφύγετε αυτήν την περίπτωση, θα πρέπει να ελέγχετε τακτικά την κατάσταση της άδειας· εάν είναι σε κατάσταση αξιολόγησης, καλέστε ξανά αυτό το API. |
| static [GetConsumptionCredit](../../com.aspose.html/metered/getconsumptioncredit/)() | Λαμβάνει πίστωση κατανάλωσης |
| static [GetConsumptionQuantity](../../com.aspose.html/metered/getconsumptionquantity/)() | Λαμβάνει το μέγεθος αρχείου κατανάλωσης |
| static [IsMeteredLicensed](../../com.aspose.html/metered/ismeteredlicensed/)() | Ελέγξτε εάν το metered είναι αδειοδοτημένο |

## Παραδείγματα

Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να οριστεί το δημόσιο και ιδιωτικό κλειδί του metered

```java
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

το αρχείο jar του στοιχείου:

```java
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Δείτε επίσης

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
