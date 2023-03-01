---
title: Class Metered
second_title: Aspose.HTML για Αναφορά API .NET
description: Aspose.Html.Metered τάξη. Παρέχει μεθόδους για να ορίσετε μετρημένο κλειδί.
type: docs
weight: 3830
url: /el/net/aspose.html/metered/
---
## Metered class

Παρέχει μεθόδους για να ορίσετε μετρημένο κλειδί.

```csharp
public class Metered
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [Metered](metered/)() | Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [SetMeteredKey](../../aspose.html/metered/setmeteredkey/)(string, string) | Ορίζει το μετρημένο δημόσιο και ιδιωτικό κλειδί. Εάν αγοράσετε μετρημένη άδεια, κατά την έναρξη της εφαρμογής, αυτό το API θα πρέπει να καλείται, κανονικά, αυτό είναι αρκετό. Ωστόσο, εάν πάντα αποτυγχάνει η αποστολή δεδομένων κατανάλωσης και υπερβαίνει τις 24 ώρες, η άδεια θα οριστεί σε κατάσταση αξιολόγησης, για να αποφευχθεί τέτοια περίπτωση, θα πρέπει να ελέγχετε τακτικά την κατάσταση της άδειας, εάν είναι κατάσταση αξιολόγησης, καλέστε ξανά αυτό το API. |
| static [GetConsumptionCredit](../../aspose.html/metered/getconsumptioncredit/)() | Λαμβάνει πίστωση κατανάλωσης |
| static [GetConsumptionQuantity](../../aspose.html/metered/getconsumptionquantity/)() | Λαμβάνει μέγεθος αρχείου κατανάλωσης |

### Παραδείγματα

Σε αυτό το παράδειγμα, θα γίνει μια προσπάθεια να οριστεί το μετρημένο δημόσιο και ιδιωτικό κλειδί

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

το αρχείο jar του στοιχείου:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Δείτε επίσης

* χώρος ονομάτων [Aspose.Html](../../aspose.html/)
* συνέλευση [Aspose.HTML](../../)


