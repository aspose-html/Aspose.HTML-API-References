---
title: "Converter.ConvertTemplate"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Converter. Συγχωνεύστε την πηγή προτύπου που παρουσιάζεται από HTMLDocument με τα δεδομένα προτύπου XML JSON. Το αποτέλεσμα είναι αρχείο html που δημιουργείται από τη διαδρομή εξόδου αρχείου."
type: docs

url: /el/java/com.aspose.html.converters/converter/converttemplate/
---
## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions, String) {#converttemplate_7}

Συγχωνεύστε την πηγή προτύπου που παρουσιάζεται από [`HTMLDocument`](../../../com.aspose.html/htmldocument/) με τα δεδομένα προτύπου (XML, JSON). Το αποτέλεσμα είναι αρχείο html που δημιουργείται από τη διαδρομή εξόδου αρχείου.

```java
public static void ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| template | HTMLDocument | Συγχώνευση σκελετού πηγής που παρουσιάζεται από [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| δεδομένα | TemplateData | Δεδομένα προτύπου για συγχώνευση - αντικατάσταση (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) αντικείμενο. Χρησιμοποιείται για να καθορίσει εάν τα ονόματα του προτύπου και του στοιχείου δεδομένων ταιριάζουν, ανεξάρτητα από πεζά ή κεφαλαία (επιλογές). |
| outputPath | String | Πλήρης διαδρομή αρχείου html ως αποτέλεσμα εξόδου μετατροπής. |

## Παρατηρήσεις

Συγχωνευτής Προτύπου

Η ιδέα του συγχωνεύματος προτύπων είναι να δημιουργηθεί ένα έγγραφο HTML βασισμένο σε ένα πρότυπο html και να γεμίσει από μια πηγή δεδομένων. Aspose.HTML παρέχει τη σύνταξη ενσωματωμένων εκφράσεων για εργασία με πρότυπα και διάφορους τύπους πηγών δεδομένων, όπως XML και JSON. Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) όπου μπορείτε να βρείτε περισσότερες πληροφορίες σχετικά με το συγχώνευμα προτύπων και τη χρήση της μεθόδου ConvertTemplate().

Βήματα μετατροπής (συγχώνευσης)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Πηγή προτύπου. Ορίστε την πηγή του προτύπου HTML μέσω αρχείου, [`URL`](../../../com.aspose.html/url/), αντικειμένου [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ή ακόμη και μέσω ενσωματωμένου περιεχομένου. Αποτέλεσμα μετατροπής. Μπορείτε να λάβετε απευθείας το προκύπτον HTMLDocument ή να ορίσετε τη διαδρομή εξόδου του αρχείου αποτελέσματος ανάλογα με την υπογραφή της μεθόδου. Δημιουργήστε ένα στιγμιότυπο του [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Χρησιμοποιήστε τη μέθοδο ConvertTemplate() της κλάσης Converter για να συγχωνεύσετε το πρότυπο με τα δεδομένα. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Κώδικας πηγής

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής σκελετού html φόρμας
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Διαδρομή αρχείου δεδομένων προτύπου xml (json) φόρμας
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");
      
      // Ορίστε ένα στιγμιότυπο αντικειμένου TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Ορίστε το προεπιλεγμένο αντικείμενο TemplateLoadOptions
      var options = new TemplateLoadOptions();

      // Έγγραφο HTML φόρμας ως πηγή μετατροπής
      var document = new HTMLDocument(sourcePath, new Configuration());

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertTemplate(document, templateData, options, resultPath);

      // Καθαρισμός πόρων
      document.Dispose();





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions, String) {#converttemplate_9}

Συγχωνεύστε την πηγή HTML του προτύπου που παρουσιάζεται από [`URL`](../../../com.aspose.html/url/) με τα δεδομένα προτύπου (XML, JSON). Το αποτέλεσμα είναι αρχείο html που δημιουργείται με τη διαδρομή εξόδου.

```java
public static void ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options, 
    String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| url | Url | Συγχώνευση σκελετού πηγής HTML που παρουσιάζεται από [`URL`](../../../com.aspose.html/url/). |
| δεδομένα | TemplateData | Δεδομένα προτύπου για συγχώνευση - αντικατάσταση (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) αντικείμενο. Χρησιμοποιείται για να καθορίσει εάν τα ονόματα του προτύπου και του στοιχείου δεδομένων ταιριάζουν, ανεξάρτητα από πεζά ή κεφαλαία (επιλογές). |
| outputPath | String | Πλήρης διαδρομή αρχείου html ως αποτέλεσμα εξόδου μετατροπής. |

## Παρατηρήσεις

Συγχωνευτής Προτύπου

Η ιδέα του συγχωνεύματος προτύπων είναι να δημιουργηθεί ένα έγγραφο HTML βασισμένο σε ένα πρότυπο html και να γεμίσει από μια πηγή δεδομένων. Aspose.HTML παρέχει τη σύνταξη ενσωματωμένων εκφράσεων για εργασία με πρότυπα και διάφορους τύπους πηγών δεδομένων, όπως XML και JSON. Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) όπου μπορείτε να βρείτε περισσότερες πληροφορίες σχετικά με το συγχώνευμα προτύπων και τη χρήση της μεθόδου ConvertTemplate().

