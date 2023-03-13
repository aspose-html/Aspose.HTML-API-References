---
title: Interface IElementTraversal
second_title: Aspose.HTML για Αναφορά API .NET
description: Aspose.Html.Dom.Traversal.IElementTraversal διεπαφή. Η διεπαφή ElementTraversal είναι ένα σύνολο χαρακτηριστικών μόνο για ανάγνωση που επιτρέπουν στον συγγραφέα να πλοηγείται εύκολα μεταξύ των στοιχείων ενός εγγράφου. Κατά τη συμμόρφωση με υλοποιήσεις του Element Traversal όλα τα αντικείμενα που υλοποιούν το Element πρέπει επίσης να υλοποιούν τη διεπαφή ElementTraversal.
type: docs
weight: 2480
url: /el/net/aspose.html.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

Η διεπαφή ElementTraversal είναι ένα σύνολο χαρακτηριστικών μόνο για ανάγνωση που επιτρέπουν στον συγγραφέα να πλοηγείται εύκολα μεταξύ των στοιχείων ενός εγγράφου. Κατά τη συμμόρφωση με υλοποιήσεις του Element Traversal, όλα τα αντικείμενα που υλοποιούν το Element πρέπει επίσης να υλοποιούν τη διεπαφή ElementTraversal.

```csharp
public interface IElementTraversal
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [ChildElementCount](../../aspose.html.dom.traversal/ielementtraversal/childelementcount/) { get; } | Επιστρέφει τον τρέχοντα αριθμό κόμβων στοιχείων που είναι παιδιά αυτού του στοιχείου. 0 εάν αυτό το στοιχείο δεν έχει θυγατρικούς κόμβους που είναι τύπου node 1. |
| [FirstElementChild](../../aspose.html.dom.traversal/ielementtraversal/firstelementchild/) { get; } | Επιστρέφει τον πρώτο κόμβο θυγατρικού στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει θυγατρικά στοιχεία. |
| [LastElementChild](../../aspose.html.dom.traversal/ielementtraversal/lastelementchild/) { get; } | Επιστρέφει τον τελευταίο κόμβο θυγατρικού στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει θυγατρικά στοιχεία. |
| [NextElementSibling](../../aspose.html.dom.traversal/ielementtraversal/nextelementsibling/) { get; } | Επιστρέφει τον επόμενο κόμβο αδελφικού στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει κανένα στοιχείο αδελφούς κόμβους που έρχονται μετά από αυτό στο δέντρο εγγράφων. |
| [PreviousElementSibling](../../aspose.html.dom.traversal/ielementtraversal/previouselementsibling/) { get; } | Επιστρέφει τον προηγούμενο κόμβο αδελφικού στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει κόμβους αδερφού στοιχείου που βρίσκονται πριν από αυτό στο δέντρο εγγράφων. |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* συνέλευση [Aspose.HTML](../../)


