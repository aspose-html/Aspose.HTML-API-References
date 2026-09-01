---
title: "ICSS2Properties.Width"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Ιδιότητα ICSS2Properties. Αυτή η ιδιότητα καθορίζει το πλάτος περιεχομένου των πλαισίων που δημιουργούνται από στοιχεία επιπέδου block και αντικαταστάσιμα στοιχεία."
type: docs

url: /el/java/com.aspose.html.dom.css/icss2properties/width/
---
## ICSS2Properties.Width property

Αυτή η ιδιότητα καθορίζει το [πλάτος περιεχομένου](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#content-width) των πλαισίων που δημιουργούνται από στοιχεία επιπέδου block και [αντικαταστάσιμα](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#replaced-element) στοιχεία.

Αυτή η ιδιότητα δεν ισχύει για μη-αντικαταστάσιμα στοιχεία [inline-level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#inline-level). Το πλάτος των κουτιών ενός μη-αντικαταστάσιμου inline στοιχείου είναι το πλάτος του αποδομένου περιεχομένου μέσα σε αυτά (πριν οποιαδήποτε σχετική μετατόπιση των παιδιών). Θυμηθείτε ότι τα inline κουτιά ρέουν σε [line boxes](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#line-box). Το πλάτος των line boxes δίνεται από το [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block), αλλά μπορεί να περιοριστεί από την παρουσία των [floats](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#floats).

Το πλάτος του κουτιού ενός αντικαταστάσιμου στοιχείου είναι [intrinsic](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#intrinsic) και μπορεί να κλιμακωθεί από τον πράκτορα χρήστη εάν η τιμή αυτής της ιδιότητας είναι διαφορετική από το 'auto'.

Οι τιμές έχουν τις ακόλουθες σημασίες:

'[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' - Καθορίζει σταθερό πλάτος.'[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - Καθορίζει πλάτος σε ποσοστό. Το ποσοστό υπολογίζεται σε σχέση με το πλάτος του παραγόμενου κουτιού του [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block).auto - Το πλάτος εξαρτάται από τις τιμές άλλων ιδιοτήτων. Δείτε τις ενότητες παρακάτω.Σημείωση: Οι αρνητικές τιμές για ['width'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-width) είναι παράνομες.

```java
public String Width { get; set; }
```

### Τιμή Επιστροφής

ιδιότητα width

### Δείτε επίσης

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