Βήματα μετατροπής (συγχώνευσης)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Πηγή προτύπου. Ορίστε την πηγή του προτύπου HTML μέσω αρχείου, [`URL`](../../../com.aspose.html/url/), αντικειμένου [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ή ακόμη και μέσω ενσωματωμένου περιεχομένου. Αποτέλεσμα μετατροπής. Μπορείτε να λάβετε απευθείας το προκύπτον HTMLDocument ή να ορίσετε τη διαδρομή εξόδου του αρχείου αποτελέσματος ανάλογα με την υπογραφή της μεθόδου. Δημιουργήστε ένα στιγμιότυπο του [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Χρησιμοποιήστε τη μέθοδο ConvertTemplate() της κλάσης Converter για να συγχωνεύσετε το πρότυπο με τα δεδομένα. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Κώδικας πηγής

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διεύθυνση URL πηγής σκελετού html φόρμας
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Διαδρομή αρχείου δεδομένων προτύπου xml (json) φόρμας
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Ορίστε ένα στιγμιότυπο αντικειμένου TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Ορίστε το προεπιλεγμένο αντικείμενο TemplateLoadOptions
      var options = new TemplateLoadOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertTemplate(sourceUrl, templateData, options, resultPath);





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_8}

Συγχωνεύστε την πηγή HTML του προτύπου που παρουσιάζεται από [`URL`](../../../com.aspose.html/url/) με τα δεδομένα προτύπου (XML, JSON). Το αποτέλεσμα είναι αρχείο html που δημιουργείται με τη διαδρομή εξόδου.

```java
public static void ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| url | Url | Συγχώνευση σκελετού πηγής HTML που παρουσιάζεται από [`URL`](../../../com.aspose.html/url/). |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| δεδομένα | TemplateData | Δεδομένα προτύπου για συγχώνευση - αντικατάσταση (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) αντικείμενο. Χρησιμοποιείται για να καθορίσει εάν τα ονόματα του προτύπου και του στοιχείου δεδομένων ταιριάζουν, ανεξάρτητα από πεζά ή κεφαλαία (επιλογές). |
| outputPath | String | Πλήρης διαδρομή αρχείου html ως αποτέλεσμα εξόδου μετατροπής. |

## Παρατηρήσεις

Συγχωνευτής Προτύπου

Η ιδέα του συγχωνεύματος προτύπων είναι να δημιουργηθεί ένα έγγραφο HTML βασισμένο σε ένα πρότυπο html και να γεμίσει από μια πηγή δεδομένων. Aspose.HTML παρέχει τη σύνταξη ενσωματωμένων εκφράσεων για εργασία με πρότυπα και διάφορους τύπους πηγών δεδομένων, όπως XML και JSON. Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) όπου μπορείτε να βρείτε περισσότερες πληροφορίες σχετικά με το συγχώνευμα προτύπων και τη χρήση της μεθόδου ConvertTemplate().

Βήματα μετατροπής (συγχώνευσης)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Πηγή προτύπου. Ορίστε την πηγή του προτύπου HTML μέσω αρχείου, [`URL`](../../../com.aspose.html/url/), αντικειμένου [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ή ακόμη και μέσω ενσωματωμένου περιεχομένου. Αποτέλεσμα μετατροπής. Μπορείτε να λάβετε απευθείας το προκύπτον HTMLDocument ή να ορίσετε τη διαδρομή εξόδου του αρχείου αποτελέσματος ανάλογα με την υπογραφή της μεθόδου. Δημιουργήστε ένα στιγμιότυπο του [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Χρησιμοποιήστε τη μέθοδο ConvertTemplate() της κλάσης Converter για να συγχωνεύσετε το πρότυπο με τα δεδομένα. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Κώδικας πηγής

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διεύθυνση URL πηγής σκελετού html φόρμας
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Διαδρομή αρχείου δεδομένων προτύπου xml (json) φόρμας
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Ορίστε ένα στιγμιότυπο αντικειμένου TemplateData 
      var templateData = new TemplateData(templateDataPath);

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Ορίστε το προεπιλεγμένο αντικείμενο TemplateLoadOptions
      var options = new TemplateLoadOptions();

      // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
      Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, TemplateData, TemplateLoadOptions, String) {#converttemplate_11}

Συγχωνεύστε την πηγή HTML προτύπου που παρουσιάζεται από πλήρη διαδρομή αρχείου με τα δεδομένα προτύπου (XML, JSON). Το αποτέλεσμα είναι αρχείο html που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Συγχώνευση σκελετού πηγής HTML που παρουσιάζεται με πλήρη διαδρομή αρχείου. |
| δεδομένα | TemplateData | Δεδομένα προτύπου για συγχώνευση - αντικατάσταση (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) αντικείμενο. Χρησιμοποιείται για να καθορίσει εάν τα ονόματα του προτύπου και του στοιχείου δεδομένων ταιριάζουν, ανεξάρτητα από πεζά ή κεφαλαία (επιλογές). |
| outputPath | String | Πλήρης διαδρομή αρχείου html ως αποτέλεσμα εξόδου μετατροπής. |

## Παρατηρήσεις

Συγχωνευτής Προτύπου

Η ιδέα του συγχωνεύματος προτύπων είναι να δημιουργηθεί ένα έγγραφο HTML βασισμένο σε ένα πρότυπο html και να γεμίσει από μια πηγή δεδομένων. Aspose.HTML παρέχει τη σύνταξη ενσωματωμένων εκφράσεων για εργασία με πρότυπα και διάφορους τύπους πηγών δεδομένων, όπως XML και JSON. Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) όπου μπορείτε να βρείτε περισσότερες πληροφορίες σχετικά με το συγχώνευμα προτύπων και τη χρήση της μεθόδου ConvertTemplate().

Βήματα μετατροπής (συγχώνευσης)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Πηγή προτύπου. Ορίστε την πηγή του προτύπου HTML μέσω αρχείου, [`URL`](../../../com.aspose.html/url/), αντικειμένου [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ή ακόμη και μέσω ενσωματωμένου περιεχομένου. Αποτέλεσμα μετατροπής. Μπορείτε να λάβετε απευθείας το προκύπτον HTMLDocument ή να ορίσετε τη διαδρομή εξόδου του αρχείου αποτελέσματος ανάλογα με την υπογραφή της μεθόδου. Δημιουργήστε ένα στιγμιότυπο του [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Χρησιμοποιήστε τη μέθοδο ConvertTemplate() της κλάσης Converter για να συγχωνεύσετε το πρότυπο με τα δεδομένα. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Κώδικας πηγής

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής σκελετού html φόρμας
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Διαδρομή αρχείου δεδομένων προτύπου xml (json) φόρμας
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Ορίστε ένα στιγμιότυπο αντικειμένου TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Ορίστε το προεπιλεγμένο αντικείμενο TemplateLoadOptions
      var options = new TemplateLoadOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertTemplate(sourcePath, templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_10}

Συγχωνεύστε την πηγή HTML προτύπου που παρουσιάζεται από πλήρη διαδρομή αρχείου με τα δεδομένα προτύπου (XML, JSON). Το αποτέλεσμα είναι αρχείο html που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Συγχώνευση σκελετού πηγής HTML που παρουσιάζεται με πλήρη διαδρομή αρχείου. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| δεδομένα | TemplateData | Δεδομένα προτύπου για συγχώνευση - αντικατάσταση (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) αντικείμενο. Χρησιμοποιείται για να καθορίσει εάν τα ονόματα του προτύπου και του στοιχείου δεδομένων ταιριάζουν, ανεξάρτητα από πεζά ή κεφαλαία (επιλογές). |
| outputPath | String | Πλήρης διαδρομή αρχείου html ως αποτέλεσμα εξόδου μετατροπής. |

## Παρατηρήσεις

Συγχωνευτής Προτύπου

Η ιδέα του συγχωνεύματος προτύπων είναι να δημιουργηθεί ένα έγγραφο HTML βασισμένο σε ένα πρότυπο html και να γεμίσει από μια πηγή δεδομένων. Aspose.HTML παρέχει τη σύνταξη ενσωματωμένων εκφράσεων για εργασία με πρότυπα και διάφορους τύπους πηγών δεδομένων, όπως XML και JSON. Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) όπου μπορείτε να βρείτε περισσότερες πληροφορίες σχετικά με το συγχώνευμα προτύπων και τη χρήση της μεθόδου ConvertTemplate().

Βήματα μετατροπής (συγχώνευσης)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Πηγή προτύπου. Ορίστε την πηγή του προτύπου HTML μέσω αρχείου, [`URL`](../../../com.aspose.html/url/), αντικειμένου [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ή ακόμη και μέσω ενσωματωμένου περιεχομένου. Αποτέλεσμα μετατροπής. Μπορείτε να λάβετε απευθείας το προκύπτον HTMLDocument ή να ορίσετε τη διαδρομή εξόδου του αρχείου αποτελέσματος ανάλογα με την υπογραφή της μεθόδου. Δημιουργήστε ένα στιγμιότυπο του [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Χρησιμοποιήστε τη μέθοδο ConvertTemplate() της κλάσης Converter για να συγχωνεύσετε το πρότυπο με τα δεδομένα. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Κώδικας πηγής

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής σκελετού html φόρμας
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Διαδρομή αρχείου δεδομένων προτύπου xml (json) φόρμας
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Ορίστε ένα στιγμιότυπο αντικειμένου TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Ορίστε το προεπιλεγμένο αντικείμενο TemplateLoadOptions
      var options = new TemplateLoadOptions();

      // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
      Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions, String) {#converttemplate_13}

Συγχωνεύστε την πηγή HTML προτύπου που παρουσιάζεται από ενσωματωμένο περιεχόμενο με τα δεδομένα προτύπου (XML, JSON). Το αποτέλεσμα είναι αρχείο html που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | String | Συγχώνευση σκελετού πηγής HTML που παρουσιάζεται με ενσωματωμένο περιεχόμενο String. |
| baseUrl | String | Βασική URI του προτύπου html. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει μια απόλυτη URL. |
| δεδομένα | TemplateData | Δεδομένα προτύπου για συγχώνευση - αντικατάσταση (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) αντικείμενο. Χρησιμοποιείται για να καθορίσει εάν τα ονόματα του προτύπου και του στοιχείου δεδομένων ταιριάζουν, ανεξάρτητα από πεζά ή κεφαλαία (επιλογές). |
| outputPath | String | Πλήρης διαδρομή αρχείου html ως αποτέλεσμα εξόδου μετατροπής. |

## Παρατηρήσεις

Συγχωνευτής Προτύπου

Η ιδέα του συγχωνεύματος προτύπων είναι να δημιουργηθεί ένα έγγραφο HTML βασισμένο σε ένα πρότυπο html και να γεμίσει από μια πηγή δεδομένων. Aspose.HTML παρέχει τη σύνταξη ενσωματωμένων εκφράσεων για εργασία με πρότυπα και διάφορους τύπους πηγών δεδομένων, όπως XML και JSON. Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) όπου μπορείτε να βρείτε περισσότερες πληροφορίες σχετικά με το συγχώνευμα προτύπων και τη χρήση της μεθόδου ConvertTemplate().

Βήματα μετατροπής (συγχώνευσης)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Πηγή προτύπου. Ορίστε την πηγή του προτύπου HTML μέσω αρχείου, [`URL`](../../../com.aspose.html/url/), αντικειμένου [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ή ακόμη και μέσω ενσωματωμένου περιεχομένου. Αποτέλεσμα μετατροπής. Μπορείτε να λάβετε απευθείας το προκύπτον HTMLDocument ή να ορίσετε τη διαδρομή εξόδου του αρχείου αποτελέσματος ανάλογα με την υπογραφή της μεθόδου. Δημιουργήστε ένα στιγμιότυπο του [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Χρησιμοποιήστε τη μέθοδο ConvertTemplate() της κλάσης Converter για να συγχωνεύσετε το πρότυπο με τα δεδομένα. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Κώδικας πηγής

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
	  // Περιεχόμενο ενσωματωμένης πηγής φόρμας ως πρότυπο
      String templateContent =
        "<html>" + 
        "<body>" +
        "<div data_merge=\"{{#foreach Person}}\">" +
        "<p>{{Title}}</p>" +
        "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
        "<p>Address:</p>" +
        "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
        "</div>" +
        "</body></html>";
       
      // Διαδρομή αρχείου δεδομένων προτύπου xml (json) φόρμας
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Ορίστε ένα στιγμιότυπο αντικειμένου TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Έξοδος φόρμας ως αποτέλεσμα συγχώνευσης 
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Ορίστε το προεπιλεγμένο αντικείμενο TemplateLoadOptions
      var options = new TemplateLoadOptions();
	  
      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertTemplate(templateContent, String.Empty, templateData, options, resultFilePath);

*TemplateFolder - user template data folder.
*OutputFolder - user output file path.

Below is sample data file to merge with source

<?xml version="1.0" encoding="utf-8" ?>
<Data>
	<Person>
	<Title>Title 1</Title>
	<Name>John</Name>
	<Surname>Smith</Surname>
	<Address>
		<Number>200</Number>
		<Street>Austin rd.</Street>
		<City>Dallas</City>
	</Address>
	</Person>
	<Person>
	<Title>Title 2</Title>
	<Name>Mike</Name>
	<Surname>Milbert</Surname>
	<Address>
		<Number>126</Number>
		<Street>First Avenue</Street>
		<City>Chicago</City>
	</Address>
	</Person>
</Data>
```

### Δείτε επίσης

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_12}

