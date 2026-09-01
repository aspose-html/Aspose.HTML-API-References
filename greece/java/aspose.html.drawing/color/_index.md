---
title: "Κλάση Color"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "κλάση com.aspose.html.drawing.Color. Η κλάση Color σας επιτρέπει να καθορίζετε χρώματα ως τιμές Red-Green-Blue RGB, τιμές Hue-Saturation-Luminosity HSL, τιμές Hue-Saturation-Value HSV, τιμές Hue-Whiteness-Blackness HWB, τιμές lightness-A-B LAB, τιμές Luminance-Chroma-Hue LCH, τιμές Cyan-Magenta-Yellow-Key CMYK, τιμές Natural colors NCOL ή με όνομα χρώματος. Ένα κανάλι Alpha είναι επίσης διαθέσιμο για να υποδεικνύει τη διαφάνεια"
type: docs

url: /el/java/com.aspose.html.drawing/color/
---
## Color class

Η κλάση Color σας επιτρέπει να καθορίζετε χρώματα ως τιμές Red-Green-Blue (RGB), Hue-Saturation-Luminosity (HSL), Hue-Saturation-Value (HSV), Hue-Whiteness-Blackness (HWB), lightness-A-B (LAB), Luminance-Chroma-Hue (LCH), Cyan-Magenta-Yellow-Key (CMYK), Natural colors (NCOL) ή με όνομα χρώματος. Ένα κανάλι Alpha είναι επίσης διαθέσιμο για να υποδεικνύει διαφάνεια.

