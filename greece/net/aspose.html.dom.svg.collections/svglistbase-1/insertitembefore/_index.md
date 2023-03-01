---
title: SVGListBase1.InsertItemBefore
second_title: Aspose.HTML για Αναφορά API .NET
description: SVGListBase μέθοδος. Εισάγει ένα νέο στοιχείο στη λίστα στην καθορισμένη θέση. Το πρώτο στοιχείο είναι ο αριθμός 0.
type: docs
weight: 90
url: /el/net/aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase&lt;T&gt;.InsertItemBefore method

Εισάγει ένα νέο στοιχείο στη λίστα στην καθορισμένη θέση. Το πρώτο στοιχείο είναι ο αριθμός 0.

```csharp
public T InsertItemBefore(T newItem, ulong index)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newItem | T | Το στοιχείο που πρόκειται να εισαχθεί στη λίστα. |
| index | UInt64 | Το ευρετήριο του στοιχείου πριν από το οποίο θα εισαχθεί το νέο στοιχείο. Το πρώτο στοιχείο είναι ο αριθμός 0. Εάν το ευρετήριο είναι ίσο με 0, τότε το νέο στοιχείο εισάγεται στο μπροστινό μέρος της λίστας. Εάν το ευρετήριο είναι μεγαλύτερο ή ίσο με το numberOfItems, τότε το νέο στοιχείο προστίθεται στο τέλος της λίστας. |

### Επιστρεφόμενη Αξία

Το αντικείμενο που έχει εισαχθεί.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Κώδικας[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). Αυξάνεται όταν η λίστα δεν μπορεί να τροποποιηθεί. |

### Δείτε επίσης

* class [SVGListBase&lt;T&gt;](../)
* χώρος ονομάτων [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* συνέλευση [Aspose.HTML](../../../)


