---
title: "MutationRecord Κλάση"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.mutations.MutationRecord κλάση. Ένα MutationRecord αντιπροσωπεύει μια μεμονωμένη μεταβολή DOM. Είναι το αντικείμενο που περνάει στο MutationObservers MutationCallback"
type: docs

url: /el/java/com.aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

Ένα MutationRecord αντιπροσωπεύει μια μεμονωμένη μεταβολή DOM. Είναι το αντικείμενο που περνάει στο [`MutationObserver`](../mutationobserver/)'s [`MutationCallback`](../mutationcallback/).

```java
public class MutationRecord : DOMObject
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getAddedNodes](../../com.aspose.html.dom.mutations/mutationrecord/addednodes/) Επιστρέφει τους προστιθέμενους κόμβους. |
| [getAttributeName](../../com.aspose.html.dom.mutations/mutationrecord/attributename/) Επιστρέφει το τοπικό όνομα του τροποποιημένου χαρακτηριστικού, και null διαφορετικά. |
| [getAttributeNamespace](../../com.aspose.html.dom.mutations/mutationrecord/attributepackage/) Επιστρέφει το πακέτο του τροποποιημένου χαρακτηριστικού, και null διαφορετικά. |
| [getNextSibling](../../com.aspose.html.dom.mutations/mutationrecord/nextsibling/) Επιστρέφει τον επόμενο αδελφό των προστιθέμενων ή αφαιρεθέντων κόμβων, ή null. |
| [getOldValue](../../com.aspose.html.dom.mutations/mutationrecord/oldvalue/) Η τιμή επιστροφής εξαρτάται από τον τύπο. Για "attributes", είναι η τιμή του τροποποιημένου χαρακτηριστικού πριν την αλλαγή. Για "characterData", είναι τα δεδομένα του τροποποιημένου κόμβου πριν την αλλαγή. Για "childList", είναι null. |
| [getPreviousSibling](../../com.aspose.html.dom.mutations/mutationrecord/previoussibling/) Επιστρέφει τον προηγούμενο αδελφό των προστιθέμενων ή αφαιρεθέντων κόμβων, ή null. |
| [getRemovedNodes](../../com.aspose.html.dom.mutations/mutationrecord/removednodes/) Επιστρέφει τους αφαιρεθέντες κόμβους. |
| [getTarget](../../com.aspose.html.dom.mutations/mutationrecord/target/) Επιστρέφει τον κόμβο που επηρεάστηκε από τη μεταβολή, ανάλογα με τον τύπο. Για "attributes", είναι το στοιχείο του οποίου το χαρακτηριστικό άλλαξε. Για "characterData", είναι ο κόμβος CharacterData. Για "childList", είναι ο κόμβος του οποίου τα παιδιά άλλαξαν. |
| [getType](../../com.aspose.html.dom.mutations/mutationrecord/type/) Επιστρέφει "attributes" αν ήταν μεταβολή χαρακτηριστικού, "characterData" αν ήταν μεταβολή σε κόμβο CharacterData και "childList" αν ήταν μεταβολή στο δέντρο των κόμβων. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του αντικειμένου ECMAScript. |

### Δείτε επίσης

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
