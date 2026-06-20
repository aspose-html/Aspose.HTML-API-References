---
title: "Converter.ConvertMHTML"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Converter. Μετατρέψτε την πηγή MHTML που παρουσιάζεται από ροή εισόδου. Το αποτέλεσμα είναι αρχείο xps που δημιουργείται από τη διαδρομή εξόδου"
type: docs

url: /el/java/com.aspose.html.converters/converter/convertmhtml/
---
## ConvertMHTML(Stream, XpsSaveOptions, String) {#convertmhtml_31}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται μέσω εισόδου [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0). Το αποτέλεσμα είναι αρχείο xps που δημιουργείται από τη διαδρομή εξόδου του αρχείου.

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή δεδομένων εισόδου mhtml (.mht). |
| options | XpsSaveOptions | Η χρήση του αντικειμένου [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε την [Τεκμηρίωση Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου xps ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε [XPS](https://docs.fileformat.com/page-description-language/xps/) συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή XPS για συγκεκριμένες εργασίες. Ένα αρχείο XPS αντιπροσωπεύει αρχεία διάταξης σελίδας που βασίζονται στις XML Paper Specifications, δημιουργημένα από τη Microsoft.

Ανατρέξτε στο [άρθρο](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε XPS χρησιμοποιώντας τις μεθόδους ConvertHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε XPS

Η κλάση Converter προσφέρει λίγες ειδικές μετατροπές MHTML σε XPS. Για να μετατρέψετε MHTML σε XPS, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπική ή προσαρμοσμένη ροή ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα XPS με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [Μετατροπέας MHTML σε XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) που μετατρέπει MHTML σε XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Ορισμός προεπιλεγμένου αντικειμένου XpsSaveOptions
      var options = new XpsSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, String) {#convertmhtml_47}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται με πλήρη διαδρομή αρχείου σε XPS. Το αποτέλεσμα είναι αρχείο xps που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής MHTML. |
| options | XpsSaveOptions | Η χρήση του αντικειμένου [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε την [Τεκμηρίωση Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου xps ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε [XPS](https://docs.fileformat.com/page-description-language/xps/) συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή XPS για συγκεκριμένες εργασίες. Ένα αρχείο XPS αντιπροσωπεύει αρχεία διάταξης σελίδας που βασίζονται στις XML Paper Specifications, δημιουργημένα από τη Microsoft.

Ανατρέξτε στο [άρθρο](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε XPS χρησιμοποιώντας τις μεθόδους ConvertHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε XPS

Η κλάση Converter προσφέρει λίγες ειδικές μετατροπές MHTML σε XPS. Για να μετατρέψετε MHTML σε XPS, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπική ή προσαρμοσμένη ροή ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα XPS με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [Μετατροπέας MHTML σε XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) που μετατρέπει MHTML σε XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Διαδρομή αρχείου πηγής φόρμας
	var sourcePath = Path.Combine(InputFolder, "sample.mht");

	// Διαδρομή αρχείου αποτελέσματος φόρμας
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Ορισμός προεπιλεγμένου αντικειμένου XpsSaveOptions
	var options = new XpsSaveOptions();

	// Ξεκινήστε τη διαδικασία μετατροπής
	Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, String) {#convertmhtml_15}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται μέσω URL. Το αποτέλεσμα είναι αρχείο xps που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL εγγράφου πηγής MHTML - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| options | XpsSaveOptions | Η χρήση του αντικειμένου [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε την [Τεκμηρίωση Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου xps ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε [XPS](https://docs.fileformat.com/page-description-language/xps/) συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή XPS για συγκεκριμένες εργασίες. Ένα αρχείο XPS αντιπροσωπεύει αρχεία διάταξης σελίδας που βασίζονται στις XML Paper Specifications, δημιουργημένα από τη Microsoft.

Ανατρέξτε στο [άρθρο](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε XPS χρησιμοποιώντας τις μεθόδους ConvertHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε XPS

Η κλάση Converter προσφέρει λίγες ειδικές μετατροπές MHTML σε XPS. Για να μετατρέψετε MHTML σε XPS, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπική ή προσαρμοσμένη ροή ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα XPS με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [Μετατροπέας MHTML σε XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) που μετατρέπει MHTML σε XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Διαδρομή αρχείου πηγής φόρμας
	var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

	// Διαδρομή αρχείου αποτελέσματος φόρμας
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Ορισμός προεπιλεγμένου αντικειμένου XpsSaveOptions
	var options = new XpsSaveOptions();

	// Ξεκινήστε τη διαδικασία μετατροπής
	Converter.ConvertMHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, String) {#convertmhtml_23}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται από την είσοδο [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0). Το αποτέλεσμα είναι αρχείο xps που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή δεδομένων πηγής μετατροπής mhtml (.mht). |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | XpsSaveOptions | Η χρήση του αντικειμένου [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε την [Τεκμηρίωση Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου xps ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε [XPS](https://docs.fileformat.com/page-description-language/xps/) συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή XPS για συγκεκριμένες εργασίες. Ένα αρχείο XPS αντιπροσωπεύει αρχεία διάταξης σελίδας που βασίζονται στις XML Paper Specifications, δημιουργημένα από τη Microsoft.

Ανατρέξτε στο [άρθρο](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε XPS χρησιμοποιώντας τις μεθόδους ConvertHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε XPS

Η κλάση Converter προσφέρει λίγες ειδικές μετατροπές MHTML σε XPS. Για να μετατρέψετε MHTML σε XPS, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπική ή προσαρμοσμένη ροή ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα XPS με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [Μετατροπέας MHTML σε XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) που μετατρέπει MHTML σε XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Ορισμός προεπιλεγμένου αντικειμένου XpsSaveOptions
      var options = new XpsSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
      Converter.ConvertMHTML(File.OpenRead(sourcePath), new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, XpsSaveOptions, String) {#convertmhtml_39}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται με πλήρη διαδρομή αρχείου σε XPS. Το αποτέλεσμα είναι αρχείο xps που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής MHTML. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | XpsSaveOptions | Η χρήση του αντικειμένου [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε την [Τεκμηρίωση Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου xps ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε [XPS](https://docs.fileformat.com/page-description-language/xps/) συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή XPS για συγκεκριμένες εργασίες. Ένα αρχείο XPS αντιπροσωπεύει αρχεία διάταξης σελίδας που βασίζονται στις XML Paper Specifications, δημιουργημένα από τη Microsoft.

Ανατρέξτε στο [άρθρο](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε XPS χρησιμοποιώντας τις μεθόδους ConvertHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε XPS

Η κλάση Converter προσφέρει λίγες ειδικές μετατροπές MHTML σε XPS. Για να μετατρέψετε MHTML σε XPS, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπική ή προσαρμοσμένη ροή ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα XPS με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [Μετατροπέας MHTML σε XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) που μετατρέπει MHTML σε XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Ορισμός προεπιλεγμένου αντικειμένου XpsSaveOptions
      var options = new XpsSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, XpsSaveOptions, String) {#convertmhtml_7}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται μέσω URL. Το αποτέλεσμα είναι αρχείο xps που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL εγγράφου πηγής MHTML - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | XpsSaveOptions | Η χρήση του αντικειμένου [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε την [Τεκμηρίωση Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου xps ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε [XPS](https://docs.fileformat.com/page-description-language/xps/) συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή XPS για συγκεκριμένες εργασίες. Ένα αρχείο XPS αντιπροσωπεύει αρχεία διάταξης σελίδας που βασίζονται στις XML Paper Specifications, δημιουργημένα από τη Microsoft.

Ανατρέξτε στο [άρθρο](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε XPS χρησιμοποιώντας τις μεθόδους ConvertHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε XPS

Η κλάση Converter προσφέρει λίγες ειδικές μετατροπές MHTML σε XPS. Για να μετατρέψετε MHTML σε XPS, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπική ή προσαρμοσμένη ροή ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα XPS με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [Μετατροπέας MHTML σε XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) που μετατρέπει MHTML σε XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Διαδρομή αρχείου πηγής φόρμας
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Ορισμός προεπιλεγμένου αντικειμένου XpsSaveOptions
      var options = new XpsSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_30}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται από ροή εισόδου. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή δεδομένων πηγής μετατροπής mhtml (.mht). |
| options | XpsSaveOptions | Η χρήση του αντικειμένου [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε την [Τεκμηρίωση Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση του [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την λήψη ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε [XPS](https://docs.fileformat.com/page-description-language/xps/) συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή XPS για συγκεκριμένες εργασίες. Ένα αρχείο XPS αντιπροσωπεύει αρχεία διάταξης σελίδας που βασίζονται στις XML Paper Specifications, δημιουργημένα από τη Microsoft.

Ανατρέξτε στο [άρθρο](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε XPS χρησιμοποιώντας τις μεθόδους ConvertHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε XPS

Η κλάση Converter προσφέρει λίγες ειδικές μετατροπές MHTML σε XPS. Για να μετατρέψετε MHTML σε XPS, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπική ή προσαρμοσμένη ροή ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα XPS με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [Μετατροπέας MHTML σε XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) που μετατρέπει MHTML σε XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Χρήση μιας υλοποίησης του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ορισμός προεπιλεγμένου αντικειμένου XpsSaveOptions
      var options = new XpsSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_46}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται από πλήρη διαδρομή αρχείου σε XPS. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής MHTML. |
| options | XpsSaveOptions | Η χρήση του αντικειμένου [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε την [Τεκμηρίωση Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Γνωστή (δείτε [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ή προσαρμοσμένη υλοποίηση του interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε [XPS](https://docs.fileformat.com/page-description-language/xps/) συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή XPS για συγκεκριμένες εργασίες. Ένα αρχείο XPS αντιπροσωπεύει αρχεία διάταξης σελίδας που βασίζονται στις XML Paper Specifications, δημιουργημένα από τη Microsoft.

Ανατρέξτε στο [άρθρο](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε XPS χρησιμοποιώντας τις μεθόδους ConvertHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε XPS

Η κλάση Converter προσφέρει λίγες ειδικές μετατροπές MHTML σε XPS. Για να μετατρέψετε MHTML σε XPS, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπική ή προσαρμοσμένη ροή ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα XPS με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [Μετατροπέας MHTML σε XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) που μετατρέπει MHTML σε XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορισμός προεπιλεγμένου αντικειμένου XpsSaveOptions
      var options = new XpsSaveOptions();

      // Χρήση μιας υλοποίησης του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertMHTML(sourcePath, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_14}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται από [`URL`](../../../com.aspose.html/url/). Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL εγγράφου πηγής MHTML - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| options | XpsSaveOptions | Η χρήση του αντικειμένου [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε την [Τεκμηρίωση Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση του [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την λήψη ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε [XPS](https://docs.fileformat.com/page-description-language/xps/) συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή XPS για συγκεκριμένες εργασίες. Ένα αρχείο XPS αντιπροσωπεύει αρχεία διάταξης σελίδας που βασίζονται στις XML Paper Specifications, δημιουργημένα από τη Microsoft.

Ανατρέξτε στο [άρθρο](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε XPS χρησιμοποιώντας τις μεθόδους ConvertHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε XPS

Η κλάση Converter προσφέρει λίγες ειδικές μετατροπές MHTML σε XPS. Για να μετατρέψετε MHTML σε XPS, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπική ή προσαρμοσμένη ροή ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα XPS με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [Μετατροπέας MHTML σε XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) που μετατρέπει MHTML σε XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io; 
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Διαδρομή αρχείου πηγής φόρμας
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορισμός προεπιλεγμένου αντικειμένου XpsSaveOptions
      var options = new XpsSaveOptions();

      // Χρήση μιας υλοποίησης του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertMHTML(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_22}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται από ροή εισόδου. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή δεδομένων πηγής μετατροπής mhtml (.mht). |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | XpsSaveOptions | Η χρήση του αντικειμένου [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε την [Τεκμηρίωση Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση του [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την λήψη ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε [XPS](https://docs.fileformat.com/page-description-language/xps/) συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή XPS για συγκεκριμένες εργασίες. Ένα αρχείο XPS αντιπροσωπεύει αρχεία διάταξης σελίδας που βασίζονται στις XML Paper Specifications, δημιουργημένα από τη Microsoft.

Ανατρέξτε στο [άρθρο](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε XPS χρησιμοποιώντας τις μεθόδους ConvertHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε XPS

Η κλάση Converter προσφέρει λίγες ειδικές μετατροπές MHTML σε XPS. Για να μετατρέψετε MHTML σε XPS, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπική ή προσαρμοσμένη ροή ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα XPS με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [Μετατροπέας MHTML σε XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) που μετατρέπει MHTML σε XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Χρήση μιας υλοποίησης του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ορισμός προεπιλεγμένου αντικειμένου XpsSaveOptions
      var options = new XpsSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_38}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται από πλήρη διαδρομή αρχείου σε XPS. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής MHTML. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | XpsSaveOptions | Η χρήση του αντικειμένου [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε την [Τεκμηρίωση Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Γνωστή (δείτε [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ή προσαρμοσμένη υλοποίηση του interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε [XPS](https://docs.fileformat.com/page-description-language/xps/) συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή XPS για συγκεκριμένες εργασίες. Ένα αρχείο XPS αντιπροσωπεύει αρχεία διάταξης σελίδας που βασίζονται στις XML Paper Specifications, δημιουργημένα από τη Microsoft.

Ανατρέξτε στο [άρθρο](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε XPS χρησιμοποιώντας τις μεθόδους ConvertHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε XPS

Η κλάση Converter προσφέρει λίγες ειδικές μετατροπές MHTML σε XPS. Για να μετατρέψετε MHTML σε XPS, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπική ή προσαρμοσμένη ροή ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα XPS με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [Μετατροπέας MHTML σε XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) που μετατρέπει MHTML σε XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορισμός προεπιλεγμένου αντικειμένου XpsSaveOptions
      var options = new XpsSaveOptions();

      // Χρήση μιας υλοποίησης του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_6}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται από URL. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL εγγράφου πηγής MHTML - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | XpsSaveOptions | Η χρήση του αντικειμένου [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε την [Τεκμηρίωση Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Γνωστή (δείτε [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ή προσαρμοσμένη υλοποίηση του interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε [XPS](https://docs.fileformat.com/page-description-language/xps/) συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή XPS για συγκεκριμένες εργασίες. Ένα αρχείο XPS αντιπροσωπεύει αρχεία διάταξης σελίδας που βασίζονται στις XML Paper Specifications, δημιουργημένα από τη Microsoft.

Ανατρέξτε στο [άρθρο](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε XPS χρησιμοποιώντας τις μεθόδους ConvertHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε XPS

Η κλάση Converter προσφέρει λίγες ειδικές μετατροπές MHTML σε XPS. Για να μετατρέψετε MHTML σε XPS, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπική ή προσαρμοσμένη ροή ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα XPS με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [Μετατροπέας MHTML σε XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) που μετατρέπει MHTML σε XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Διαδρομή αρχείου πηγής φόρμας
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορισμός προεπιλεγμένου αντικειμένου XpsSaveOptions
      var options = new XpsSaveOptions();

      // Χρήση μιας υλοποίησης του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, DocSaveOptions, String) {#convertmhtml_25}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται μέσω ροής εισόδου. Το αποτέλεσμα είναι αρχείο docx που δημιουργείται από τη διαδρομή εξόδου του αρχείου.

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή δεδομένων εισόδου μετατροπής MHTML. |
| options | DocSaveOptions | Η χρήση του αντικειμένου [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου docx ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε DOCX συχνά απαιτείται για να αξιοποιηθεί η μορφή [DOCX](https://docs.fileformat.com/word-processing/docx/) για συγκεκριμένες εργασίες. Το DOCX είναι μια γνωστή μορφή εγγράφων Microsoft Word. Μπορεί να περιέχει ένα ευρύ φάσμα δεδομένων, συμπεριλαμβανομένου κειμένου, πινάκων, ραστών και διανυσματικών γραφικών, βίντεο, ήχων και διαγραμμάτων. Αυτή η μορφή είναι δημοφιλής επειδή υποστηρίζει σύνθετες δυνατότητες μορφοποίησης και προσφέρει στους χρήστες ποικίλες επιλογές για τη δημιουργία οποιουδήποτε τύπου εγγράφου.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε DOCX χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε DOCX

Η κλάση Converter προσφέρει μερικές συγκεκριμένες μετατροπές MHTML σε DOCX. Για να μετατρέψετε MHTML σε DOCX, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπική ή προσαρμοσμένη συγκεκριμένη ροή ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή αρχείου εξόδου του αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα DOCX με τρία ή περισσότερα παραμέτρους ανάλογα με το σενάριο χρήστη. Online MHTML converter

Η Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) που μετατρέπει MHTML σε DOCX με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Ορίστε το προεπιλεγμένο αντικείμενο DocSaveOptions
      var options = new DocSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, DocSaveOptions, String) {#convertmhtml_41}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται μέσω πλήρους διαδρομής αρχείου σε DOCX. Το αποτέλεσμα είναι αρχείο docx που δημιουργείται από τη διαδρομή εξόδου του αρχείου.

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Διαδρομή αρχείου πηγής MHTML. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει απόλυτο URL. |
| options | DocSaveOptions | Η χρήση του αντικειμένου [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου docx ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε DOCX συχνά απαιτείται για να αξιοποιηθεί η μορφή [DOCX](https://docs.fileformat.com/word-processing/docx/) για συγκεκριμένες εργασίες. Το DOCX είναι μια γνωστή μορφή εγγράφων Microsoft Word. Μπορεί να περιέχει ένα ευρύ φάσμα δεδομένων, συμπεριλαμβανομένου κειμένου, πινάκων, ραστών και διανυσματικών γραφικών, βίντεο, ήχων και διαγραμμάτων. Αυτή η μορφή είναι δημοφιλής επειδή υποστηρίζει σύνθετες δυνατότητες μορφοποίησης και προσφέρει στους χρήστες ποικίλες επιλογές για τη δημιουργία οποιουδήποτε τύπου εγγράφου.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε DOCX χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε DOCX

Η κλάση Converter προσφέρει μερικές συγκεκριμένες μετατροπές MHTML σε DOCX. Για να μετατρέψετε MHTML σε DOCX, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπική ή προσαρμοσμένη συγκεκριμένη ροή ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή αρχείου εξόδου του αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα DOCX με τρία ή περισσότερα παραμέτρους ανάλογα με το σενάριο χρήστη. Online MHTML converter

Η Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) που μετατρέπει MHTML σε DOCX με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Ορίστε το προεπιλεγμένο αντικείμενο DocSaveOptions
      var options = new DocSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, DocSaveOptions, String) {#convertmhtml_9}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται μέσω URL. Το αποτέλεσμα είναι αρχείο docx που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL εγγράφου πηγής MHTML - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| options | DocSaveOptions | Η χρήση του αντικειμένου [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου docx ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε DOCX συχνά απαιτείται για να αξιοποιηθεί η μορφή [DOCX](https://docs.fileformat.com/word-processing/docx/) για συγκεκριμένες εργασίες. Το DOCX είναι μια γνωστή μορφή εγγράφων Microsoft Word. Μπορεί να περιέχει ένα ευρύ φάσμα δεδομένων, συμπεριλαμβανομένου κειμένου, πινάκων, ραστών και διανυσματικών γραφικών, βίντεο, ήχων και διαγραμμάτων. Αυτή η μορφή είναι δημοφιλής επειδή υποστηρίζει σύνθετες δυνατότητες μορφοποίησης και προσφέρει στους χρήστες ποικίλες επιλογές για τη δημιουργία οποιουδήποτε τύπου εγγράφου.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε DOCX χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε DOCX

Η κλάση Converter προσφέρει μερικές συγκεκριμένες μετατροπές MHTML σε DOCX. Για να μετατρέψετε MHTML σε DOCX, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπική ή προσαρμοσμένη συγκεκριμένη ροή ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή αρχείου εξόδου του αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα DOCX με τρία ή περισσότερα παραμέτρους ανάλογα με το σενάριο χρήστη. Online MHTML converter

Η Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) που μετατρέπει MHTML σε DOCX με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Δημιουργήστε Url βάσει διαδρομής αρχείου εισόδου
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Ορίστε το προεπιλεγμένο αντικείμενο DocSaveOptions
      var options = new DocSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertMHTML(sourceUrl, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, DocSaveOptions, String) {#convertmhtml_17}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται μέσω ροής εισόδου. Το αποτέλεσμα είναι αρχείο docx που δημιουργείται από τη διαδρομή εξόδου του αρχείου.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή δεδομένων εισόδου μετατροπής MHTML. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | DocSaveOptions | Η χρήση του αντικειμένου [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου docx ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε DOCX συχνά απαιτείται για να αξιοποιηθεί η μορφή [DOCX](https://docs.fileformat.com/word-processing/docx/) για συγκεκριμένες εργασίες. Το DOCX είναι μια γνωστή μορφή εγγράφων Microsoft Word. Μπορεί να περιέχει ένα ευρύ φάσμα δεδομένων, συμπεριλαμβανομένου κειμένου, πινάκων, ραστών και διανυσματικών γραφικών, βίντεο, ήχων και διαγραμμάτων. Αυτή η μορφή είναι δημοφιλής επειδή υποστηρίζει σύνθετες δυνατότητες μορφοποίησης και προσφέρει στους χρήστες ποικίλες επιλογές για τη δημιουργία οποιουδήποτε τύπου εγγράφου.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε DOCX χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε DOCX

Η κλάση Converter προσφέρει μερικές συγκεκριμένες μετατροπές MHTML σε DOCX. Για να μετατρέψετε MHTML σε DOCX, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπική ή προσαρμοσμένη συγκεκριμένη ροή ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή αρχείου εξόδου του αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα DOCX με τρία ή περισσότερα παραμέτρους ανάλογα με το σενάριο χρήστη. Online MHTML converter

Η Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) που μετατρέπει MHTML σε DOCX με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Ορίστε το προεπιλεγμένο αντικείμενο DocSaveOptions
      var options = new DocSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, DocSaveOptions, String) {#convertmhtml_33}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται μέσω πλήρους διαδρομής αρχείου σε DOCX. Το αποτέλεσμα είναι αρχείο docx που δημιουργείται από τη διαδρομή εξόδου του αρχείου.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής MHTML. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | DocSaveOptions | Η χρήση του αντικειμένου [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου docx ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε DOCX συχνά απαιτείται για να αξιοποιηθεί η μορφή [DOCX](https://docs.fileformat.com/word-processing/docx/) για συγκεκριμένες εργασίες. Το DOCX είναι μια γνωστή μορφή εγγράφων Microsoft Word. Μπορεί να περιέχει ένα ευρύ φάσμα δεδομένων, συμπεριλαμβανομένου κειμένου, πινάκων, ραστών και διανυσματικών γραφικών, βίντεο, ήχων και διαγραμμάτων. Αυτή η μορφή είναι δημοφιλής επειδή υποστηρίζει σύνθετες δυνατότητες μορφοποίησης και προσφέρει στους χρήστες ποικίλες επιλογές για τη δημιουργία οποιουδήποτε τύπου εγγράφου.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε DOCX χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε DOCX

Η κλάση Converter προσφέρει μερικές συγκεκριμένες μετατροπές MHTML σε DOCX. Για να μετατρέψετε MHTML σε DOCX, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπική ή προσαρμοσμένη συγκεκριμένη ροή ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή αρχείου εξόδου του αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα DOCX με τρία ή περισσότερα παραμέτρους ανάλογα με το σενάριο χρήστη. Online MHTML converter

Η Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) που μετατρέπει MHTML σε DOCX με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Ορίστε το προεπιλεγμένο αντικείμενο DocSaveOptions
      var options = new DocSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, DocSaveOptions, String) {#convertmhtml_1}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται από [`URL`](../../../com.aspose.html/url/). Το αποτέλεσμα είναι αρχείο docx που δημιουργείται από τη διαδρομή αρχείου εξόδου.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | Έγγραφο πηγής MHTML [`URL`](../../../com.aspose.html/url/) - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | DocSaveOptions | Η χρήση του αντικειμένου [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου docx ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε DOCX συχνά απαιτείται για να αξιοποιηθεί η μορφή [DOCX](https://docs.fileformat.com/word-processing/docx/) για συγκεκριμένες εργασίες. Το DOCX είναι μια γνωστή μορφή εγγράφων Microsoft Word. Μπορεί να περιέχει ένα ευρύ φάσμα δεδομένων, συμπεριλαμβανομένου κειμένου, πινάκων, ραστών και διανυσματικών γραφικών, βίντεο, ήχων και διαγραμμάτων. Αυτή η μορφή είναι δημοφιλής επειδή υποστηρίζει σύνθετες δυνατότητες μορφοποίησης και προσφέρει στους χρήστες ποικίλες επιλογές για τη δημιουργία οποιουδήποτε τύπου εγγράφου.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε DOCX χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε DOCX

Η κλάση Converter προσφέρει μερικές συγκεκριμένες μετατροπές MHTML σε DOCX. Για να μετατρέψετε MHTML σε DOCX, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπική ή προσαρμοσμένη συγκεκριμένη ροή ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή αρχείου εξόδου του αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα DOCX με τρία ή περισσότερα παραμέτρους ανάλογα με το σενάριο χρήστη. Online MHTML converter

Η Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) που μετατρέπει MHTML σε DOCX με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργήστε Url βάσει διαδρομής αρχείου εισόδου
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Ορίστε το προεπιλεγμένο αντικείμενο DocSaveOptions
      var options = new DocSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_24}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται από ροή εισόδου. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή δεδομένων εισόδου μετατροπής MHTML. |
| options | DocSaveOptions | Η χρήση του αντικειμένου [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση του [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την λήψη ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε DOCX συχνά απαιτείται για να αξιοποιηθεί η μορφή [DOCX](https://docs.fileformat.com/word-processing/docx/) για συγκεκριμένες εργασίες. Το DOCX είναι μια γνωστή μορφή εγγράφων Microsoft Word. Μπορεί να περιέχει ένα ευρύ φάσμα δεδομένων, συμπεριλαμβανομένου κειμένου, πινάκων, ραστών και διανυσματικών γραφικών, βίντεο, ήχων και διαγραμμάτων. Αυτή η μορφή είναι δημοφιλής επειδή υποστηρίζει σύνθετες δυνατότητες μορφοποίησης και προσφέρει στους χρήστες ποικίλες επιλογές για τη δημιουργία οποιουδήποτε τύπου εγγράφου.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε DOCX χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε DOCX

Η κλάση Converter προσφέρει μερικές συγκεκριμένες μετατροπές MHTML σε DOCX. Για να μετατρέψετε MHTML σε DOCX, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπική ή προσαρμοσμένη συγκεκριμένη ροή ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή αρχείου εξόδου του αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα DOCX με τρία ή περισσότερα παραμέτρους ανάλογα με το σενάριο χρήστη. Online MHTML converter

Η Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) που μετατρέπει MHTML σε DOCX με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Χρήση μιας υλοποίησης του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ορίστε το προεπιλεγμένο αντικείμενο DocSaveOptions
      var options = new DocSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_40}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται από πλήρη διαδρομή αρχείου σε DOCX. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής MHTML. |
| options | DocSaveOptions | Η χρήση του αντικειμένου [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση του [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την λήψη ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε DOCX συχνά απαιτείται για να αξιοποιηθεί η μορφή [DOCX](https://docs.fileformat.com/word-processing/docx/) για συγκεκριμένες εργασίες. Το DOCX είναι μια γνωστή μορφή εγγράφων Microsoft Word. Μπορεί να περιέχει ένα ευρύ φάσμα δεδομένων, συμπεριλαμβανομένου κειμένου, πινάκων, ραστών και διανυσματικών γραφικών, βίντεο, ήχων και διαγραμμάτων. Αυτή η μορφή είναι δημοφιλής επειδή υποστηρίζει σύνθετες δυνατότητες μορφοποίησης και προσφέρει στους χρήστες ποικίλες επιλογές για τη δημιουργία οποιουδήποτε τύπου εγγράφου.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε DOCX χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε DOCX

Η κλάση Converter προσφέρει μερικές συγκεκριμένες μετατροπές MHTML σε DOCX. Για να μετατρέψετε MHTML σε DOCX, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπική ή προσαρμοσμένη συγκεκριμένη ροή ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή αρχείου εξόδου του αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα DOCX με τρία ή περισσότερα παραμέτρους ανάλογα με το σενάριο χρήστη. Online MHTML converter

Η Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) που μετατρέπει MHTML σε DOCX με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο DocSaveOptions
      var options = new DocSaveOptions();

      // Χρήση μιας υλοποίησης του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertMHTML(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_8}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται από URL. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | Έγγραφο πηγής MHTML [`URL`](../../../com.aspose.html/url/) - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| options | DocSaveOptions | Η χρήση του αντικειμένου [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Γνωστή (δείτε [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ή προσαρμοσμένη υλοποίηση του interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε DOCX συχνά απαιτείται για να αξιοποιηθεί η μορφή [DOCX](https://docs.fileformat.com/word-processing/docx/) για συγκεκριμένες εργασίες. Το DOCX είναι μια γνωστή μορφή εγγράφων Microsoft Word. Μπορεί να περιέχει ένα ευρύ φάσμα δεδομένων, συμπεριλαμβανομένου κειμένου, πινάκων, ραστών και διανυσματικών γραφικών, βίντεο, ήχων και διαγραμμάτων. Αυτή η μορφή είναι δημοφιλής επειδή υποστηρίζει σύνθετες δυνατότητες μορφοποίησης και προσφέρει στους χρήστες ποικίλες επιλογές για τη δημιουργία οποιουδήποτε τύπου εγγράφου.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε DOCX χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε DOCX

Η κλάση Converter προσφέρει μερικές συγκεκριμένες μετατροπές MHTML σε DOCX. Για να μετατρέψετε MHTML σε DOCX, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπική ή προσαρμοσμένη συγκεκριμένη ροή ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή αρχείου εξόδου του αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα DOCX με τρία ή περισσότερα παραμέτρους ανάλογα με το σενάριο χρήστη. Online MHTML converter

Η Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) που μετατρέπει MHTML σε DOCX με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργήστε Url βάσει διαδρομής αρχείου εισόδου
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο DocSaveOptions
      var options = new DocSaveOptions();

      // Χρήση μιας υλοποίησης του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_16}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται από ροή εισόδου. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή δεδομένων εισόδου μετατροπής MHTML. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | DocSaveOptions | Η χρήση του αντικειμένου [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Γνωστή (δείτε [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ή προσαρμοσμένη υλοποίηση του interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε DOCX συχνά απαιτείται για να αξιοποιηθεί η μορφή [DOCX](https://docs.fileformat.com/word-processing/docx/) για συγκεκριμένες εργασίες. Το DOCX είναι μια γνωστή μορφή εγγράφων Microsoft Word. Μπορεί να περιέχει ένα ευρύ φάσμα δεδομένων, συμπεριλαμβανομένου κειμένου, πινάκων, ραστών και διανυσματικών γραφικών, βίντεο, ήχων και διαγραμμάτων. Αυτή η μορφή είναι δημοφιλής επειδή υποστηρίζει σύνθετες δυνατότητες μορφοποίησης και προσφέρει στους χρήστες ποικίλες επιλογές για τη δημιουργία οποιουδήποτε τύπου εγγράφου.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε DOCX χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε DOCX

Η κλάση Converter προσφέρει μερικές συγκεκριμένες μετατροπές MHTML σε DOCX. Για να μετατρέψετε MHTML σε DOCX, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπική ή προσαρμοσμένη συγκεκριμένη ροή ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή αρχείου εξόδου του αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα DOCX με τρία ή περισσότερα παραμέτρους ανάλογα με το σενάριο χρήστη. Online MHTML converter

Η Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) που μετατρέπει MHTML σε DOCX με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Χρήση μιας υλοποίησης του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ορίστε το προεπιλεγμένο αντικείμενο DocSaveOptions
      var options = new DocSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_32}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται από πλήρη διαδρομή αρχείου σε DOCX. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής MHTML. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | DocSaveOptions | Η χρήση του αντικειμένου [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση του [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την λήψη ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε DOCX συχνά απαιτείται για να αξιοποιηθεί η μορφή [DOCX](https://docs.fileformat.com/word-processing/docx/) για συγκεκριμένες εργασίες. Το DOCX είναι μια γνωστή μορφή εγγράφων Microsoft Word. Μπορεί να περιέχει ένα ευρύ φάσμα δεδομένων, συμπεριλαμβανομένου κειμένου, πινάκων, ραστών και διανυσματικών γραφικών, βίντεο, ήχων και διαγραμμάτων. Αυτή η μορφή είναι δημοφιλής επειδή υποστηρίζει σύνθετες δυνατότητες μορφοποίησης και προσφέρει στους χρήστες ποικίλες επιλογές για τη δημιουργία οποιουδήποτε τύπου εγγράφου.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε DOCX χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε DOCX

Η κλάση Converter προσφέρει μερικές συγκεκριμένες μετατροπές MHTML σε DOCX. Για να μετατρέψετε MHTML σε DOCX, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπική ή προσαρμοσμένη συγκεκριμένη ροή ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή αρχείου εξόδου του αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το configuration ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα DOCX με τρία ή περισσότερα παραμέτρους ανάλογα με το σενάριο χρήστη. Online MHTML converter

Η Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) που μετατρέπει MHTML σε DOCX με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο DocSaveOptions
      var options = new DocSaveOptions();

      // Χρήση μιας υλοποίησης του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται από [`URL`](../../../com.aspose.html/url/). Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | Έγγραφο πηγής MHTML [`URL`](../../../com.aspose.html/url/) - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | DocSaveOptions | Η χρήση του αντικειμένου [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση του [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την λήψη ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε DOCX συχνά απαιτείται για να αξιοποιηθεί η μορφή [DOCX](https://docs.fileformat.com/word-processing/docx/) για συγκεκριμένες εργασίες. Το DOCX είναι μια γνωστή μορφή εγγράφων Microsoft Word. Μπορεί να περιέχει ένα ευρύ φάσμα δεδομένων, συμπεριλαμβανομένου κειμένου, πινάκων, ραστών και διανυσματικών γραφικών, βίντεο, ήχων και διαγραμμάτων. Αυτή η μορφή είναι δημοφιλής επειδή υποστηρίζει σύνθετες δυνατότητες μορφοποίησης και προσφέρει στους χρήστες ποικίλες επιλογές για τη δημιουργία οποιουδήποτε τύπου εγγράφου.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε DOCX χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε DOCX

Η κλάση Converter προσφέρει μερικές συγκεκριμένες μετατροπές MHTML σε DOCX. Για να μετατρέψετε MHTML σε DOCX, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/). Μπορείτε επίσης να χρησιμοποιήσετε τυπική ή προσαρμοσμένη συγκεκριμένη ροή ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή αρχείου εξόδου του αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/). Μπορείτε επίσης να προσθέσετε το configuration ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα DOCX με τρία ή περισσότερα παραμέτρους ανάλογα με το σενάριο χρήστη. Online MHTML converter

Η Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) που μετατρέπει MHTML σε DOCX με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργήστε Url βάσει διαδρομής αρχείου εισόδου
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο DocSaveOptions
      var options = new DocSaveOptions();

      // Χρήση μιας υλοποίησης του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source folder path.

*OutputFolder - user output folder path.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, PdfSaveOptions, String) {#convertmhtml_29}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται μέσω ροής εισόδου. Το αποτέλεσμα είναι αρχείο pdf που δημιουργείται από τη διαδρομή εξόδου του αρχείου.

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή δεδομένων εισόδου μετατροπής MHTML. |
| options | PdfSaveOptions | Η χρήση του αντικειμένου [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου pdf ως αποτέλεσμα μετατροπής εξόδου. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε PDF συχνά απαιτείται για να αξιοποιηθεί η μορφή [PDF](https://docs.fileformat.com/pdf/) για συγκεκριμένες εργασίες. Το PDF προσφέρει πολλά οφέλη που άλλα αρχεία δεν έχουν. Για παράδειγμα, πολλά προγράμματα και εφαρμογές υποστηρίζουν έγγραφα PDF· τα αρχεία PDF είναι βελτιστοποιημένα για εκτύπωση και είναι ιδανικά για τη δημιουργία φυσικών αντιτύπων των εγγράφων σας· μπορείτε να διαμορφώσετε τις ρυθμίσεις ασφαλείας για τα αρχεία PDF - απενεργοποίηση εκτύπωσης, επεξεργασίας, χρήσης ηλεκτρονικής υπογραφής κ.λπ.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε PDF χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε PDF

Η κλάση Converter προσφέρει λίγες συγκεκριμένες μετατροπές MHTML σε PDF. Για να μετατρέψετε MHTML σε PDF, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο Url ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπικό ή προσαρμοσμένο συγκεκριμένο [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) ως πηγή. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα PDF με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) που μετατρέπει MHTML σε PDF με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Ορίστε το προεπιλεγμένο αντικείμενο PdfSaveOptions
      var options = new PdfSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, PdfSaveOptions, String) {#convertmhtml_45}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται με πλήρη διαδρομή αρχείου σε PDF. Το αποτέλεσμα είναι αρχείο pdf που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής MHTML. |
| options | PdfSaveOptions | Η χρήση του αντικειμένου [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου pdf ως αποτέλεσμα μετατροπής εξόδου. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε PDF συχνά απαιτείται για να αξιοποιηθεί η μορφή [PDF](https://docs.fileformat.com/pdf/) για συγκεκριμένες εργασίες. Το PDF προσφέρει πολλά οφέλη που άλλα αρχεία δεν έχουν. Για παράδειγμα, πολλά προγράμματα και εφαρμογές υποστηρίζουν έγγραφα PDF· τα αρχεία PDF είναι βελτιστοποιημένα για εκτύπωση και είναι ιδανικά για τη δημιουργία φυσικών αντιτύπων των εγγράφων σας· μπορείτε να διαμορφώσετε τις ρυθμίσεις ασφαλείας για τα αρχεία PDF - απενεργοποίηση εκτύπωσης, επεξεργασίας, χρήσης ηλεκτρονικής υπογραφής κ.λπ.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε PDF χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε PDF

Η κλάση Converter προσφέρει λίγες συγκεκριμένες μετατροπές MHTML σε PDF. Για να μετατρέψετε MHTML σε PDF, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο Url ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπικό ή προσαρμοσμένο συγκεκριμένο [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) ως πηγή. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε configuration ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα PDF με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) που μετατρέπει MHTML σε PDF με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Ορίστε το προεπιλεγμένο αντικείμενο PdfSaveOptions
      var options = new PdfSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, PdfSaveOptions, String) {#convertmhtml_13}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται μέσω URL. Το αποτέλεσμα είναι αρχείο pdf που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL εγγράφου πηγής MHTML - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| options | PdfSaveOptions | Η χρήση του αντικειμένου [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου pdf ως αποτέλεσμα μετατροπής εξόδου. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε PDF συχνά απαιτείται για να αξιοποιηθεί η μορφή [PDF](https://docs.fileformat.com/pdf/) για συγκεκριμένες εργασίες. Το PDF προσφέρει πολλά οφέλη που άλλα αρχεία δεν έχουν. Για παράδειγμα, πολλά προγράμματα και εφαρμογές υποστηρίζουν έγγραφα PDF· τα αρχεία PDF είναι βελτιστοποιημένα για εκτύπωση και είναι ιδανικά για τη δημιουργία φυσικών αντιτύπων των εγγράφων σας· μπορείτε να διαμορφώσετε τις ρυθμίσεις ασφαλείας για τα αρχεία PDF - απενεργοποίηση εκτύπωσης, επεξεργασίας, χρήσης ηλεκτρονικής υπογραφής κ.λπ.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε PDF χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε PDF

Η κλάση Converter προσφέρει λίγες συγκεκριμένες μετατροπές MHTML σε PDF. Για να μετατρέψετε MHTML σε PDF, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο Url ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπικό ή προσαρμοσμένο συγκεκριμένο [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) ως πηγή. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε configuration ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα PDF με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) που μετατρέπει MHTML σε PDF με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργήστε Url βάσει διαδρομής αρχείου εισόδου
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Ορίστε το προεπιλεγμένο αντικείμενο PdfSaveOptions
      var options = new PdfSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, String) {#convertmhtml_21}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται μέσω ροής εισόδου. Το αποτέλεσμα είναι αρχείο pdf που δημιουργείται από τη διαδρομή εξόδου του αρχείου.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή δεδομένων εισόδου μετατροπής MHTML. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | PdfSaveOptions | Η χρήση του αντικειμένου [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου pdf ως αποτέλεσμα μετατροπής εξόδου. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε PDF συχνά απαιτείται για να αξιοποιηθεί η μορφή [PDF](https://docs.fileformat.com/pdf/) για συγκεκριμένες εργασίες. Το PDF προσφέρει πολλά οφέλη που άλλα αρχεία δεν έχουν. Για παράδειγμα, πολλά προγράμματα και εφαρμογές υποστηρίζουν έγγραφα PDF· τα αρχεία PDF είναι βελτιστοποιημένα για εκτύπωση και είναι ιδανικά για τη δημιουργία φυσικών αντιτύπων των εγγράφων σας· μπορείτε να διαμορφώσετε τις ρυθμίσεις ασφαλείας για τα αρχεία PDF - απενεργοποίηση εκτύπωσης, επεξεργασίας, χρήσης ηλεκτρονικής υπογραφής κ.λπ.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε PDF χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε PDF

Η κλάση Converter προσφέρει λίγες συγκεκριμένες μετατροπές MHTML σε PDF. Για να μετατρέψετε MHTML σε PDF, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο Url ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπικό ή προσαρμοσμένο συγκεκριμένο [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) ως πηγή. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε configuration ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα PDF με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) που μετατρέπει MHTML σε PDF με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Ορίστε το προεπιλεγμένο αντικείμενο PdfSaveOptions
      var options = new PdfSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, PdfSaveOptions, String) {#convertmhtml_37}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται με πλήρη διαδρομή αρχείου σε PDF. Το αποτέλεσμα είναι αρχείο pdf που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Διαδρομή αρχείου πηγής MHTML. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει απόλυτο URL. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | PdfSaveOptions | Η χρήση του αντικειμένου [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου pdf ως αποτέλεσμα μετατροπής εξόδου. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε PDF συχνά απαιτείται για να αξιοποιηθεί η μορφή [PDF](https://docs.fileformat.com/pdf/) για συγκεκριμένες εργασίες. Το PDF προσφέρει πολλά οφέλη που άλλα αρχεία δεν έχουν. Για παράδειγμα, πολλά προγράμματα και εφαρμογές υποστηρίζουν έγγραφα PDF· τα αρχεία PDF είναι βελτιστοποιημένα για εκτύπωση και είναι ιδανικά για τη δημιουργία φυσικών αντιτύπων των εγγράφων σας· μπορείτε να διαμορφώσετε τις ρυθμίσεις ασφαλείας για τα αρχεία PDF - απενεργοποίηση εκτύπωσης, επεξεργασίας, χρήσης ηλεκτρονικής υπογραφής κ.λπ.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε PDF χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε PDF

Η κλάση Converter προσφέρει λίγες συγκεκριμένες μετατροπές MHTML σε PDF. Για να μετατρέψετε MHTML σε PDF, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο Url ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπικό ή προσαρμοσμένο συγκεκριμένο [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) ως πηγή. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε configuration ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα PDF με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) που μετατρέπει MHTML σε PDF με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Ορίστε το προεπιλεγμένο αντικείμενο PdfSaveOptions
      var options = new PdfSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, PdfSaveOptions, String) {#convertmhtml_5}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται μέσω URL. Το αποτέλεσμα είναι αρχείο pdf που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL εγγράφου πηγής MHTML - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | PdfSaveOptions | Η χρήση του αντικειμένου [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου pdf ως αποτέλεσμα μετατροπής εξόδου. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε PDF συχνά απαιτείται για να αξιοποιηθεί η μορφή [PDF](https://docs.fileformat.com/pdf/) για συγκεκριμένες εργασίες. Το PDF προσφέρει πολλά οφέλη που άλλα αρχεία δεν έχουν. Για παράδειγμα, πολλά προγράμματα και εφαρμογές υποστηρίζουν έγγραφα PDF· τα αρχεία PDF είναι βελτιστοποιημένα για εκτύπωση και είναι ιδανικά για τη δημιουργία φυσικών αντιτύπων των εγγράφων σας· μπορείτε να διαμορφώσετε τις ρυθμίσεις ασφαλείας για τα αρχεία PDF - απενεργοποίηση εκτύπωσης, επεξεργασίας, χρήσης ηλεκτρονικής υπογραφής κ.λπ.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε PDF χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε PDF

Η κλάση Converter προσφέρει λίγες συγκεκριμένες μετατροπές MHTML σε PDF. Για να μετατρέψετε MHTML σε PDF, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο Url ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπικό ή προσαρμοσμένο συγκεκριμένο [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) ως πηγή. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε configuration ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα PDF με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) που μετατρέπει MHTML σε PDF με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργήστε Url βάσει διαδρομής αρχείου εισόδου
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Ορίστε το προεπιλεγμένο αντικείμενο PdfSaveOptions
      var options = new PdfSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_28}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται από ροή εισόδου. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή δεδομένων εισόδου μετατροπής MHTML. |
| options | PdfSaveOptions | Η χρήση του αντικειμένου [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Γνωστή (δείτε [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ή προσαρμοσμένη υλοποίηση του interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε PDF συχνά απαιτείται για να αξιοποιηθεί η μορφή [PDF](https://docs.fileformat.com/pdf/) για συγκεκριμένες εργασίες. Το PDF προσφέρει πολλά οφέλη που άλλα αρχεία δεν έχουν. Για παράδειγμα, πολλά προγράμματα και εφαρμογές υποστηρίζουν έγγραφα PDF· τα αρχεία PDF είναι βελτιστοποιημένα για εκτύπωση και είναι ιδανικά για τη δημιουργία φυσικών αντιτύπων των εγγράφων σας· μπορείτε να διαμορφώσετε τις ρυθμίσεις ασφαλείας για τα αρχεία PDF - απενεργοποίηση εκτύπωσης, επεξεργασίας, χρήσης ηλεκτρονικής υπογραφής κ.λπ.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε PDF χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε PDF

Η κλάση Converter προσφέρει λίγες συγκεκριμένες μετατροπές MHTML σε PDF. Για να μετατρέψετε MHTML σε PDF, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο Url ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπικό ή προσαρμοσμένο συγκεκριμένο [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) ως πηγή. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε configuration ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα PDF με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) που μετατρέπει MHTML σε PDF με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Χρήση μιας υλοποίησης του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ορίστε το προεπιλεγμένο αντικείμενο PdfSaveOptions
      var options = new PdfSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_44}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται με πλήρη διαδρομή αρχείου σε PDF. Το αποτέλεσμα είναι τα δεδομένα εξόδου που σχηματίζονται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Διαδρομή αρχείου πηγής MHTML. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει απόλυτο URL. |
| options | PdfSaveOptions | Η χρήση του αντικειμένου [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση του [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την λήψη ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε PDF συχνά απαιτείται για να αξιοποιηθεί η μορφή [PDF](https://docs.fileformat.com/pdf/) για συγκεκριμένες εργασίες. Το PDF προσφέρει πολλά οφέλη που άλλα αρχεία δεν έχουν. Για παράδειγμα, πολλά προγράμματα και εφαρμογές υποστηρίζουν έγγραφα PDF· τα αρχεία PDF είναι βελτιστοποιημένα για εκτύπωση και είναι ιδανικά για τη δημιουργία φυσικών αντιτύπων των εγγράφων σας· μπορείτε να διαμορφώσετε τις ρυθμίσεις ασφαλείας για τα αρχεία PDF - απενεργοποίηση εκτύπωσης, επεξεργασίας, χρήσης ηλεκτρονικής υπογραφής κ.λπ.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε PDF χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε PDF

Η κλάση Converter προσφέρει λίγες συγκεκριμένες μετατροπές MHTML σε PDF. Για να μετατρέψετε MHTML σε PDF, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο Url ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπικό ή προσαρμοσμένο συγκεκριμένο [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) ως πηγή. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε configuration ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα PDF με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) που μετατρέπει MHTML σε PDF με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο PdfSaveOptions
      var options = new PdfSaveOptions();

      // Χρήση μιας υλοποίησης του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertMHTML(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_12}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται από URL. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL εγγράφου πηγής MHTML - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| options | PdfSaveOptions | Η χρήση του αντικειμένου [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση του [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την λήψη ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε PDF συχνά απαιτείται για να αξιοποιηθεί η μορφή [PDF](https://docs.fileformat.com/pdf/) για συγκεκριμένες εργασίες. Το PDF προσφέρει πολλά οφέλη που άλλα αρχεία δεν έχουν. Για παράδειγμα, πολλά προγράμματα και εφαρμογές υποστηρίζουν έγγραφα PDF· τα αρχεία PDF είναι βελτιστοποιημένα για εκτύπωση και είναι ιδανικά για τη δημιουργία φυσικών αντιτύπων των εγγράφων σας· μπορείτε να διαμορφώσετε τις ρυθμίσεις ασφαλείας για τα αρχεία PDF - απενεργοποίηση εκτύπωσης, επεξεργασίας, χρήσης ηλεκτρονικής υπογραφής κ.λπ.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε PDF χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε PDF

Η κλάση Converter προσφέρει λίγες συγκεκριμένες μετατροπές MHTML σε PDF. Για να μετατρέψετε MHTML σε PDF, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο Url ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπικό ή προσαρμοσμένο συγκεκριμένο [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) ως πηγή. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε configuration ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα PDF με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) που μετατρέπει MHTML σε PDF με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργήστε Url βάσει διαδρομής αρχείου εισόδου
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο PdfSaveOptions
      var options = new PdfSaveOptions();

      // Χρήση μιας υλοποίησης του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_20}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται από ροή εισόδου. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή δεδομένων εισόδου μετατροπής MHTML. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | PdfSaveOptions | Η χρήση του αντικειμένου [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση του [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την λήψη ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε PDF συχνά απαιτείται για να αξιοποιηθεί η μορφή [PDF](https://docs.fileformat.com/pdf/) για συγκεκριμένες εργασίες. Το PDF προσφέρει πολλά οφέλη που άλλα αρχεία δεν έχουν. Για παράδειγμα, πολλά προγράμματα και εφαρμογές υποστηρίζουν έγγραφα PDF· τα αρχεία PDF είναι βελτιστοποιημένα για εκτύπωση και είναι ιδανικά για τη δημιουργία φυσικών αντιτύπων των εγγράφων σας· μπορείτε να διαμορφώσετε τις ρυθμίσεις ασφαλείας για τα αρχεία PDF - απενεργοποίηση εκτύπωσης, επεξεργασίας, χρήσης ηλεκτρονικής υπογραφής κ.λπ.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε PDF χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε PDF

Η κλάση Converter προσφέρει λίγες συγκεκριμένες μετατροπές MHTML σε PDF. Για να μετατρέψετε MHTML σε PDF, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο Url ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπικό ή προσαρμοσμένο συγκεκριμένο [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) ως πηγή. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε configuration ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα PDF με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) που μετατρέπει MHTML σε PDF με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Χρήση μιας υλοποίησης του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ορίστε το προεπιλεγμένο αντικείμενο PdfSaveOptions
      var options = new PdfSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_36}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται με πλήρη διαδρομή αρχείου σε PDF. Το αποτέλεσμα είναι τα δεδομένα εξόδου που σχηματίζονται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής MHTML. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | PdfSaveOptions | Η χρήση του αντικειμένου [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση του [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την λήψη ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε PDF συχνά απαιτείται για να αξιοποιηθεί η μορφή [PDF](https://docs.fileformat.com/pdf/) για συγκεκριμένες εργασίες. Το PDF προσφέρει πολλά οφέλη που άλλα αρχεία δεν έχουν. Για παράδειγμα, πολλά προγράμματα και εφαρμογές υποστηρίζουν έγγραφα PDF· τα αρχεία PDF είναι βελτιστοποιημένα για εκτύπωση και είναι ιδανικά για τη δημιουργία φυσικών αντιτύπων των εγγράφων σας· μπορείτε να διαμορφώσετε τις ρυθμίσεις ασφαλείας για τα αρχεία PDF - απενεργοποίηση εκτύπωσης, επεξεργασίας, χρήσης ηλεκτρονικής υπογραφής κ.λπ.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε PDF χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε PDF

Η κλάση Converter προσφέρει λίγες συγκεκριμένες μετατροπές MHTML σε PDF. Για να μετατρέψετε MHTML σε PDF, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο Url ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπικό ή προσαρμοσμένο συγκεκριμένο [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) ως πηγή. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε configuration ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα PDF με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) που μετατρέπει MHTML σε PDF με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο PdfSaveOptions
      var options = new PdfSaveOptions();

      // Χρήση μιας υλοποίησης του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_4}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται από [`URL`](../../../com.aspose.html/url/). Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL εγγράφου πηγής MHTML - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | PdfSaveOptions | Η χρήση του αντικειμένου [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση του [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την λήψη ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας MHTML

Η μετατροπή MHTML σε PDF συχνά απαιτείται για να αξιοποιηθεί η μορφή [PDF](https://docs.fileformat.com/pdf/) για συγκεκριμένες εργασίες. Το PDF προσφέρει πολλά οφέλη που άλλα αρχεία δεν έχουν. Για παράδειγμα, πολλά προγράμματα και εφαρμογές υποστηρίζουν έγγραφα PDF· τα αρχεία PDF είναι βελτιστοποιημένα για εκτύπωση και είναι ιδανικά για τη δημιουργία φυσικών αντιτύπων των εγγράφων σας· μπορείτε να διαμορφώσετε τις ρυθμίσεις ασφαλείας για τα αρχεία PDF - απενεργοποίηση εκτύπωσης, επεξεργασίας, χρήσης ηλεκτρονικής υπογραφής κ.λπ.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε PDF χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε PDF

Η κλάση Converter προσφέρει λίγες συγκεκριμένες μετατροπές MHTML σε PDF. Για να μετατρέψετε MHTML σε PDF, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο Url ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπικό ή προσαρμοσμένο συγκεκριμένο [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) ως πηγή. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε configuration ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα PDF με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) που μετατρέπει MHTML σε PDF με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργήστε Url βάσει διαδρομής αρχείου εισόδου
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο PdfSaveOptions
      var options = new PdfSaveOptions();

      // Χρήση μιας υλοποίησης του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, ImageSaveOptions, String) {#convertmhtml_27}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται μέσω ροής εισόδου σε εικόνα. Το αποτέλεσμα είναι αρχείο εικόνας που δημιουργείται από τη διαδρομή εξόδου του αρχείου.

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή δεδομένων εισόδου μετατροπής MHTML. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| outputPath | String | Πλήρης διαδρομή αρχείου εικόνας ως αποτέλεσμα της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας MHTML

Τα αρχεία με επέκταση [MHTML](https://docs.fileformat.com/web/mhtml/) αντιπροσωπεύουν μια μορφή αρχείου αρχειοθέτησης ιστοσελίδων που μπορούν να δημιουργήσουν διάφορες εφαρμογές. Η μορφή αυτή είναι γνωστή ως μορφή αρχειοθέτησης επειδή αποθηκεύει τον κώδικα HTML του ιστότοπου και τους σχετικούς πόρους σε ένα μόνο αρχείο. Αυτοί οι πόροι περιλαμβάνουν οτιδήποτε συνδέεται με τη σελίδα, όπως εικόνες, μικροεφαρμογές, κινούμενα σχέδια, αρχεία ήχου κ.λπ. Τα αρχεία MHTML μπορούν να ανοίξουν σε διάφορες εφαρμογές όπως Internet Explorer και Microsoft Word. Οι πραγματικές προδιαγραφές της μορφής περιγράφονται λεπτομερώς από το [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Ανατρέξτε στο άρθρο, όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε εικόνες σε διαφορετικές μορφές χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης Converter και πώς να εφαρμόσετε τις παραμέτρους [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε Εικόνα

Η κλάση Converter προσφέρει λίγες συγκεκριμένες μετατροπές MHTML σε εικόνες. Οι υποστηριζόμενες μορφές είναι [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) και [TIFF](https://docs.fileformat.com/image/tiff/). Για να μετατρέψετε MHTML σε εικόνα, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπικό ή προσαρμοσμένο συγκεκριμένο stream ως πηγή. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Η προεπιλεγμένη μορφή εικόνας είναι PNG. Μπορείτε επίσης να προσθέσετε configuration ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα εικόνας με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) που μετατρέπει MHTML σε αρχείο jpeg με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Ορίστε το προεπιλεγμένο αντικείμενο ImageSaveOptions
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, ImageSaveOptions, String) {#convertmhtml_43}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται μέσω πλήρους διαδρομής αρχείου. Το αποτέλεσμα είναι αρχείο εικόνας που δημιουργείται από τη διαδρομή εξόδου του αρχείου.

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής MHTML. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| outputPath | String | Πλήρης διαδρομή αρχείου εικόνας ως αποτέλεσμα της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας MHTML

Τα αρχεία με επέκταση [MHTML](https://docs.fileformat.com/web/mhtml/) αντιπροσωπεύουν μια μορφή αρχείου αρχειοθέτησης ιστοσελίδων που μπορούν να δημιουργήσουν διάφορες εφαρμογές. Η μορφή αυτή είναι γνωστή ως μορφή αρχειοθέτησης επειδή αποθηκεύει τον κώδικα HTML του ιστότοπου και τους σχετικούς πόρους σε ένα μόνο αρχείο. Αυτοί οι πόροι περιλαμβάνουν οτιδήποτε συνδέεται με τη σελίδα, όπως εικόνες, μικροεφαρμογές, κινούμενα σχέδια, αρχεία ήχου κ.λπ. Τα αρχεία MHTML μπορούν να ανοίξουν σε διάφορες εφαρμογές όπως Internet Explorer και Microsoft Word. Οι πραγματικές προδιαγραφές της μορφής περιγράφονται λεπτομερώς από το [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Ανατρέξτε στο άρθρο, όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε εικόνες σε διαφορετικές μορφές χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης Converter και πώς να εφαρμόσετε τις παραμέτρους [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε Εικόνα

Η κλάση Converter προσφέρει λίγες συγκεκριμένες μετατροπές MHTML σε εικόνες. Οι υποστηριζόμενες μορφές είναι [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) και [TIFF](https://docs.fileformat.com/image/tiff/). Για να μετατρέψετε MHTML σε εικόνα, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπικό ή προσαρμοσμένο συγκεκριμένο stream ως πηγή. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Η προεπιλεγμένη μορφή εικόνας είναι PNG. Μπορείτε επίσης να προσθέσετε configuration ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα εικόνας με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) που μετατρέπει MHTML σε αρχείο jpeg με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Ορίστε το προεπιλεγμένο αντικείμενο ImageSaveOptions
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, ImageSaveOptions, String) {#convertmhtml_11}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται μέσω URL. Το αποτέλεσμα είναι αρχείο εικόνας που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL εγγράφου πηγής MHTML - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| options | ImageSaveOptions | Η χρήση του αντικειμένου [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| outputPath | String | Πλήρης διαδρομή αρχείου εικόνας ως αποτέλεσμα της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας MHTML

Τα αρχεία με επέκταση [MHTML](https://docs.fileformat.com/web/mhtml/) αντιπροσωπεύουν μια μορφή αρχείου αρχειοθέτησης ιστοσελίδων που μπορούν να δημιουργήσουν διάφορες εφαρμογές. Η μορφή αυτή είναι γνωστή ως μορφή αρχειοθέτησης επειδή αποθηκεύει τον κώδικα HTML του ιστότοπου και τους σχετικούς πόρους σε ένα μόνο αρχείο. Αυτοί οι πόροι περιλαμβάνουν οτιδήποτε συνδέεται με τη σελίδα, όπως εικόνες, μικροεφαρμογές, κινούμενα σχέδια, αρχεία ήχου κ.λπ. Τα αρχεία MHTML μπορούν να ανοίξουν σε διάφορες εφαρμογές όπως Internet Explorer και Microsoft Word. Οι πραγματικές προδιαγραφές της μορφής περιγράφονται λεπτομερώς από το [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Ανατρέξτε στο άρθρο, όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε εικόνες σε διαφορετικές μορφές χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης Converter και πώς να εφαρμόσετε τις παραμέτρους [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε Εικόνα

Η κλάση Converter προσφέρει λίγες συγκεκριμένες μετατροπές MHTML σε εικόνες. Οι υποστηριζόμενες μορφές είναι [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) και [TIFF](https://docs.fileformat.com/image/tiff/). Για να μετατρέψετε MHTML σε εικόνα, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπικό ή προσαρμοσμένο συγκεκριμένο stream ως πηγή. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Η προεπιλεγμένη μορφή εικόνας είναι PNG. Μπορείτε επίσης να προσθέσετε configuration ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα εικόνας με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) που μετατρέπει MHTML σε αρχείο jpeg με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργήστε Url βάσει διαδρομής αρχείου εισόδου
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Ορίστε το προεπιλεγμένο αντικείμενο ImageSaveOptions
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, String) {#convertmhtml_19}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται μέσω ροής εισόδου σε εικόνα. Το αποτέλεσμα είναι αρχείο εικόνας που δημιουργείται από τη διαδρομή εξόδου του αρχείου.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή δεδομένων εισόδου μετατροπής MHTML. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| outputPath | String | Πλήρης διαδρομή αρχείου εικόνας ως αποτέλεσμα της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας MHTML

Τα αρχεία με επέκταση [MHTML](https://docs.fileformat.com/web/mhtml/) αντιπροσωπεύουν μια μορφή αρχείου αρχειοθέτησης ιστοσελίδων που μπορούν να δημιουργήσουν διάφορες εφαρμογές. Η μορφή αυτή είναι γνωστή ως μορφή αρχειοθέτησης επειδή αποθηκεύει τον κώδικα HTML του ιστότοπου και τους σχετικούς πόρους σε ένα μόνο αρχείο. Αυτοί οι πόροι περιλαμβάνουν οτιδήποτε συνδέεται με τη σελίδα, όπως εικόνες, μικροεφαρμογές, κινούμενα σχέδια, αρχεία ήχου κ.λπ. Τα αρχεία MHTML μπορούν να ανοίξουν σε διάφορες εφαρμογές όπως Internet Explorer και Microsoft Word. Οι πραγματικές προδιαγραφές της μορφής περιγράφονται λεπτομερώς από το [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Ανατρέξτε στο άρθρο, όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε εικόνες σε διαφορετικές μορφές χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης Converter και πώς να εφαρμόσετε τις παραμέτρους [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε Εικόνα

Η κλάση Converter προσφέρει λίγες συγκεκριμένες μετατροπές MHTML σε εικόνες. Οι υποστηριζόμενες μορφές είναι [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) και [TIFF](https://docs.fileformat.com/image/tiff/). Για να μετατρέψετε MHTML σε εικόνα, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπικό ή προσαρμοσμένο συγκεκριμένο stream ως πηγή. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Η προεπιλεγμένη μορφή εικόνας είναι PNG. Μπορείτε επίσης να προσθέσετε configuration ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα εικόνας με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) που μετατρέπει MHTML σε αρχείο jpeg με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Ορίστε το προεπιλεγμένο αντικείμενο ImageSaveOptions
      var options = new ImageSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, ImageSaveOptions, String) {#convertmhtml_35}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται μέσω πλήρους διαδρομής αρχείου. Το αποτέλεσμα είναι αρχείο εικόνας που δημιουργείται από τη διαδρομή εξόδου του αρχείου.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής MHTML. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| outputPath | String | Πλήρης διαδρομή αρχείου εικόνας ως αποτέλεσμα της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας MHTML

Τα αρχεία με επέκταση [MHTML](https://docs.fileformat.com/web/mhtml/) αντιπροσωπεύουν μια μορφή αρχείου αρχειοθέτησης ιστοσελίδων που μπορούν να δημιουργήσουν διάφορες εφαρμογές. Η μορφή αυτή είναι γνωστή ως μορφή αρχειοθέτησης επειδή αποθηκεύει τον κώδικα HTML του ιστότοπου και τους σχετικούς πόρους σε ένα μόνο αρχείο. Αυτοί οι πόροι περιλαμβάνουν οτιδήποτε συνδέεται με τη σελίδα, όπως εικόνες, μικροεφαρμογές, κινούμενα σχέδια, αρχεία ήχου κ.λπ. Τα αρχεία MHTML μπορούν να ανοίξουν σε διάφορες εφαρμογές όπως Internet Explorer και Microsoft Word. Οι πραγματικές προδιαγραφές της μορφής περιγράφονται λεπτομερώς από το [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Ανατρέξτε στο άρθρο, όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε εικόνες σε διαφορετικές μορφές χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης Converter και πώς να εφαρμόσετε τις παραμέτρους [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε Εικόνα

Η κλάση Converter προσφέρει λίγες συγκεκριμένες μετατροπές MHTML σε εικόνες. Οι υποστηριζόμενες μορφές είναι [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) και [TIFF](https://docs.fileformat.com/image/tiff/). Για να μετατρέψετε MHTML σε εικόνα, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπικό ή προσαρμοσμένο συγκεκριμένο stream ως πηγή. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Η προεπιλεγμένη μορφή εικόνας είναι PNG. Μπορείτε επίσης να προσθέσετε configuration ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα εικόνας με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) που μετατρέπει MHTML σε αρχείο jpeg με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Ορίστε το προεπιλεγμένο αντικείμενο ImageSaveOptions
      var options = new ImageSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, ImageSaveOptions, String) {#convertmhtml_3}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται μέσω URL. Το αποτέλεσμα είναι αρχείο εικόνας που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL εγγράφου πηγής MHTML - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| outputPath | String | Πλήρης διαδρομή αρχείου εικόνας ως αποτέλεσμα της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας MHTML

Τα αρχεία με επέκταση [MHTML](https://docs.fileformat.com/web/mhtml/) αντιπροσωπεύουν μια μορφή αρχείου αρχειοθέτησης ιστοσελίδων που μπορούν να δημιουργήσουν διάφορες εφαρμογές. Η μορφή αυτή είναι γνωστή ως μορφή αρχειοθέτησης επειδή αποθηκεύει τον κώδικα HTML του ιστότοπου και τους σχετικούς πόρους σε ένα μόνο αρχείο. Αυτοί οι πόροι περιλαμβάνουν οτιδήποτε συνδέεται με τη σελίδα, όπως εικόνες, μικροεφαρμογές, κινούμενα σχέδια, αρχεία ήχου κ.λπ. Τα αρχεία MHTML μπορούν να ανοίξουν σε διάφορες εφαρμογές όπως Internet Explorer και Microsoft Word. Οι πραγματικές προδιαγραφές της μορφής περιγράφονται λεπτομερώς από το [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Ανατρέξτε στο άρθρο, όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε εικόνες σε διαφορετικές μορφές χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης Converter και πώς να εφαρμόσετε τις παραμέτρους [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε Εικόνα

Η κλάση Converter προσφέρει λίγες συγκεκριμένες μετατροπές MHTML σε εικόνες. Οι υποστηριζόμενες μορφές είναι [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) και [TIFF](https://docs.fileformat.com/image/tiff/). Για να μετατρέψετε MHTML σε εικόνα, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπικό ή προσαρμοσμένο συγκεκριμένο stream ως πηγή. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Η προεπιλεγμένη μορφή εικόνας είναι PNG. Μπορείτε επίσης να προσθέσετε configuration ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα εικόνας με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) που μετατρέπει MHTML σε αρχείο jpeg με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργήστε Url βάσει διαδρομής αρχείου εισόδου
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Ορίστε το προεπιλεγμένο αντικείμενο ImageSaveOptions
      var options = new ImageSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_26}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται από ροή εισόδου. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή δεδομένων εισόδου μετατροπής MHTML. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| provider | ICreateStreamProvider | Υλοποίηση του [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την λήψη ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας MHTML

Τα αρχεία με επέκταση [MHTML](https://docs.fileformat.com/web/mhtml/) αντιπροσωπεύουν μια μορφή αρχείου αρχειοθέτησης ιστοσελίδων που μπορούν να δημιουργήσουν διάφορες εφαρμογές. Η μορφή αυτή είναι γνωστή ως μορφή αρχειοθέτησης επειδή αποθηκεύει τον κώδικα HTML του ιστότοπου και τους σχετικούς πόρους σε ένα μόνο αρχείο. Αυτοί οι πόροι περιλαμβάνουν οτιδήποτε συνδέεται με τη σελίδα, όπως εικόνες, μικροεφαρμογές, κινούμενα σχέδια, αρχεία ήχου κ.λπ. Τα αρχεία MHTML μπορούν να ανοίξουν σε διάφορες εφαρμογές όπως Internet Explorer και Microsoft Word. Οι πραγματικές προδιαγραφές της μορφής περιγράφονται λεπτομερώς από το [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Ανατρέξτε στο άρθρο, όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε εικόνες σε διαφορετικές μορφές χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης Converter και πώς να εφαρμόσετε τις παραμέτρους [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε Εικόνα

Η κλάση Converter προσφέρει λίγες συγκεκριμένες μετατροπές MHTML σε εικόνες. Οι υποστηριζόμενες μορφές είναι [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) και [TIFF](https://docs.fileformat.com/image/tiff/). Για να μετατρέψετε MHTML σε εικόνα, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπικό ή προσαρμοσμένο συγκεκριμένο stream ως πηγή. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Η προεπιλεγμένη μορφή εικόνας είναι PNG. Μπορείτε επίσης να προσθέσετε configuration ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα εικόνας με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) που μετατρέπει MHTML σε αρχείο jpeg με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Χρήση μιας υλοποίησης του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ορίστε το προεπιλεγμένο αντικείμενο ImageSaveOptions
      var options = new ImageSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_42}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται με πλήρη διαδρομή αρχείου σε εικόνα. Το αποτέλεσμα είναι τα δεδομένα εξόδου που σχηματίζονται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής MHTML. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| provider | ICreateStreamProvider | Γνωστή (δείτε [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ή προσαρμοσμένη υλοποίηση του interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Παρατηρήσεις

Μετατροπέας MHTML

Τα αρχεία με επέκταση [MHTML](https://docs.fileformat.com/web/mhtml/) αντιπροσωπεύουν μια μορφή αρχείου αρχειοθέτησης ιστοσελίδων που μπορούν να δημιουργήσουν διάφορες εφαρμογές. Η μορφή αυτή είναι γνωστή ως μορφή αρχειοθέτησης επειδή αποθηκεύει τον κώδικα HTML του ιστότοπου και τους σχετικούς πόρους σε ένα μόνο αρχείο. Αυτοί οι πόροι περιλαμβάνουν οτιδήποτε συνδέεται με τη σελίδα, όπως εικόνες, μικροεφαρμογές, κινούμενα σχέδια, αρχεία ήχου κ.λπ. Τα αρχεία MHTML μπορούν να ανοίξουν σε διάφορες εφαρμογές όπως Internet Explorer και Microsoft Word. Οι πραγματικές προδιαγραφές της μορφής περιγράφονται λεπτομερώς από το [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Ανατρέξτε στο άρθρο, όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε εικόνες σε διαφορετικές μορφές χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης Converter και πώς να εφαρμόσετε τις παραμέτρους [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε Εικόνα

Η κλάση Converter προσφέρει λίγες συγκεκριμένες μετατροπές MHTML σε εικόνες. Οι υποστηριζόμενες μορφές είναι [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) και [TIFF](https://docs.fileformat.com/image/tiff/). Για να μετατρέψετε MHTML σε εικόνα, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπικό ή προσαρμοσμένο συγκεκριμένο stream ως πηγή. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Η προεπιλεγμένη μορφή εικόνας είναι PNG. Μπορείτε επίσης να προσθέσετε configuration ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα εικόνας με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) που μετατρέπει MHTML σε αρχείο jpeg με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο ImageSaveOptions
      var options = new ImageSaveOptions();

      // Χρήση μιας υλοποίησης του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertMHTML(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_10}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται από URL. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL εγγράφου πηγής MHTML - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| options | ImageSaveOptions | Η χρήση του αντικειμένου [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| provider | ICreateStreamProvider | Γνωστή (δείτε [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ή προσαρμοσμένη υλοποίηση του interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Παρατηρήσεις

Μετατροπέας MHTML

Τα αρχεία με επέκταση [MHTML](https://docs.fileformat.com/web/mhtml/) αντιπροσωπεύουν μια μορφή αρχείου αρχειοθέτησης ιστοσελίδων που μπορούν να δημιουργήσουν διάφορες εφαρμογές. Η μορφή αυτή είναι γνωστή ως μορφή αρχειοθέτησης επειδή αποθηκεύει τον κώδικα HTML του ιστότοπου και τους σχετικούς πόρους σε ένα μόνο αρχείο. Αυτοί οι πόροι περιλαμβάνουν οτιδήποτε συνδέεται με τη σελίδα, όπως εικόνες, μικροεφαρμογές, κινούμενα σχέδια, αρχεία ήχου κ.λπ. Τα αρχεία MHTML μπορούν να ανοίξουν σε διάφορες εφαρμογές όπως Internet Explorer και Microsoft Word. Οι πραγματικές προδιαγραφές της μορφής περιγράφονται λεπτομερώς από το [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Ανατρέξτε στο άρθρο, όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε εικόνες σε διαφορετικές μορφές χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης Converter και πώς να εφαρμόσετε τις παραμέτρους [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε Εικόνα

Η κλάση Converter προσφέρει λίγες συγκεκριμένες μετατροπές MHTML σε εικόνες. Οι υποστηριζόμενες μορφές είναι [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) και [TIFF](https://docs.fileformat.com/image/tiff/). Για να μετατρέψετε MHTML σε εικόνα, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπικό ή προσαρμοσμένο συγκεκριμένο stream ως πηγή. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Η προεπιλεγμένη μορφή εικόνας είναι PNG. Μπορείτε επίσης να προσθέσετε configuration ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα εικόνας με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) που μετατρέπει MHTML σε αρχείο jpeg με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργήστε Url βάσει διαδρομής αρχείου εισόδου
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο ImageSaveOptions
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // Χρήση μιας υλοποίησης του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_18}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται από ροή εισόδου. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή δεδομένων εισόδου μετατροπής MHTML. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| provider | ICreateStreamProvider | Υλοποίηση του [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την λήψη ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας MHTML

Τα αρχεία με επέκταση [MHTML](https://docs.fileformat.com/web/mhtml/) αντιπροσωπεύουν μια μορφή αρχείου αρχειοθέτησης ιστοσελίδων που μπορούν να δημιουργήσουν διάφορες εφαρμογές. Η μορφή αυτή είναι γνωστή ως μορφή αρχειοθέτησης επειδή αποθηκεύει τον κώδικα HTML του ιστότοπου και τους σχετικούς πόρους σε ένα μόνο αρχείο. Αυτοί οι πόροι περιλαμβάνουν οτιδήποτε συνδέεται με τη σελίδα, όπως εικόνες, μικροεφαρμογές, κινούμενα σχέδια, αρχεία ήχου κ.λπ. Τα αρχεία MHTML μπορούν να ανοίξουν σε διάφορες εφαρμογές όπως Internet Explorer και Microsoft Word. Οι πραγματικές προδιαγραφές της μορφής περιγράφονται λεπτομερώς από το [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Ανατρέξτε στο άρθρο, όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε εικόνες σε διαφορετικές μορφές χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης Converter και πώς να εφαρμόσετε τις παραμέτρους [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε Εικόνα

Η κλάση Converter προσφέρει λίγες συγκεκριμένες μετατροπές MHTML σε εικόνες. Οι υποστηριζόμενες μορφές είναι [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) και [TIFF](https://docs.fileformat.com/image/tiff/). Για να μετατρέψετε MHTML σε εικόνα, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπικό ή προσαρμοσμένο συγκεκριμένο stream ως πηγή. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Η προεπιλεγμένη μορφή εικόνας είναι PNG. Μπορείτε επίσης να προσθέσετε configuration ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα εικόνας με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) που μετατρέπει MHTML σε αρχείο jpeg με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Χρήση μιας υλοποίησης του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ορίστε το προεπιλεγμένο αντικείμενο ImageSaveOptions
      var options = new ImageSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_34}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται με πλήρη διαδρομή αρχείου σε εικόνα. Το αποτέλεσμα είναι τα δεδομένα εξόδου που σχηματίζονται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής MHTML. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| provider | ICreateStreamProvider | Υλοποίηση της [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την απόκτηση ενός ρεύματος εξόδου. |

## Παρατηρήσεις

Μετατροπέας MHTML

Τα αρχεία με επέκταση [MHTML](https://docs.fileformat.com/web/mhtml/) αντιπροσωπεύουν μια μορφή αρχείου αρχειοθέτησης ιστοσελίδων που μπορούν να δημιουργήσουν διάφορες εφαρμογές. Η μορφή αυτή είναι γνωστή ως μορφή αρχειοθέτησης επειδή αποθηκεύει τον κώδικα HTML του ιστότοπου και τους σχετικούς πόρους σε ένα μόνο αρχείο. Αυτοί οι πόροι περιλαμβάνουν οτιδήποτε συνδέεται με τη σελίδα, όπως εικόνες, μικροεφαρμογές, κινούμενα σχέδια, αρχεία ήχου κ.λπ. Τα αρχεία MHTML μπορούν να ανοίξουν σε διάφορες εφαρμογές όπως Internet Explorer και Microsoft Word. Οι πραγματικές προδιαγραφές της μορφής περιγράφονται λεπτομερώς από το [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Ανατρέξτε στο άρθρο, όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε εικόνες σε διαφορετικές μορφές χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης Converter και πώς να εφαρμόσετε τις παραμέτρους [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε Εικόνα

Η κλάση Converter προσφέρει λίγες συγκεκριμένες μετατροπές MHTML σε εικόνες. Οι υποστηριζόμενες μορφές είναι [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) και [TIFF](https://docs.fileformat.com/image/tiff/). Για να μετατρέψετε MHTML σε εικόνα, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπικό ή προσαρμοσμένο συγκεκριμένο stream ως πηγή. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Η προεπιλεγμένη μορφή εικόνας είναι PNG. Μπορείτε επίσης να προσθέσετε configuration ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα εικόνας με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) που μετατρέπει MHTML σε αρχείο jpeg με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο ImageSaveOptions
      var options = new ImageSaveOptions();

      // Χρήση μιας υλοποίησης του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_2}

Μετατρέψτε την πηγή MHTML που παρουσιάζεται από URL. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL εγγράφου πηγής MHTML - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| provider | ICreateStreamProvider | Υλοποίηση του [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την λήψη ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας MHTML

Τα αρχεία με επέκταση [MHTML](https://docs.fileformat.com/web/mhtml/) αντιπροσωπεύουν μια μορφή αρχείου αρχειοθέτησης ιστοσελίδων που μπορούν να δημιουργήσουν διάφορες εφαρμογές. Η μορφή αυτή είναι γνωστή ως μορφή αρχειοθέτησης επειδή αποθηκεύει τον κώδικα HTML του ιστότοπου και τους σχετικούς πόρους σε ένα μόνο αρχείο. Αυτοί οι πόροι περιλαμβάνουν οτιδήποτε συνδέεται με τη σελίδα, όπως εικόνες, μικροεφαρμογές, κινούμενα σχέδια, αρχεία ήχου κ.λπ. Τα αρχεία MHTML μπορούν να ανοίξουν σε διάφορες εφαρμογές όπως Internet Explorer και Microsoft Word. Οι πραγματικές προδιαγραφές της μορφής περιγράφονται λεπτομερώς από το [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Ανατρέξτε στο άρθρο, όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε MHTML σε εικόνες σε διαφορετικές μορφές χρησιμοποιώντας τις μεθόδους ConvertMHTML() της κλάσης Converter και πώς να εφαρμόσετε τις παραμέτρους [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή MHTML σε Εικόνα

Η κλάση Converter προσφέρει λίγες συγκεκριμένες μετατροπές MHTML σε εικόνες. Οι υποστηριζόμενες μορφές είναι [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) και [TIFF](https://docs.fileformat.com/image/tiff/). Για να μετατρέψετε MHTML σε εικόνα, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Ανιχνεύστε ένα υπάρχον τοπικό αρχείο MHTML (.mht) ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να χρησιμοποιήσετε τυπικό ή προσαρμοσμένο συγκεκριμένο stream ως πηγή. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Η προεπιλεγμένη μορφή εικόνας είναι PNG. Μπορείτε επίσης να προσθέσετε configuration ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertMHTML() της κλάσης Converter για να αποθηκεύσετε το MHTML ως αποτέλεσμα εικόνας με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο του χρήστη. Online μετατροπέας MHTML

Η Aspose.HTML προσφέρει έναν δωρεάν online [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) που μετατρέπει MHTML σε αρχείο jpeg με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργήστε Url βάσει διαδρομής αρχείου εισόδου
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο ImageSaveOptions
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // Χρήση μιας υλοποίησης του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
