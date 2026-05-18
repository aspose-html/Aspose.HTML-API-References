---
title: "ICSSStyleDeclaration.RemoveProperty"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος ICSSStyleDeclaration. Η διεπαφή της μεθόδου CSSStyleDeclaration.removeProperty αφαιρεί μια ιδιότητα από ένα αντικείμενο δήλωσης στυλ CSS."
type: docs

url: /el/java/com.aspose.html.dom.css/icssstyledeclaration/removeproperty/
---
## ICSSStyleDeclaration.RemoveProperty method

Η διεπαφή μεθόδου CSSStyleDeclaration.removeProperty() αφαιρεί μια ιδιότητα από ένα αντικείμενο δήλωσης στυλ CSS.

```java
public String RemoveProperty(String propertyName)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| propertyName | String | propertyName είναι μια String που αντιπροσωπεύει το όνομα της ιδιότητας που θα αφαιρεθεί. Σημειώστε ότι τα ονόματα ιδιοτήτων πολλών λέξεων έχουν παύλες και δεν είναι σε camelCase. |

### Τιμή επιστροφής

oldValue είναι ένα DOMString ίσο με την τιμή της ιδιότητας CSS πριν αφαιρεθεί.

### Exceptions

| exception | condition |
| --- | --- |
| DOMException | NO_MODIFICATION_ALLOWED_ERR: εάν η ιδιότητα ή το μπλοκ δήλωσης είναι μόνο για ανάγνωση. |

### Δείτε επίσης

* interface [ICSSStyleDeclaration](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
