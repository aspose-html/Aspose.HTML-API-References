---
title: "Διεπαφή ICSSRuleList"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Διεπαφή com.aspose.html.dom.css.ICSSRuleList. Ένα CSSRuleList αντιπροσωπεύει μια διατεταγμένη συλλογή αντικειμένων CSSRule μόνο για ανάγνωση."
type: docs

url: /el/java/com.aspose.html.dom.css/icssrulelist/
---
## ICSSRuleList interface

Ένα CSSRuleList αντιπροσωπεύει μια διατεταγμένη συλλογή αντικειμένων [`CSSRule`](../icssrule/) μόνο για ανάγνωση.

Ενώ το αντικείμενο CSSRuleList είναι μόνο για ανάγνωση και δεν μπορεί να τροποποιηθεί άμεσα, θεωρείται ζωντανό αντικείμενο, καθώς το περιεχόμενο μπορεί να αλλάξει με την πάροδο του χρόνου.

Για να επεξεργαστείτε τους υποκείμενους κανόνες που επιστρέφονται από αντικείμενα [`CSSRule`](../icssrule/), χρησιμοποιήστε τις μεθόδους CSSStyleSheet.insertRule() και CSSStyleSheet.deleteRule(), οι οποίες είναι μέθοδοι του [`CSSStyleSheet`](../icssstylesheet/).

```java
public interface ICSSRuleList : IEnumerable<ICSSRule>
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssrulelist/item/) Χρησιμοποιείται για την ανάκτηση ενός κανόνα CSS με τη μέθοδο item() (http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSRuleList). Η σειρά σε αυτή τη συλλογή αντιπροσωπεύει τη σειρά των κανόνων στο φύλλο στυλ CSS. Εάν το index είναι μεγαλύτερο ή ίσο με τον αριθμό των κανόνων στη λίστα, επιστρέφει null. |
| [getLength](../../com.aspose.html.dom.css/icssrulelist/length/) Η ιδιότητα length της διεπαφής `CSSRuleList` επιστρέφει τον αριθμό των αντικειμένων [`CSSRule`](../icssrule/) στη λίστα. |

### Δείτε επίσης

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
