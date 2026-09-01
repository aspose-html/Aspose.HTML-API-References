---
title: "ICSSStyleSheet.InsertRule"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος ICSSStyleSheet. Η μέθοδος CSSStyleSheet.insertRule εισάγει έναν νέο κανόνα CSS στο τρέχον φύλλο στυλ με ορισμένους περιορισμούς"
type: docs

url: /el/java/com.aspose.html.dom.css/icssstylesheet/insertrule/
---
## ICSSStyleSheet.InsertRule method

Η μέθοδος CSSStyleSheet.insertRule() εισάγει έναν νέο κανόνα CSS στο τρέχον φύλλο στυλ, με ορισμένους περιορισμούς.

Σημείωση: Αν και η insertRule() είναι αποκλειστικά μια μέθοδος του [`CSSStyleSheet`](../), στην πραγματικότητα εισάγει τον κανόνα στο CSSStyleSheet.cssRules — τη εσωτερική [`CSSRuleList`](../../icssrulelist/).

```java
public long InsertRule(String rule, int index)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κανόνας | String | Μια String που περιέχει τον κανόνα που θα εισαχθεί. Το τι πρέπει να περιέχει ο εισαχθείς κανόνας εξαρτάται από τον τύπο του: |
| index | Int32 | Ένας θετικός ακέραιος μικρότερος ή ίσος με το stylesheet.cssRules.length, που αντιπροσωπεύει τη θέση του νέου εισαχθέντος κανόνα στο CSSStyleSheet.cssRules. Η προεπιλογή είναι 0. |

### Τιμή Επιστροφής

Το ευρετήριο του νέου εισαχθέντος κανόνα μέσα στη λίστα κανόνων του φύλλου στυλ.

## Παρατηρήσεις

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Αναφορά

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-cssstylesheet-insertrule](https://drafts.csswg.org/cssom/#dom-cssstylesheet-insertrule) – The CSSOM definition.

### Δείτε επίσης

* interface [ICSSStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
