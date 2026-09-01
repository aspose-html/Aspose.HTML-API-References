---
title: "Converter.ConvertMarkdown"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Converter. Μετατρέπει την πηγή MD markdown που παρουσιάζεται μέσω ροής εισόδου σε html. Το αποτέλεσμα είναι HTMLDocument το οποίο μπορεί να αποθηκευτεί μέσω της διαδρομής αρχείου εξόδου."
type: docs

url: /el/java/com.aspose.html.converters/converter/convertmarkdown/
---
## ConvertMarkdown(Stream, String) {#convertmarkdown}

Μετατρέπει την πηγή MD (markdown) που παρουσιάζεται μέσω ροής εισόδου σε html. Το αποτέλεσμα είναι [`HTMLDocument`](../../../com.aspose.html/htmldocument/) το οποίο μπορεί να αποθηκευτεί μέσω της διαδρομής αρχείου εξόδου.

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή δεδομένων εισόδου για μετατροπή MD (Markdown). |
| baseUri | String | Το βασικό URI του εγγράφου. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργηθεί ένα απόλυτο URL. |

### Τιμή Επιστροφής

Νέο δημιουργημένο [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ως αποτέλεσμα μετατροπής που μπορεί να αποθηκευτεί μέσω της διαδρομής αρχείου εξόδου.

## Παρατηρήσεις

Μετατροπέας Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Βήματα μετατροπής

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο MD ή δημιουργήστε ροή δεδομένων εισόδου ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Μπορείτε να λάβετε απευθείας το [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ή να ορίσετε τη διαδρομή αρχείου εξόδου του αποτελέσματος ανάλογα με την υπογραφή της μεθόδου. Χρησιμοποιήστε τη μέθοδο ConvertMarkdown() της κλάσης Converter για να αποθηκεύσετε το MD ως αποτέλεσμα html. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως προαιρετική παράμετρο. Online μετατροπέας MD

Μπορεί επίσης να σας ενδιαφέρει ένας δωρεάν online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) που μετατρέπει MD σε HTML με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα! Επίσης μπορείτε να ελέγξετε άλλους online μετατροπείς MD: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) και βρείτε κατάλληλους [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.html");
       
      // Άνοιγμα αρχείου πηγής ως ροή
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Ξεκινήστε τη διαδικασία μετατροπής
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty);
         
        // Αποθήκευση αποτελέσματος μετατροπής
        document.Save(resultPath);
      }





*InputFolder - user source folder path.



