---
title: MhtmlRenderer.Render
second_title: Aspose.HTML για Αναφορά API .NET
description: MhtmlRenderer μέθοδος. Αποδίδει πολλαπλά έγγραφα MHTML σε καθορισμέναIDevice . Η απόδοση θα εκτελεστεί όταν δεν υπάρχουν λειτουργίες δικτύου για φόρτωση πόρων ενεργούς χρονοδιακόπτες εργασίες κινούμενης εικόνας ή καθορισμένο χρονικό όριο λήξης.
type: docs
weight: 20
url: /el/net/aspose.html.rendering/mhtmlrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_9}

Αποδίδει πολλαπλά έγγραφα MHTML σε καθορισμένα[`IDevice`](../../idevice/) . Η απόδοση θα εκτελεστεί όταν δεν υπάρχουν λειτουργίες δικτύου για φόρτωση πόρων, ενεργούς χρονοδιακόπτες, εργασίες κινούμενης εικόνας ή καθορισμένο χρονικό όριο λήξης.

```csharp
public override void Render(IDevice device, TimeSpan timeout, params Stream[] documents)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| device | IDevice | Η συσκευή. |
| timeout | TimeSpan | ΕΝΑTimeSpan που αντιπροσωπεύει τον αριθμό των χιλιοστών του δευτερολέπτου για αναμονή, ή αTimeSpan που αντιπροσωπεύει -1 χιλιοστό του δευτερολέπτου για απεριόριστη αναμονή. |
| documents | Stream[] | Τα έγγραφα προς απόδοση. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* χώρος ονομάτων [Aspose.Html.Rendering](../../mhtmlrenderer/)
* συνέλευση [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

Αποδίδει έγγραφο MHTML σε καθορισμένο[`IDevice`](../../idevice/) .

```csharp
public void Render(IDevice device, Stream document, Configuration configuration)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| device | IDevice | Η συσκευή. |
| document | Stream | Το έγγραφο. |
| configuration | Configuration | Η διαμόρφωση. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [MhtmlRenderer](../)
* χώρος ονομάτων [Aspose.Html.Rendering](../../mhtmlrenderer/)
* συνέλευση [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

Αποδίδει έγγραφο MHTML σε καθορισμένο[`IDevice`](../../idevice/) . Η απόδοση θα εκτελεστεί όταν δεν υπάρχουν λειτουργίες δικτύου για φόρτωση πόρων, ενεργούς χρονοδιακόπτες, εργασίες κινούμενης εικόνας ή καθορισμένο χρονικό όριο λήξης.

```csharp
public void Render(IDevice device, Stream document, Configuration configuration, TimeSpan timeout)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| device | IDevice | Η συσκευή. |
| document | Stream | Το έγγραφο. |
| configuration | Configuration | Η διαμόρφωση. |
| timeout | TimeSpan | ΕΝΑTimeSpan που αντιπροσωπεύει τον αριθμό των χιλιοστών του δευτερολέπτου για αναμονή, ή αTimeSpan που αντιπροσωπεύει -1 χιλιοστό του δευτερολέπτου για απεριόριστη αναμονή. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [MhtmlRenderer](../)
* χώρος ονομάτων [Aspose.Html.Rendering](../../mhtmlrenderer/)
* συνέλευση [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

Αποδίδει πολλαπλά έγγραφα MHTML σε καθορισμένα[`IDevice`](../../idevice/) .

```csharp
public void Render(IDevice device, IList<Stream> documents, Configuration configuration)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| device | IDevice | Η συσκευή. |
| documents | IList`1 | οIList των εγγράφων προς απόδοση. |
| configuration | Configuration | Η διαμόρφωση. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [MhtmlRenderer](../)
* χώρος ονομάτων [Aspose.Html.Rendering](../../mhtmlrenderer/)
* συνέλευση [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

Αποδίδει πολλαπλά έγγραφα MHTML σε καθορισμένα[`IDevice`](../../idevice/) . Η απόδοση θα εκτελεστεί όταν δεν υπάρχουν λειτουργίες δικτύου για φόρτωση πόρων, ενεργούς χρονοδιακόπτες, εργασίες κινούμενης εικόνας ή καθορισμένο χρονικό όριο λήξης.

```csharp
public void Render(IDevice device, IList<Stream> documents, Configuration configuration, 
    TimeSpan timeout)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| device | IDevice | Η συσκευή. |
| documents | IList`1 | οIList των εγγράφων προς απόδοση. |
| configuration | Configuration | Η διαμόρφωση. |
| timeout | TimeSpan | ΕΝΑTimeSpan που αντιπροσωπεύει τον αριθμό των χιλιοστών του δευτερολέπτου για αναμονή, ή αTimeSpan που αντιπροσωπεύει -1 χιλιοστό του δευτερολέπτου για απεριόριστη αναμονή. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [MhtmlRenderer](../)
* χώρος ονομάτων [Aspose.Html.Rendering](../../mhtmlrenderer/)
* συνέλευση [Aspose.HTML](../../../)


