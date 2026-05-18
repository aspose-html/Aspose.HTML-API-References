---
title: "SVGLength Κλάση"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.svg.datatypes.SVGLength κλάση. Η διεπαφή SVGLength αντιστοιχεί στον βασικό τύπο δεδομένων μήκος. Ένα αντικείμενο SVGLength μπορεί να οριστεί ως μόνο για ανάγνωση, πράγμα που σημαίνει ότι οι προσπάθειες τροποποίησης του αντικειμένου θα οδηγήσουν σε εξαίρεση όπως περιγράφεται παρακάτω."
type: docs

url: /el/java/com.aspose.html.dom.svg.datatypes/svglength/
---
## SVGLength class

Η διεπαφή SVGLength αντιστοιχεί στον βασικό τύπο δεδομένων length. Ένα αντικείμενο SVGLength μπορεί να οριστεί ως μόνο για ανάγνωση, κάτι που σημαίνει ότι οι προσπάθειες τροποποίησης του αντικειμένου θα προκαλέσουν την εμφάνιση μιας εξαίρεσης, όπως περιγράφεται παρακάτω.

```java
public class SVGLength : SVGValueType
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svglength/unittype/) Ο τύπος της τιμής όπως καθορίζεται από μία από τις σταθερές SVG_LENGTHTYPE_* που ορίζονται σε αυτή τη διεπαφή. |
[getValue]
[setValue] The value as a floating point value, in user units. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/)(ushort) | Διατηρεί την ίδια υποκείμενη αποθηκευμένη τιμή, αλλά επαναφέρει το αποθηκευμένο αναγνωριστικό μονάδας στον δοθέν unitType. Τα χαρακτηριστικά του αντικειμένου unitType, valueInSpecifiedUnits και valueAsString ενδέχεται να τροποποιηθούν ως αποτέλεσμα αυτής της μεθόδου. Για παράδειγμα, εάν η αρχική τιμή ήταν "0.5cm" και η μέθοδος κλήθηκε για μετατροπή σε χιλιοστά, τότε το unitType θα αλλάξει σε SVG_LENGTHTYPE_MM, το valueInSpecifiedUnits θα αλλάξει στην αριθμητική τιμή 5 και το valueAsString θα αλλάξει σε "5mm". |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Απελευθερώνει μη διαχειριζόμενους και - προαιρετικά - διαχειριζόμενους πόρους. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του αντικειμένου ECMAScript. |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/)(ushort, float) | Επαναφέρετε την τιμή ως αριθμό με συσχετισμένο unitType, αντικαθιστώντας έτσι τις τιμές για όλα τα χαρακτηριστικά του αντικειμένου. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svglength/toString/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_cm/) | Μια τιμή καθορίστηκε χρησιμοποιώντας τις μονάδες cm που ορίζονται στο CSS2. |
| const [SVG_LENGTHTYPE_EMS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_ems/) | Μια τιμή καθορίστηκε χρησιμοποιώντας τις μονάδες em που ορίζονται στο CSS2. |
| const [SVG_LENGTHTYPE_EXS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_exs/) | Μια τιμή καθορίστηκε χρησιμοποιώντας τις μονάδες ex που ορίζονται στο CSS2. |
| const [SVG_LENGTHTYPE_IN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_in/) | Μια τιμή καθορίστηκε χρησιμοποιώντας τις μονάδες in που ορίζονται στο CSS2. |
| const [SVG_LENGTHTYPE_MM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_mm/) | Μια τιμή καθορίστηκε χρησιμοποιώντας τις μονάδες mm που ορίζονται στο CSS2. |
| const [SVG_LENGTHTYPE_NUMBER](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_number/) | Δεν παρέχεται τύπος μονάδας (δηλαδή, καθορίστηκε τιμή χωρίς μονάδα), που υποδεικνύει τιμή σε μονάδες χρήστη. |
| const [SVG_LENGTHTYPE_PC](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pc/) | Μια τιμή καθορίστηκε χρησιμοποιώντας τις μονάδες pc που ορίζονται στο CSS2. |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_percentage/) | Καθορίστηκε τιμή ποσοστού. |
| const [SVG_LENGTHTYPE_PT](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pt/) | Μια τιμή καθορίστηκε χρησιμοποιώντας τις μονάδες pt που ορίζονται στο CSS2. |
| const [SVG_LENGTHTYPE_PX](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_px/) | Μια τιμή καθορίστηκε χρησιμοποιώντας τις μονάδες px που ορίζονται στο CSS2. |
| const [SVG_LENGTHTYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_unknown/) | Ο τύπος μονάδας δεν είναι ένας από τους προκαθορισμένους τύπους μονάδας. Είναι άκυρο να προσπαθήσετε να ορίσετε μια νέα τιμή αυτού του τύπου ή να προσπαθήσετε να μεταβιβάσετε μια υπάρχουσα τιμή σε αυτόν τον τύπο. |

### Δείτε επίσης

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