```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration) {#convertmarkdown_1}

Μετατρέπει την πηγή MD (markdown) που παρουσιάζεται μέσω ροής εισόδου σε html. Το αποτέλεσμα είναι [`HTMLDocument`](../../../com.aspose.html/htmldocument/) το οποίο μπορεί να αποθηκευτεί μέσω της διαδρομής αρχείου εξόδου.

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri, 
    Configuration configuration)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή δεδομένων εισόδου για μετατροπή MD (Markdown). |
| baseUri | String | Το βασικό URI του εγγράφου. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργηθεί ένα απόλυτο URL. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |

### Τιμή Επιστροφής

Νέο δημιουργημένο [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ως αποτέλεσμα μετατροπής που μπορεί να αποθηκευτεί μέσω της διαδρομής αρχείου εξόδου.

## Παρατηρήσεις

Μετατροπέας Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Βήματα μετατροπής

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο MD ή δημιουργήστε ροή δεδομένων εισόδου ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Μπορείτε να λάβετε απευθείας το [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ή να ορίσετε τη διαδρομή αρχείου εξόδου του αποτελέσματος ανάλογα με την υπογραφή της μεθόδου. Χρησιμοποιήστε τη μέθοδο ConvertMarkdown() της κλάσης Converter για να αποθηκεύσετε το MD ως αποτέλεσμα html. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως προαιρετική παράμετρο. Online μετατροπέας MD

Μπορεί επίσης να σας ενδιαφέρει ένας δωρεάν online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) που μετατρέπει MD σε HTML με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα! Επίσης μπορείτε να ελέγξετε άλλους online μετατροπείς MD: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) και βρείτε κατάλληλους [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Άνοιγμα αρχείου πηγής ως ροή
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration());

        // Αποθήκευση αποτελέσματος μετατροπής
        document.Save(resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, String) {#convertmarkdown_5}

Μετατρέψτε την πηγή MD (markdown) που παρουσιάζεται μέσω ροής εισόδου σε html. Το αποτέλεσμα είναι αρχείο html που δημιουργείται από τη διαδρομή εξόδου του αρχείου.

```java
public static void ConvertMarkdown(Stream stream, String baseUri, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή δεδομένων εισόδου για μετατροπή MD (Markdown). |
| baseUri | String | Το βασικό URI του εγγράφου. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργηθεί ένα απόλυτο URL. |
| outputPath | String | Πλήρης διαδρομή αρχείου html ως αποτέλεσμα εξόδου μετατροπής. |

## Παρατηρήσεις

Μετατροπέας Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Βήματα μετατροπής

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο MD ή δημιουργήστε ροή δεδομένων εισόδου ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Μπορείτε να λάβετε απευθείας το [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ή να ορίσετε τη διαδρομή αρχείου εξόδου του αποτελέσματος ανάλογα με την υπογραφή της μεθόδου. Χρησιμοποιήστε τη μέθοδο ConvertMarkdown() της κλάσης Converter για να αποθηκεύσετε το MD ως αποτέλεσμα html. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως προαιρετική παράμετρο. Online μετατροπέας MD

Μπορεί επίσης να σας ενδιαφέρει ένας δωρεάν online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) που μετατρέπει MD σε HTML με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα! Επίσης μπορείτε να ελέγξετε άλλους online μετατροπείς MD: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) και βρείτε κατάλληλους [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Άνοιγμα αρχείου πηγής ως ροή
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Ξεκινήστε τη διαδικασία μετατροπής
        Converter.ConvertMarkdown(sourceStream, String.Empty, resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration, String) {#convertmarkdown_4}

Μετατρέψτε την πηγή MD (markdown) που παρουσιάζεται μέσω ροής εισόδου σε html. Το αποτέλεσμα είναι αρχείο html που δημιουργείται από τη διαδρομή εξόδου του αρχείου.

```java
public static void ConvertMarkdown(Stream stream, String baseUri, Configuration configuration, 
    String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή δεδομένων εισόδου για μετατροπή MD (Markdown). |
| baseUri | String | Το βασικό URI του εγγράφου. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργηθεί ένα απόλυτο URL. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| outputPath | String | Πλήρης διαδρομή αρχείου html ως αποτέλεσμα εξόδου μετατροπής. |

## Παρατηρήσεις

Μετατροπέας Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Βήματα μετατροπής

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο MD ή δημιουργήστε ροή δεδομένων εισόδου ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Μπορείτε να λάβετε απευθείας το [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ή να ορίσετε τη διαδρομή αρχείου εξόδου του αποτελέσματος ανάλογα με την υπογραφή της μεθόδου. Χρησιμοποιήστε τη μέθοδο ConvertMarkdown() της κλάσης Converter για να αποθηκεύσετε το MD ως αποτέλεσμα html. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως προαιρετική παράμετρο. Online μετατροπέας MD

Μπορεί επίσης να σας ενδιαφέρει ένας δωρεάν online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) που μετατρέπει MD σε HTML με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα! Επίσης μπορείτε να ελέγξετε άλλους online μετατροπείς MD: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) και βρείτε κατάλληλους [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Άνοιγμα αρχείου πηγής ως ροή
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
        Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration(), resultPath);
      }
```

*InputFolder - user source folder path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String) {#convertmarkdown_2}

Μετατρέπει την πηγή MD (markdown) που παρουσιάζεται μέσω πλήρους διαδρομής αρχείου σε html. Το αποτέλεσμα είναι [`HTMLDocument`](../../../com.aspose.html/htmldocument/) το οποίο μπορεί να αποθηκευτεί μέσω της διαδρομής αρχείου εξόδου.

```java
public static HTMLDocument ConvertMarkdown(String sourcePath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής MD (Markdown). |

### Τιμή Επιστροφής

Νέο δημιουργημένο [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ως αποτέλεσμα μετατροπής που μπορεί να αποθηκευτεί μέσω της διαδρομής αρχείου εξόδου.

## Παρατηρήσεις

Μετατροπέας Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Βήματα μετατροπής

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο MD ή δημιουργήστε ροή δεδομένων εισόδου ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Μπορείτε να λάβετε απευθείας το [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ή να ορίσετε τη διαδρομή αρχείου εξόδου του αποτελέσματος ανάλογα με την υπογραφή της μεθόδου. Χρησιμοποιήστε τη μέθοδο ConvertMarkdown() της κλάσης Converter για να αποθηκεύσετε το MD ως αποτέλεσμα html. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως προαιρετική παράμετρο. Online μετατροπέας MD

Μπορεί επίσης να σας ενδιαφέρει ένας δωρεάν online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) που μετατρέπει MD σε HTML με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα! Επίσης μπορείτε να ελέγξετε άλλους online μετατροπείς MD: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) και βρείτε κατάλληλους [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Ξεκινήστε τη διαδικασία μετατροπής
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath))
      {
        // Αποθήκευση αποτελέσματος μετατροπής ως τοπικό αρχείο
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration) {#convertmarkdown_3}

Μετατρέπει την πηγή MD (markdown) που παρουσιάζεται μέσω πλήρους διαδρομής αρχείου σε html. Το αποτέλεσμα είναι [`HTMLDocument`](../../../com.aspose.html/htmldocument/) το οποίο μπορεί να αποθηκευτεί μέσω της διαδρομής αρχείου εξόδου.

```java
public static HTMLDocument ConvertMarkdown(String sourcePath, Configuration configuration)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής MD (Markdown). |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |

### Τιμή Επιστροφής

Νέο δημιουργημένο [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ως αποτέλεσμα μετατροπής που μπορεί να αποθηκευτεί μέσω της διαδρομής αρχείου εξόδου.

## Παρατηρήσεις

Μετατροπέας Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Βήματα μετατροπής

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο MD ή δημιουργήστε ροή δεδομένων εισόδου ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Μπορείτε να λάβετε απευθείας το [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ή να ορίσετε τη διαδρομή αρχείου εξόδου του αποτελέσματος ανάλογα με την υπογραφή της μεθόδου. Χρησιμοποιήστε τη μέθοδο ConvertMarkdown() της κλάσης Converter για να αποθηκεύσετε το MD ως αποτέλεσμα html. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως προαιρετική παράμετρο. Online μετατροπέας MD

Μπορεί επίσης να σας ενδιαφέρει ένας δωρεάν online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) που μετατρέπει MD σε HTML με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα! Επίσης μπορείτε να ελέγξετε άλλους online μετατροπείς MD: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) και βρείτε κατάλληλους [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath, new Configuration()))
      {
        // Αποθήκευση αποτελέσματος μετατροπής ως τοπικό αρχείο
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, String) {#convertmarkdown_7}

Μετατρέψτε την πηγή MD (markdown) που παρουσιάζεται μέσω πλήρους διαδρομής αρχείου σε html. Το αποτέλεσμα είναι αρχείο html που δημιουργείται από τη διαδρομή εξόδου του αρχείου.

```java
public static void ConvertMarkdown(String sourcePath, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Διαδρομή προς το αρχείο πηγής Markdown. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει απόλυτο URL. |
| outputPath | String | Πλήρης διαδρομή αρχείου html ως αποτέλεσμα εξόδου μετατροπής. |

## Παρατηρήσεις

Μετατροπέας Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Βήματα μετατροπής

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο MD ή δημιουργήστε ροή δεδομένων εισόδου ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Μπορείτε να λάβετε απευθείας το [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ή να ορίσετε τη διαδρομή αρχείου εξόδου του αποτελέσματος ανάλογα με την υπογραφή της μεθόδου. Χρησιμοποιήστε τη μέθοδο ConvertMarkdown() της κλάσης Converter για να αποθηκεύσετε το MD ως αποτέλεσμα html. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως προαιρετική παράμετρο. Online μετατροπέας MD

Μπορεί επίσης να σας ενδιαφέρει ένας δωρεάν online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) που μετατρέπει MD σε HTML με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα! Επίσης μπορείτε να ελέγξετε άλλους online μετατροπείς MD: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) και βρείτε κατάλληλους [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertMarkdown(sourcePath, resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration, String) {#convertmarkdown_6}

Μετατρέψτε την πηγή MD (markdown) που παρουσιάζεται μέσω πλήρους διαδρομής αρχείου σε html. Το αποτέλεσμα είναι αρχείο html που δημιουργείται από τη διαδρομή εξόδου του αρχείου.

```java
public static void ConvertMarkdown(String sourcePath, Configuration configuration, 
    String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Διαδρομή προς το αρχείο πηγής Markdown. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει απόλυτο URL. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| outputPath | String | Πλήρης διαδρομή αρχείου html ως αποτέλεσμα εξόδου μετατροπής. |

## Παρατηρήσεις

Μετατροπέας Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Βήματα μετατροπής

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο MD ή δημιουργήστε ροή δεδομένων εισόδου ως πηγή μετατροπής. Αποτέλεσμα μετατροπής. Μπορείτε να λάβετε απευθείας το [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ή να ορίσετε τη διαδρομή αρχείου εξόδου του αποτελέσματος ανάλογα με την υπογραφή της μεθόδου. Χρησιμοποιήστε τη μέθοδο ConvertMarkdown() της κλάσης Converter για να αποθηκεύσετε το MD ως αποτέλεσμα html. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως προαιρετική παράμετρο. Online μετατροπέας MD

Μπορεί επίσης να σας ενδιαφέρει ένας δωρεάν online [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) που μετατρέπει MD σε HTML με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα! Επίσης μπορείτε να ελέγξετε άλλους online μετατροπείς MD: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) και βρείτε κατάλληλους [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
      Converter.ConvertMarkdown(sourcePath, new Configuration(), resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
