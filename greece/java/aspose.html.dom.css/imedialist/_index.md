---
title: "IMediaList Διεπαφή"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.css.IMediaList διεπαφή. Η διεπαφή MediaList παρέχει την αφαίρεση μιας διατεταγμένης συλλογής μέσων χωρίς να ορίζει ή να περιορίζει τον τρόπο υλοποίησης αυτής της συλλογής. Μια κενή λίστα είναι η ίδια με μια λίστα που περιέχει όλα τα μέσα."
type: docs

url: /el/java/com.aspose.html.dom.css/imedialist/
---
## IMediaList interface

Η διεπαφή MediaList παρέχει την αφαίρεση μιας διατεταγμένης συλλογής μέσων, χωρίς να ορίζει ή να περιορίζει πώς υλοποιείται αυτή η συλλογή. Μια κενή λίστα είναι η ίδια με μια λίστα που περιέχει το μέσο "all".

Δείτε επίσης το [CSS Object Model (CSSOM) # ](https://www.w3.org/TR/cssom-1/#the-medialist-interface)[MediaList](https://www.w3.org/TR/cssom-1/#the-medialist-interface).

```java
public interface IMediaList : IEnumerable<String>
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/imedialist/item/) Η μέθοδος item(index) πρέπει να επιστρέφει μια σειριοποίηση του ερωτήματος μέσου στη συλλογή ερωτημάτων μέσων που δίνεται από το index, ή null, εάν το index είναι μεγαλύτερο ή ίσο με τον αριθμό των ερωτημάτων μέσων στη συλλογή. |
| [getLength](../../com.aspose.html.dom.css/imedialist/length/) Η ιδιότητα length πρέπει να επιστρέφει τον αριθμό των ερωτημάτων μέσων στη συλλογή. Το εύρος των έγκυρων μέσων είναι από 0 έως length-1 συμπεριλαμβανομένου. |
| [getMediaText](../../com.aspose.html.dom.css/imedialist/mediatext/) Ένας Stringifier που επιστρέφει ένα DOMString που αντιπροσωπεύει το MediaList ως κείμενο, και επίσης επιτρέπει τον ορισμό ενός νέου MediaList. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [appendMedium](../../com.aspose.html.dom.css/imedialist/appendmedium/)(String) | Προσθέτει το μέσο newMedium στο τέλος της λίστας. Εάν το newMedium χρησιμοποιείται ήδη, αφαιρείται πρώτα. |
| [deleteMedium](../../com.aspose.html.dom.css/imedialist/deletemedium/)(String) | Διαγράφει το μέσο που υποδεικνύεται από το oldMedium από τη λίστα. |

## Παρατηρήσεις

Σημείωση: Το MediaList είναι μια ζωντανή λίστα· η ενημέρωση της λίστας χρησιμοποιώντας τις ιδιότητες ή τις μεθόδους που παρατίθενται παρακάτω θα ενημερώσει αμέσως τη συμπεριφορά του εγγράφου.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Αναφορά

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # medialist](https://drafts.csswg.org/cssom/#medialist) – The CSSOM definition.

## Παραδείγματα

Το παρακάτω θα καταγράψει στην κονσόλα μια κειμενική αναπαράσταση του MediaList του πρώτου φύλλου στυλ που εφαρμόζεται στο τρέχον έγγραφο.

```java
var stylesheets = document.StyleSheets;
var stylesheet = stylesheets[0];
Console.Write(stylesheet.Media.MediaText);
```

### Δείτε επίσης

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
