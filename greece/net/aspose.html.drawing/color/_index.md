---
title: Class Color
second_title: Aspose.HTML για Αναφορά API .NET
description: Aspose.Html.Drawing.Color τάξη. Η κλάση Χρώμα σάς επιτρέπει να καθορίσετε χρώματα ως τιμές ΚόκκινοΠράσινοΜπλε RGB Τιμές HueSaturationLuminosity HSL HueSaturationValue HSV Τιμές HueSaturationValue HSV0HBhinesste_xe  τιμές τιμές ελαφρότηταςAB LAB Τιμές φωτεινότηταςΧρώμαΧρώμα LCH τιμές κυανούματζέντακίτρινου κλειδιού CMYK Τιμές φυσικών χρωμάτων NCOL με όνομα_ ή χ00 . Διατίθεται επίσης ένα κανάλι Alpha για να υποδείξει τη διαφάνεια.
type: docs
weight: 2640
url: /el/net/aspose.html.drawing/color/
---
## Color class

Η κλάση Χρώμα σάς επιτρέπει να καθορίσετε χρώματα ως τιμές Κόκκινο-Πράσινο-Μπλε (RGB), Τιμές Hue-Saturation-Luminosity (HSL), Hue-Saturation-Value (HSV) Τιμές Hue-Saturation-Value (HSV)0HBhinesste,_xe ) τιμές, τιμές ελαφρότητας-AB (LAB), Τιμές φωτεινότητας-Χρώμα-Χρώμα (LCH), τιμές κυανού-ματζέντα-κίτρινου κλειδιού (CMYK), Τιμές φυσικών χρωμάτων (NCOL) με όνομα_ ή χ00 . Διατίθεται επίσης ένα κανάλι Alpha για να υποδείξει τη διαφάνεια.

