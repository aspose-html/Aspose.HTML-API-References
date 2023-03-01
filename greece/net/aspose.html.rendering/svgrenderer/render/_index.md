---
title: SvgRenderer.Render
second_title: Aspose.HTML για Αναφορά API .NET
description: SvgRenderer μέθοδος. Καθορίζει τη μέθοδο απόδοσης πολλαπλώνSVGDocument s σε συγκεκριμέναIDevice . Η απόδοση θα εκτελεστεί όταν δεν υπάρχουν λειτουργίες δικτύου για φόρτωση πόρων ενεργούς χρονοδιακόπτες εργασίες κινούμενης εικόνας ή καθορισμένο χρονικό όριο λήξης.
type: docs
weight: 20
url: /el/net/aspose.html.rendering/svgrenderer/render/
---
## SvgRenderer.Render method

Καθορίζει τη μέθοδο απόδοσης πολλαπλών[`SVGDocument`](../../../aspose.html.dom.svg/svgdocument/) s σε συγκεκριμένα[`IDevice`](../../idevice/) . Η απόδοση θα εκτελεστεί όταν δεν υπάρχουν λειτουργίες δικτύου για φόρτωση πόρων, ενεργούς χρονοδιακόπτες, εργασίες κινούμενης εικόνας ή καθορισμένο χρονικό όριο λήξης.

```csharp
public override void Render(IDevice device, TimeSpan timeout, params SVGDocument[] documents)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| device | IDevice | Η συσκευή εξόδου. |
| timeout | TimeSpan | ΕΝΑTimeSpan που αντιπροσωπεύει τον αριθμό των χιλιοστών του δευτερολέπτου για αναμονή, ή αTimeSpan που αντιπροσωπεύει -1 χιλιοστό του δευτερολέπτου για απεριόριστη αναμονή. |
| documents | SVGDocument[] | Τα έγγραφα προς απόδοση. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* χώρος ονομάτων [Aspose.Html.Rendering](../../svgrenderer/)
* συνέλευση [Aspose.HTML](../../../)


