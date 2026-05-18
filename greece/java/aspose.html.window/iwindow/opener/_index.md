---
title: "IWindow.Opener"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "IWindow ιδιότητα. Το opener IDL attribute στο αντικείμενο Window κατά την ανάγνωση πρέπει να επιστρέφει το αντικείμενο WindowProxy του browsing context από το οποίο δημιουργήθηκε το τρέχον browsing context (το opener browsing context) αν υπάρχει, αν είναι ακόμη διαθέσιμο και αν το τρέχον browsing context δεν έχει αποχωρήσει τον opener του· διαφορετικά πρέπει να επιστρέφει null. Κατά τη ρύθμιση, αν η νέα τιμή είναι null, τότε το τρέχον browsing context πρέπει να αποχωρήσει τον opener του· αν η νέα τιμή είναι κάτι άλλο, τότε ο user agent πρέπει να καλέσει τη μέθοδο εσωτερική [[DefineOwnProperty]] του αντικειμένου Window, περνώντας το όνομα ιδιότητας \"opener\" ως κλειδί ιδιότητας και τον Περιγραφέα Ιδιότητας { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } ως περιγραφέα ιδιότητας, όπου value είναι η νέα τιμή"
type: docs

url: /el/java/com.aspose.html.window/iwindow/opener/
---
## IWindow.Opener property

Το opener IDL attribute στο αντικείμενο Window, κατά την ανάγνωση, πρέπει να επιστρέφει το αντικείμενο WindowProxy του browsing context από το οποίο δημιουργήθηκε το τρέχον browsing context (το opener browsing context), αν υπάρχει, αν είναι ακόμη διαθέσιμο, και αν το τρέχον browsing context δεν έχει αποχωρήσει τον opener του· διαφορετικά πρέπει να επιστρέφει null. Κατά τη ρύθμιση, αν η νέα τιμή είναι null, τότε το τρέχον browsing context πρέπει να αποχωρήσει τον opener του· αν η νέα τιμή είναι κάτι άλλο, τότε ο user agent πρέπει να καλέσει τη μέθοδο εσωτερική [[DefineOwnProperty]] του αντικειμένου Window, περνώντας το όνομα ιδιότητας "opener" ως κλειδί ιδιότητας και τον Περιγραφέα Ιδιότητας { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } ως περιγραφέα ιδιότητας, όπου value είναι η νέα τιμή

```java
public IWindow Opener { get; }
```

### Property Value

Ο opener.

### Δείτε επίσης

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
