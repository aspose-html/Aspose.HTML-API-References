---
title: "MhtmlRenderer.Render"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος MhtmlRenderer. Αποδίδει πολλαπλά έγγραφα MHTML σε καθορισμένο IDevice. Η απόδοση θα εκτελεστεί όταν δεν υπάρχουν καμία δικτυακή λειτουργία για τη φόρτωση πόρων, ενεργά χρονόμετρα, εργασίες animation ή όταν έχει παρέλθει το καθορισμένο χρονικό όριο."
type: docs

url: /el/java/com.aspose.html.rendering/mhtmlrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_10}

Αποδίδει πολλαπλά έγγραφα MHTML σε καθορισμένο [`IDevice`](../../idevice/). Η απόδοση θα εκτελεστεί όταν δεν υπάρχουν καμία δικτυακή λειτουργία για τη φόρτωση πόρων, ενεργά χρονόμετρα, εργασίες animation ή όταν έχει παρέλθει το καθορισμένο χρονικό όριο.

```java
public void Render(IDevice device, TimeSpan timeout, params Stream[] sources)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| συσκευή | IDevice | Η συσκευή. |
| χρονικό όριο | TimeSpan | Ένα TimeSpan που αντιπροσωπεύει τον αριθμό των χιλιοστών του δευτερολέπτου για αναμονή, ή ένα TimeSpan που αντιπροσωπεύει -1 χιλιοστέπτο του δευτερολέπτου για απεριόριστη αναμονή. |
| έγγραφα | Stream[] | Τα έγγραφα προς απόδοση. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params Stream[]) {#render_9}

Ορίζει μια μέθοδο για την απόδοση πολλαπλών εγγράφων MHTML σε μια συγκεκριμένη [`IDevice`](../../idevice/), χρησιμοποιώντας ένα token ακύρωσης για να ζητήσει την ακύρωση της λειτουργίας.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params Stream[] sources)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| συσκευή | IDevice | Η συσκευή εξόδου. |
| cancellationToken | CancellationToken | Ένα CancellationToken για παρακολούθηση ενώ περιμένετε την ολοκλήρωση της εργασίας. |
| πηγές | Stream[] | Τα έγγραφα MHTML προς απόδοση. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

Αποδίδει το έγγραφο MHTML στην καθορισμένη [`IDevice`](../../idevice/).

```java
public void Render(IDevice device, Stream source, Configuration configuration)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| συσκευή | IDevice | Η συσκευή. |
| έγγραφο | Ροή | Το έγγραφο. |
| διαμόρφωση | Διαμόρφωση | Η διαμόρφωση. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

Αποδίδει το έγγραφο MHTML στην καθορισμένη [`IDevice`](../../idevice/). Η απόδοση θα εκτελεστεί όταν δεν υπάρχουν δικτυακές λειτουργίες για τη φόρτωση πόρων, ενεργά χρονόμετρα, εργασίες animation ή όταν έχει λήξει το καθορισμένο χρονικό όριο.

```java
public void Render(IDevice device, Stream source, Configuration configuration, TimeSpan timeout)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| συσκευή | IDevice | Η συσκευή. |
| έγγραφο | Ροή | Το έγγραφο. |
| διαμόρφωση | Διαμόρφωση | Η διαμόρφωση. |
| χρονικό όριο | TimeSpan | Ένα TimeSpan που αντιπροσωπεύει τον αριθμό των χιλιοστών του δευτερολέπτου για αναμονή, ή ένα TimeSpan που αντιπροσωπεύει -1 χιλιοστέπτο του δευτερολέπτου για απεριόριστη αναμονή. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

Αποδίδει πολλαπλά έγγραφα MHTML στην καθορισμένη [`IDevice`](../../idevice/).

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| συσκευή | IDevice | Η συσκευή. |
| έγγραφα | IList`1 | Η IList των εγγράφων προς απόδοση. |
| διαμόρφωση | Διαμόρφωση | Η διαμόρφωση. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

Αποδίδει πολλαπλά έγγραφα MHTML σε καθορισμένο [`IDevice`](../../idevice/). Η απόδοση θα εκτελεστεί όταν δεν υπάρχουν καμία δικτυακή λειτουργία για τη φόρτωση πόρων, ενεργά χρονόμετρα, εργασίες animation ή όταν έχει παρέλθει το καθορισμένο χρονικό όριο.

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration, 
    TimeSpan timeout)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| συσκευή | IDevice | Η συσκευή. |
| έγγραφα | IList`1 | Η IList των εγγράφων προς απόδοση. |
| διαμόρφωση | Διαμόρφωση | Η διαμόρφωση. |
| χρονικό όριο | TimeSpan | Ένα TimeSpan που αντιπροσωπεύει τον αριθμό των χιλιοστών του δευτερολέπτου για αναμονή, ή ένα TimeSpan που αντιπροσωπεύει -1 χιλιοστέπτο του δευτερολέπτου για απεριόριστη αναμονή. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
