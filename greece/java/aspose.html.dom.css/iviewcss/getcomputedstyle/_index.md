---
title: "IViewCSS.GetComputedStyle"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος IViewCSS. Η μέθοδος IViewCSS.getComputedStyle επιστρέφει ένα αντικείμενο που περιέχει τις τιμές όλων των ιδιοτήτων CSS ενός στοιχείου μετά την εφαρμογή ενεργών φύλλων στυλ και την επίλυση τυχόν βασικών υπολογισμών που μπορεί να περιέχουν αυτές οι τιμές."
type: docs

url: /el/java/com.aspose.html.dom.css/iviewcss/getcomputedstyle/
---
## GetComputedStyle(Element) {#getcomputedstyle}

Η μέθοδος IViewCSS.getComputedStyle() επιστρέφει ένα αντικείμενο που περιέχει τις τιμές όλων των ιδιοτήτων CSS ενός στοιχείου, μετά την εφαρμογή ενεργών φύλλων στυλ και την επίλυση τυχόν βασικών υπολογισμών που μπορεί να περιέχουν αυτές οι τιμές.

Ατομικές τιμές ιδιοτήτων CSS προσπελάζονται μέσω των API που παρέχει το αντικείμενο, ή με ευρετηρίαση με τα ονόματα ιδιοτήτων CSS.

```java
public ICSSStyleDeclaration GetComputedStyle(Element element)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| element | Element | Το [`Element`](../../../com.aspose.html.dom/element/) για το οποίο θα ληφθεί το υπολογισμένο στυλ. Αυτό το παράμετρο δεν μπορεί να είναι null. |

### Τιμή επιστροφής

Το επιστρεφόμενο στυλ είναι ένα ζωντανό αντικείμενο [`CSSStyleDeclaration`](../../icssstyledeclaration/), το οποίο ενημερώνεται αυτόματα όταν τα στυλ του στοιχείου αλλάζουν.

### Exceptions

| exception | condition |
| --- | --- |
| TypeError | Εάν το περασμένο αντικείμενο δεν είναι Element ή το pseudoElt δεν είναι έγκυρος επιλογέας ψευδο-στοιχείου. |

## Παρατηρήσεις

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Αναφορά

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### Δείτε επίσης

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

---

## GetComputedStyle(Element, String) {#getcomputedstyle_1}

Η μέθοδος IViewCSS.getComputedStyle() επιστρέφει ένα αντικείμενο που περιέχει τις τιμές όλων των ιδιοτήτων CSS ενός στοιχείου, μετά την εφαρμογή ενεργών φύλλων στυλ και την επίλυση τυχόν βασικών υπολογισμών που μπορεί να περιέχουν αυτές οι τιμές.

Ατομικές τιμές ιδιοτήτων CSS προσπελάζονται μέσω των API που παρέχει το αντικείμενο, ή με ευρετηρίαση με τα ονόματα ιδιοτήτων CSS.

```java
public ICSSStyleDeclaration GetComputedStyle(Element element, String pseudoElement)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| element | Element | Το [`Element`](../../../com.aspose.html.dom/element/) για το οποίο θα ληφθεί το υπολογισμένο στυλ. Αυτό το παράμετρο δεν μπορεί να είναι null. |
| pseudoElement | String | Μια συμβολοσειρά που καθορίζει το ψευδο-στοιχείο προς αντιστοίχιση. Παραλείπεται (ή null) για πραγματικά στοιχεία. |

### Τιμή επιστροφής

Το επιστρεφόμενο στυλ είναι ένα ζωντανό αντικείμενο [`CSSStyleDeclaration`](../../icssstyledeclaration/), το οποίο ενημερώνεται αυτόματα όταν τα στυλ του στοιχείου αλλάζουν.

### Exceptions

| exception | condition |
| --- | --- |
| TypeError | Εάν το περασμένο αντικείμενο δεν είναι Element ή το pseudoElt δεν είναι έγκυρος επιλογέας ψευδο-στοιχείου. |

## Παρατηρήσεις

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Αναφορά

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### Δείτε επίσης

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
