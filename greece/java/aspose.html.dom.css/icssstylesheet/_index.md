---
title: "Διεπαφή ICSSStyleSheet"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Διεπαφή com.aspose.html.dom.css.ICSSStyleSheet. Η διεπαφή CSSStyleSheet αντιπροσωπεύει ένα μοναδικό φύλλο στυλ CSS και σας επιτρέπει να εξετάσετε και να τροποποιήσετε τη λίστα των κανόνων που περιέχονται στο φύλλο στυλ. Κληρονομεί ιδιότητες και μεθόδους από τον γονέα της, IStyleSheet."
type: docs

url: /el/java/com.aspose.html.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

Η διεπαφή CSSStyleSheet αντιπροσωπεύει ένα μοναδικό φύλλο στυλ CSS και σας επιτρέπει να εξετάσετε και να τροποποιήσετε τη λίστα των κανόνων που περιέχονται στο φύλλο στυλ. Κληρονομεί ιδιότητες και μεθόδους από τον γονέα της, [`IStyleSheet`](../istylesheet/).

Ένα φύλλο στυλ αποτελείται από μια συλλογή αντικειμένων [`ICSSRule`](../icssrule/) που αντιπροσωπεύουν καθέναν από τους κανόνες στο φύλλο στυλ. Οι κανόνες περιέχονται σε μια [`ICSSRuleList`](../icssrulelist/), η οποία μπορεί να ληφθεί από την ιδιότητα cssRules του φύλλου στυλ.

Για παράδειγμα, ένας κανόνας μπορεί να είναι ένα αντικείμενο [`ICSSStyleRule`](../icssstylerule/) που περιέχει ένα στυλ όπως

```java
h1, h2 {   font-size: 16pt; }
```

Ένας άλλος κανόνας μπορεί να είναι ένας at-rule όπως @import ή @media, κ.λπ.

```java
public interface ICSSStyleSheet : IStyleSheet
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getCSSRules](../../com.aspose.html.dom.css/icssstylesheet/cssrules/) Η ιδιότητα μόνο για ανάγνωση cssRules του CSSStyleSheet επιστρέφει μια ζωντανή [`CSSRuleList`](../icssrulelist/) που παρέχει μια σε πραγματικό χρόνο, ενημερωμένη λίστα με κάθε κανόνα CSS που αποτελεί το φύλλο στυλ. Κάθε στοιχείο στη λίστα είναι ένα [`CSSRule`](../icssrule/) που ορίζει έναν μοναδικό κανόνα. |
| [getOwnerRule](../../com.aspose.html.dom.css/icssstylesheet/ownerrule/) Η ιδιότητα μόνο για ανάγνωση ownerRule του CSSStyleSheet επιστρέφει το [`CSSImportRule`](../icssimportrule/) που αντιστοιχεί στον at-rule @import που εισήγαγε το φύλλο στυλ στο έγγραφο. Εάν το φύλλο στυλ δεν εισήχθη στο έγγραφο χρησιμοποιώντας @import, η επιστρεφόμενη τιμή είναι null. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [deleteRule](../../com.aspose.html.dom.css/icssstylesheet/deleterule/)(int) | Η μέθοδος `CSSStyleSheet` deleteRule() αφαιρεί έναν κανόνα από το αντικείμενο του φύλλου στυλ. |
| [insertRule](../../com.aspose.html.dom.css/icssstylesheet/insertrule/)(String, int) | Η μέθοδος CSSStyleSheet.insertRule() εισάγει έναν νέο κανόνα CSS στο τρέχον φύλλο στυλ, με ορισμένους περιορισμούς. |

## Παρατηρήσεις

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Αναφορά

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstylesheet](https://drafts.csswg.org/cssom/#cssstylesheet) – The CSSOM definition.

### Δείτε επίσης

* interface [IStyleSheet](../istylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
