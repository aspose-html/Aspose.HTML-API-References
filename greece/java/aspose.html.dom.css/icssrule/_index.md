---
title: "ICSSRule Διεπαφή"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.css.ICSSRule διεπαφή. Η διεπαφή CSSRule είναι η αφηρημένη βασική διεπαφή για οποιονδήποτε τύπο δήλωσης CSS. Αυτό περιλαμβάνει τόσο σύνολα κανόνων όσο και at-rules. Αναμένεται μια υλοποίηση να διατηρεί όλους τους κανόνες που ορίζονται σε ένα φύλλο στυλ CSS ακόμη και αν ο κανόνας δεν αναγνωρίζεται από τον αναλυτή. Οι μη αναγνωρισμένοι κανόνες αντιπροσωπεύονται χρησιμοποιώντας τη διεπαφή."
type: docs

url: /el/java/com.aspose.html.dom.css/icssrule/
---
## ICSSRule interface

Η διεπαφή CSSRule είναι η αφηρημένη βασική διεπαφή για οποιονδήποτε τύπο δήλωσης CSS. Αυτό περιλαμβάνει τόσο σύνολα κανόνων όσο και at-rules. Αναμένεται μια υλοποίηση να διατηρεί όλους τους κανόνες που ορίζονται σε ένα φύλλο στυλ CSS, ακόμη και αν ο κανόνας δεν αναγνωρίζεται από τον αναλυτή. Οι μη αναγνωρισμένοι κανόνες αντιπροσωπεύονται με τη χρήση της διεπαφής.

```java
public interface ICSSRule
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
[getCSSText]
[setCSSText] The cssText property of the `CSSRule` interface returns the actual text of a [`CSSStyleSheet`](../icssstylesheet/) style-rule. |
| [getParentRule](../../com.aspose.html.dom.css/icssrule/parentrule/) Εάν αυτός ο κανόνας περιέχεται μέσα σε άλλο κανόνα (π.χ. ένας κανόνας στυλ μέσα σε μπλοκ @media), αυτός είναι ο περιέχων κανόνας. Εάν αυτός ο κανόνας δεν είναι ενσωματωμένος μέσα σε άλλους κανόνες, επιστρέφει null. |
| [getParentStyleSheet](../../com.aspose.html.dom.css/icssrule/parentstylesheet/) Η ιδιότητα parentStyleSheet της διεπαφής `CSSRule` επιστρέφει το αντικείμενο [`StyleSheet`](../istylesheet/) στο οποίο ορίζεται ο τρέχων κανόνας. |
| [getType](../../com.aspose.html.dom.css/icssrule/type/) Ο τύπος του κανόνα, όπως ορίζεται στο [CSSOM # dom-cssrule-type](https://drafts.csswg.org/cssom/#dom-cssrule-type). Η προσδοκία είναι ότι οι μεθόδους μετατροπής ειδικές για binding μπορούν να χρησιμοποιηθούν για να μετατρέψουν μια παρουσία της διεπαφής CSSRule στην συγκεκριμένη παράγωγη διεπαφή που υποδεικνύεται από τον τύπο. |

### Δείτε επίσης

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
