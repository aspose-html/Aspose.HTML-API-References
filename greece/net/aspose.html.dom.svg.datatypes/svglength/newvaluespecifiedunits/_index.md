---
title: SVGLength.NewValueSpecifiedUnits
second_title: Aspose.HTML για Αναφορά API .NET
description: SVGLength μέθοδος. Επαναφέρετε την τιμή ως αριθμό με ένα συσχετισμένο unitType αντικαθιστώντας έτσι τις τιμές για όλα τα χαρακτηριστικά του αντικειμένου.
type: docs
weight: 60
url: /el/net/aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

Επαναφέρετε την τιμή ως αριθμό με ένα συσχετισμένο unitType, αντικαθιστώντας έτσι τις τιμές για όλα τα χαρακτηριστικά του αντικειμένου.

```csharp
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| unitType | UInt16 | Ο τύπος μονάδας για την τιμή. |
| valueInSpecifiedUnits | Single | Η νέα αξία.. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Κωδ[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) Αυξάνεται εάν το unitType είναι SVG_LENGTHTYPE_UNKNOWN ή δεν είναι έγκυρη σταθερά τύπου μονάδας (μία από τις άλλες σταθερές SVG_LENGTHTYPE_* που ορίζονται σε αυτήν τη διεπαφή). |
| [DOMException](../../../aspose.html.dom/domexception/) | Κωδ[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) Αυξάνεται όταν το μήκος αντιστοιχεί σε ένα χαρακτηριστικό μόνο για ανάγνωση ή όταν το ίδιο το αντικείμενο είναι μόνο για ανάγνωση. |

### Δείτε επίσης

* class [SVGLength](../)
* χώρος ονομάτων [Aspose.Html.Dom.Svg.DataTypes](../../svglength/)
* συνέλευση [Aspose.HTML](../../../)


