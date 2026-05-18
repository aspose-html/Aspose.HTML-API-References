---
title: "Node.TextContent"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Node ιδιότητα. Η ιδιότητα textContent της διεπαφής Node αντιπροσωπεύει το κείμενο του κόμβου και των απογόνων του"
type: docs

url: /el/java/com.aspose.html.dom/node/textcontent/
---
## Node.TextContent property

Η ιδιότητα textContent της διεπαφής [`Node`](../) αντιπροσωπεύει το κείμενο του κόμβου και των απογόνων του.

```java
public String TextContent { get; set; }
```

### Property Value

Μια String, ή null. Η τιμή της εξαρτάται από την κατάσταση:

Εάν ο κόμβος είναι ένα έγγραφο ή ένα doctype, το textContent επιστρέφει null.Σημείωση: Για να λάβετε όλο το κείμενο και τα δεδομένα CDATA για ολόκληρο το έγγραφο, χρησιμοποιήστε document.documentElement.textContent.Εάν ο κόμβος είναι μια ενότητα CDATA, ένα σχόλιο, μια οδηγία επεξεργασίας ή ένας κόμβος κειμένου, το textContent επιστρέφει ή ορίζει το κείμενο μέσα στον κόμβο, δηλαδή το [`Node.nodeValue`](../nodevalue/).Για άλλους τύπους κόμβων, το textContent επιστρέφει τη σύνθεση του textContent κάθε παιδικού κόμβου, εξαιρώντας σχόλια και οδηγίες επεξεργασίας.

## Παρατηρήσεις

Αναφορά:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-textcontent](https://dom.spec.whatwg.org/#dom-node-textcontent).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Δείτε επίσης

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
