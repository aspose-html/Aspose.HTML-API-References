---
title: "Διεπαφή ICSSKeyframesRule"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Διεπαφή com.aspose.html.dom.css.ICSSKeyframesRule. Η ιδιότητα name της διεπαφής CSSKeyframeRule λαμβάνει και ορίζει το όνομα της κίνησης όπως χρησιμοποιείται από την ιδιότητα animation-name."
type: docs

url: /el/java/com.aspose.html.dom.css/icsskeyframesrule/
---
## ICSSKeyframesRule interface

Η ιδιότητα name της διεπαφής CSSKeyframeRule λαμβάνει και ορίζει το όνομα της κίνησης όπως χρησιμοποιείται από την ιδιότητα animation-name.

```java
public interface ICSSKeyframesRule : ICSSRule
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getCSSRules](../../com.aspose.html.dom.css/icsskeyframesrule/cssrules/) Η ιδιότητα μόνο‑ανάγνωση cssRules της διεπαφής [`CSSKeyframeRule`](../icsskeyframerule/) επιστρέφει μια [`CSSRuleList`](../icssrulelist/) που περιέχει τους κανόνες στην at‑rule των keyframes. |
| [getName](../../com.aspose.html.dom.css/icsskeyframesrule/name/) Η ιδιότητα name της διεπαφής [`CSSKeyframeRule`](../icsskeyframerule/) λαμβάνει και ορίζει το όνομα της κίνησης όπως χρησιμοποιείται από την ιδιότητα animation‑name. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [appendRule](../../com.aspose.html.dom.css/icsskeyframesrule/appendrule/)(String) | Η μέθοδος appendRule προσθέτει το παρεχόμενο [`CSSKeyframeRule`](../icsskeyframerule/) στο τέλος της συλλογής κανόνων keyframes. |
| [deleteRule](../../com.aspose.html.dom.css/icsskeyframesrule/deleterule/)(String) | Η μέθοδος deleteRule διαγράφει το [`CSSKeyframeRule`](../icsskeyframerule/) με το δοθέν κλειδί. Εάν δεν υπάρχει κανόνας με αυτό το κλειδί, η μέθοδος δεν κάνει τίποτα. |
| [findRule](../../com.aspose.html.dom.css/icsskeyframesrule/findrule/)(String) | Η μέθοδος findRule επιστρέφει τον κανόνα με κλειδί που ταιριάζει με το δοθέν κλειδί. Εάν δεν υπάρχει τέτοιος κανόνας, επιστρέφεται τιμή null. |

### Δείτε επίσης

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
