---
title: "Διεπαφή ICSSStyleDeclaration"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Διεπαφή com.aspose.html.dom.css.ICSSStyleDeclaration. Η διεπαφή CSSStyleDeclaration αντιπροσωπεύει ένα αντικείμενο που είναι μπλοκ δήλωσης CSS και εκθέτει πληροφορίες στυλ καθώς και διάφορες μεθόδους και ιδιότητες σχετικές με το στυλ."
type: docs

url: /el/java/com.aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

Η διεπαφή CSSStyleDeclaration αντιπροσωπεύει ένα αντικείμενο που είναι ένα μπλοκ δήλωσης CSS και εκθέτει πληροφορίες στυλ και διάφορες μεθόδους και ιδιότητες σχετικές με το στυλ.

Ένα αντικείμενο CSSStyleDeclaration μπορεί να εκτεθεί χρησιμοποιώντας τρία διαφορετικά API:

Μέσω HTMLElement.style, που χειρίζεται τα ενσωματωμένα στυλ ενός μόνο στοιχείου. Μέσω του API [`CSSStyleSheet`](../icssstylesheet/). Για παράδειγμα, document.styleSheets[0].cssRules[0].style επιστρέφει ένα αντικείμενο `CSSStyleDeclaration` στον πρώτο κανόνα CSS του πρώτου φύλλου στυλ του εγγράφου. Μέσω Window.getComputedStyle(), που εκθέτει το αντικείμενο `CSSStyleDeclaration` ως διεπαφή μόνο για ανάγνωση.

```java
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<String>
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
[getCSSText]
[setCSSText] The parsable textual representation of the declaration block (excluding the surrounding curly braces). Setting this attribute will result in the parsing of the new value and resetting of all the properties in the declaration block including the removal or addition of properties. |
| [getItem](../../com.aspose.html.dom.css/icssstyledeclaration/item/) Χρησιμοποιείται για την ανάκτηση των ιδιοτήτων που έχουν οριστεί ρητά σε αυτό το μπλοκ δήλωσης. Η σειρά των ιδιοτήτων που ανακτώνται με αυτή τη μέθοδο δεν χρειάζεται να είναι η σειρά με την οποία ορίστηκαν. Αυτή η μέθοδος μπορεί να χρησιμοποιηθεί για επανάληψη σε όλες τις ιδιότητες σε αυτό το μπλοκ δήλωσης. |
| [getLength](../../com.aspose.html.dom.css/icssstyledeclaration/length/) Η ιδιότητα μόνο για ανάγνωση επιστρέφει έναν ακέραιο αριθμό ιδιοτήτων που έχουν οριστεί ρητά σε αυτό το μπλοκ δήλωσης CSS. Το εύρος των έγκυρων δεικτών είναι από 0 έως length-1 συμπεριλαμβανομένου. |
| [getParentRule](../../com.aspose.html.dom.css/icssstyledeclaration/parentrule/) Η ιδιότητα μόνο για ανάγνωση CSSStyleDeclaration.parentRule επιστρέφει ένα CSSRule που είναι ο γονέας αυτού του μπλοκ στυλ, π.χ. ένα [`CSSStyleRule`](../icssstylerule/) που αντιπροσωπεύει το στυλ για έναν CSS selector. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getPropertyCSSValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(String) | Χρησιμοποιείται για την ανάκτηση της αντικειμενικής αναπαράστασης της τιμής μιας ιδιότητας CSS εάν έχει οριστεί ρητά μέσα σε αυτό το μπλοκ δήλωσης. Αυτή η μέθοδος επιστρέφει null εάν η ιδιότητα είναι συντομευμένη. Οι τιμές συντομευμένων ιδιοτήτων μπορούν να προσπελαστούν και να τροποποιηθούν μόνο ως Strings, χρησιμοποιώντας τις μεθόδους getPropertyValue και setProperty. |
| [getPropertyPriority](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(String) | Χρησιμοποιείται για την ανάκτηση της προτεραιότητας μιας ιδιότητας CSS (π.χ. ο προσδιοριστής \"important\" ) εάν η ιδιότητα έχει οριστεί ρητά σε αυτό το μπλοκ δήλωσης. |
| [getPropertyValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(String) | Η διεπαφή μεθόδου CSSStyleDeclaration.getPropertyValue() επιστρέφει ένα String που περιέχει την τιμή μιας συγκεκριμένης ιδιότητας CSS. |
| [removeProperty](../../com.aspose.html.dom.css/icssstyledeclaration/removeproperty/)(String) | Η διεπαφή μεθόδου CSSStyleDeclaration.removeProperty() αφαιρεί μια ιδιότητα από ένα αντικείμενο δήλωσης στυλ CSS. |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(String, String) | Η διεπαφή μεθόδου CSSStyleDeclaration.setProperty() χρησιμοποιείται για τον ορισμό μιας τιμής ιδιότητας με προεπιλεγμένη προτεραιότητα μέσα σε αυτό το μπλοκ δήλωσης. Η προεπιλεγμένη προτεραιότητα δεν είναι \"important\", δηλαδή String.Empty. |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(String, String, String) | Η διεπαφή μεθόδου CSSStyleDeclaration.setProperty() χρησιμοποιείται για τον ορισμό μιας τιμής ιδιότητας με προεπιλεγμένη προτεραιότητα μέσα σε αυτό το μπλοκ δήλωσης. Η προεπιλεγμένη προτεραιότητα δεν είναι \"important\", δηλαδή String.Empty. |

## Παρατηρήσεις

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Αναφορά

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstyledeclaration](https://drafts.csswg.org/cssom/#cssstyledeclaration) – The CSSOM definition.

### Δείτε επίσης

* interface [ICSS2Properties](../icss2properties/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
