---
title: "Converter.ConvertSVG"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Converter. Μετατρέψτε την πηγή SVG που παρουσιάζεται από SVGDocument. Το αποτέλεσμα είναι τα δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής ICreateStreamProvider"
type: docs

url: /el/java/com.aspose.html.converters/converter/convertsvg/
---
## ConvertSVG(SVGDocument, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_6}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Το αποτέλεσμα είναι τα δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(SVGDocument document, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| document | SVGDocument | Πηγή μετατροπής που παρουσιάζεται από [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) χρήση του αντικειμένου σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση της [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την απόκτηση ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε XPS χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε XPS

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε XPS. Για να μετατρέψετε SVG σε XPS, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα XPS με τρία ή περισσότερα παραμέτρους ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Η Aspose.HTML προσφέρει έναν δωρεάν online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) που μετατρέπει SVG σε XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο XpsSaveOptions
      var options = new XpsSaveOptions();

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Δημιουργήστε το έγγραφο SVG ως πηγή μετατροπής
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
			// Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
			Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_22}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από [`URL`](../../../com.aspose.html/url/). Το αποτέλεσμα είναι τα δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| url | Url | Έγγραφο πηγής SVG [`URL`](../../../com.aspose.html/url/) - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) η χρήση του αντικειμένου σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. |
| provider | ICreateStreamProvider | Γνωστή (δείτε [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε XPS χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε XPS

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε XPS. Για να μετατρέψετε SVG σε XPS, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα XPS με τρία ή περισσότερα παραμέτρους ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Η Aspose.HTML προσφέρει έναν δωρεάν online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) που μετατρέπει SVG σε XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Διαδρομή αρχείου πηγής φόρμας
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο XpsSaveOptions
      var options = new XpsSaveOptions();

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertSVG(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_14}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από [`URL`](../../../com.aspose.html/url/). Το αποτέλεσμα είναι τα δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| url | Url | Έγγραφο πηγής SVG [`URL`](../../../com.aspose.html/url/) - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) χρήση του αντικειμένου σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Γνωστή (δείτε [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε XPS χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε XPS

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε XPS. Για να μετατρέψετε SVG σε XPS, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα XPS με τρία ή περισσότερα παραμέτρους ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Η Aspose.HTML προσφέρει έναν δωρεάν online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) που μετατρέπει SVG σε XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Διαδρομή αρχείου πηγής φόρμας
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο XpsSaveOptions
      var options = new XpsSaveOptions();

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

## ConvertSVG(String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_38}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από πλήρη διαδρομή αρχείου σε XPS. Το αποτέλεσμα είναι τα δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής SVG. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) η χρήση του αντικειμένου σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. |
| provider | ICreateStreamProvider | Υλοποίηση της [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την απόκτηση ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε XPS χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε XPS

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε XPS. Για να μετατρέψετε SVG σε XPS, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα XPS με τρία ή περισσότερα παραμέτρους ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Η Aspose.HTML προσφέρει έναν δωρεάν online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) που μετατρέπει SVG σε XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο XpsSaveOptions
      var options = new XpsSaveOptions();

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertSVG(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_30}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από πλήρη διαδρομή αρχείου σε XPS. Το αποτέλεσμα είναι τα δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής SVG. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) χρήση του αντικειμένου σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση της [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την απόκτηση ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε XPS χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε XPS

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε XPS. Για να μετατρέψετε SVG σε XPS, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα XPS με τρία ή περισσότερα παραμέτρους ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Η Aspose.HTML προσφέρει έναν δωρεάν online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) που μετατρέπει SVG σε XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο XpsSaveOptions
      var options = new XpsSaveOptions();

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_54}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από ενσωματωμένο περιεχόμενο σε XPS. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | String | String ως ενσωματωμένο περιεχόμενο SVG. |
| baseUri | String | Η βασική URI του εγγράφου. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει μια απόλυτη URL. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) η χρήση του αντικειμένου σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. |
| provider | ICreateStreamProvider | Υλοποίηση της [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την απόκτηση ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε XPS χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε XPS

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε XPS. Για να μετατρέψετε SVG σε XPS, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα XPS με τρία ή περισσότερα παραμέτρους ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Η Aspose.HTML προσφέρει έναν δωρεάν online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) που μετατρέπει SVG σε XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ορίστε το προεπιλεγμένο αντικείμενο XpsSaveOptions
      var options = new XpsSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_46}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από ενσωματωμένο περιεχόμενο σε XPS. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | String | String ως ενσωματωμένο περιεχόμενο SVG. |
| baseUri | String | Η βασική URI του εγγράφου. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει μια απόλυτη URL. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) χρήση του αντικειμένου σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Γνωστή (δείτε [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε XPS χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε XPS

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε XPS. Για να μετατρέψετε SVG σε XPS, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα XPS με τρία ή περισσότερα παραμέτρους ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Η Aspose.HTML προσφέρει έναν δωρεάν online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) που μετατρέπει SVG σε XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ορίστε το προεπιλεγμένο αντικείμενο XpsSaveOptions
      var options = new XpsSaveOptions();

      // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
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

## ConvertSVG(SVGDocument, DocSaveOptions, String) {#convertsvg_1}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Το αποτέλεσμα είναι αρχείο docx που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(SVGDocument source, DocSaveOptions options, String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| source | SVGDocument | Πηγή μετατροπής που παρουσιάζεται από [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | DocSaveOptions | Η χρήση του αντικειμένου [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Πλήρης διαδρομή αρχείου docx ως αποτέλεσμα εξόδου μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε [DOCX](https://docs.fileformat.com/word-processing/docx/) χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης Converter και πώς να εφαρμόσετε τις παραμέτρους [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε DOCX

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε DOCX. Για να μετατρέψετε SVG σε DOCX, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα DOCX με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) που μετατρέπει SVG σε DOCX με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο DocSaveOptions
      var options = new DocSaveOptions();

      // Δημιουργήστε το έγγραφο SVG ως πηγή μετατροπής
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, String) {#convertsvg_17}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από το [`URL`](../../../com.aspose.html/url/). Το αποτέλεσμα είναι αρχείο docx που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(Url url, DocSaveOptions options, String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| url | Url | Έγγραφο πηγής SVG [`URL`](../../../com.aspose.html/url/) - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| options | DocSaveOptions | Η χρήση του αντικειμένου [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Πλήρης διαδρομή αρχείου docx ως αποτέλεσμα εξόδου μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε [DOCX](https://docs.fileformat.com/word-processing/docx/) χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης Converter και πώς να εφαρμόσετε τις παραμέτρους [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε DOCX

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε DOCX. Για να μετατρέψετε SVG σε DOCX, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα DOCX με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) που μετατρέπει SVG σε DOCX με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργήστε Url βάσει της διαδρομής εισόδου αρχείου
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Ορίστε το προεπιλεγμένο αντικείμενο DocSaveOptions
      var options = new DocSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertSVG(sourceUrl, options, resultPath);





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