```csharp
public class Color
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [Color](color/#constructor)() | Αρχικοποιεί μια νέα παρουσία του`Color` class. Από προεπιλογή το χρώμα είναι μαύρο. |
| [Color](color/#constructor_1)(byte, byte, byte) | Αρχικοποιεί μια νέα παρουσία του`Color`class. Όλα τα στοιχεία χρώματος πρέπει να είναι στην περιοχή 0-255. |
| [Color](color/#constructor_5)(float, float, float) | Αρχικοποιεί μια νέα παρουσία του`Color` class. Όλα τα στοιχεία χρώματος πρέπει να είναι στην περιοχή 0-1. |
| [Color](color/#constructor_3)(int, int, int) | Αρχικοποιεί μια νέα παρουσία του`Color`class. Όλα τα στοιχεία χρώματος πρέπει να είναι στην περιοχή 0-255. |
| [Color](color/#constructor_2)(byte, byte, byte, byte) | Αρχικοποιεί μια νέα παρουσία του`Color`class. Όλα τα στοιχεία χρώματος πρέπει να είναι στην περιοχή 0-255. |
| [Color](color/#constructor_6)(float, float, float, float) | Αρχικοποιεί μια νέα παρουσία του`Color` class. Όλα τα στοιχεία χρώματος πρέπει να είναι στην περιοχή 0-1. |
| [Color](color/#constructor_4)(int, int, int, int) | Αρχικοποιεί μια νέα παρουσία του`Color`class. Όλα τα στοιχεία χρώματος πρέπει να είναι στην περιοχή 0-255. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Alpha](../../aspose.html.drawing/color/alpha/) { get; } | Αντιπροσωπεύει την άλφα συνιστώσα του χρώματος. |
| [Blue](../../aspose.html.drawing/color/blue/) { get; } | Αντιπροσωπεύει το μπλε στοιχείο του χρώματος. |
| [Green](../../aspose.html.drawing/color/green/) { get; } | Αντιπροσωπεύει την πράσινη συνιστώσα του χρώματος. |
| [Red](../../aspose.html.drawing/color/red/) { get; } | Αντιπροσωπεύει το κόκκινο στοιχείο του χρώματος |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [FromCmyk](../../aspose.html.drawing/color/fromcmyk/)(float, float, float, float) | Επιστρέφει ένα νέο χρώμα με τις ζητούμενες τιμές κυανό, ματζέντα, κίτρινο, κλειδί (μαύρο). |
| static [FromCmyka](../../aspose.html.drawing/color/fromcmyka/)(float, float, float, float, float) | Επιστρέφει ένα νέο χρώμα με τις ζητούμενες τιμές κυανό, ματζέντα, κίτρινο, κλειδί (μαύρο), άλφα. |
| static [FromGray](../../aspose.html.drawing/color/fromgray/)(float) | Επιστρέφει ένα νέο χρώμα με την ζητούμενη τιμή γκρι. |
| static [FromHsl](../../aspose.html.drawing/color/fromhsl/)(float, float, float) | Επιστρέφει ένα νέο χρώμα με τις ζητούμενες τιμές απόχρωσης, κορεσμού, κορεσμού. |
| static [FromHsla](../../aspose.html.drawing/color/fromhsla/)(float, float, float, float) | Επιστρέφει ένα νέο χρώμα με τις ζητούμενες τιμές απόχρωσης, κορεσμού, κορεσμού, άλφα. |
| static [FromHsv](../../aspose.html.drawing/color/fromhsv/)(float, float, float) | Επιστρέφει ένα νέο χρώμα με την ζητούμενη απόχρωση, κορεσμό, τιμή. |
| static [FromHsva](../../aspose.html.drawing/color/fromhsva/)(float, float, float, float) | Επιστρέφει ένα νέο χρώμα με την ζητούμενη απόχρωση, κορεσμό, τιμή, άλφα. |
| static [FromHwb](../../aspose.html.drawing/color/fromhwb/)(float, float, float) | Επιστρέφει ένα νέο χρώμα με τις ζητούμενες τιμές απόχρωσης, λευκότητας, μαύρου χρώματος. |
| static [FromHwba](../../aspose.html.drawing/color/fromhwba/)(float, float, float, float) | Επιστρέφει ένα νέο χρώμα με τις ζητούμενες τιμές απόχρωσης, λευκότητας, μαύρου χρώματος. |
| static [FromInt](../../aspose.html.drawing/color/fromint/)(int) | Επιστρέφει ένα νέο χρώμα με την ζητούμενη τιμή ARGB. |
| static [FromLab](../../aspose.html.drawing/color/fromlab/)(float, float, float) | Επιστρέφει ένα νέο χρώμα με την ζητούμενη φωτεινότητα, τιμές A, B. |
| static [FromLaba](../../aspose.html.drawing/color/fromlaba/)(float, float, float, float) | Επιστρέφει ένα νέο χρώμα με την ζητούμενη φωτεινότητα, A, B, τιμές άλφα. |
| static [FromLch](../../aspose.html.drawing/color/fromlch/)(float, float, float) | Επιστρέφει ένα νέο χρώμα με τις ζητούμενες τιμές φωτεινότητας, χρώματος, απόχρωσης. |
| static [FromLcha](../../aspose.html.drawing/color/fromlcha/)(float, float, float, float) | Επιστρέφει ένα νέο χρώμα με τις ζητούμενες τιμές φωτεινότητας, χρώματος, απόχρωσης, άλφα. |
| static [FromOklab](../../aspose.html.drawing/color/fromoklab/)(float, float, float) | Επιστρέφει ένα νέο χρώμα με την ζητούμενη φωτεινότητα, τιμές A, B για το μοντέλο OKLAB. |
| static [FromOklaba](../../aspose.html.drawing/color/fromoklaba/)(float, float, float, float) | Επιστρέφει ένα νέο χρώμα με την ζητούμενη φωτεινότητα, A, B, τιμές άλφα για το μοντέλο OKLAB. |
| static [FromOklch](../../aspose.html.drawing/color/fromoklch/)(float, float, float) | Επιστρέφει ένα νέο χρώμα με τις ζητούμενες τιμές φωτεινότητας, χρώματος, απόχρωσης για το μοντέλο OKLAB. |
| static [FromOklcha](../../aspose.html.drawing/color/fromoklcha/)(float, float, float, float) | Επιστρέφει ένα νέο χρώμα με τις ζητούμενες τιμές φωτεινότητας, χρώματος, απόχρωσης, άλφα για το μοντέλο OKLAB. |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb)(byte, byte, byte) | Επιστρέφει ένα νέο χρώμα με τις ζητούμενες τιμές ged, πράσινο, μπλε. Όλα τα στοιχεία χρώματος πρέπει να βρίσκονται στην περιοχή 0-255. |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb_2)(float, float, float) | Επιστρέφει ένα νέο χρώμα με τις ζητούμενες τιμές ged, πράσινο, μπλε. Όλα τα στοιχεία χρώματος πρέπει να βρίσκονται στην περιοχή 0-1. |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb_1)(int, int, int) | Επιστρέφει ένα νέο χρώμα με τις ζητούμενες τιμές ged, πράσινο, μπλε. Όλα τα στοιχεία χρώματος πρέπει να βρίσκονται στην περιοχή 0-255. |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba)(byte, byte, byte, byte) | Επιστρέφει ένα νέο χρώμα με τις ζητούμενες τιμές ged, πράσινο, μπλε, άλφα. Όλα τα στοιχεία χρώματος πρέπει να βρίσκονται στην περιοχή 0-255. |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba_2)(float, float, float, float) | Επιστρέφει ένα νέο χρώμα με τις ζητούμενες τιμές ged, πράσινο, μπλε, άλφα. Όλα τα στοιχεία χρώματος πρέπει να βρίσκονται στην περιοχή 0-1. |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba_1)(int, int, int, int) | Επιστρέφει ένα νέο χρώμα με τις ζητούμενες τιμές ged, πράσινο, μπλε, άλφα. Όλα τα στοιχεία χρώματος πρέπει να βρίσκονται στην περιοχή 0-255. |
| static [FromString](../../aspose.html.drawing/color/fromstring/)(string) | Αναλύει τη συμβολοσειρά που περιέχει το χρώμα CSS και επιστρέφει ένα νέο χρώμα. |
| static [FromUint](../../aspose.html.drawing/color/fromuint/)(uint) | Επιστρέφει ένα νέο χρώμα με την ζητούμενη τιμή ARGB. |
| [AddLuminosity](../../aspose.html.drawing/color/addluminosity/)(float) | Δημιουργεί αντίγραφο του χρώματος με το άθροισμα της φωτεινότητάς του και την τιμή δέλτα. |
| [Convert](../../aspose.html.drawing/color/convert/)(ColorModel) | Επιστρέφει στοιχεία χρώματος στη μορφή του καθορισμένου μοντέλου χρώματος. |
| override [Equals](../../aspose.html.drawing/color/equals/)(object) | Καθορίζει εάν το καθορισμένο`Color` ισούται με αυτήν την περίπτωση. |
| [GetComplementary](../../aspose.html.drawing/color/getcomplementary/)() | Επιστρέφει ένα νέο χρώμα που βρίσκεται στην αντίθετη πλευρά του χρωματικού τροχού από το αρχικό. |
| override [GetHashCode](../../aspose.html.drawing/color/gethashcode/)() | Επιστρέφει έναν κωδικό κατακερματισμού. |
| [GetHue](../../aspose.html.drawing/color/gethue/)() | Επιστρέφει μια απόχρωση του χρώματος. |
| [GetLuminosity](../../aspose.html.drawing/color/getluminosity/)() | Επιστρέφει μια φωτεινότητα του χρώματος. |
| [GetSaturation](../../aspose.html.drawing/color/getsaturation/)() | Επιστρέφει έναν κορεσμό του χρώματος. |
| [ToInt](../../aspose.html.drawing/color/toint/)() | Κωδικοποιεί τα στοιχεία Color ARGB σε int. |
| [ToName](../../aspose.html.drawing/color/toname/)() | Επιστρέφει το όνομα του χρώματος εάν ταιριάζει με ένα χρώμα στη λίστα των χρωμάτων με όνομα CSS ή με μια κενή συμβολοσειρά. |
| [ToNaturalColorString](../../aspose.html.drawing/color/tonaturalcolorstring/)(int) | Επιστρέφει ένα καθορισμένο χρώμα σε φυσικά χρώματα (NCol) χρησιμοποιώντας ένα έγχρωμο γράμμα με έναν αριθμό για να καθορίσει την απόσταση (σε ποσοστό) από το χρώμα. |
| [ToRgbaHexString](../../aspose.html.drawing/color/torgbahexstring/)() | Επιστρέφει ένα δεκαεξαδικό χρώμα που καθορίζεται με: #RRGGBBAA. |
| [ToRgbaString](../../aspose.html.drawing/color/torgbastring/)() | Επιστρέφει μια συμβολοσειρά που περιέχει το χρώμα RGBA που καθορίζεται από: rgba(R, G, B, A). |
| [ToRgbHexString](../../aspose.html.drawing/color/torgbhexstring/)() | Επιστρέφει ένα δεκαεξαδικό χρώμα που καθορίζεται με: #RRGGBB. |
| [ToRgbString](../../aspose.html.drawing/color/torgbstring/)() | Επιστρέφει μια συμβολοσειρά που περιέχει το χρώμα RGB που καθορίζεται από: rgb(R, G, B). |
| override [ToString](../../aspose.html.drawing/color/tostring/)() | Επιστρέφει μια συμβολοσειρά που αποτελείται από τις τιμές στοιχείων RGBA. |
| [ToUint](../../aspose.html.drawing/color/touint/)() | Κωδικοποιεί τα στοιχεία Έγχρωμου ARGB σε ανυπόγραφο int. |
| [WithAlpha](../../aspose.html.drawing/color/withalpha/)(float) | Δημιουργεί αντίγραφο του χρώματος με καθορισμένο στοιχείο άλφα. |
| [WithHue](../../aspose.html.drawing/color/withhue/)(float) | Δημιουργεί αντίγραφο του χρώματος με καθορισμένη απόχρωση. |
| [WithLuminosity](../../aspose.html.drawing/color/withluminosity/)(float) | Δημιουργεί αντίγραφο του χρώματος με καθορισμένη φωτεινότητα. |
| [WithSaturation](../../aspose.html.drawing/color/withsaturation/)(float) | Δημιουργεί αντίγραφο του χρώματος με καθορισμένο κορεσμό. |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.Html.Drawing](../../aspose.html.drawing/)
* συνέλευση [Aspose.HTML](../../)