Συγχωνεύστε την πηγή HTML προτύπου που παρουσιάζεται από ενσωματωμένο περιεχόμενο με τα δεδομένα προτύπου (XML, JSON). Το αποτέλεσμα είναι αρχείο html που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertTemplate(String content, String baseUrl, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | String | Συγχώνευση σκελετού πηγής HTML που παρουσιάζεται με ενσωματωμένο περιεχόμενο String. |
| baseUrl | String | Βασική URI του προτύπου html. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει μια απόλυτη URL. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| δεδομένα | TemplateData | Δεδομένα προτύπου για συγχώνευση - αντικατάσταση (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) αντικείμενο. Χρησιμοποιείται για να καθορίσει εάν τα ονόματα του προτύπου και του στοιχείου δεδομένων ταιριάζουν, ανεξάρτητα από πεζά ή κεφαλαία (επιλογές). |
| outputPath | String | Πλήρης διαδρομή αρχείου html ως αποτέλεσμα εξόδου μετατροπής. |

## Παρατηρήσεις

Συγχωνευτής Προτύπου

Η ιδέα του συγχωνεύματος προτύπων είναι να δημιουργηθεί ένα έγγραφο HTML βασισμένο σε ένα πρότυπο html και να γεμίσει από μια πηγή δεδομένων. Aspose.HTML παρέχει τη σύνταξη ενσωματωμένων εκφράσεων για εργασία με πρότυπα και διάφορους τύπους πηγών δεδομένων, όπως XML και JSON. Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) όπου μπορείτε να βρείτε περισσότερες πληροφορίες σχετικά με το συγχώνευμα προτύπων και τη χρήση της μεθόδου ConvertTemplate().

