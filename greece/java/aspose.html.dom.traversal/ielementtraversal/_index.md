---
title: "Διεπαφή IElementTraversal"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Διεπαφή com.aspose.html.dom.traversal.IElementTraversal. Η διεπαφή ElementTraversal είναι ένα σύνολο ιδιοτήτων μόνο για ανάγνωση που επιτρέπουν σε έναν δημιουργό να πλοηγείται εύκολα μεταξύ των στοιχείων σε ένα έγγραφο. Σε συμβατές υλοποιήσεις του Element Traversal, όλα τα αντικείμενα που υλοποιούν το Element πρέπει επίσης να υλοποιούν τη διεπαφή ElementTraversal."
type: docs

url: /el/java/com.aspose.html.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

Η διεπαφή ElementTraversal είναι ένα σύνολο μόνο-για-ανάγνωση χαρακτηριστικών που επιτρέπουν σε έναν συγγραφέα να πλοηγείται εύκολα μεταξύ στοιχείων σε ένα έγγραφο. Σε συμμορφούμενες υλοποιήσεις του Element Traversal, όλα τα αντικείμενα που υλοποιούν το Element πρέπει επίσης να υλοποιούν τη διεπαφή ElementTraversal.

```java
public interface IElementTraversal
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getChildElementCount](../../com.aspose.html.dom.traversal/ielementtraversal/childelementcount/) Επιστρέφει τον τρέχοντα αριθμό κόμβων στοιχείων που είναι παιδιά αυτού του στοιχείου. 0 εάν αυτό το στοιχείο δεν έχει κόμβους-παιδιά τύπου nodeType 1. |
| [getFirstElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/firstelementchild/) Επιστρέφει τον πρώτο παιδικό κόμβο στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει παιδικά στοιχεία. |
| [getLastElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/lastelementchild/) Επιστρέφει τον τελευταίο παιδικό κόμβο στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει παιδικά στοιχεία. |
| [getNextElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/nextelementsibling/) Επιστρέφει τον επόμενο αδερφό κόμβο στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει αδερφούς κόμβους στοιχείου που έρχονται μετά από αυτό στο δέντρο του εγγράφου. |
| [getPreviousElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/previouselementsibling/) Επιστρέφει τον προηγούμενο αδερφό κόμβο στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει αδερφούς κόμβους στοιχείου που έρχονται πριν από αυτό στο δέντρο του εγγράφου. |

### Δείτε επίσης

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
