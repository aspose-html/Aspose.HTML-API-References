---
title: "Κλάση SVGAngle"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.svg.datatypes.SVGAngle class. Το interface SVGAngle αντιστοιχεί στον βασικό τύπο δεδομένων angle"
type: docs

url: /el/java/com.aspose.html.dom.svg.datatypes/svgangle/
---
## SVGAngle class

Η διεπαφή SVGAngle αντιστοιχεί στον βασικό τύπο δεδομένων γωνίας.

```java
public class SVGAngle : SVGValueType
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svgangle/unittype/) Ο τύπος της τιμής όπως ορίζεται από μία από τις σταθερές SVG_ANGLETYPE_* που ορίζονται σε αυτό το interface. |
[getValue]
[setValue] The angle value as a floating point value, in degrees. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The angle value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The angle value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/)(ushort) | Διατηρήστε την ίδια υποκείμενη αποθηκευμένη τιμή, αλλά επαναφέρετε το αποθηκευμένο αναγνωριστικό μονάδας στον δεδομένο unitType. Τα χαρακτηριστικά αντικειμένου unitType, valueInSpecifiedUnits και valueAsString μπορεί να τροποποιηθούν ως αποτέλεσμα αυτής της μεθόδου. |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Απελευθερώνει μη διαχειριζόμενους και - προαιρετικά - διαχειριζόμενους πόρους. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του αντικειμένου ECMAScript. |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/)(ushort, float) | Επαναφέρετε την τιμή ως αριθμό με συσχετισμένο unitType, αντικαθιστώντας έτσι τις τιμές για όλα τα χαρακτηριστικά του αντικειμένου. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgangle/toString/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_deg/) | Ο τύπος μονάδας ορίστηκε ρητά σε μοίρες. |
| const [SVG_ANGLETYPE_GRAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_grad/) | Ο τύπος μονάδας είναι ακτίνια. |
| const [SVG_ANGLETYPE_RAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_rad/) | Ο τύπος μονάδας είναι ακτίνια. |
| const [SVG_ANGLETYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unknown/) | Ο τύπος μονάδας δεν είναι ένας από τους προκαθορισμένους τύπους μονάδας. Είναι άκυρο να προσπαθήσετε να ορίσετε μια νέα τιμή αυτού του τύπου ή να προσπαθήσετε να μεταβιβάσετε μια υπάρχουσα τιμή σε αυτόν τον τύπο. |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unspecified/) | Δεν παρέχεται τύπος μονάδας (δηλαδή, καθορίστηκε μια τιμή χωρίς μονάδα). Για γωνίες, μια τιμή χωρίς μονάδα αντιμετωπίζεται όπως αν είχαν καθοριστεί μοίρες. |

### Δείτε επίσης

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
