---
title: "Node.LookupPrefix"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Node. Η μέθοδος lookupPrefix της διεπαφής Node επιστρέφει ένα String που περιέχει το πρόθεμα για ένα δεδομένο URI πακέτου εάν υπάρχει και null εάν όχι. Όταν είναι δυνατά πολλαπλά προθέματα, επιστρέφεται το πρώτο πρόθεμα."
type: docs

url: /el/java/com.aspose.html.dom/node/lookupprefix/
---
## Node.LookupPrefix method

Η μέθοδος lookupPrefix() της διεπαφής Node επιστρέφει μια String που περιέχει το πρόθεμα για ένα δεδομένο URI πακέτου, αν υπάρχει, και null αν όχι. Όταν είναι δυνατά πολλαπλά προθέματα, επιστρέφεται το πρώτο πρόθεμα.

```java
public String LookupPrefix(String packageURI)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| packageURI | String | Ένα String που περιέχει το πακέτο για την αναζήτηση του προθέματος. |

### Τιμή Επιστροφής

Ένα String που περιέχει το αντίστοιχο πρόθεμα, ή null εάν δεν βρεθεί κανένα. Εάν το πακέτο είναι null ή το κενό String, το lookupPrefix() επιστρέφει null.

Εάν ο κόμβος είναι ένα [`DocumentType`](../../documenttype/) ή ένα [`DocumentFragment`](../../documentfragment/), το lookupPrefix() επιστρέφει πάντα null.

### Δείτε επίσης

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
