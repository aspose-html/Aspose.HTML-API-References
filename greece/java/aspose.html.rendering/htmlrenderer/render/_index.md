---
title: "HtmlRenderer.Render"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος HtmlRenderer. Ορίζει μέθοδο για την απόδοση πολλαπλών HTMLDocuments σε συγκεκριμένο IDevice"
type: docs

url: /el/java/com.aspose.html.rendering/htmlrenderer/render/
---
## Render(IDevice, TimeSpan, params HTMLDocument[]) {#render_6}

Ορίζει μέθοδο για την απόδοση πολλαπλών [`HTMLDocument`](../../../com.aspose.html/htmldocument/)s σε συγκεκριμένο [`IDevice`](../../idevice/).

```java
public void Render(IDevice device, TimeSpan timeout, params HTMLDocument[] sources)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| συσκευή | IDevice | Η συσκευή εξόδου. |
| χρονικό όριο | TimeSpan | Ένα TimeSpan που αντιπροσωπεύει τον αριθμό των χιλιοστών του δευτερολέπτου για αναμονή, ή ένα TimeSpan που αντιπροσωπεύει -1 χιλιοστέπτο του δευτερολέπτου για απεριόριστη αναμονή. |
| πηγές | HTMLDocument[] | Τα HTML έγγραφα για απόδοση. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params HTMLDocument[]) {#render_5}

Ορίζει μια μέθοδο για την απόδοση πολλαπλών [`HTMLDocument`](../../../com.aspose.html/htmldocument/)s σε συγκεκριμένο [`IDevice`](../../idevice/), χρησιμοποιώντας ένα token ακύρωσης για να ζητήσει την ακύρωση της λειτουργίας.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params HTMLDocument[] sources)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| συσκευή | IDevice | Η συσκευή εξόδου. |
| cancellationToken | CancellationToken | Ένα CancellationToken για παρακολούθηση ενώ περιμένετε την ολοκλήρωση της εργασίας. |
| πηγές | HTMLDocument[] | Τα HTML έγγραφα για απόδοση. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