## ConvertSVG(Url, Configuration, DocSaveOptions, String) {#convertsvg_9}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από το [`URL`](../../../com.aspose.html/url/). Το αποτέλεσμα είναι αρχείο docx που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| url | Url | Έγγραφο πηγής SVG [`URL`](../../../com.aspose.html/url/) - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| options | DocSaveOptions | Η χρήση του αντικειμένου [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Πλήρης διαδρομή αρχείου docx ως αποτέλεσμα εξόδου μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε [DOCX](https://docs.fileformat.com/word-processing/docx/) χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης Converter και πώς να εφαρμόσετε τις παραμέτρους [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε DOCX

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε DOCX. Για να μετατρέψετε SVG σε DOCX, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα DOCX με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) που μετατρέπει SVG σε DOCX με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργήστε Url βάσει της διαδρομής εισόδου αρχείου
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Ορίστε το προεπιλεγμένο αντικείμενο DocSaveOptions
      var options = new DocSaveOptions();

      // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, DocSaveOptions, String) {#convertsvg_33}

Μετατρέψτε την πηγή SVG που παρέχεται με πλήρη διαδρομή αρχείου σε DOCX. Το αποτέλεσμα είναι αρχείο docx που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής SVG. |
| options | DocSaveOptions | Η χρήση του αντικειμένου [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Πλήρης διαδρομή αρχείου docx ως αποτέλεσμα εξόδου μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε [DOCX](https://docs.fileformat.com/word-processing/docx/) χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης Converter και πώς να εφαρμόσετε τις παραμέτρους [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε DOCX

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε DOCX. Για να μετατρέψετε SVG σε DOCX, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα DOCX με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) που μετατρέπει SVG σε DOCX με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Ορίστε το προεπιλεγμένο αντικείμενο DocSaveOptions
      var options = new DocSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertSVG(sourcePath, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, DocSaveOptions, String) {#convertsvg_25}

Μετατρέψτε την πηγή SVG που παρέχεται με πλήρη διαδρομή αρχείου σε DOCX. Το αποτέλεσμα είναι αρχείο docx που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής SVG. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| options | DocSaveOptions | Η χρήση του αντικειμένου [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Πλήρης διαδρομή αρχείου docx ως αποτέλεσμα εξόδου μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε [DOCX](https://docs.fileformat.com/word-processing/docx/) χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης Converter και πώς να εφαρμόσετε τις παραμέτρους [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε DOCX

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε DOCX. Για να μετατρέψετε SVG σε DOCX, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα DOCX με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) που μετατρέπει SVG σε DOCX με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Ορίστε το προεπιλεγμένο αντικείμενο DocSaveOptions
      var options = new DocSaveOptions();

      // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, DocSaveOptions, String) {#convertsvg_49}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από ενσωματωμένο περιεχόμενο. Το αποτέλεσμα είναι αρχείο docx που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | String | String ως ενσωματωμένο περιεχόμενο SVG. |
| baseUri | String | Η βασική URI του εγγράφου. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει μια απόλυτη URL. |
| options | DocSaveOptions | Η χρήση του αντικειμένου [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Πλήρης διαδρομή αρχείου docx ως αποτέλεσμα εξόδου μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε [DOCX](https://docs.fileformat.com/word-processing/docx/) χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης Converter και πώς να εφαρμόσετε τις παραμέτρους [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε DOCX

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε DOCX. Για να μετατρέψετε SVG σε DOCX, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα DOCX με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) που μετατρέπει SVG σε DOCX με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργία ενσωματωμένου περιεχομένου SVG
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Ορίστε το προεπιλεγμένο αντικείμενο DocSaveOptions
      var options = new DocSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, String) {#convertsvg_41}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από ενσωματωμένο περιεχόμενο. Το αποτέλεσμα είναι αρχείο docx που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | String | String ως ενσωματωμένο περιεχόμενο SVG. |
| baseUri | String | Η βασική URI του εγγράφου. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει μια απόλυτη URL. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| options | DocSaveOptions | Η χρήση του αντικειμένου [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Πλήρης διαδρομή αρχείου docx ως αποτέλεσμα εξόδου μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε [DOCX](https://docs.fileformat.com/word-processing/docx/) χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης Converter και πώς να εφαρμόσετε τις παραμέτρους [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε DOCX

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε DOCX. Για να μετατρέψετε SVG σε DOCX, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα DOCX με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) που μετατρέπει SVG σε DOCX με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργία ενσωματωμένου περιεχομένου SVG
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Ορίστε το προεπιλεγμένο αντικείμενο DocSaveOptions
      var options = new DocSaveOptions();

      // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, DocSaveOptions, ICreateStreamProvider) {#convertsvg}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Το αποτέλεσμα είναι τα δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(SVGDocument document, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| document | SVGDocument | Πηγή μετατροπής που παρουσιάζεται από [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | DocSaveOptions | Η χρήση του αντικειμένου [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Γνωστή (δείτε [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε [DOCX](https://docs.fileformat.com/word-processing/docx/) χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης Converter και πώς να εφαρμόσετε τις παραμέτρους [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε DOCX

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε DOCX. Για να μετατρέψετε SVG σε DOCX, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα DOCX με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) που μετατρέπει SVG σε DOCX με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο DocSaveOptions
      var options = new DocSaveOptions();

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Δημιουργήστε το έγγραφο SVG ως πηγή μετατροπής
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, ICreateStreamProvider) {#convertsvg_16}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από [`URL`](../../../com.aspose.html/url/). Το αποτέλεσμα είναι τα δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| url | Url | Έγγραφο πηγής SVG [`URL`](../../../com.aspose.html/url/) - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| options | DocSaveOptions | Η χρήση του αντικειμένου [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Υλοποίηση της [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την απόκτηση ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε [DOCX](https://docs.fileformat.com/word-processing/docx/) χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης Converter και πώς να εφαρμόσετε τις παραμέτρους [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε DOCX

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε DOCX. Για να μετατρέψετε SVG σε DOCX, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα DOCX με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) που μετατρέπει SVG σε DOCX με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργήστε Url βάσει της διαδρομής εισόδου αρχείου
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο DocSaveOptions
      var options = new DocSaveOptions();

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertSVG(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_8}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από το [`URL`](../../../com.aspose.html/url/). Το αποτέλεσμα είναι αρχείο docx που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| url | Url | Έγγραφο πηγής SVG [`URL`](../../../com.aspose.html/url/) - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| options | DocSaveOptions | Η χρήση του αντικειμένου [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Γνωστή (δείτε [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε [DOCX](https://docs.fileformat.com/word-processing/docx/) χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης Converter και πώς να εφαρμόσετε τις παραμέτρους [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε DOCX

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε DOCX. Για να μετατρέψετε SVG σε DOCX, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα DOCX με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) που μετατρέπει SVG σε DOCX με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργήστε Url βάσει της διαδρομής εισόδου αρχείου
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο DocSaveOptions
      var options = new DocSaveOptions();

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_32}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από πλήρη διαδρομή αρχείου σε DOCX. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής SVG. |
| options | DocSaveOptions | Η χρήση του αντικειμένου [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Γνωστή (δείτε [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε [DOCX](https://docs.fileformat.com/word-processing/docx/) χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης Converter και πώς να εφαρμόσετε τις παραμέτρους [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε DOCX

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε DOCX. Για να μετατρέψετε SVG σε DOCX, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα DOCX με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) που μετατρέπει SVG σε DOCX με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο DocSaveOptions
      var options = new DocSaveOptions();

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_24}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από πλήρη διαδρομή αρχείου σε DOCX. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής SVG. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| options | DocSaveOptions | Η χρήση του αντικειμένου [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Υλοποίηση της [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την απόκτηση ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε [DOCX](https://docs.fileformat.com/word-processing/docx/) χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης Converter και πώς να εφαρμόσετε τις παραμέτρους [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε DOCX

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε DOCX. Για να μετατρέψετε SVG σε DOCX, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα DOCX με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) που μετατρέπει SVG σε DOCX με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο DocSaveOptions
      var options = new DocSaveOptions();

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_48}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από ενσωματωμένο περιεχόμενο σε DOCX. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | String | String ως ενσωματωμένο περιεχόμενο SVG. |
| baseUri | String | Η βασική URI του εγγράφου. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει μια απόλυτη URL. |
| options | DocSaveOptions | Η χρήση του αντικειμένου [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Υλοποίηση της [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την απόκτηση ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε [DOCX](https://docs.fileformat.com/word-processing/docx/) χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης Converter και πώς να εφαρμόσετε τις παραμέτρους [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε DOCX

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε DOCX. Για να μετατρέψετε SVG σε DOCX, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα DOCX με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) που μετατρέπει SVG σε DOCX με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ορίστε το προεπιλεγμένο αντικείμενο DocSaveOptions
      var options = new DocSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_40}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από ενσωματωμένο περιεχόμενο σε DOCX. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | String | String ως ενσωματωμένο περιεχόμενο SVG. |
| baseUri | String | Η βασική URI του εγγράφου. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει μια απόλυτη URL. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| options | DocSaveOptions | Η χρήση του αντικειμένου [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Υλοποίηση της [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την απόκτηση ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε [DOCX](https://docs.fileformat.com/word-processing/docx/) χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης Converter και πώς να εφαρμόσετε τις παραμέτρους [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε DOCX

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε DOCX. Για να μετατρέψετε SVG σε DOCX, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα DOCX με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) που μετατρέπει SVG σε DOCX με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ορίστε το προεπιλεγμένο αντικείμενο DocSaveOptions
      var options = new DocSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, PdfSaveOptions, String) {#convertsvg_5}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) σε PDF. Το αποτέλεσμα είναι αρχείο pdf που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(SVGDocument source, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| source | SVGDocument | Πηγή μετατροπής που παρουσιάζεται από [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | PdfSaveOptions | Η χρήση του αντικειμένου [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου pdf ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε PDF χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε PDF

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε PDF. Για να μετατρέψετε SVG σε PDF, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα PDF με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) που μετατρέπει SVG σε PDF με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο PdfSaveOptions
      var options = new PdfSaveOptions();

      // Δημιουργήστε το έγγραφο SVG ως πηγή μετατροπής
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, String) {#convertsvg_21}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από το [`URL`](../../../com.aspose.html/url/). Το αποτέλεσμα είναι αρχείο pdf που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| url | Url | Έγγραφο πηγής SVG [`URL`](../../../com.aspose.html/url/) - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| options | PdfSaveOptions | Η χρήση του αντικειμένου [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου pdf ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε PDF χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε PDF

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε PDF. Για να μετατρέψετε SVG σε PDF, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα PDF με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) που μετατρέπει SVG σε PDF με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργήστε Url βάσει της διαδρομής εισόδου αρχείου
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Ορίστε το προεπιλεγμένο αντικείμενο PdfSaveOptions
      var options = new PdfSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, PdfSaveOptions, String) {#convertsvg_13}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από το [`URL`](../../../com.aspose.html/url/). Το αποτέλεσμα είναι αρχείο pdf που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| url | Url | Έγγραφο πηγής SVG [`URL`](../../../com.aspose.html/url/) - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| options | PdfSaveOptions | Η χρήση του αντικειμένου [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου pdf ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε PDF χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε PDF

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε PDF. Για να μετατρέψετε SVG σε PDF, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα PDF με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) που μετατρέπει SVG σε PDF με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργήστε Url βάσει της διαδρομής εισόδου αρχείου
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Ορίστε το προεπιλεγμένο αντικείμενο PdfSaveOptions
      var options = new PdfSaveOptions();

      // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertSVG(String, PdfSaveOptions, String) {#convertsvg_37}

Μετατρέψτε την πηγή SVG που παρέχεται με πλήρη διαδρομή αρχείου σε PDF. Το αποτέλεσμα είναι αρχείο pdf που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής SVG. |
| options | PdfSaveOptions | Η χρήση του αντικειμένου [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου pdf ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε PDF χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε PDF

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε PDF. Για να μετατρέψετε SVG σε PDF, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα PDF με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) που μετατρέπει SVG σε PDF με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Ορίστε το προεπιλεγμένο αντικείμενο PdfSaveOptions
      var options = new PdfSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, PdfSaveOptions, String) {#convertsvg_29}

Μετατρέψτε την πηγή SVG που παρέχεται με πλήρη διαδρομή αρχείου σε PDF. Το αποτέλεσμα είναι αρχείο pdf που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής SVG. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| options | PdfSaveOptions | Η χρήση του αντικειμένου [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου pdf ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε PDF χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε PDF

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε PDF. Για να μετατρέψετε SVG σε PDF, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα PDF με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) που μετατρέπει SVG σε PDF με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Ορίστε το προεπιλεγμένο αντικείμενο PdfSaveOptions
      var options = new PdfSaveOptions();

      // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, PdfSaveOptions, String) {#convertsvg_53}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από ενσωματωμένο περιεχόμενο σε PDF. Το αποτέλεσμα είναι αρχείο pdf που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | String | String ως ενσωματωμένο περιεχόμενο SVG. |
| baseUri | String | Η βασική URI του εγγράφου. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει μια απόλυτη URL. |
| options | PdfSaveOptions | Η χρήση του αντικειμένου [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου pdf ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε PDF χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε PDF

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε PDF. Για να μετατρέψετε SVG σε PDF, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα PDF με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) που μετατρέπει SVG σε PDF με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργία ενσωματωμένου περιεχομένου SVG
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Ορίστε το προεπιλεγμένο αντικείμενο PdfSaveOptions
      var options = new PdfSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, String) {#convertsvg_45}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από ενσωματωμένο περιεχόμενο σε PDF. Το αποτέλεσμα είναι αρχείο pdf που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | String | String ως ενσωματωμένο περιεχόμενο SVG. |
| baseUri | String | Η βασική URI του εγγράφου. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει μια απόλυτη URL. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| options | PdfSaveOptions | Η χρήση του αντικειμένου [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου pdf ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε PDF χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε PDF

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε PDF. Για να μετατρέψετε SVG σε PDF, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα PDF με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) που μετατρέπει SVG σε PDF με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργία ενσωματωμένου περιεχομένου SVG
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Ορίστε το προεπιλεγμένο αντικείμενο PdfSaveOptions
      var options = new PdfSaveOptions();

      // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_4}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) σε PDF. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(SVGDocument document, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| document | SVGDocument | Πηγή μετατροπής που παρουσιάζεται από [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | PdfSaveOptions | Η χρήση του αντικειμένου [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Γνωστή (δείτε [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε PDF χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε PDF

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε PDF. Για να μετατρέψετε SVG σε PDF, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα PDF με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) που μετατρέπει SVG σε PDF με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο PdfSaveOptions
      var options = new PdfSaveOptions();

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Δημιουργήστε το έγγραφο SVG ως πηγή μετατροπής
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_20}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από [`URL`](../../../com.aspose.html/url/). Το αποτέλεσμα είναι τα δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| url | Url | Έγγραφο πηγής SVG [`URL`](../../../com.aspose.html/url/) - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| options | PdfSaveOptions | Η χρήση του αντικειμένου [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Γνωστή (δείτε [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε PDF χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε PDF

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε PDF. Για να μετατρέψετε SVG σε PDF, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα PDF με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) που μετατρέπει SVG σε PDF με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργήστε Url βάσει της διαδρομής εισόδου αρχείου
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο PdfSaveOptions
      var options = new PdfSaveOptions();

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertSVG(sourceUrl, options, sp);
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

## ConvertSVG(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_12}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από [`URL`](../../../com.aspose.html/url/). Το αποτέλεσμα είναι τα δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| url | Url | Έγγραφο πηγής SVG [`URL`](../../../com.aspose.html/url/) - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| options | PdfSaveOptions | Η χρήση του αντικειμένου [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Γνωστή (δείτε [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε PDF χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε PDF

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε PDF. Για να μετατρέψετε SVG σε PDF, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα PDF με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) που μετατρέπει SVG σε PDF με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργήστε Url βάσει της διαδρομής εισόδου αρχείου
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο PdfSaveOptions
      var options = new PdfSaveOptions();

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

## ConvertSVG(String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_36}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από πλήρη διαδρομή αρχείου σε PDF. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής SVG. |
| options | PdfSaveOptions | Η χρήση του αντικειμένου [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση της [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την απόκτηση ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε PDF χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε PDF

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε PDF. Για να μετατρέψετε SVG σε PDF, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα PDF με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) που μετατρέπει SVG σε PDF με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο PdfSaveOptions
      var options = new PdfSaveOptions();

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_28}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από πλήρη διαδρομή αρχείου σε PDF. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής SVG. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| options | PdfSaveOptions | Η χρήση του αντικειμένου [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση της [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την απόκτηση ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε PDF χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε PDF

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε PDF. Για να μετατρέψετε SVG σε PDF, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα PDF με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) που μετατρέπει SVG σε PDF με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο PdfSaveOptions
      var options = new PdfSaveOptions();

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_52}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από ενσωματωμένο περιεχόμενο σε PDF. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | String | String ως ενσωματωμένο περιεχόμενο SVG. |
| baseUri | String | Η βασική URI του εγγράφου. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει μια απόλυτη URL. |
| options | PdfSaveOptions | Η χρήση του αντικειμένου [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση της [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την απόκτηση ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε PDF χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε PDF

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε PDF. Για να μετατρέψετε SVG σε PDF, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα PDF με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) που μετατρέπει SVG σε PDF με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ορίστε το προεπιλεγμένο αντικείμενο PdfSaveOptions
      var options = new PdfSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_44}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από ενσωματωμένο περιεχόμενο σε PDF. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | String | String ως ενσωματωμένο περιεχόμενο SVG. |
| baseUri | String | Η βασική URI του εγγράφου. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει μια απόλυτη URL. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| options | PdfSaveOptions | Η χρήση του αντικειμένου [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες, δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Γνωστή (δείτε [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) όπου θα βρείτε πληροφορίες σχετικά με το πώς να μετατρέψετε SVG σε PDF χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε PDF

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε PDF. Για να μετατρέψετε SVG σε PDF, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα PDF με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Το Aspose.HTML προσφέρει έναν δωρεάν online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) που μετατρέπει SVG σε PDF με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ορίστε το προεπιλεγμένο αντικείμενο PdfSaveOptions
      var options = new PdfSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, ImageSaveOptions, String) {#convertsvg_3}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Το αποτέλεσμα είναι αρχείο εικόνας που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(SVGDocument source, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| source | SVGDocument | Πηγή μετατροπής που παρουσιάζεται από [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | ImageSaveOptions | Η χρήση του αντικειμένου [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| outputPath | String | Πλήρης διαδρομή αρχείου εικόνας ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε JPG χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Άλλα δημοφιλή άρθρα σχετικά με μορφές εικόνας: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) και [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Μετατροπή SVG σε εικόνα

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε εικόνα σε δημοφιλείς μορφές. Για να μετατρέψετε SVG σε εικόνα, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Σημειώστε ότι η προεπιλεγμένη μορφή εικόνας είναι PNG. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα εικόνας με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online SVG converter

Το Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) που μετατρέπει SVG σε JPG με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Άλλοι δημοφιλείς μετατροπείς εικόνας για διαφορετικές μορφές μπορείτε να τους βρείτε εδώ: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) και [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο ImageSaveOptions
      var options = new ImageSaveOptions();

      // Δημιουργήστε το έγγραφο SVG ως πηγή μετατροπής
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, String) {#convertsvg_19}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από [`URL`](../../../com.aspose.html/url/). Το αποτέλεσμα είναι αρχείο εικόνας που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| url | Url | Έγγραφο πηγής SVG [`URL`](../../../com.aspose.html/url/) - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| options | ImageSaveOptions | Η χρήση του αντικειμένου [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| outputPath | String | Πλήρης διαδρομή αρχείου εικόνας ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε JPG χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Άλλα δημοφιλή άρθρα σχετικά με μορφές εικόνας: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) και [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Μετατροπή SVG σε εικόνα

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε εικόνα σε δημοφιλείς μορφές. Για να μετατρέψετε SVG σε εικόνα, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Σημειώστε ότι η προεπιλεγμένη μορφή εικόνας είναι PNG. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα εικόνας με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online SVG converter

Το Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) που μετατρέπει SVG σε JPG με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Άλλοι δημοφιλείς μετατροπείς εικόνας για διαφορετικές μορφές μπορείτε να τους βρείτε εδώ: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) και [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργήστε Url βάσει της διαδρομής εισόδου αρχείου
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Ορίστε το προεπιλεγμένο αντικείμενο ImageSaveOptions
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, ImageSaveOptions, String) {#convertsvg_11}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από [`URL`](../../../com.aspose.html/url/). Το αποτέλεσμα είναι αρχείο εικόνας που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| url | Url | Έγγραφο πηγής SVG [`URL`](../../../com.aspose.html/url/) - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| outputPath | String | Πλήρης διαδρομή αρχείου εικόνας ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε JPG χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Άλλα δημοφιλή άρθρα σχετικά με μορφές εικόνας: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) και [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Μετατροπή SVG σε εικόνα

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε εικόνα σε δημοφιλείς μορφές. Για να μετατρέψετε SVG σε εικόνα, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Σημειώστε ότι η προεπιλεγμένη μορφή εικόνας είναι PNG. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα εικόνας με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online SVG converter

Το Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) που μετατρέπει SVG σε JPG με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Άλλοι δημοφιλείς μετατροπείς εικόνας για διαφορετικές μορφές μπορείτε να τους βρείτε εδώ: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) και [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργήστε Url βάσει της διαδρομής εισόδου αρχείου
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Ορίστε το προεπιλεγμένο αντικείμενο ImageSaveOptions
      var options = new ImageSaveOptions();

      // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertSVG(String, ImageSaveOptions, String) {#convertsvg_35}

Μετατρέψτε την πηγή SVG που παρέχεται με πλήρη διαδρομή αρχείου σε εικόνα. Το αποτέλεσμα είναι αρχείο εικόνας που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής SVG. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| outputPath | String | Πλήρης διαδρομή αρχείου εικόνας ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε JPG χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Άλλα δημοφιλή άρθρα σχετικά με μορφές εικόνας: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) και [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Μετατροπή SVG σε εικόνα

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε εικόνα σε δημοφιλείς μορφές. Για να μετατρέψετε SVG σε εικόνα, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Σημειώστε ότι η προεπιλεγμένη μορφή εικόνας είναι PNG. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα εικόνας με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online SVG converter

Το Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) που μετατρέπει SVG σε JPG με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Άλλοι δημοφιλείς μετατροπείς εικόνας για διαφορετικές μορφές μπορείτε να τους βρείτε εδώ: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) και [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Ορίστε το προεπιλεγμένο αντικείμενο ImageSaveOptions
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, ImageSaveOptions, String) {#convertsvg_27}

Μετατρέψτε την πηγή SVG που παρέχεται με πλήρη διαδρομή αρχείου σε εικόνα. Το αποτέλεσμα είναι αρχείο εικόνας που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής SVG. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| outputPath | String | Πλήρης διαδρομή αρχείου εικόνας ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε JPG χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Άλλα δημοφιλή άρθρα σχετικά με μορφές εικόνας: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) και [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Μετατροπή SVG σε εικόνα

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε εικόνα σε δημοφιλείς μορφές. Για να μετατρέψετε SVG σε εικόνα, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Σημειώστε ότι η προεπιλεγμένη μορφή εικόνας είναι PNG. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα εικόνας με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online SVG converter

Το Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) που μετατρέπει SVG σε JPG με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Άλλοι δημοφιλείς μετατροπείς εικόνας για διαφορετικές μορφές μπορείτε να τους βρείτε εδώ: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) και [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Ορίστε το προεπιλεγμένο αντικείμενο ImageSaveOptions
      var options = new ImageSaveOptions();

      // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, ImageSaveOptions, String) {#convertsvg_51}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από ενσωματωμένο περιεχόμενο σε εικόνα. Το αποτέλεσμα είναι αρχείο εικόνας που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | String | String ως ενσωματωμένο περιεχόμενο SVG. |
| baseUri | String | Η βασική URI του εγγράφου. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει μια απόλυτη URL. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| outputPath | String | Πλήρης διαδρομή αρχείου εικόνας ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε JPG χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Άλλα δημοφιλή άρθρα σχετικά με μορφές εικόνας: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) και [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Μετατροπή SVG σε εικόνα

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε εικόνα σε δημοφιλείς μορφές. Για να μετατρέψετε SVG σε εικόνα, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Σημειώστε ότι η προεπιλεγμένη μορφή εικόνας είναι PNG. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα εικόνας με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online SVG converter

Το Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) που μετατρέπει SVG σε JPG με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Άλλοι δημοφιλείς μετατροπείς εικόνας για διαφορετικές μορφές μπορείτε να τους βρείτε εδώ: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) και [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργία ενσωματωμένου περιεχομένου SVG
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Ορίστε το προεπιλεγμένο αντικείμενο ImageSaveOptions
      var options = new ImageSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, String) {#convertsvg_43}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από ενσωματωμένο περιεχόμενο σε εικόνα. Το αποτέλεσμα είναι αρχείο εικόνας που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | String | String ως ενσωματωμένο περιεχόμενο SVG. |
| baseUri | String | Η βασική URI του εγγράφου. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει μια απόλυτη URL. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| outputPath | String | Πλήρης διαδρομή αρχείου εικόνας ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε JPG χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Άλλα δημοφιλή άρθρα σχετικά με μορφές εικόνας: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) και [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Μετατροπή SVG σε εικόνα

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε εικόνα σε δημοφιλείς μορφές. Για να μετατρέψετε SVG σε εικόνα, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Σημειώστε ότι η προεπιλεγμένη μορφή εικόνας είναι PNG. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα εικόνας με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online SVG converter

Το Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) που μετατρέπει SVG σε JPG με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Άλλοι δημοφιλείς μετατροπείς εικόνας για διαφορετικές μορφές μπορείτε να τους βρείτε εδώ: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) και [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργία ενσωματωμένου περιεχομένου SVG
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Ορίστε το προεπιλεγμένο αντικείμενο ImageSaveOptions
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_2}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Το αποτέλεσμα είναι τα δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(SVGDocument document, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| document | SVGDocument | Πηγή μετατροπής που παρουσιάζεται από [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | ImageSaveOptions | Η χρήση του αντικειμένου [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| provider | ICreateStreamProvider | Γνωστή (δείτε [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε JPG χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Άλλα δημοφιλή άρθρα σχετικά με μορφές εικόνας: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) και [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Μετατροπή SVG σε εικόνα

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε εικόνα σε δημοφιλείς μορφές. Για να μετατρέψετε SVG σε εικόνα, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Σημειώστε ότι η προεπιλεγμένη μορφή εικόνας είναι PNG. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα εικόνας με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online SVG converter

Το Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) που μετατρέπει SVG σε JPG με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Άλλοι δημοφιλείς μετατροπείς εικόνας για διαφορετικές μορφές μπορείτε να τους βρείτε εδώ: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) και [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο ImageSaveOptions
      var options = new ImageSaveOptions();

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Δημιουργήστε το έγγραφο SVG ως πηγή μετατροπής
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Ξεκινήστε τη διαδικασία μετατροπής
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_18}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από [`URL`](../../../com.aspose.html/url/). Το αποτέλεσμα είναι τα δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| url | Url | Έγγραφο πηγής SVG [`URL`](../../../com.aspose.html/url/) - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| options | ImageSaveOptions | Η χρήση του αντικειμένου [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| provider | ICreateStreamProvider | Υλοποίηση της [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την απόκτηση ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε JPG χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Άλλα δημοφιλή άρθρα σχετικά με μορφές εικόνας: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) και [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Μετατροπή SVG σε εικόνα

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε εικόνα σε δημοφιλείς μορφές. Για να μετατρέψετε SVG σε εικόνα, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Σημειώστε ότι η προεπιλεγμένη μορφή εικόνας είναι PNG. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα εικόνας με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online SVG converter

Το Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) που μετατρέπει SVG σε JPG με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Άλλοι δημοφιλείς μετατροπείς εικόνας για διαφορετικές μορφές μπορείτε να τους βρείτε εδώ: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) και [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργήστε Url βάσει της διαδρομής εισόδου αρχείου
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο ImageSaveOptions
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertSVG(sourceUrl, options, sp);
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

## ConvertSVG(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_10}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από [`URL`](../../../com.aspose.html/url/). Το αποτέλεσμα είναι τα δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| url | Url | Έγγραφο πηγής SVG [`URL`](../../../com.aspose.html/url/) - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| provider | ICreateStreamProvider | Υλοποίηση της [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την απόκτηση ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε JPG χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Άλλα δημοφιλή άρθρα σχετικά με μορφές εικόνας: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) και [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Μετατροπή SVG σε εικόνα

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε εικόνα σε δημοφιλείς μορφές. Για να μετατρέψετε SVG σε εικόνα, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Σημειώστε ότι η προεπιλεγμένη μορφή εικόνας είναι PNG. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα εικόνας με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online SVG converter

Το Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) που μετατρέπει SVG σε JPG με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Άλλοι δημοφιλείς μετατροπείς εικόνας για διαφορετικές μορφές μπορείτε να τους βρείτε εδώ: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) και [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργήστε Url βάσει της διαδρομής εισόδου αρχείου
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο ImageSaveOptions
      var options = new ImageSaveOptions();

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

---

## ConvertSVG(String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_34}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από πλήρη διαδρομή αρχείου σε εικόνα. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής SVG. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| provider | ICreateStreamProvider | Υλοποίηση της [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την απόκτηση ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε JPG χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Άλλα δημοφιλή άρθρα σχετικά με μορφές εικόνας: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) και [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Μετατροπή SVG σε εικόνα

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε εικόνα σε δημοφιλείς μορφές. Για να μετατρέψετε SVG σε εικόνα, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Σημειώστε ότι η προεπιλεγμένη μορφή εικόνας είναι PNG. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα εικόνας με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online SVG converter

Το Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) που μετατρέπει SVG σε JPG με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Άλλοι δημοφιλείς μετατροπείς εικόνας για διαφορετικές μορφές μπορείτε να τους βρείτε εδώ: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) και [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο ImageSaveOptions
      var options = new ImageSaveOptions();

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_26}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από πλήρη διαδρομή αρχείου σε εικόνα. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής SVG. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| provider | ICreateStreamProvider | Γνωστή (δείτε [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε JPG χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Άλλα δημοφιλή άρθρα σχετικά με μορφές εικόνας: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) και [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Μετατροπή SVG σε εικόνα

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε εικόνα σε δημοφιλείς μορφές. Για να μετατρέψετε SVG σε εικόνα, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Σημειώστε ότι η προεπιλεγμένη μορφή εικόνας είναι PNG. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα εικόνας με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online SVG converter

Το Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) που μετατρέπει SVG σε JPG με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Άλλοι δημοφιλείς μετατροπείς εικόνας για διαφορετικές μορφές μπορείτε να τους βρείτε εδώ: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) και [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο ImageSaveOptions
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_50}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από ενσωματωμένο περιεχόμενο σε εικόνα. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | String | String ως ενσωματωμένο περιεχόμενο SVG. |
| baseUri | String | Η βασική URI του εγγράφου. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει μια απόλυτη URL. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| provider | ICreateStreamProvider | Γνωστή (δείτε [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε JPG χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Άλλα δημοφιλή άρθρα σχετικά με μορφές εικόνας: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) και [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Μετατροπή SVG σε εικόνα

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε εικόνα σε δημοφιλείς μορφές. Για να μετατρέψετε SVG σε εικόνα, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Σημειώστε ότι η προεπιλεγμένη μορφή εικόνας είναι PNG. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα εικόνας με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online SVG converter

Το Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) που μετατρέπει SVG σε JPG με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Άλλοι δημοφιλείς μετατροπείς εικόνας για διαφορετικές μορφές μπορείτε να τους βρείτε εδώ: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) και [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ορίστε το προεπιλεγμένο αντικείμενο ImageSaveOptions
      var options = new ImageSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_42}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από ενσωματωμένο περιεχόμενο σε εικόνα. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | String | String ως ενσωματωμένο περιεχόμενο SVG. |
| baseUri | String | Η βασική URI του εγγράφου. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει μια απόλυτη URL. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| provider | ICreateStreamProvider | Υλοποίηση της [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για την απόκτηση ροής εξόδου. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε JPG χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Άλλα δημοφιλή άρθρα σχετικά με μορφές εικόνας: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) και [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Μετατροπή SVG σε εικόνα

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε εικόνα σε δημοφιλείς μορφές. Για να μετατρέψετε SVG σε εικόνα, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Σημειώστε ότι η προεπιλεγμένη μορφή εικόνας είναι PNG. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα εικόνας με τρία ή περισσότερα παραμέτρους, ανάλογα με το σενάριο χρήστη. Online SVG converter

Το Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) που μετατρέπει SVG σε JPG με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Άλλοι δημοφιλείς μετατροπείς εικόνας για διαφορετικές μορφές μπορείτε να τους βρείτε εδώ: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) και [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Χρησιμοποιήστε μία από τις υλοποιήσεις του ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Ορίστε το προεπιλεγμένο αντικείμενο ImageSaveOptions
      var options = new ImageSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, XpsSaveOptions, String) {#convertsvg_7}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Το αποτέλεσμα είναι αρχείο xps που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(SVGDocument source, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| source | SVGDocument | Πηγή μετατροπής που παρουσιάζεται από [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) χρήση του αντικειμένου σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου xps ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε XPS χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε XPS

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε XPS. Για να μετατρέψετε SVG σε XPS, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα XPS με τρία ή περισσότερα παραμέτρους ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Η Aspose.HTML προσφέρει έναν δωρεάν online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) που μετατρέπει SVG σε XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result");

      // Ορίστε το προεπιλεγμένο αντικείμενο XpsSaveOptions
      var options = new XpsSaveOptions();

      // Δημιουργήστε το έγγραφο SVG ως πηγή μετατροπής
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
		// Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
		Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, String) {#convertsvg_23}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από [`URL`](../../../com.aspose.html/url/). Το αποτέλεσμα είναι αρχείο xps που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| url | Url | Έγγραφο πηγής SVG [`URL`](../../../com.aspose.html/url/) - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) χρήση του αντικειμένου σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου xps ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε XPS χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε XPS

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε XPS. Για να μετατρέψετε SVG σε XPS, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα XPS με τρία ή περισσότερα παραμέτρους ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Η Aspose.HTML προσφέρει έναν δωρεάν online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) που μετατρέπει SVG σε XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργήστε Url βασισμένο στη διαδρομή εισόδου αρχείου
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Ορίστε το προεπιλεγμένο αντικείμενο XpsSaveOptions
      var options = new XpsSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, XpsSaveOptions, String) {#convertsvg_15}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από [`URL`](../../../com.aspose.html/url/). Το αποτέλεσμα είναι αρχείο xps που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| url | Url | Έγγραφο πηγής SVG [`URL`](../../../com.aspose.html/url/) - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) χρήση του αντικειμένου σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου xps ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε XPS χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε XPS

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε XPS. Για να μετατρέψετε SVG σε XPS, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα XPS με τρία ή περισσότερα παραμέτρους ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Η Aspose.HTML προσφέρει έναν δωρεάν online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) που μετατρέπει SVG σε XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Δημιουργήστε Url βάσει της διαδρομής εισόδου αρχείου
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Ορίστε το προεπιλεγμένο αντικείμενο XpsSaveOptions
      var options = new XpsSaveOptions();

      // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, XpsSaveOptions, String) {#convertsvg_39}

