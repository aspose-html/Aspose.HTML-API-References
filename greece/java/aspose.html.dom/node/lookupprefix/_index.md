---
title: "Node.LookupPrefix"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Node. Η μέθοδος lookupPrefix της διεπαφής Node επιστρέφει ένα String που περιέχει το πρόθεμα για ένα δεδομένο URI πακέτου εάν υπάρχει, και null αν όχι. Όταν είναι δυνατά πολλαπλά προθέματα, επιστρέφεται το πρώτο πρόθεμα."
type: docs

url: /el/java/com.aspose.html.dom/node/lookupprefix/
---
## Node.LookupPrefix method

Η μέθοδος lookupPrefix() του interface Node επιστρέφει μια Συμβολοσειρά που περιέχει το πρόθεμα για ένα δεδομένο URI πακέτου, εάν υπάρχει, και null εάν όχι. Όταν είναι δυνατές πολλαπλές προθέματα, επιστρέφεται το πρώτο πρόθεμα.

```java
public String LookupPrefix(String packageURI)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| packageURI | String | Ένα String που περιέχει το πακέτο για το οποίο θα αναζητηθεί το πρόθεμα. |

### Τιμή επιστροφής

Ένα String που περιέχει το αντίστοιχο πρόθεμα, ή null αν δεν βρεθεί κανένα. Εάν το package είναι null ή το String είναι κενό, η lookupPrefix() επιστρέφει null.

Εάν ο κόμβος είναι ένας [`DocumentType`](../../documenttype/) ή ένας [`DocumentFragment`](../../documentfragment/), η lookupPrefix() επιστρέφει πάντα null.

### Δείτε επίσης

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
