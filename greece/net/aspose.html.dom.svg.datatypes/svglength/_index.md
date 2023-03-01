---
title: Class SVGLength
second_title: Aspose.HTML για Αναφορά API .NET
description: Aspose.Html.Dom.Svg.DataTypes.SVGLength τάξη. Η διεπαφή SVGLength αντιστοιχεί στον βασικό τύπο δεδομένων μήκους. Ένα αντικείμενο SVGLength μπορεί να οριστεί ως μόνο για ανάγνωση πράγμα που σημαίνει ότι οι προσπάθειες τροποποίησης του αντικειμένου θα έχουν ως αποτέλεσμα τη δημιουργία εξαίρεσης όπως περιγράφεται παρακάτω.
type: docs
weight: 1200
url: /el/net/aspose.html.dom.svg.datatypes/svglength/
---
## SVGLength class

Η διεπαφή SVGLength αντιστοιχεί στον βασικό τύπο δεδομένων μήκους. Ένα αντικείμενο SVGLength μπορεί να οριστεί ως μόνο για ανάγνωση, πράγμα που σημαίνει ότι οι προσπάθειες τροποποίησης του αντικειμένου θα έχουν ως αποτέλεσμα τη δημιουργία εξαίρεσης, όπως περιγράφεται παρακάτω.

```csharp
public class SVGLength : SVGValueType
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [UnitType](../../aspose.html.dom.svg.datatypes/svglength/unittype/) { get; } | Ο τύπος της τιμής όπως καθορίζεται από μία από τις σταθερές SVG_LENGTHTYPE_* που ορίζονται σε αυτήν τη διεπαφή. |
| [Value](../../aspose.html.dom.svg.datatypes/svglength/value/) { get; set; } | Η τιμή ως τιμή κινητής υποδιαστολής, σε μονάδες χρήστη. Η ρύθμιση αυτού του χαρακτηριστικού θα προκαλέσει την αυτόματη ενημέρωση των valueInSpecifiedUnits και valueAsString ώστε να αντικατοπτρίζει αυτήν τη ρύθμιση. |
| [ValueAsString](../../aspose.html.dom.svg.datatypes/svglength/valueasstring/) { get; set; } | Η τιμή ως τιμή συμβολοσειράς, στις μονάδες που εκφράζονται με unitType. Η ρύθμιση αυτού του χαρακτηριστικού θα προκαλέσει την αυτόματη ενημέρωση των τιμών, valueInSpecifiedUnits και unitType ώστε να αντικατοπτρίζει αυτήν τη ρύθμιση. |
| [ValueInSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/valueinspecifiedunits/) { get; set; } | Η τιμή ως τιμή κινητής υποδιαστολής, στις μονάδες που εκφράζεται με unitType. Η ρύθμιση αυτού του χαρακτηριστικού θα προκαλέσει την αυτόματη ενημέρωση της τιμής και του valueAsString ώστε να αντικατοπτρίζει αυτήν τη ρύθμιση. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/)(ushort) | Διατηρήστε την ίδια υποκείμενη αποθηκευμένη τιμή, αλλά επαναφέρετε το αναγνωριστικό αποθηκευμένης μονάδας στο δεδομένο unitType. Χαρακτηριστικά αντικειμένου unitType, valueInSpecifiedUnits και valueAsString ενδέχεται να τροποποιηθούν ως αποτέλεσμα αυτής της μεθόδου. Για παράδειγμα, εάν η αρχική τιμή ήταν "0,5cm" και η μέθοδος χρησιμοποιήθηκε για μετατροπή σε χιλιοστά, τότε το unitType θα άλλαζε σε SVG_LENGTHTYPE_MM, το valueInSpecifiedUnits θα άλλαζε στην αριθμητική τιμή 5 και το valueAsString θα άλλαζε σε "5mm". |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Απελευθερώνει μη διαχειριζόμενους και - προαιρετικά - διαχειριζόμενους πόρους. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση αντικειμένου ECMAScriptType . |
| [NewValueSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/)(ushort, float) | Επαναφέρετε την τιμή ως αριθμό με ένα συσχετισμένο unitType, αντικαθιστώντας έτσι τις τιμές για όλα τα χαρακτηριστικά του αντικειμένου. |
| override [ToString](../../aspose.html.dom.svg.datatypes/svglength/tostring/)() | Επιστρέφει αString που αντιπροσωπεύει αυτήν την περίπτωση. |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_cm/) | Καθορίστηκε μια τιμή χρησιμοποιώντας τις μονάδες cm που ορίζονται στο CSS2. |
| const [SVG_LENGTHTYPE_EMS](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_ems/) | Καθορίστηκε μια τιμή χρησιμοποιώντας τις μονάδες em που ορίζονται στο CSS2. |
| const [SVG_LENGTHTYPE_EXS](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_exs/) | Καθορίστηκε μια τιμή χρησιμοποιώντας τις μονάδες ex που ορίζονται στο CSS2. |
| const [SVG_LENGTHTYPE_IN](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_in/) | Καθορίστηκε μια τιμή χρησιμοποιώντας τις μονάδες in που ορίζονται στο CSS2. |
| const [SVG_LENGTHTYPE_MM](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_mm/) | Καθορίστηκε μια τιμή χρησιμοποιώντας τις μονάδες mm που ορίζονται στο CSS2. |
| const [SVG_LENGTHTYPE_NUMBER](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_number/) | Δεν παρέχεται τύπος μονάδας (δηλαδή, καθορίστηκε τιμή χωρίς μονάδα), η οποία υποδεικνύει μια τιμή σε μονάδες χρήστη. |
| const [SVG_LENGTHTYPE_PC](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pc/) | Καθορίστηκε μια τιμή χρησιμοποιώντας τις μονάδες υπολογιστή που ορίζονται στο CSS2. |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_percentage/) | Καθορίστηκε μια ποσοστιαία τιμή. |
| const [SVG_LENGTHTYPE_PT](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pt/) | Καθορίστηκε μια τιμή χρησιμοποιώντας τις μονάδες pt που ορίζονται στο CSS2. |
| const [SVG_LENGTHTYPE_PX](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_px/) | Καθορίστηκε μια τιμή χρησιμοποιώντας τις μονάδες px που ορίζονται στο CSS2. |
| const [SVG_LENGTHTYPE_UNKNOWN](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_unknown/) | Ο τύπος μονάδας δεν είναι ένας από τους προκαθορισμένους τύπους μονάδας. Δεν είναι έγκυρο να επιχειρήσετε να ορίσετε μια νέα τιμή αυτού του τύπου ή να προσπαθήσετε να αλλάξετε μια υπάρχουσα τιμή σε αυτόν τον τύπο. |

### Δείτε επίσης

* class [SVGValueType](../svgvaluetype/)
* χώρος ονομάτων [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* συνέλευση [Aspose.HTML](../../)


