---
title: "Διεπαφή IStyleSheetList"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Διεπαφή com.aspose.html.dom.css.IStyleSheetList. Η διεπαφή StyleSheetList αντιπροσωπεύει μια λίστα αντικειμένων CSSStyleSheet. Ένα στιγμιότυπο αυτού του αντικειμένου μπορεί να ληφθεί από το Document.styleSheets."
type: docs

url: /el/java/com.aspose.html.dom.css/istylesheetlist/
---
## IStyleSheetList interface

Η διεπαφή StyleSheetList αντιπροσωπεύει μια λίστα αντικειμένων [`CSSStyleSheet`](../icssstylesheet/). Ένα στιγμιότυπο αυτού του αντικειμένου μπορεί να ληφθεί από το [`Document.styleSheets`](../../com.aspose.html.dom/document/stylesheets/).

Οι υποστηριζόμενοι δείκτες ιδιοτήτων του αντικειμένου είναι οι αριθμοί στο εύρος από το μηδέν έως ένα λιγότερο από τον αριθμό των φύλλων στυλ CSS που αντιπροσωπεύονται από τη συλλογή. Εάν δεν υπάρχουν τέτοια φύλλα στυλ CSS, τότε δεν υπάρχουν υποστηριζόμενοι δείκτες ιδιοτήτων.

```java
public interface IStyleSheetList : IEnumerable<ICSSStyleSheet>
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/istylesheetlist/item/) Η μέθοδος item(index) πρέπει να επιστρέφει το στοιχείο με τον συγκεκριμένο δείκτη [`CSS style sheet`](../icssstylesheet/) στη συλλογή. Εάν δεν υπάρχει αντικείμενο με αυτόν τον δείκτη στη συλλογή, η μέθοδος πρέπει να επιστρέφει null. |
| [getLength](../../com.aspose.html.dom.css/istylesheetlist/length/) Το χαρακτηριστικό length πρέπει να επιστρέφει τον αριθμό των φύλλων στυλ CSS που αντιπροσωπεύονται από τη συλλογή. Το εύρος των έγκυρων δεικτών υποφύλλων είναι από 0 έως length‑1, συμπεριλαμβανομένου. |

## Παρατηρήσεις

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Αναφορά

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # stylesheetlist](https://drafts.csswg.org/cssom/#stylesheetlist) – The CSSOM definition.

### Δείτε επίσης

* interface [ICSSStyleSheet](../icssstylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