Μετατρέψτε την πηγή SVG που παρέχεται με πλήρη διαδρομή αρχείου σε XPS. Το αποτέλεσμα είναι αρχείο xps που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής SVG. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) η χρήση του αντικειμένου σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. |
| outputPath | String | Πλήρης διαδρομή αρχείου xps ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε XPS χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε XPS

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε XPS. Για να μετατρέψετε SVG σε XPS, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα XPS με τρία ή περισσότερα παραμέτρους ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Η Aspose.HTML προσφέρει έναν δωρεάν online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) που μετατρέπει SVG σε XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Ορίστε το προεπιλεγμένο αντικείμενο XpsSaveOptions
      var options = new XpsSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, XpsSaveOptions, String) {#convertsvg_31}

Μετατρέψτε την πηγή SVG που παρέχεται με πλήρη διαδρομή αρχείου σε XPS. Το αποτέλεσμα είναι αρχείο xps που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πλήρης διαδρομή αρχείου πηγής SVG. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) χρήση του αντικειμένου σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου xps ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε XPS χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε XPS

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε XPS. Για να μετατρέψετε SVG σε XPS, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα XPS με τρία ή περισσότερα παραμέτρους ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Η Aspose.HTML προσφέρει έναν δωρεάν online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) που μετατρέπει SVG σε XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Διαδρομή αρχείου πηγής φόρμας
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Ορίστε το προεπιλεγμένο αντικείμενο XpsSaveOptions
      var options = new XpsSaveOptions();

      // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, XpsSaveOptions, String) {#convertsvg_55}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από ενσωματωμένο περιεχόμενο σε XPS. Το αποτέλεσμα είναι αρχείο xps που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | String | String ως ενσωματωμένο περιεχόμενο SVG. |
