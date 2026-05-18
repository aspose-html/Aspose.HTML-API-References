---
title: "ICSSStyleSheet.InsertRule"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος ICSSStyleSheet. Η μέθοδος CSSStyleSheet.insertRule εισάγει έναν νέο κανόνα CSS στο τρέχον φύλλο στυλ με ορισμένους περιορισμούς"
type: docs

url: /el/java/com.aspose.html.dom.css/icssstylesheet/insertrule/
---
## ICSSStyleSheet.InsertRule method

Η μέθοδος CSSStyleSheet.insertRule() εισάγει έναν νέο κανόνα CSS στο τρέχον φύλλο στυλ, με ορισμένους περιορισμούς.

Σημείωση: Παρόλο που η insertRule() είναι αποκλειστικά μέθοδος του [`CSSStyleSheet`](../), στην πραγματικότητα εισάγει τον κανόνα στο CSSStyleSheet.cssRules — τη δική της εσωτερική [`CSSRuleList`](../../icssrulelist/).

```java
public long InsertRule(String rule, int index)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| κανόνας | String | Μια συμβολοσειρά που περιέχει τον κανόνα που θα εισαχθεί. Το τι πρέπει να περιέχει ο εισαχθείς κανόνας εξαρτάται από τον τύπο του: |
| index | Int32 | Ένας θετικός ακέραιος μικρότερος ή ίσος με το stylesheet.cssRules.length, που αντιπροσωπεύει τη θέση του νεοεισαχθέντος κανόνα στο CSSStyleSheet.cssRules. Η προεπιλογή είναι 0. |

### Τιμή επιστροφής

Το ευρετήριο του νεοεισαχθέντος κανόνα μέσα στη λίστα κανόνων του φύλλου στυλ.

## Παρατηρήσεις

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Αναφορά

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-cssstylesheet-insertrule](https://drafts.csswg.org/cssom/#dom-cssstylesheet-insertrule) – The CSSOM definition.

### Δείτε επίσης

* interface [ICSSStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
