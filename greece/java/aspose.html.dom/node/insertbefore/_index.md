---
title: "Node.InsertBefore"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Node. Η μέθοδος insertBefore της διεπαφής Node εισάγει έναν κόμβο πριν από έναν κόμβο αναφοράς ως παιδί ενός καθορισμένου γονικού κόμβου"
type: docs

url: /el/java/com.aspose.html.dom/node/insertbefore/
---
## Node.InsertBefore method

Η μέθοδος insertBefore() της διεπαφής Node εισάγει έναν κόμβο πριν από έναν κόμβο αναφοράς ως παιδί ενός καθορισμένου γονικού κόμβου.

Εάν ο δοσμένος κόμβος υπάρχει ήδη στο έγγραφο, η insertBefore() τον μετακινεί από την τρέχουσα θέση του στη νέα θέση. (Δηλαδή, θα αφαιρεθεί αυτόματα από τον υπάρχοντα γονέα του πριν προσαρτηθεί στον καθορισμένο νέο γονέα.)

Αυτό σημαίνει ότι ένας κόμβος δεν μπορεί να βρίσκεται σε δύο θέσεις του εγγράφου ταυτόχρονα.

```java
public Node InsertBefore(Node node, Node child)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κόμβος | Node | Ο κόμβος που θα εισαχθεί. |
| παιδί | Node | Ο κόμβος πριν από τον οποίο εισάγεται το newNode. Εάν είναι null, τότε το newNode εισάγεται στο τέλος των παιδικών κόμβων του κόμβου. |

### Τιμή Επιστροφής

Επιστρέφει το προστιθέμενο παιδί (εκτός εάν το newNode είναι ένα [`DocumentFragment`](../../documentfragment/), στην οποία περίπτωση επιστρέφεται το κενό [`DocumentFragment`](../../documentfragment/)).

### Δείτε επίσης

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