Βήματα μετατροπής (συγχώνευσης)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Πηγή προτύπου. Ορίστε την πηγή του προτύπου HTML μέσω αρχείου, [`URL`](../../../com.aspose.html/url/), αντικειμένου [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ή ακόμη και μέσω ενσωματωμένου περιεχομένου. Αποτέλεσμα μετατροπής. Μπορείτε να λάβετε απευθείας το προκύπτον HTMLDocument ή να ορίσετε τη διαδρομή εξόδου του αρχείου αποτελέσματος ανάλογα με την υπογραφή της μεθόδου. Δημιουργήστε ένα στιγμιότυπο του [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Χρησιμοποιήστε τη μέθοδο ConvertTemplate() της κλάσης Converter για να συγχωνεύσετε το πρότυπο με τα δεδομένα. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Κώδικας πηγής

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
   // Περιεχόμενο ενσωματωμένης πηγής φόρμας ως πρότυπο
   String templateContent =
    "<html>" + 
    "<body>" +
    "<div data_merge=\"{{#foreach Person}}\">" +
    "<p>{{Title}}</p>" +
    "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
    "<p>Address:</p>" +
    "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
    "</div>" +
    "</body></html>";
    
   // Διαδρομή αρχείου δεδομένων προτύπου xml (json) φόρμας
   var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

   // Ορίστε ένα στιγμιότυπο αντικειμένου TemplateData
   var templateData = new TemplateData(templateDataPath);

   // Έξοδος φόρμας ως αποτέλεσμα συγχώνευσης 
   var resultFilePath = Path.Combine(OutputFolder, "result.html");

   // Ορίστε ένα στιγμιότυπο αντικειμένου configuration
   var configuration = new Configuration();

   // Ορίστε το προεπιλεγμένο αντικείμενο TemplateLoadOptions
   var options = new TemplateLoadOptions();

   // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
   Converter.ConvertTemplate(templateContent, String.Empty,
        configuration, templateData, options, resultFilePath);
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

Παρακάτω είναι το αρχείο δεδομένων για συγχώνευση με την πηγή ως πρότυπο

```java
<?xml version="1.0" encoding="utf-8" ?>
<Data>
	<Person>
	<Title>Title 1</Title>
	<Name>John</Name>
	<Surname>Smith</Surname>
	<Address>
		<Number>200</Number>
		<Street>Austin rd.</Street>
		<City>Dallas</City>
	</Address>
	</Person>
	<Person>
	<Title>Title 2</Title>
	<Name>Mike</Name>
	<Surname>Milbert</Surname>
	<Address>
		<Number>126</Number>
		<Street>First Avenue</Street>
		<City>Chicago</City>
	</Address>
	</Person>
</Data>
```

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions) {#converttemplate}

Συγχωνεύστε την πηγή προτύπου που παρουσιάζεται από [`HTMLDocument`](../../../com.aspose.html/htmldocument/) με τα δεδομένα προτύπου (XML, JSON). Το αποτέλεσμα είναι ένα νέο δημιουργημένο HTMLDocument που μπορεί να αποθηκευτεί ως αρχείο.

```java
public static HTMLDocument ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| template | HTMLDocument | Συγχώνευση σκελετού πηγής που παρουσιάζεται από [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| δεδομένα | TemplateData | Δεδομένα προτύπου για συγχώνευση - αντικατάσταση (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) αντικείμενο. Χρησιμοποιείται για να καθορίσει εάν τα ονόματα του προτύπου και του στοιχείου δεδομένων ταιριάζουν, ανεξάρτητα από πεζά ή κεφαλαία (επιλογές). |

### Τιμή επιστροφής

Νέο δημιουργημένο [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ως αποτέλεσμα μετατροπής που μπορεί να αποθηκευτεί μέσω της διαδρομής εξόδου αρχείου.

## Παρατηρήσεις

Συγχωνευτής Προτύπου

Η ιδέα του συγχωνεύματος προτύπων είναι να δημιουργηθεί ένα έγγραφο HTML βασισμένο σε ένα πρότυπο html και να γεμίσει από μια πηγή δεδομένων. Aspose.HTML παρέχει τη σύνταξη ενσωματωμένων εκφράσεων για εργασία με πρότυπα και διάφορους τύπους πηγών δεδομένων, όπως XML και JSON. Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) όπου μπορείτε να βρείτε περισσότερες πληροφορίες σχετικά με το συγχώνευμα προτύπων και τη χρήση της μεθόδου ConvertTemplate().

Βήματα μετατροπής (συγχώνευσης)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Πηγή προτύπου. Ορίστε την πηγή του προτύπου HTML μέσω αρχείου, [`URL`](../../../com.aspose.html/url/), αντικειμένου [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ή ακόμη και μέσω ενσωματωμένου περιεχομένου. Αποτέλεσμα μετατροπής. Μπορείτε να λάβετε απευθείας το προκύπτον HTMLDocument ή να ορίσετε τη διαδρομή εξόδου του αρχείου αποτελέσματος ανάλογα με την υπογραφή της μεθόδου. Δημιουργήστε ένα στιγμιότυπο του [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Χρησιμοποιήστε τη μέθοδο ConvertTemplate() της κλάσης Converter για να συγχωνεύσετε το πρότυπο με τα δεδομένα. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Κώδικας πηγής

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής σκελετού html φόρμας
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Διαδρομή αρχείου δεδομένων προτύπου xml (json) φόρμας
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Ορίστε ένα στιγμιότυπο αντικειμένου TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Ορίστε το προεπιλεγμένο αντικείμενο TemplateLoadOptions
      var options = new TemplateLoadOptions();
      
      // Έγγραφο HTML φόρμας ως πηγή μετατροπής
      using (var template = new HTMLDocument(sourcePath, new Configuration()))
      {
        // Ξεκινήστε τη διαδικασία μετατροπής
        var document = Converter.ConvertTemplate(template, templateData, options);
         
        // Αποθηκεύστε το αποτέλεσμα με τους συνδεδεμένους πόρους
        document.Save(new Url(resultPath));
      }





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions) {#converttemplate_2}

Συγχωνεύστε την πηγή HTML προτύπου που παρουσιάζεται από [`URL`](../../../com.aspose.html/url/) με τα δεδομένα προτύπου (XML, JSON). Το αποτέλεσμα είναι ένα νέο δημιουργημένο [`HTMLDocument`](../../../com.aspose.html/htmldocument/) που μπορεί να αποθηκευτεί ως αρχείο.

```java
public static HTMLDocument ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| url | Url | Συγχώνευση σκελετού πηγής HTML που παρουσιάζεται από [`URL`](../../../com.aspose.html/url/). |
| δεδομένα | TemplateData | Δεδομένα προτύπου για συγχώνευση - αντικατάσταση (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) αντικείμενο. Χρησιμοποιείται για να καθορίσει εάν τα ονόματα του προτύπου και του στοιχείου δεδομένων ταιριάζουν, ανεξάρτητα από πεζά ή κεφαλαία (επιλογές). |

### Τιμή επιστροφής

Νέο δημιουργημένο [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ως αποτέλεσμα μετατροπής που μπορεί να αποθηκευτεί μέσω της διαδρομής εξόδου αρχείου.

## Παρατηρήσεις

Συγχωνευτής Προτύπου

Η ιδέα του συγχωνεύματος προτύπων είναι να δημιουργηθεί ένα έγγραφο HTML βασισμένο σε ένα πρότυπο html και να γεμίσει από μια πηγή δεδομένων. Aspose.HTML παρέχει τη σύνταξη ενσωματωμένων εκφράσεων για εργασία με πρότυπα και διάφορους τύπους πηγών δεδομένων, όπως XML και JSON. Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) όπου μπορείτε να βρείτε περισσότερες πληροφορίες σχετικά με το συγχώνευμα προτύπων και τη χρήση της μεθόδου ConvertTemplate().

Βήματα μετατροπής (συγχώνευσης)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Πηγή προτύπου. Ορίστε την πηγή του προτύπου HTML μέσω αρχείου, [`URL`](../../../com.aspose.html/url/), αντικειμένου [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ή ακόμη και μέσω ενσωματωμένου περιεχομένου. Αποτέλεσμα μετατροπής. Μπορείτε να λάβετε απευθείας το προκύπτον HTMLDocument ή να ορίσετε τη διαδρομή εξόδου του αρχείου αποτελέσματος ανάλογα με την υπογραφή της μεθόδου. Δημιουργήστε ένα στιγμιότυπο του [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Χρησιμοποιήστε τη μέθοδο ConvertTemplate() της κλάσης Converter για να συγχωνεύσετε το πρότυπο με τα δεδομένα. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Κώδικας πηγής

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργήστε URL για το αρχείο πηγής σκελετού html
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Διαδρομή αρχείου δεδομένων προτύπου xml (json) φόρμας
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Ορίστε ένα στιγμιότυπο αντικειμένου TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Ορίστε το προεπιλεγμένο αντικείμενο TemplateLoadOptions
      var options = new TemplateLoadOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      using (var document = Converter.ConvertTemplate(sourceUrl, templateData, options))
      {
        // Αποθηκεύστε το αποτέλεσμα με τους συνδεδεμένους πόρους
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_1}

Συγχωνεύστε την πηγή HTML προτύπου που παρουσιάζεται από [`URL`](../../../com.aspose.html/url/) με τα δεδομένα προτύπου (XML, JSON). Το αποτέλεσμα είναι ένα νέο δημιουργημένο [`HTMLDocument`](../../../com.aspose.html/htmldocument/) που μπορεί να αποθηκευτεί ως αρχείο.

```java
public static HTMLDocument ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| url | Url | Συγχώνευση σκελετού πηγής HTML που παρουσιάζεται από [`URL`](../../../com.aspose.html/url/). |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| δεδομένα | TemplateData | Δεδομένα προτύπου για συγχώνευση - αντικατάσταση (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) αντικείμενο. Χρησιμοποιείται για να καθορίσει εάν τα ονόματα του προτύπου και του στοιχείου δεδομένων ταιριάζουν, ανεξάρτητα από πεζά ή κεφαλαία (επιλογές). |

### Τιμή επιστροφής

Νέο δημιουργημένο [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ως αποτέλεσμα μετατροπής που μπορεί να αποθηκευτεί μέσω της διαδρομής εξόδου αρχείου.

## Παρατηρήσεις

Συγχωνευτής Προτύπου

Η ιδέα του συγχωνεύματος προτύπων είναι να δημιουργηθεί ένα έγγραφο HTML βασισμένο σε ένα πρότυπο html και να γεμίσει από μια πηγή δεδομένων. Aspose.HTML παρέχει τη σύνταξη ενσωματωμένων εκφράσεων για εργασία με πρότυπα και διάφορους τύπους πηγών δεδομένων, όπως XML και JSON. Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) όπου μπορείτε να βρείτε περισσότερες πληροφορίες σχετικά με το συγχώνευμα προτύπων και τη χρήση της μεθόδου ConvertTemplate().

Βήματα μετατροπής (συγχώνευσης)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Πηγή προτύπου. Ορίστε την πηγή του προτύπου HTML μέσω αρχείου, [`URL`](../../../com.aspose.html/url/), αντικειμένου [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ή ακόμη και μέσω ενσωματωμένου περιεχομένου. Αποτέλεσμα μετατροπής. Μπορείτε να λάβετε απευθείας το προκύπτον HTMLDocument ή να ορίσετε τη διαδρομή εξόδου του αρχείου αποτελέσματος ανάλογα με την υπογραφή της μεθόδου. Δημιουργήστε ένα στιγμιότυπο του [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Χρησιμοποιήστε τη μέθοδο ConvertTemplate() της κλάσης Converter για να συγχωνεύσετε το πρότυπο με τα δεδομένα. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Κώδικας πηγής

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργήστε URL για το αρχείο πηγής σκελετού html
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Διαδρομή αρχείου δεδομένων προτύπου xml (json) φόρμας
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Ορίστε ένα στιγμιότυπο αντικειμένου TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Ορίστε το προεπιλεγμένο αντικείμενο TemplateLoadOptions
      var options = new TemplateLoadOptions();

      // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
      using (var document = Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options))
      {
        // Αποθηκεύστε το αποτέλεσμα με τους συνδεδεμένους πόρους
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, TemplateData, TemplateLoadOptions) {#converttemplate_4}

Συγχωνεύστε την πηγή HTML προτύπου που παρουσιάζεται από πλήρη διαδρομή αρχείου με τα δεδομένα προτύπου (XML, JSON). Το αποτέλεσμα είναι ένα νέο δημιουργημένο [`HTMLDocument`](../../../com.aspose.html/htmldocument/) που μπορεί να αποθηκευτεί ως αρχείο.

```java
public static HTMLDocument ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Συγχώνευση σκελετού πηγής HTML που παρουσιάζεται με πλήρη διαδρομή αρχείου. |
| δεδομένα | TemplateData | Δεδομένα προτύπου για συγχώνευση - αντικατάσταση (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) αντικείμενο. Χρησιμοποιείται για να καθορίσει εάν τα ονόματα του προτύπου και του στοιχείου δεδομένων ταιριάζουν, ανεξάρτητα από πεζά ή κεφαλαία (επιλογές). |

### Τιμή επιστροφής

Νέο δημιουργημένο [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ως αποτέλεσμα μετατροπής που μπορεί να αποθηκευτεί μέσω της διαδρομής εξόδου αρχείου.

## Παρατηρήσεις

Συγχωνευτής Προτύπου

Η ιδέα του συγχωνεύματος προτύπων είναι να δημιουργηθεί ένα έγγραφο HTML βασισμένο σε ένα πρότυπο html και να γεμίσει από μια πηγή δεδομένων. Aspose.HTML παρέχει τη σύνταξη ενσωματωμένων εκφράσεων για εργασία με πρότυπα και διάφορους τύπους πηγών δεδομένων, όπως XML και JSON. Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) όπου μπορείτε να βρείτε περισσότερες πληροφορίες σχετικά με το συγχώνευμα προτύπων και τη χρήση της μεθόδου ConvertTemplate().

Βήματα μετατροπής (συγχώνευσης)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Πηγή προτύπου. Ορίστε την πηγή του προτύπου HTML μέσω αρχείου, [`URL`](../../../com.aspose.html/url/), αντικειμένου [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ή ακόμη και μέσω ενσωματωμένου περιεχομένου. Αποτέλεσμα μετατροπής. Μπορείτε να λάβετε απευθείας το προκύπτον HTMLDocument ή να ορίσετε τη διαδρομή εξόδου του αρχείου αποτελέσματος ανάλογα με την υπογραφή της μεθόδου. Δημιουργήστε ένα στιγμιότυπο του [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Χρησιμοποιήστε τη μέθοδο ConvertTemplate() της κλάσης Converter για να συγχωνεύσετε το πρότυπο με τα δεδομένα. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Κώδικας πηγής

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής σκελετού html φόρμας
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Διαδρομή αρχείου δεδομένων προτύπου xml (json) φόρμας
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Ορίστε ένα στιγμιότυπο αντικειμένου TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Ορίστε το προεπιλεγμένο αντικείμενο TemplateLoadOptions
      var options = new TemplateLoadOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      using (var document = Converter.ConvertTemplate(sourcePath, templateData, options))
      {
        // Αποθηκεύστε το αποτέλεσμα με τους συνδεδεμένους πόρους
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_3}

Συγχωνεύστε την πηγή HTML προτύπου που παρουσιάζεται από πλήρη διαδρομή αρχείου με τα δεδομένα προτύπου (XML, JSON). Το αποτέλεσμα είναι ένα νέο δημιουργημένο [`HTMLDocument`](../../../com.aspose.html/htmldocument/) που μπορεί να αποθηκευτεί ως αρχείο.

```java
public static HTMLDocument ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Συγχώνευση σκελετού πηγής HTML που παρουσιάζεται με πλήρη διαδρομή αρχείου. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| δεδομένα | TemplateData | Δεδομένα προτύπου για συγχώνευση - αντικατάσταση (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) αντικείμενο. Χρησιμοποιείται για να καθορίσει εάν τα ονόματα του προτύπου και του στοιχείου δεδομένων ταιριάζουν, ανεξάρτητα από πεζά ή κεφαλαία (επιλογές). |

### Τιμή επιστροφής

Νέο δημιουργημένο [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ως αποτέλεσμα μετατροπής που μπορεί να αποθηκευτεί μέσω της διαδρομής εξόδου αρχείου.

## Παρατηρήσεις

Συγχωνευτής Προτύπου

Η ιδέα του συγχωνεύματος προτύπων είναι να δημιουργηθεί ένα έγγραφο HTML βασισμένο σε ένα πρότυπο html και να γεμίσει από μια πηγή δεδομένων. Aspose.HTML παρέχει τη σύνταξη ενσωματωμένων εκφράσεων για εργασία με πρότυπα και διάφορους τύπους πηγών δεδομένων, όπως XML και JSON. Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) όπου μπορείτε να βρείτε περισσότερες πληροφορίες σχετικά με το συγχώνευμα προτύπων και τη χρήση της μεθόδου ConvertTemplate().

Βήματα μετατροπής (συγχώνευσης)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Πηγή προτύπου. Ορίστε την πηγή του προτύπου HTML μέσω αρχείου, [`URL`](../../../com.aspose.html/url/), αντικειμένου [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ή ακόμη και μέσω ενσωματωμένου περιεχομένου. Αποτέλεσμα μετατροπής. Μπορείτε να λάβετε απευθείας το προκύπτον HTMLDocument ή να ορίσετε τη διαδρομή εξόδου του αρχείου αποτελέσματος ανάλογα με την υπογραφή της μεθόδου. Δημιουργήστε ένα στιγμιότυπο του [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Χρησιμοποιήστε τη μέθοδο ConvertTemplate() της κλάσης Converter για να συγχωνεύσετε το πρότυπο με τα δεδομένα. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Κώδικας πηγής

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής σκελετού html φόρμας
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Διαδρομή αρχείου δεδομένων προτύπου xml (json) φόρμας
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Ορίστε ένα στιγμιότυπο αντικειμένου TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Ορίστε το προεπιλεγμένο αντικείμενο TemplateLoadOptions
      var options = new TemplateLoadOptions();

      // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
      using (var document = Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options))
      {
        // Αποθηκεύστε το αποτέλεσμα με τους συνδεδεμένους πόρους
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions) {#converttemplate_6}

Συγχωνεύστε την πηγή HTML προτύπου που παρουσιάζεται από ενσωματωμένο περιεχόμενο με τα δεδομένα προτύπου (XML, JSON). Το αποτέλεσμα είναι ένα νέο δημιουργημένο [`HTMLDocument`](../../../com.aspose.html/htmldocument/) που μπορεί να αποθηκευτεί ως αρχείο.

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | String | Συγχώνευση σκελετού πηγής HTML που παρουσιάζεται με ενσωματωμένο περιεχόμενο String. |
| baseUrl | String | Βασική URI του προτύπου html. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει μια απόλυτη URL. |
| δεδομένα | TemplateData | Δεδομένα προτύπου για συγχώνευση - αντικατάσταση (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) αντικείμενο. Χρησιμοποιείται για να καθορίσει εάν τα ονόματα του προτύπου και του στοιχείου δεδομένων ταιριάζουν, ανεξάρτητα από πεζά ή κεφαλαία (επιλογές). |

### Τιμή επιστροφής

Νέο δημιουργημένο [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ως αποτέλεσμα μετατροπής που μπορεί να αποθηκευτεί μέσω της διαδρομής εξόδου αρχείου.

## Παρατηρήσεις

Συγχωνευτής Προτύπου

Η ιδέα του συγχωνεύματος προτύπων είναι να δημιουργηθεί ένα έγγραφο HTML βασισμένο σε ένα πρότυπο html και να γεμίσει από μια πηγή δεδομένων. Aspose.HTML παρέχει τη σύνταξη ενσωματωμένων εκφράσεων για εργασία με πρότυπα και διάφορους τύπους πηγών δεδομένων, όπως XML και JSON. Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) όπου μπορείτε να βρείτε περισσότερες πληροφορίες σχετικά με το συγχώνευμα προτύπων και τη χρήση της μεθόδου ConvertTemplate().

Βήματα μετατροπής (συγχώνευσης)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Πηγή προτύπου. Ορίστε την πηγή του προτύπου HTML μέσω αρχείου, [`URL`](../../../com.aspose.html/url/), αντικειμένου [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ή ακόμη και μέσω ενσωματωμένου περιεχομένου. Αποτέλεσμα μετατροπής. Μπορείτε να λάβετε απευθείας το προκύπτον HTMLDocument ή να ορίσετε τη διαδρομή εξόδου του αρχείου αποτελέσματος ανάλογα με την υπογραφή της μεθόδου. Δημιουργήστε ένα στιγμιότυπο του [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Χρησιμοποιήστε τη μέθοδο ConvertTemplate() της κλάσης Converter για να συγχωνεύσετε το πρότυπο με τα δεδομένα. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Κώδικας πηγής

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Περιεχόμενο ενσωματωμένης πηγής φόρμας ως πρότυπο
      String templateContent =
        "<html>" +
        "<body>" +
        "<div data_merge=\"{{#foreach Person}}\">" +
        "<p>{{Title}}</p>" +
        "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
        "<p>Address:</p>" +
        "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
        "</div>" +
        "</body></html>";

      // Διαδρομή αρχείου δεδομένων προτύπου xml (json) φόρμας
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Ορίστε ένα στιγμιότυπο αντικειμένου TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Έξοδος φόρμας ως αποτέλεσμα συγχώνευσης 
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Ορίστε το προεπιλεγμένο αντικείμενο TemplateLoadOptions
      var options = new TemplateLoadOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής και αποθηκεύστε το αποτέλεσμα
      using (var document = Converter.ConvertTemplate(
        templateContent, String.Empty,
        templateData,
        options))
      {
        document.Save(new Url(resultFilePath));
      }
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_5}

Συγχωνεύστε την πηγή HTML προτύπου που παρουσιάζεται από ενσωματωμένο περιεχόμενο με τα δεδομένα προτύπου (XML, JSON). Το αποτέλεσμα είναι ένα νέο δημιουργημένο [`HTMLDocument`](../../../com.aspose.html/htmldocument/) που μπορεί να αποθηκευτεί ως αρχείο.

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, 
    Configuration configuration, TemplateData data, TemplateLoadOptions options)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | String | Συγχώνευση σκελετού πηγής HTML που παρουσιάζεται με ενσωματωμένο περιεχόμενο String. |
| baseUrl | String | Βασική URI του προτύπου html. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει μια απόλυτη URL. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| δεδομένα | TemplateData | Δεδομένα προτύπου για συγχώνευση - αντικατάσταση (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) αντικείμενο. Χρησιμοποιείται για να καθορίσει εάν τα ονόματα του προτύπου και του στοιχείου δεδομένων ταιριάζουν, ανεξάρτητα από πεζά ή κεφαλαία (επιλογές). |

### Τιμή επιστροφής

Νέο δημιουργημένο [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ως αποτέλεσμα μετατροπής που μπορεί να αποθηκευτεί μέσω της διαδρομής εξόδου αρχείου.

## Παρατηρήσεις

Συγχωνευτής Προτύπου

Η ιδέα του συγχωνεύματος προτύπων είναι να δημιουργηθεί ένα έγγραφο HTML βασισμένο σε ένα πρότυπο html και να γεμίσει από μια πηγή δεδομένων. Aspose.HTML παρέχει τη σύνταξη ενσωματωμένων εκφράσεων για εργασία με πρότυπα και διάφορους τύπους πηγών δεδομένων, όπως XML και JSON. Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) όπου μπορείτε να βρείτε περισσότερες πληροφορίες σχετικά με το συγχώνευμα προτύπων και τη χρήση της μεθόδου ConvertTemplate().

Βήματα μετατροπής (συγχώνευσης)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Πηγή προτύπου. Ορίστε την πηγή του προτύπου HTML μέσω αρχείου, [`URL`](../../../com.aspose.html/url/), αντικειμένου [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ή ακόμη και μέσω ενσωματωμένου περιεχομένου. Αποτέλεσμα μετατροπής. Μπορείτε να λάβετε απευθείας το προκύπτον HTMLDocument ή να ορίσετε τη διαδρομή εξόδου του αρχείου αποτελέσματος ανάλογα με την υπογραφή της μεθόδου. Δημιουργήστε ένα στιγμιότυπο του [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Χρησιμοποιήστε τη μέθοδο ConvertTemplate() της κλάσης Converter για να συγχωνεύσετε το πρότυπο με τα δεδομένα. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Κώδικας πηγής

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Περιεχόμενο ενσωματωμένης πηγής φόρμας ως πρότυπο
      String templateContent =
        "<html>" + 
        "<body>" +
        "<div data_merge=\"{{#foreach Person}}\">" +
        "<p>{{Title}}</p>" +
        "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
        "<p>Address:</p>" +
        "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
        "</div>" +
        "</body></html>";
       
      // Διαδρομή αρχείου δεδομένων προτύπου xml (json) φόρμας
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Ορίστε ένα στιγμιότυπο αντικειμένου TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Έξοδος φόρμας ως αποτέλεσμα συγχώνευσης 
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Ορίστε ένα στιγμιότυπο αντικειμένου configuration
      var configuration = new Configuration();

      // Ορίστε το προεπιλεγμένο αντικείμενο TemplateLoadOptions
      var options = new TemplateLoadOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής και αποθηκεύστε το αποτέλεσμα
      using (var document = Converter.ConvertTemplate(
        templateContent, String.Empty,
        configuration,
        templateData,
        options))
      {
        document.Save(new Url(resultFilePath));
      }
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
