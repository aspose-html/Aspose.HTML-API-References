---
title: "Node.RemoveChild"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Node. Η μέθοδος removeChild της διεπαφής Node αφαιρεί έναν υποκόμβο από το DOM και επιστρέφει τον αφαιρεθέντα κόμβο."
type: docs

url: /el/java/com.aspose.html.dom/node/removechild/
---
## Node.RemoveChild method

Η μέθοδος removeChild() του interface Node αφαιρεί ένα child node από το DOM και επιστρέφει το αφαιρεθέν node.

Σημείωση: Εφόσον διατηρείται μια αναφορά στο αφαιρεθέντα παιδί, αυτό εξακολουθεί να υπάρχει στη μνήμη, αλλά δεν αποτελεί πλέον μέρος του DOM. Μπορεί ακόμη να χρησιμοποιηθεί ξανά αργότερα στον κώδικα. Εάν η τιμή επιστροφής του removeChild() δεν αποθηκευτεί και δεν διατηρηθεί άλλη αναφορά, θα διαγραφεί αυτόματα από τη μνήμη μετά από λίγο χρόνο.

```java
public Node RemoveChild(Node child)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| child | Node | Ένα [`Node`](../) που είναι ο υποκόμβος προς αφαίρεση από το DOM. |

### Τιμή επιστροφής

Σε αντίθεση με το [`Node.cloneNode()`](../clonenode/), η τιμή επιστροφής διατηρεί τα αντικείμενα [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/) που σχετίζονται με αυτό.

### Δείτε επίσης

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
