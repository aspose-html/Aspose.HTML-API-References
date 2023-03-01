---
title: SVGListBase1.ReplaceItem
second_title: Aspose.HTML για Αναφορά API .NET
description: SVGListBase μέθοδος. Αντικαθιστά ένα υπάρχον στοιχείο στη λίστα με ένα νέο στοιχείο.
type: docs
weight: 110
url: /el/net/aspose.html.dom.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase&lt;T&gt;.ReplaceItem method

Αντικαθιστά ένα υπάρχον στοιχείο στη λίστα με ένα νέο στοιχείο.

```csharp
public T ReplaceItem(T newItem, ulong index)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newItem | T | Το στοιχείο που πρόκειται να εισαχθεί στη λίστα. |
| index | UInt64 | Το ευρετήριο του αντικειμένου που πρόκειται να αντικατασταθεί. Το πρώτο στοιχείο είναι ο αριθμός 0. |

### Επιστρεφόμενη Αξία

Το αντικείμενο που έχει εισαχθεί.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Κώδικας[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). Αυξάνεται όταν η λίστα δεν μπορεί να τροποποιηθεί. |
| [DOMException](../../../aspose.html.dom/domexception/) | Κώδικας[`INDEX_SIZE_ERR`](../../../aspose.html.dom/domexception/index_size_err/). Αυξάνεται εάν ο αριθμός ευρετηρίου είναι μεγαλύτερος ή ίσος με το numberOfItems. |

### Δείτε επίσης

* class [SVGListBase&lt;T&gt;](../)
* χώρος ονομάτων [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* συνέλευση [Aspose.HTML](../../../)


