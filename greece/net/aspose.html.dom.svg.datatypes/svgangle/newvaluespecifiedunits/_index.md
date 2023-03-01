---
title: SVGAngle.NewValueSpecifiedUnits
second_title: Aspose.HTML για Αναφορά API .NET
description: SVGAngle μέθοδος. Επαναφέρετε την τιμή ως αριθμό με ένα συσχετισμένο unitType αντικαθιστώντας έτσι τις τιμές για όλα τα χαρακτηριστικά του αντικειμένου.
type: docs
weight: 60
url: /el/net/aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

Επαναφέρετε την τιμή ως αριθμό με ένα συσχετισμένο unitType, αντικαθιστώντας έτσι τις τιμές για όλα τα χαρακτηριστικά του αντικειμένου.

```csharp
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newUnitType | UInt16 | Ο τύπος μονάδας για την τιμή (π.χ. SVG_ANGLETYPE_DEG). |
| valueInSpecifiedUnits | Single | Η τιμή της γωνίας. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Κωδ[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) Αυξάνεται εάν το unitType είναι SVG_ANGLETYPE_UNKNOWN ή δεν είναι έγκυρη σταθερά τύπου μονάδας (μία από τις άλλες σταθερές SVG_ANGLETYPE_* που ορίζονται σε αυτήν τη διεπαφή). |
| [DOMException](../../../aspose.html.dom/domexception/) | Κωδ[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) Ανυψώνεται όταν η γωνία αντιστοιχεί σε ένα χαρακτηριστικό μόνο για ανάγνωση ή όταν το ίδιο το αντικείμενο είναι μόνο για ανάγνωση. |

### Δείτε επίσης

* class [SVGAngle](../)
* χώρος ονομάτων [Aspose.Html.Dom.Svg.DataTypes](../../svgangle/)
* συνέλευση [Aspose.HTML](../../../)


