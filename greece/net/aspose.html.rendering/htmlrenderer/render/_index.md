---
title: HtmlRenderer.Render
second_title: Aspose.HTML για Αναφορά API .NET
description: HtmlRenderer μέθοδος. Καθορίζει τη μέθοδο απόδοσης πολλαπλώνDocument s σε συγκεκριμέναIDevice . Η απόδοση θα εκτελεστεί όταν δεν υπάρχουν λειτουργίες δικτύου για φόρτωση πόρων ενεργούς χρονοδιακόπτες εργασίες κινούμενης εικόνας ή καθορισμένο χρονικό όριο λήξης.
type: docs
weight: 20
url: /el/net/aspose.html.rendering/htmlrenderer/render/
---
## HtmlRenderer.Render method

Καθορίζει τη μέθοδο απόδοσης πολλαπλών[`Document`](../../../aspose.html.dom/document/) s σε συγκεκριμένα[`IDevice`](../../idevice/) . Η απόδοση θα εκτελεστεί όταν δεν υπάρχουν λειτουργίες δικτύου για φόρτωση πόρων, ενεργούς χρονοδιακόπτες, εργασίες κινούμενης εικόνας ή καθορισμένο χρονικό όριο λήξης.

```csharp
public override void Render(IDevice device, TimeSpan timeout, params Document[] documents)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| device | IDevice | Η συσκευή εξόδου. |
| timeout | TimeSpan | ΕΝΑTimeSpan που αντιπροσωπεύει τον αριθμό των χιλιοστών του δευτερολέπτου για αναμονή, ή αTimeSpan που αντιπροσωπεύει -1 χιλιοστό του δευτερολέπτου για απεριόριστη αναμονή. |
| documents | Document[] | Τα έγγραφα προς απόδοση. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [Document](../../../aspose.html.dom/document/)
* class [HtmlRenderer](../)
* χώρος ονομάτων [Aspose.Html.Rendering](../../htmlrenderer/)
* συνέλευση [Aspose.HTML](../../../)


