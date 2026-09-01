---
title: "SvgRenderer.Render"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "SvgRenderer method. Ορίζει μέθοδο για την απόδοση πολλαπλών SVGDocuments σε συγκεκριμένο IDevice. Η απόδοση θα εκτελεστεί όταν δεν υπάρχουν καμία λειτουργία δικτύου για τη φόρτωση πόρων, ενεργά χρονόμετρα, εργασίες animation ή όταν έχει λήξει το καθορισμένο χρονικό όριο"
type: docs

url: /el/java/com.aspose.html.rendering/svgrenderer/render/
---
## Render(IDevice, TimeSpan, params SVGDocument[]) {#render_6}

Ορίζει μέθοδο για την απόδοση πολλαπλών [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)s σε συγκεκριμένο [`IDevice`](../../idevice/). Η απόδοση θα εκτελεστεί όταν δεν υπάρχουν καμία λειτουργία δικτύου για τη φόρτωση πόρων, ενεργά χρονόμετρα, εργασίες animation ή όταν έχει λήξει το καθορισμένο χρονικό όριο.

```java
public void Render(IDevice device, TimeSpan timeout, params SVGDocument[] sources)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| συσκευή | IDevice | Η συσκευή εξόδου. |
| χρονικό όριο | TimeSpan | Ένα TimeSpan που αντιπροσωπεύει τον αριθμό των χιλιοστών του δευτερολέπτου για αναμονή, ή ένα TimeSpan που αντιπροσωπεύει -1 χιλιοστέπτο του δευτερολέπτου για απεριόριστη αναμονή. |
| έγγραφα | SVGDocument[] | Τα έγγραφα προς απόδοση. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params SVGDocument[]) {#render_5}

Ορίζει μια μέθοδο για την απόδοση πολλαπλών [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)s σε συγκεκριμένο [`IDevice`](../../idevice/), χρησιμοποιώντας ένα token ακύρωσης για να ζητήσει την ακύρωση της λειτουργίας.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params SVGDocument[] sources)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| συσκευή | IDevice | Η συσκευή εξόδου. |
| cancellationToken | CancellationToken | Ένα token ακύρωσης για παρακολούθηση ενώ περιμένετε την ολοκλήρωση της εργασίας. |
| πηγές | SVGDocument[] | Τα έγγραφα SVG για απόδοση. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
