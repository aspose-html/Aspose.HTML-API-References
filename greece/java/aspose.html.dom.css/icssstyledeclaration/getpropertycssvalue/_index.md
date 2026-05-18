---
title: "ICSSStyleDeclaration.GetPropertyCSSValue"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος ICSSStyleDeclaration. Χρησιμοποιείται για την ανάκτηση της αντικειμενικής αναπαράστασης της τιμής μιας ιδιότητας CSS εάν έχει οριστεί ρητά μέσα σε αυτό το μπλοκ δήλωσης. Αυτή η μέθοδος επιστρέφει null εάν η ιδιότητα είναι συντομευμένη. Οι τιμές συντομευμένων ιδιοτήτων μπορούν να προσπελαστούν και να τροποποιηθούν μόνο ως Strings χρησιμοποιώντας τις μεθόδους getPropertyValue και setProperty."
type: docs

url: /el/java/com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/
---
## ICSSStyleDeclaration.GetPropertyCSSValue method

Χρησιμοποιείται για την ανάκτηση της αντικειμενικής αναπαράστασης της τιμής μιας ιδιότητας CSS εάν έχει οριστεί ρητά μέσα σε αυτό το μπλοκ δήλωσης. Αυτή η μέθοδος επιστρέφει null εάν η ιδιότητα είναι συντομευμένη ιδιότητα. Οι τιμές συντομευμένων ιδιοτήτων μπορούν να προσπελαστούν και να τροποποιηθούν μόνο ως Strings, χρησιμοποιώντας τις μεθόδους getPropertyValue και setProperty.

```java
public CSSValue GetPropertyCSSValue(String propertyName)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| propertyName | String | propertyName είναι ένα String που αντιπροσωπεύει το όνομα της ιδιότητας που θα ανακτηθεί. |

### Τιμή επιστροφής

value είναι ένα CSSValue που περιέχει την τιμή CSS για μια ιδιότητα. Εάν δεν υπάρχει, επιστρέφει null.

### Δείτε επίσης

* class [CSSValue](../../cssvalue/)
* interface [ICSSStyleDeclaration](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
