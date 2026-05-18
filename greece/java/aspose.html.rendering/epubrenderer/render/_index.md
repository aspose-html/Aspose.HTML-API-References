---
title: "EpubRenderer.Render"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "EpubRenderer μέθοδος. Ορίζει μέθοδο για την απόδοση πολλαπλών ροών EPub σε συγκεκριμένο IDevice. Η απόδοση θα εκτελεστεί όταν δεν υπάρχουν ενεργές λειτουργίες δικτύου για τη φόρτωση πόρων, ενεργά χρονόμετρα, εργασίες animation ή όταν έχει λήξει το καθορισμένο χρονικό όριο."
type: docs

url: /el/java/com.aspose.html.rendering/epubrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_10}

Ορίζει μέθοδο για την απόδοση πολλαπλών ροών EPub σε συγκεκριμένο [`IDevice`](../../idevice/). Η απόδοση θα εκτελεστεί όταν δεν υπάρχουν λειτουργίες δικτύου για τη φόρτωση πόρων, ενεργά χρονόμετρα, εργασίες animation ή όταν έχει λήξει το καθορισμένο χρονικό όριο.

```java
public void Render(IDevice device, TimeSpan timeout, params Stream[] sources)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| συσκευή | IDevice | Η συσκευή εξόδου. |
| timeout | TimeSpan | Ένα TimeSpan που αντιπροσωπεύει τον αριθμό των χιλιοστών του δευτερολέπτου για αναμονή, ή ένα TimeSpan που αντιπροσωπεύει -1 χιλιοστό του δευτερολέπτου για απεριόριστη αναμονή. |
| έγγραφα | Stream[] | Τα έγγραφα για απόδοση. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params Stream[]) {#render_9}

Ορίζει μια μέθοδο για την απόδοση πολλαπλών εγγράφων EPub σε συγκεκριμένο [`IDevice`](../../idevice/), χρησιμοποιώντας ένα token ακύρωσης για να ζητήσει την ακύρωση της λειτουργίας.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params Stream[] sources)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| συσκευή | IDevice | Η συσκευή εξόδου. |
| cancellationToken | CancellationToken | Ένα CancellationToken για παρακολούθηση ενώ περιμένετε την ολοκλήρωση της εργασίας. |
| πηγές | Stream[] | Τα έγγραφα EPub προς απόδοση. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

Αποδίδει το έγγραφο EPub σε καθορισμένο [`IDevice`](../../idevice/).

```java
public void Render(IDevice device, Stream source, Configuration configuration)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| συσκευή | IDevice | Η συσκευή. |
| έγγραφο | Ροή | Το έγγραφο. |
| διαμόρφωση | Διαμόρφωση | Η διαμόρφωση. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

Αποδίδει το έγγραφο EPub σε καθορισμένο [`IDevice`](../../idevice/). Η απόδοση θα εκτελεστεί όταν δεν υπάρχουν λειτουργίες δικτύου για τη φόρτωση πόρων, ενεργά χρονόμετρα, εργασίες animation ή όταν έχει λήξει το καθορισμένο χρονικό όριο.

```java
public void Render(IDevice device, Stream source, Configuration configuration, TimeSpan timeout)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| συσκευή | IDevice | Η συσκευή. |
| έγγραφο | Ροή | Το έγγραφο. |
| διαμόρφωση | Διαμόρφωση | Η διαμόρφωση. |
| timeout | TimeSpan | Ένα TimeSpan που αντιπροσωπεύει τον αριθμό των χιλιοστών του δευτερολέπτου για αναμονή, ή ένα TimeSpan που αντιπροσωπεύει -1 χιλιοστό του δευτερολέπτου για απεριόριστη αναμονή. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

Αποδίδει πολλαπλά έγγραφα EPub σε καθορισμένο [`IDevice`](../../idevice/).

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| συσκευή | IDevice | Η συσκευή. |
| έγγραφα | IList`1 | Η IList των εγγράφων για απόδοση. |
| διαμόρφωση | Διαμόρφωση | Η διαμόρφωση. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

Αποδίδει πολλαπλά έγγραφα EPub σε καθορισμένο [`IDevice`](../../idevice/). Η απόδοση θα εκτελεστεί όταν δεν υπάρχουν λειτουργίες δικτύου για τη φόρτωση πόρων, ενεργά χρονόμετρα, εργασίες animation ή όταν έχει λήξει το καθορισμένο χρονικό όριο.

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration, 
    TimeSpan timeout)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| συσκευή | IDevice | Η συσκευή. |
| έγγραφα | IList`1 | Η IList των εγγράφων για απόδοση. |
| διαμόρφωση | Διαμόρφωση | Η διαμόρφωση. |
| timeout | TimeSpan | Ένα TimeSpan που αντιπροσωπεύει τον αριθμό των χιλιοστών του δευτερολέπτου για αναμονή, ή ένα TimeSpan που αντιπροσωπεύει -1 χιλιοστό του δευτερολέπτου για απεριόριστη αναμονή. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