```java
public class Color
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Color](color/#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `Color`. Από προεπιλογή το χρώμα είναι μαύρο. |
| [Color](color/#constructor_1)(byte, byte, byte) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Color`. Όλα τα συστατικά χρώματος πρέπει να βρίσκονται στο εύρος 0-255. |
| [Color](color/#constructor_5)(float, float, float) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Color`. Όλα τα συστατικά χρώματος πρέπει να βρίσκονται στο εύρος 0-1. |
| [Color](color/#constructor_3)(int, int, int) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Color`. Όλα τα συστατικά χρώματος πρέπει να βρίσκονται στο εύρος 0-255. |
| [Color](color/#constructor_2)(byte, byte, byte, byte) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Color`. Όλα τα συστατικά χρώματος πρέπει να βρίσκονται στο εύρος 0-255. |
| [Color](color/#constructor_6)(float, float, float, float) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Color`. Όλα τα συστατικά χρώματος πρέπει να βρίσκονται στο εύρος 0-1. |
| [Color](color/#constructor_4)(int, int, int, int) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Color`. Όλα τα συστατικά χρώματος πρέπει να βρίσκονται στο εύρος 0-255. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getAlpha](../../com.aspose.html.drawing/color/alpha/) Αντιπροσωπεύει το συστατικό alpha του χρώματος. |
| [getBlue](../../com.aspose.html.drawing/color/blue/) Αντιπροσωπεύει το συστατικό μπλε του χρώματος. |
| [getGreen](../../com.aspose.html.drawing/color/green/) Αντιπροσωπεύει το συστατικό πράσινο του χρώματος. |
| [getRed](../../com.aspose.html.drawing/color/red/) Αντιπροσωπεύει το συστατικό κόκκινο του χρώματος |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [FromCmyk](../../com.aspose.html.drawing/color/fromcmyk/)(float, float, float, float) | Επιστρέφει ένα νέο Color με τις ζητούμενες τιμές cyan, magenta, yellow, key (μαύρο). |
| static [FromCmyka](../../com.aspose.html.drawing/color/fromcmyka/)(float, float, float, float, float) | Επιστρέφει ένα νέο Color με τις ζητούμενες τιμές cyan, magenta, yellow, key (μαύρο), alpha. |
| static [FromGray](../../com.aspose.html.drawing/color/fromgray/)(float) | Επιστρέφει ένα νέο Color με την ζητούμενη τιμή γκρι. |
| static [FromHsl](../../com.aspose.html.drawing/color/fromhsl/)(float, float, float) | Επιστρέφει ένα νέο Color με τις ζητούμενες τιμές hue, saturation, saturation. |
| static [FromHsla](../../com.aspose.html.drawing/color/fromhsla/)(float, float, float, float) | Επιστρέφει ένα νέο Color με τις ζητούμενες τιμές hue, saturation, saturation, alpha. |
| static [FromHsv](../../com.aspose.html.drawing/color/fromhsv/)(float, float, float) | Επιστρέφει ένα νέο Color με τις ζητούμενες τιμές hue, saturation, value. |
| static [FromHsva](../../com.aspose.html.drawing/color/fromhsva/)(float, float, float, float) | Επιστρέφει ένα νέο Color με τις ζητούμενες τιμές hue, saturation, value, alpha. |
| static [FromHwb](../../com.aspose.html.drawing/color/fromhwb/)(float, float, float) | Επιστρέφει ένα νέο Color με τις ζητούμενες τιμές hue, whiteness, blackness. |
| static [FromHwba](../../com.aspose.html.drawing/color/fromhwba/)(float, float, float, float) | Επιστρέφει ένα νέο Color με τις ζητούμενες τιμές hue, whiteness, blackness. |
| static [FromInt](../../com.aspose.html.drawing/color/fromint/)(int) | Επιστρέφει ένα νέο Color με την ζητούμενη τιμή ARGB. |
| static [FromLab](../../com.aspose.html.drawing/color/fromlab/)(float, float, float) | Επιστρέφει ένα νέο Color με τις ζητούμενες τιμές lightness, A, B. |
| static [FromLaba](../../com.aspose.html.drawing/color/fromlaba/)(float, float, float, float) | Επιστρέφει ένα νέο Color με τις ζητούμενες τιμές lightness, A, B, alpha. |
| static [FromLch](../../com.aspose.html.drawing/color/fromlch/)(float, float, float) | Επιστρέφει ένα νέο Color με τις ζητούμενες τιμές luminance, chroma, hue. |
| static [FromLcha](../../com.aspose.html.drawing/color/fromlcha/)(float, float, float, float) | Επιστρέφει ένα νέο Color με τις ζητούμενες τιμές luminance, chroma, hue, alpha. |
| static [FromOklab](../../com.aspose.html.drawing/color/fromoklab/)(float, float, float) | Επιστρέφει ένα νέο Color με τις ζητούμενες τιμές lightness, A, B για το μοντέλο OKLAB. |
| static [FromOklaba](../../com.aspose.html.drawing/color/fromoklaba/)(float, float, float, float) | Επιστρέφει ένα νέο Color με τις ζητούμενες τιμές lightness, A, B, alpha για το μοντέλο OKLAB. |
| static [FromOklch](../../com.aspose.html.drawing/color/fromoklch/)(float, float, float) | Επιστρέφει ένα νέο Color με τις ζητούμενες τιμές luminance, chroma, hue για το μοντέλο OKLAB. |
| static [FromOklcha](../../com.aspose.html.drawing/color/fromoklcha/)(float, float, float, float) | Επιστρέφει ένα νέο Color με τις ζητούμενες τιμές luminance, chroma, hue, alpha για το μοντέλο OKLAB. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb)(byte, byte, byte) | Επιστρέφει ένα νέο Color με τις ζητούμενες τιμές ged, green, blue. Όλα τα συστατικά χρώματος πρέπει να είναι στο εύρος 0-255. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_2)(float, float, float) | Επιστρέφει ένα νέο Color με τις ζητούμενες τιμές ged, green, blue. Όλα τα συστατικά χρώματος πρέπει να είναι στο εύρος 0-1. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_1)(int, int, int) | Επιστρέφει ένα νέο Color με τις ζητούμενες τιμές ged, green, blue. Όλα τα συστατικά χρώματος πρέπει να είναι στο εύρος 0-255. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba)(byte, byte, byte, byte) | Επιστρέφει ένα νέο Color με τις ζητούμενες τιμές ged, green, blue, alpha. Όλα τα συστατικά χρώματος πρέπει να είναι στο εύρος 0-255. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_2)(float, float, float, float) | Επιστρέφει ένα νέο Color με τις ζητούμενες τιμές ged, green, blue, alpha. Όλα τα συστατικά χρώματος πρέπει να είναι στο εύρος 0-1. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_1)(int, int, int, int) | Επιστρέφει ένα νέο Color με τις ζητούμενες τιμές ged, green, blue, alpha. Όλα τα συστατικά χρώματος πρέπει να είναι στο εύρος 0-255. |
| static [FromString](../../com.aspose.html.drawing/color/fromString/)(String) | Αναλύει το String που περιέχει το χρώμα CSS και επιστρέφει ένα νέο Color. |
| static [FromUint](../../com.aspose.html.drawing/color/fromuint/)(uint) | Επιστρέφει ένα νέο Color με την ζητούμενη τιμή ARGB. |
| [addLuminosity](../../com.aspose.html.drawing/color/addluminosity/)(float) | Δημιουργεί αντίγραφο του Color με το άθροισμα της luminosity του και της τιμής delta. |
| [convert](../../com.aspose.html.drawing/color/convert/)(ColorModel) | Επιστρέφει τα συστατικά χρώματος στη μορφή του καθορισμένου μοντέλου χρώματος. |
| [equals](../../com.aspose.html.drawing/color/equals/)(object) | Καθορίζει εάν το καθορισμένο `Color` είναι ίσο με αυτήν την περίπτωση. |
| [getComplementary](../../com.aspose.html.drawing/color/getcomplementary/)() | Επιστρέφει ένα νέο χρώμα που βρίσκεται στην αντίθετη πλευρά του χρωματικού τροχού από το αρχικό. |
| [getHashCode](../../com.aspose.html.drawing/color/gethashcode/)() | Επιστρέφει έναν κωδικό κατακερματισμού. |
| [getHue](../../com.aspose.html.drawing/color/gethue/)() | Επιστρέφει το Hue του Color. |
| [getLuminosity](../../com.aspose.html.drawing/color/getluminosity/)() | Επιστρέφει τη luminosity του Color. |
| [getSaturation](../../com.aspose.html.drawing/color/getsaturation/)() | Επιστρέφει το saturation του Color. |
| [toInt](../../com.aspose.html.drawing/color/toint/)() | Κωδικοποιεί τα συστατικά ARGB του Color σε int. |
| [toName](../../com.aspose.html.drawing/color/toname/)() | Επιστρέφει το όνομα του χρώματος εάν ταιριάζει με χρώμα στη λίστα των ονομαστικών χρωμάτων CSS, ή ένα κενό String. |
| [toNaturalColorString](../../com.aspose.html.drawing/color/tonaturalcolorString/)(int) | Επιστρέφει ένα Natural colors (NCol) καθορισμένο χρώμα χρησιμοποιώντας ένα γράμμα χρώματος με αριθμό για να ορίσει την απόσταση (σε ποσοστό) από το χρώμα. |
| [toRgbaHexString](../../com.aspose.html.drawing/color/torgbahexString/)() | Επιστρέφει ένα Hexadecimal χρώμα που καθορίζεται με: #RRGGBBAA. |
| [toRgbaString](../../com.aspose.html.drawing/color/torgbaString/)() | Επιστρέφει ένα String που περιέχει το χρώμα RGBA που καθορίζεται από: rgba(R, G, B, A). |
| [toRgbHexString](../../com.aspose.html.drawing/color/torgbhexString/)() | Επιστρέφει ένα δεκαεξαδικό χρώμα που καθορίζεται με: #RRGGBB. |
| [toRgbString](../../com.aspose.html.drawing/color/torgbString/)() | Επιστρέφει ένα String που περιέχει το χρώμα RGB που καθορίζεται από: rgb(R, G, B). |
| [toString](../../com.aspose.html.drawing/color/toString/)() | Επιστρέφει ένα String που αποτελείται από τις τιμές των συστατικών RGBA. |
| [toUint](../../com.aspose.html.drawing/color/touint/)() | Κωδικοποιεί τα συστατικά ARGB του Color σε unsigned int. |
| [withAlpha](../../com.aspose.html.drawing/color/withalpha/)(float) | Δημιουργεί αντίγραφο του Color με το καθορισμένο συστατικό alpha. |
| [withHue](../../com.aspose.html.drawing/color/withhue/)(float) | Δημιουργεί αντίγραφο του Color με το καθορισμένο Hue. |
| [withLuminosity](../../com.aspose.html.drawing/color/withluminosity/)(float) | Δημιουργεί αντίγραφο του Color με την καθορισμένη φωτεινότητα. |
| [withSaturation](../../com.aspose.html.drawing/color/withsaturation/)(float) | Δημιουργεί αντίγραφο του Color με τον καθορισμένο κορεσμό. |

### Δείτε επίσης

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
