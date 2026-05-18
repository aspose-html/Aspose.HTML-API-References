---
title: "Node.CloneNode"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Node. Η μέθοδος cloneNode της διεπαφής Node επιστρέφει ένα αντίγραφο του κόμβου στον οποίο κλήθηκε αυτή η μέθοδος. Η παράμετρος της ελέγχει εάν το υποδέντρο που περιέχεται σε έναν κόμβο επίσης κλωνοποιείται ή όχι."
type: docs

url: /el/java/com.aspose.html.dom/node/clonenode/
---
## CloneNode() {#clonenode}

Η μέθοδος cloneNode() του interface Node επιστρέφει ένα αντίγραφο του κόμβου στον οποίο κλήθηκε αυτή η μέθοδος. Η παράμετρός της ελέγχει αν το υποδέντρο που περιέχεται σε έναν κόμβο θα κλωνοποιηθεί επίσης ή όχι.

Η κλωνοποίηση ενός κόμβου αντιγράφει όλα τα χαρακτηριστικά του και τις τιμές τους, συμπεριλαμβανομένων των ενδογενών (inline) ακροατών. Δεν αντιγράφει τους ακροατές συμβάντων που προστέθηκαν χρησιμοποιώντας [`addEventListener()`](../../../com.aspose.html.dom.events/ieventtarget/addeventlistener/) ή εκείνους που έχουν εκχωρηθεί σε ιδιότητες στοιχείου (π.χ., node.onclick = someFunction). Επιπλέον, για ένα στοιχείο [`&lt;canvas&gt;`](../../../com.aspose.html/htmlcanvaselement/), η ζωγραφισμένη εικόνα δεν αντιγράφεται.

```java
public Node CloneNode()
```

### Τιμή επιστροφής

Ο νέος [`Node`](../) κλωνοποιήθηκε. Ο κλωνοποιημένος κόμβος δεν έχει γονέα και δεν αποτελεί μέρος του εγγράφου, μέχρι να προστεθεί σε έναν άλλο κόμβο που είναι μέρος του εγγράφου, χρησιμοποιώντας [`Node.appendChild()`](../appendchild/) ή μια παρόμοια μέθοδο.

### Δείτε επίσης

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CloneNode(bool) {#clonenode_1}

Η μέθοδος cloneNode() του interface Node επιστρέφει ένα αντίγραφο του κόμβου στον οποίο κλήθηκε αυτή η μέθοδος. Η παράμετρός της ελέγχει αν το υποδέντρο που περιέχεται σε έναν κόμβο θα κλωνοποιηθεί επίσης ή όχι.

Η κλωνοποίηση ενός κόμβου αντιγράφει όλα τα χαρακτηριστικά του και τις τιμές τους, συμπεριλαμβανομένων των ενδογενών (inline) ακροατών. Δεν αντιγράφει τους ακροατές συμβάντων που προστέθηκαν χρησιμοποιώντας [addEventListener()](M:com.aspose.html.dom.events.IEventTarget.AddEventListener(System.String,com.aspose.html.dom.events.IEventListener)) ή εκείνους που έχουν εκχωρηθεί σε ιδιότητες στοιχείου (π.χ., node.onclick = someFunction). Επιπλέον, για ένα [&lt;canvas&gt;](T:Aspose.Html.HTMLCanvasElement) στοιχείο, η ζωγραφισμένη εικόνα δεν αντιγράφεται.

```java
public Node CloneNode(bool deep)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| deep | Boolean | Εάν είναι true, τότε ο κόμβος και όλο το υποδέντρο του, συμπεριλαμβανομένου του κειμένου που μπορεί να υπάρχει σε παιδικούς κόμβους [`Text`](../../text/), επίσης αντιγράφονται. |

### Τιμή επιστροφής

Ο νέος [Node](T:com.aspose.html.dom.Node) κλωνοποιήθηκε. Ο κλωνοποιημένος κόμβος δεν έχει γονέα και δεν αποτελεί μέρος του εγγράφου, μέχρι να προστεθεί σε έναν άλλο κόμβο που είναι μέρος του εγγράφου, χρησιμοποιώντας [Node.appendChild()](M:com.aspose.html.dom.Node.AppendChild(com.aspose.html.dom.Node)) ή μια παρόμοια μέθοδο.

### Δείτε επίσης

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