| baseUri | String | Η βασική URI του εγγράφου. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει μια απόλυτη URL. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) η χρήση του αντικειμένου σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. |
| outputPath | String | Πλήρης διαδρομή αρχείου xps ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε XPS χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε XPS

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε XPS. Για να μετατρέψετε SVG σε XPS, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα XPS με τρία ή περισσότερα παραμέτρους ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Η Aspose.HTML προσφέρει έναν δωρεάν online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) που μετατρέπει SVG σε XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Δημιουργία ενσωματωμένου περιεχομένου SVG
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Ορίστε το προεπιλεγμένο αντικείμενο XpsSaveOptions
      var options = new XpsSaveOptions();

      // Ξεκινήστε τη διαδικασία μετατροπής
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, String) {#convertsvg_47}

Μετατρέψτε την πηγή SVG που παρουσιάζεται από ενσωματωμένο περιεχόμενο σε XPS. Το αποτέλεσμα είναι αρχείο xps που δημιουργείται από τη διαδρομή εξόδου.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | String | String ως ενσωματωμένο περιεχόμενο SVG. |
| baseUri | String | Η βασική URI του εγγράφου. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει μια απόλυτη URL. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων περιβάλλοντος για την εφαρμογή. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) χρήση του αντικειμένου σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου xps ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Μετατροπέας SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Ανατρέξτε στο [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) όπου θα βρείτε πληροφορίες για το πώς να μετατρέψετε SVG σε XPS χρησιμοποιώντας τις μεθόδους ConvertSVG() της κλάσης [`Converter`](../) και πώς να εφαρμόσετε τις παραμέτρους [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) και [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Μετατροπή SVG σε XPS

Η κλάση Converter προσφέρει πολλαπλές ειδικές μετατροπές SVG σε XPS. Για να μετατρέψετε SVG σε XPS, θα πρέπει να ακολουθήσετε ένα από τα απλά σενάρια που αποτελείται από λίγα βήματα:

Πηγή μετατροπής. Εντοπίστε ένα υπάρχον τοπικό αρχείο SVG ή απομακρυσμένο [`Url`](../../../com.aspose.html/url/) ως πηγή μετατροπής. Μπορείτε επίσης να ορίσετε το [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ως πηγή μετατροπής ή ακόμη και να χρησιμοποιήσετε ενσωματωμένο περιεχόμενο SVG που παρουσιάζεται από πηγή String. Αποτέλεσμα μετατροπής. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος ή χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) με συγκεκριμένες ή προεπιλεγμένες ρυθμίσεις. Μπορείτε επίσης να προσθέσετε το [`configuration`](../../../com.aspose.html/configuration/) ως παράμετρο επιλογής. Χρησιμοποιήστε τη μέθοδο ConvertSVG() της κλάσης Converter για να αποθηκεύσετε το SVG ως αποτέλεσμα XPS με τρία ή περισσότερα παραμέτρους ανάλογα με το σενάριο χρήστη. Online μετατροπέας SVG

Η Aspose.HTML προσφέρει έναν δωρεάν online [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) που μετατρέπει SVG σε XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Δημιουργία ενσωματωμένου περιεχομένου SVG
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Διαδρομή αρχείου αποτελέσματος φόρμας
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Ορίστε το προεπιλεγμένο αντικείμενο XpsSaveOptions
      var options = new XpsSaveOptions();

      // Ξεκινήτε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
