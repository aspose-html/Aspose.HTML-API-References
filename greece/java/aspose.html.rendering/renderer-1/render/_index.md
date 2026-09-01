---
title: "Renderer-1.Render"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Renderer. Ορίζει μέθοδο για την απόδοση του TDocument σε καθορισμένο IDevice"
type: docs

url: /el/java/com.aspose.html.rendering/renderer-1/render/
---
## Render(IDevice, TSource) {#render_3}

Ορίζει μέθοδο για την απόδοση του !:TDocument σε καθορισμένο [`IDevice`](../../idevice/).

```java
public void Render(IDevice device, TSource source)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| συσκευή | IDevice | Η συσκευή εξόδου. |
| έγγραφο | TSource | Το έγγραφο. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, TimeSpan) {#render_5}

Ορίζει μέθοδο για την απόδοση του !:TDocument σε καθορισμένο [`IDevice`](../../idevice/). Η απόδοση θα εκτελεστεί όταν δεν υπάρχουν καμία δικτυακή λειτουργία για τη φόρτωση πόρων, ενεργά χρονόμετρα, εργασίες animation ή όταν έχει παρέλθει το καθορισμένο χρονικό όριο.

```java
public void Render(IDevice device, TSource source, TimeSpan timeout)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| συσκευή | IDevice | Η συσκευή εξόδου. |
| έγγραφο | TSource | Το έγγραφο. |
| χρονικό όριο | TimeSpan | Ένα TimeSpan που αντιπροσωπεύει τον αριθμό των χιλιοστών του δευτερολέπτου για αναμονή, ή ένα TimeSpan που αντιπροσωπεύει -1 χιλιοστέπτο του δευτερολέπτου για απεριόριστη αναμονή. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, int) {#render_4}

Ορίζει μέθοδο για την απόδοση του !:TDocument σε καθορισμένο [`IDevice`](../../idevice/). Η απόδοση θα εκτελεστεί όταν δεν υπάρχουν καμία δικτυακή λειτουργία για τη φόρτωση πόρων, ενεργά χρονόμετρα, εργασίες animation ή όταν έχει παρέλθει το καθορισμένο χρονικό όριο.

```java
public void Render(IDevice device, TSource source, int timeout)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| συσκευή | IDevice | Η συσκευή εξόδου. |
| έγγραφο | TSource | Το έγγραφο. |
| χρονικό όριο | Int32 | Ένας αριθμός χιλιοστών του δευτερολέπτου που αντιπροσωπεύει τον χρόνο αναμονής, ή -1 χιλιοστέπτο για απεριόριστη αναμονή. |

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, params TSource[]) {#render_6}

```java
public void Render(IDevice device, params TSource[] sources)
```

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, int, params TSource[]) {#render}

```java
public void Render(IDevice device, int timeout, params TSource[] sources)
```

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TimeSpan, params TSource[]) {#render_2}

```java
public abstract void Render(IDevice device, TimeSpan timeout, params TSource[] sources)
```

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params TSource[]) {#render_1}

```java
public abstract void Render(IDevice device, CancellationToken cancellationToken, 
    params TSource[] sources)
```

### Δείτε επίσης

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
