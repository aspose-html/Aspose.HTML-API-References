---
title: "RendererTSource Κλάση"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.rendering.Renderer1TSource κλάση. Αντιπροσωπεύει μια αφηρημένη κλάση για όλους τους αποδότες"
type: docs

url: /el/java/com.aspose.html.rendering/renderer-1/
---
## Renderer&lt;TSource&gt; class

Αναπαριστά μια αφηρημένη κλάση για όλους τους renderers.

```java
public abstract class Renderer<TSource> : Renderer
```

| Parameter | Περιγραφή |
| --- | --- |
| TDocument | Ο τύπος του εγγράφου. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Απελευθερώνει μη διαχειριζόμενους και - προαιρετικά - διαχειριζόμενους πόρους. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_3)(IDevice, TSource) | Ορίζει μέθοδο για την απόδοση του !:TDocument σε καθορισμένη [`IDevice`](../idevice/). |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_6)(IDevice, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_1)(IDevice, CancellationToken, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render)(IDevice, int, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_2)(IDevice, TimeSpan, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_4)(IDevice, TSource, int) | Ορίζει μέθοδο για την απόδοση του !:TDocument σε καθορισμένη [`IDevice`](../idevice/). Η απόδοση θα εκτελεστεί όταν δεν υπάρχουν καμία δικτυακή λειτουργία για τη φόρτωση πόρων, ενεργά χρονόμετρα, εργασίες animation ή όταν έχει λήξει το καθορισμένο χρονικό όριο. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_5)(IDevice, TSource, TimeSpan) | Ορίζει μέθοδο για την απόδοση του !:TDocument σε καθορισμένη [`IDevice`](../idevice/). Η απόδοση θα εκτελεστεί όταν δεν υπάρχουν καμία δικτυακή λειτουργία για τη φόρτωση πόρων, ενεργά χρονόμετρα, εργασίες animation ή όταν έχει λήξει το καθορισμένο χρονικό όριο. |

### Δείτε επίσης

* class [Renderer](../renderer/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
