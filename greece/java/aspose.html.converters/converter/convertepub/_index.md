---
title: "Converter.ConvertEPUB"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Converter. Μετατρέψτε την πηγή EPUB που παρουσιάζεται με ροή εισόδου δεδομένων. Το αποτέλεσμα είναι το αρχείο που δημιουργείται με τη διαδρομή εξόδου."
type: docs

url: /el/java/com.aspose.html.converters/converter/convertepub/
---
## ConvertEPUB(Stream, ImageSaveOptions, String) {#convertepub_27}

Μετατρέψτε την πηγή EPUB που παρέχεται με ροή δεδομένων εισόδου. Το αποτέλεσμα είναι αρχείο που δημιουργείται με τη διαδρομή εξόδου.

```java
public static void ConvertEPUB(Stream stream, ImageSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή εισόδου ως πηγή μετατροπής. |
| options | ImageSaveOptions | Νέες δημιουργημένες επιλογές εικόνας όπως μορφή, ανάλυση κ.λπ. Δείτε την κλάση [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου εικόνας ως αποτέλεσμα της μετατροπής. |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε Εικόνα

Το EPUB είναι μια μορφή αρχείου ηλεκτρονικού βιβλίου που παρέχει ένα τυπικό ψηφιακό μορφότυπο δημοσίευσης. Δημιουργήθηκε από το International Digital Publishing Forum (IDPF) και τώρα υποστηρίζεται από πολλούς αναγνώστες e-book και λογισμικές εφαρμογές.

Η μετατροπή αρχείων EPUB σε μορφή PNG μπορεί να είναι χρήσιμη εάν χρειάζεται να ενσωματώσετε αρχεία σε παρουσίαση PowerPoint ή να τα στείλετε μέσω email. Παρακαλούμε μετατρέψτε τα σε μορφή εικόνας και χρησιμοποιήστε τα όπως θέλετε! Μπορείτε να χρησιμοποιήσετε πρόσθετες παραμέτρους μετατροπής για την επίτευξη του επιθυμητού αποτελέσματος.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση Converter που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετες και εύχρηστες. Στον οδηγό EPUB Converter, θα βρείτε τα παρακάτω άρθρα:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Μετατροπή EPUB σε Εικόνα

Για να μετατρέψετε το EPUB σε μορφή αρχείου εικόνας, πρέπει να ακολουθήσετε μερικά βήματα:

Ορίστε το Url με βάση το υπάρχον αρχείο EPUB στην καθορισμένη διαδρομή. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με το απαιτούμενο ImageFormat. Από προεπιλογή, η ιδιότητα Format είναι PNG. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της κλάσης Converter για να αποθηκεύσετε το EPUB ως εικόνα. Πρέπει επίσης να περάσετε το αντικείμενο ImageSaveOptions και το αντικείμενο Configuration στη μετατροπή εικόνας. Online EPUB converters

Το Aspose.HTML προσφέρει έναν δωρεάν online [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter που μετατρέπει το EPUB σε εικόνα PNG με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Μπορεί επίσης να σας ενδιαφέρει η μετατροπή συγκεκριμένης μορφής εικόνας

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Ανοίξτε το υπάρχον αρχείο για ανάγνωση ως ροή
var inputStream = System.IO.File.OpenRead(Path.Combine(InputFolder, "sample.epub"));

// Ορίστε τη διαδρομή εξόδου του αρχείου
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Δημιουργήστε προεπιλεγμένο αντικείμενο επιλογών
var options = new ImageSaveOptions();

// Ξεκινήστε τη διαδικασία μετατροπής
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, ImageSaveOptions, String) {#convertepub_43}

Μετατρέψτε την πηγή EPUB που παρουσιάζεται με πλήρη διαδρομή αρχείου. Το αποτέλεσμα είναι αρχείο εικόνας που δημιουργείται από τη διαδρομή αρχείου εξόδου. Η μορφή εικόνας καθορίζεται από το αντικείμενο ImageSaveOptions.

```java
public static void ConvertEPUB(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Διαδρομή αρχείου πηγής EPUB ως παράμετρο εισόδου. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου ImageSaveOptions σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| outputPath | String | Πλήρης διαδρομή αρχείου εικόνας ως αποτέλεσμα της μετατροπής. |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε Εικόνα

Το EPUB είναι μια μορφή αρχείου ηλεκτρονικού βιβλίου που παρέχει ένα τυπικό ψηφιακό μορφότυπο δημοσίευσης. Δημιουργήθηκε από το International Digital Publishing Forum (IDPF) και τώρα υποστηρίζεται από πολλούς αναγνώστες e-book και λογισμικές εφαρμογές.

Η μετατροπή αρχείων EPUB σε μορφή PNG μπορεί να είναι χρήσιμη εάν χρειάζεται να ενσωματώσετε αρχεία σε παρουσίαση PowerPoint ή να τα στείλετε μέσω email. Παρακαλούμε μετατρέψτε τα σε μορφή εικόνας και χρησιμοποιήστε τα όπως θέλετε! Μπορείτε να χρησιμοποιήσετε πρόσθετες παραμέτρους μετατροπής για την επίτευξη του επιθυμητού αποτελέσματος.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση Converter που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετες και εύχρηστες. Στον οδηγό EPUB Converter, θα βρείτε τα παρακάτω άρθρα:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Μετατροπή EPUB σε Εικόνα

Για να μετατρέψετε το EPUB σε μορφή αρχείου εικόνας, πρέπει να ακολουθήσετε μερικά βήματα:

Ορίστε το Url με βάση το υπάρχον αρχείο EPUB στην καθορισμένη διαδρομή. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με το απαιτούμενο ImageFormat. Από προεπιλογή, η ιδιότητα Format είναι PNG. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της κλάσης Converter για να αποθηκεύσετε το EPUB ως εικόνα. Πρέπει επίσης να περάσετε το αντικείμενο ImageSaveOptions και το αντικείμενο Configuration στη μετατροπή εικόνας. Online EPUB converters

Το Aspose.HTML προσφέρει έναν δωρεάν online [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter που μετατρέπει το EPUB σε εικόνα PNG με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Μπορεί επίσης να σας ενδιαφέρει η μετατροπή συγκεκριμένης μορφής εικόνας

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Διαδρομή αρχείου πηγής φόρμας
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Διαμορφώστε τη διαδρομή εξόδου του αποτελέσματος
var resultPath = Path.Combine(OutputFolder, "sample.png"); 

// Δημιουργήστε προεπιλεγμένο αντικείμενο ImageSaveOptions
var options = new ImageSaveOptions(); 

// Ξεκινήστε τη διαδικασία μετατροπής
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - custom output folder path.

### Δείτε επίσης

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, ImageSaveOptions, String) {#convertepub_11}

Μετατρέψτε την πηγή EPUB που ορίζεται από URL. Το αποτέλεσμα είναι αρχείο εικόνας που δημιουργείται από τη διαδρομή αρχείου εξόδου. Η μορφή εικόνας καθορίζεται από το αντικείμενο ImageSaveOptions.

```java
public static void ConvertEPUB(Url sourceUrl, ImageSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL πηγής EPUB - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| options | ImageSaveOptions | Η χρήση του αντικειμένου ImageSaveOptions σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. Δείτε την κλάση [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/)class. |
| outputPath | String | Πλήρης διαδρομή αρχείου εικόνας ως αποτέλεσμα της μετατροπής. |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε Εικόνα

Το EPUB είναι μια μορφή αρχείου ηλεκτρονικού βιβλίου που παρέχει ένα τυπικό ψηφιακό μορφότυπο δημοσίευσης. Δημιουργήθηκε από το International Digital Publishing Forum (IDPF) και τώρα υποστηρίζεται από πολλούς αναγνώστες e-book και λογισμικές εφαρμογές.

Η μετατροπή αρχείων EPUB σε μορφή PNG μπορεί να είναι χρήσιμη εάν χρειάζεται να ενσωματώσετε αρχεία σε παρουσίαση PowerPoint ή να τα στείλετε μέσω email. Παρακαλούμε μετατρέψτε τα σε μορφή εικόνας και χρησιμοποιήστε τα όπως θέλετε! Μπορείτε να χρησιμοποιήσετε πρόσθετες παραμέτρους μετατροπής για την επίτευξη του επιθυμητού αποτελέσματος.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση Converter που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετες και εύχρηστες. Στον οδηγό EPUB Converter, θα βρείτε τα παρακάτω άρθρα:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Μετατροπή EPUB σε Εικόνα

Για να μετατρέψετε το EPUB σε μορφή αρχείου εικόνας, πρέπει να ακολουθήσετε μερικά βήματα:

Ορίστε το Url με βάση το υπάρχον αρχείο EPUB στην καθορισμένη διαδρομή. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με το απαιτούμενο ImageFormat. Από προεπιλογή, η ιδιότητα Format είναι PNG. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της κλάσης Converter για να αποθηκεύσετε το EPUB ως εικόνα. Πρέπει επίσης να περάσετε το αντικείμενο ImageSaveOptions και το αντικείμενο Configuration στη μετατροπή εικόνας. Online EPUB converters

Το Aspose.HTML προσφέρει έναν δωρεάν online [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter που μετατρέπει το EPUB σε εικόνα PNG με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Μπορεί επίσης να σας ενδιαφέρει η μετατροπή συγκεκριμένης μορφής εικόνας

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Δημιουργήστε Url βάσει διαδρομής αρχείου εισόδου
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Διαμορφώστε τη διαδρομή εξόδου του αποτελέσματος
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Δημιουργήστε προεπιλεγμένο αντικείμενο επιλογών
var options = new ImageSaveOptions();

// Ξεκινήστε τη διαδικασία μετατροπής
Converter.ConvertEPUB(sourceUrl, options, resultPath);
```

*InputFolder - user input folder path.

*OutputFolder - user output folder.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, ImageSaveOptions, String) {#convertepub_19}

Μετατρέψτε την πηγή EPUB που παρουσιάζεται από ροή δεδομένων εισόδου. Το αποτέλεσμα είναι αρχείο εικόνας που δημιουργείται από τη διαδρομή αρχείου εξόδου. Η μορφή εικόνας καθορίζεται από το αντικείμενο ImageSaveOptions.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή εισόδου ως πηγή μετατροπής. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου ImageSaveOptions σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| outputPath | String | Πλήρης διαδρομή αρχείου εικόνας ως αποτέλεσμα της μετατροπής. |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε Εικόνα

Το EPUB είναι μια μορφή αρχείου ηλεκτρονικού βιβλίου που παρέχει ένα τυπικό ψηφιακό μορφότυπο δημοσίευσης. Δημιουργήθηκε από το International Digital Publishing Forum (IDPF) και τώρα υποστηρίζεται από πολλούς αναγνώστες e-book και λογισμικές εφαρμογές.

Η μετατροπή αρχείων EPUB σε μορφή PNG μπορεί να είναι χρήσιμη εάν χρειάζεται να ενσωματώσετε αρχεία σε παρουσίαση PowerPoint ή να τα στείλετε μέσω email. Παρακαλούμε μετατρέψτε τα σε μορφή εικόνας και χρησιμοποιήστε τα όπως θέλετε! Μπορείτε να χρησιμοποιήσετε πρόσθετες παραμέτρους μετατροπής για την επίτευξη του επιθυμητού αποτελέσματος.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση Converter που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετες και εύχρηστες. Στον οδηγό EPUB Converter, θα βρείτε τα παρακάτω άρθρα:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Μετατροπή EPUB σε Εικόνα

Για να μετατρέψετε το EPUB σε μορφή αρχείου εικόνας, πρέπει να ακολουθήσετε μερικά βήματα:

Ορίστε το Url με βάση το υπάρχον αρχείο EPUB στην καθορισμένη διαδρομή. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με το απαιτούμενο ImageFormat. Από προεπιλογή, η ιδιότητα Format είναι PNG. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της κλάσης Converter για να αποθηκεύσετε το EPUB ως εικόνα. Πρέπει επίσης να περάσετε το αντικείμενο ImageSaveOptions και το αντικείμενο Configuration στη μετατροπή εικόνας. Online EPUB converters

Το Aspose.HTML προσφέρει έναν δωρεάν online [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter που μετατρέπει το EPUB σε εικόνα PNG με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Μπορεί επίσης να σας ενδιαφέρει η μετατροπή συγκεκριμένης μορφής εικόνας

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Ανοίξτε το υπάρχον αρχείο για ανάγνωση ως ροή
var inputStream = System.IO.File.OpenRead(Path.Combine(InputFolder, "sample.epub"));

// Ορίστε τη διαδρομή εξόδου του αρχείου
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Δημιουργήστε προεπιλεγμένο αντικείμενο επιλογών
var options = new ImageSaveOptions();

// Ξεκινήστε τη διαδικασία μετατροπής με το προεπιλεγμένο αντικείμενο configuration
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);
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

## ConvertEPUB(String, Configuration, ImageSaveOptions, String) {#convertepub_35}

Μετατρέψτε την πηγή EPUB που παρουσιάζεται με πλήρη διαδρομή αρχείου. Το αποτέλεσμα είναι αρχείο εικόνας που δημιουργείται από τη διαδρομή αρχείου εξόδου. Η μορφή εικόνας καθορίζεται από το αντικείμενο ImageSaveOptions.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Διαδρομή αρχείου πηγής EPUB ως παράμετρο εισόδου. |
| configuration | Configuration | Η διαμόρφωση του περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) context που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου ImageSaveOptions σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. Δείτε την κλάση [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/)class. |
| outputPath | String | Πλήρης διαδρομή αρχείου εικόνας ως αποτέλεσμα της μετατροπής. |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε Εικόνα

Το EPUB είναι μια μορφή αρχείου ηλεκτρονικού βιβλίου που παρέχει ένα τυπικό ψηφιακό μορφότυπο δημοσίευσης. Δημιουργήθηκε από το International Digital Publishing Forum (IDPF) και τώρα υποστηρίζεται από πολλούς αναγνώστες e-book και λογισμικές εφαρμογές.

Η μετατροπή αρχείων EPUB σε μορφή PNG μπορεί να είναι χρήσιμη εάν χρειάζεται να ενσωματώσετε αρχεία σε παρουσίαση PowerPoint ή να τα στείλετε μέσω email. Παρακαλούμε μετατρέψτε τα σε μορφή εικόνας και χρησιμοποιήστε τα όπως θέλετε! Μπορείτε να χρησιμοποιήσετε πρόσθετες παραμέτρους μετατροπής για την επίτευξη του επιθυμητού αποτελέσματος.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση Converter που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετες και εύχρηστες. Στον οδηγό EPUB Converter, θα βρείτε τα παρακάτω άρθρα:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Μετατροπή EPUB σε Εικόνα

Για να μετατρέψετε το EPUB σε μορφή αρχείου εικόνας, πρέπει να ακολουθήσετε μερικά βήματα:

Ορίστε το Url με βάση το υπάρχον αρχείο EPUB στην καθορισμένη διαδρομή. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με το απαιτούμενο ImageFormat. Από προεπιλογή, η ιδιότητα Format είναι PNG. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της κλάσης Converter για να αποθηκεύσετε το EPUB ως εικόνα. Πρέπει επίσης να περάσετε το αντικείμενο ImageSaveOptions και το αντικείμενο Configuration στη μετατροπή εικόνας. Online EPUB converters

Το Aspose.HTML προσφέρει έναν δωρεάν online [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter που μετατρέπει το EPUB σε εικόνα PNG με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Μπορεί επίσης να σας ενδιαφέρει η μετατροπή συγκεκριμένης μορφής εικόνας

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Διαδρομή αρχείου πηγής φόρμας
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Διαμορφώστε τη διαδρομή εξόδου του αποτελέσματος
var resultPath = Path.Combine(OutputFolder, "sample.png"); 

// Δημιουργήστε προεπιλεγμένο αντικείμενο ImageSaveOptions
var options = new ImageSaveOptions(); 

// Ξεκινήστε τη διαδικασία μετατροπής με το προεπιλεγμένο αντικείμενο configuration
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);
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

## ConvertEPUB(Url, Configuration, ImageSaveOptions, String) {#convertepub_3}

Μετατρέψτε την πηγή EPUB που ορίζεται από URL. Το αποτέλεσμα είναι αρχείο εικόνας που δημιουργείται από τη διαδρομή αρχείου εξόδου. Η μορφή εικόνας καθορίζεται από το αντικείμενο ImageSaveOptions.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL πηγής EPUB - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου ImageSaveOptions σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [page size](https://apireference.aspose.com/html/net/aspose.html.rendering/renderingoptions/properties/pagesetup), τα [margins](https://apireference.aspose.com/html/net/aspose.html.drawing/page/properties/margin), το [CSS media-type](https://apireference.aspose.com/html/net/aspose.html.rendering/mediatype), κ.λπ. Δείτε την κλάση [ImageSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions)class. |
| outputPath | String | Πλήρης διαδρομή αρχείου εικόνας ως αποτέλεσμα της μετατροπής. |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε Εικόνα

Το EPUB είναι μια μορφή αρχείου ηλεκτρονικού βιβλίου που παρέχει ένα τυπικό ψηφιακό μορφότυπο δημοσίευσης. Δημιουργήθηκε από το International Digital Publishing Forum (IDPF) και τώρα υποστηρίζεται από πολλούς αναγνώστες e-book και λογισμικές εφαρμογές.

Η μετατροπή αρχείων EPUB σε μορφή PNG μπορεί να είναι χρήσιμη εάν χρειάζεται να ενσωματώσετε αρχεία σε παρουσίαση PowerPoint ή να τα στείλετε μέσω email. Παρακαλούμε μετατρέψτε τα σε μορφή εικόνας και χρησιμοποιήστε τα όπως θέλετε! Μπορείτε να χρησιμοποιήσετε πρόσθετες παραμέτρους μετατροπής για την επίτευξη του επιθυμητού αποτελέσματος.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση Converter που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετες και εύχρηστες. Στον οδηγό EPUB Converter, θα βρείτε τα παρακάτω άρθρα:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Μετατροπή EPUB σε Εικόνα

Για να μετατρέψετε το EPUB σε μορφή αρχείου εικόνας, πρέπει να ακολουθήσετε μερικά βήματα:

Ορίστε το Url με βάση το υπάρχον αρχείο EPUB στην καθορισμένη διαδρομή. Ορίστε τη διαδρομή εξόδου του αρχείου αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με το απαιτούμενο ImageFormat. Από προεπιλογή, η ιδιότητα Format είναι PNG. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της κλάσης Converter για να αποθηκεύσετε το EPUB ως εικόνα. Πρέπει επίσης να περάσετε το αντικείμενο ImageSaveOptions και το αντικείμενο Configuration στη μετατροπή εικόνας. Online EPUB converters

Το Aspose.HTML προσφέρει έναν δωρεάν online [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter που μετατρέπει το EPUB σε εικόνα PNG με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Μπορεί επίσης να σας ενδιαφέρει η μετατροπή συγκεκριμένης μορφής εικόνας

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Δημιουργήστε Url βάσει διαδρομής αρχείου εισόδου
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));  

// Ορίστε τη διαδρομή εξόδου του αρχείου
var resultPath = Path.Combine(OutputFolder, "sample.png"); 
 
// Δημιουργήστε προεπιλεγμένο αντικείμενο επιλογών
var options = new ImageSaveOptions(); 

// Ξεκινήστε τη διαδικασία μετατροπής με το προεπιλεγμένο αντικείμενο configuration
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);  
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

## ConvertEPUB(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertepub_26}

Μετατρέψτε την πηγή epub που παρουσιάζεται από την είσοδο [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) σε εικόνα. Το αποτέλεσμα είναι αρχείο εικόνας που δημιουργείται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface.

```java
public static void ConvertEPUB(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή εισόδου ως πηγή μετατροπής. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου ImageSaveOptions σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. Δείτε την κλάση [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/)class. |
| provider | ICreateStreamProvider | Υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface, που θα χρησιμοποιηθεί για την λήψη μιας ροής εξόδου. Δείτε το προχωρημένο παράδειγμα στην [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε Εικόνα

Το EPUB είναι μια μορφή αρχείου ηλεκτρονικού βιβλίου που παρέχει ένα τυπικό ψηφιακό μορφότυπο δημοσίευσης. Δημιουργήθηκε από το International Digital Publishing Forum (IDPF) και τώρα υποστηρίζεται από πολλούς αναγνώστες e-book και λογισμικές εφαρμογές.

Η μετατροπή αρχείων EPUB σε μορφή PNG μπορεί να είναι χρήσιμη εάν χρειάζεται να ενσωματώσετε αρχεία σε παρουσίαση PowerPoint ή να τα στείλετε μέσω email. Παρακαλούμε μετατρέψτε τα σε μορφή εικόνας και χρησιμοποιήστε τα όπως θέλετε! Μπορείτε να χρησιμοποιήσετε πρόσθετες παραμέτρους μετατροπής για την επίτευξη του επιθυμητού αποτελέσματος.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση Converter που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετες και εύχρηστες. Στον οδηγό EPUB Converter, θα βρείτε τα παρακάτω άρθρα:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Μετατροπή EPUB σε Εικόνα

Για να μετατρέψετε το EPUB σε μορφή αρχείου εικόνας, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Στο παράδειγμα, χρησιμοποιούμε τη μέθοδο OpenRead() της κλάσης System.IO.FileStream για να ανοίξουμε και να διαβάσουμε ένα αρχείο EPUB από το σύστημα αρχείων στην καθορισμένη διαδρομή. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) με το απαιτούμενο ImageFormat. Από προεπιλογή, η ιδιότητα Format είναι PNG. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της κλάσης Converter για να αποθηκεύσετε το EPUB ως εικόνα. Πρέπει να περάσετε το EPUB inputStream, το ImageSaveOptions και τη ροή εξόδου στη μέθοδο ConvertEPUB() για τη μετατροπή EPUB σε εικόνα. Online EPUB converters

Το Aspose.HTML προσφέρει έναν δωρεάν online [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter που μετατρέπει το EPUB σε εικόνα PNG με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Μπορεί επίσης να σας ενδιαφέρει η μετατροπή συγκεκριμένης μορφής εικόνας

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Ανοίξτε το υπάρχον αρχείο για ανάγνωση ως ροή  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Αναφερθείτε στην υλοποίηση της διεπαφής ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new ImageSaveOptions();    

// Ξεκινήστε τη διαδικασία μετατροπής  
Converter.ConvertEPUB(inputStream, options, sp);
```

*InputFolder - user input folder path.

*OutputFolder - user output folder path.

### Δείτε επίσης

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, ImageSaveOptions, ICreateStreamProvider) {#convertepub_42}

Μετατρέψτε την πηγή EPUB που παρουσιάζεται από τη διαδρομή αρχείου σε εικόνα. Το αποτέλεσμα είναι αρχείο εικόνας που δημιουργείται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface.

```java
public static void ConvertEPUB(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Διαδρομή αρχείου πηγής EPUB. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να σχηματίσει ένα απόλυτο URL. |
| options | ImageSaveOptions | Νέες δημιουργημένες επιλογές εικόνας όπως μορφή, ανάλυση κ.λπ. Δείτε την κλάση [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) και την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση της διεπαφής, η οποία θα χρησιμοποιηθεί για την λήψη μιας ροής εξόδου. Περισσότερες πληροφορίες για τους παρόχους μπορείτε να δείτε στην [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε Εικόνα

Το EPUB είναι μια μορφή αρχείου ηλεκτρονικού βιβλίου που παρέχει ένα τυπικό ψηφιακό μορφότυπο δημοσίευσης. Δημιουργήθηκε από το International Digital Publishing Forum (IDPF) και τώρα υποστηρίζεται από πολλούς αναγνώστες e-book και λογισμικές εφαρμογές.

Η μετατροπή αρχείων EPUB σε μορφή PNG μπορεί να είναι χρήσιμη εάν χρειάζεται να ενσωματώσετε αρχεία σε παρουσίαση PowerPoint ή να τα στείλετε μέσω email. Παρακαλούμε μετατρέψτε τα σε μορφή εικόνας και χρησιμοποιήστε τα όπως θέλετε! Μπορείτε να χρησιμοποιήσετε πρόσθετες παραμέτρους μετατροπής για την επίτευξη του επιθυμητού αποτελέσματος.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση Converter που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετες και εύχρηστες. Στον οδηγό EPUB Converter, θα βρείτε τα παρακάτω άρθρα:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Μετατροπή EPUB σε Εικόνα

Για να μετατρέψετε το EPUB σε μορφή αρχείου εικόνας, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Στο παράδειγμα, χρησιμοποιούμε τη μέθοδο OpenRead() της κλάσης System.IO.FileStream για να ανοίξουμε και να διαβάσουμε ένα αρχείο EPUB από το σύστημα αρχείων στην καθορισμένη διαδρομή. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο ImageSaveOptions με το απαιτούμενο ImageFormat. Από προεπιλογή, η ιδιότητα Format είναι PNG. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της κλάσης Converter για να αποθηκεύσετε το EPUB ως εικόνα. Πρέπει να περάσετε το EPUB inputStream, το ImageSaveOptions και τη ροή εξόδου στη μέθοδο ConvertEPUB() για τη μετατροπή EPUB σε εικόνα. Online EPUB converters

Το Aspose.HTML προσφέρει έναν δωρεάν online [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter που μετατρέπει το EPUB σε εικόνα PNG με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Μπορεί επίσης να σας ενδιαφέρει η μετατροπή συγκεκριμένης μορφής εικόνας

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

EPUB σε JPG με δύο γραμμές κώδικα

```java
import System.IO;
import com.aspose.html.converters;
import com.aspose.html.rendering.image;
import com.aspose.html.saving;
...
// Ανοίξτε ένα υπάρχον αρχείο EPUB για ανάγνωση.
import var stream = File.OpenRead(DataDir + "input.epub");

// Κλήστε τη μέθοδο ConvertEPUB για να μετατρέψετε τον κώδικα EPUB σε εικόνα JPG
Converter.ConvertEPUB(stream, new ImageSaveOptions(ImageFormat.Jpeg), Path.Combine(OutputDir, "convert-by-two-lines.jpg"));
```

*DataDir - user source file path.

*OutputDir - user output file path.

### Δείτε επίσης

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, ImageSaveOptions, ICreateStreamProvider) {#convertepub_10}

Μετατρέψτε την πηγή epub που παρουσιάζεται μέσω URL σε εικόνα. Το αποτέλεσμα είναι αρχείο εικόνας που δημιουργείται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface.

```java
public static void ConvertEPUB(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL πηγής EPUB - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| options | ImageSaveOptions | Η χρήση του αντικειμένου ImageSaveOptions σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. Δείτε την κλάση [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/)class. |
| provider | ICreateStreamProvider | Υλοποίηση της διεπαφής, η οποία θα χρησιμοποιηθεί για την λήψη μιας ροής εξόδου. Περισσότερες πληροφορίες για τους παρόχους μπορείτε να δείτε στην [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε Εικόνα

Το EPUB είναι μια μορφή αρχείου ηλεκτρονικού βιβλίου που παρέχει ένα τυπικό ψηφιακό μορφότυπο δημοσίευσης. Δημιουργήθηκε από το International Digital Publishing Forum (IDPF) και τώρα υποστηρίζεται από πολλούς αναγνώστες e-book και λογισμικές εφαρμογές.

Η μετατροπή αρχείων EPUB σε μορφή PNG μπορεί να είναι χρήσιμη εάν χρειάζεται να ενσωματώσετε αρχεία σε παρουσίαση PowerPoint ή να τα στείλετε μέσω email. Παρακαλούμε μετατρέψτε τα σε μορφή εικόνας και χρησιμοποιήστε τα όπως θέλετε! Μπορείτε να χρησιμοποιήσετε πρόσθετες παραμέτρους μετατροπής για την επίτευξη του επιθυμητού αποτελέσματος.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση Converter που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετες και εύχρηστες. Στον οδηγό EPUB Converter, θα βρείτε τα παρακάτω άρθρα:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Μετατροπή EPUB σε Εικόνα

Για να μετατρέψετε το EPUB σε μορφή αρχείου εικόνας, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Στο παράδειγμα, χρησιμοποιούμε τη μέθοδο OpenRead() της κλάσης System.IO.FileStream για να ανοίξουμε και να διαβάσουμε ένα αρχείο EPUB από το σύστημα αρχείων στην καθορισμένη διαδρομή. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο ImageSaveOptions με το απαιτούμενο ImageFormat. Από προεπιλογή, η ιδιότητα Format είναι PNG. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της κλάσης Converter για να αποθηκεύσετε το EPUB ως εικόνα. Πρέπει να περάσετε το EPUB inputStream, το ImageSaveOptions και τη ροή εξόδου στη μέθοδο ConvertEPUB() για τη μετατροπή EPUB σε εικόνα. Online EPUB converters

Το Aspose.HTML προσφέρει έναν δωρεάν online [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter που μετατρέπει το EPUB σε εικόνα PNG με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Μπορεί επίσης να σας ενδιαφέρει η μετατροπή συγκεκριμένης μορφής εικόνας

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

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
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Αναφερθείτε στην υλοποίηση της διεπαφής ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new ImageSaveOptions();

// Ξεκινήστε τη διαδικασία μετατροπής  
Converter.ConvertEPUB(sourceUrl, options, sp);
```

*InputFolder - user input folder.

*OutputFolder - user output folder.

*ImageSaveOptions supposes PNG format of new formed image.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_18}

Μετατρέψτε την πηγή epub που παρουσιάζεται από την είσοδο [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) σε εικόνα. Το αποτέλεσμα είναι αρχείο εικόνας που δημιουργείται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή εισόδου ως πηγή μετατροπής. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου ImageSaveOptions σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| παροχέας | ICreateStreamProvider | Υλοποίηση της διεπαφής, η οποία θα χρησιμοποιηθεί για λήψη ροής εξόδου. |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε Εικόνα

Το EPUB είναι μια μορφή αρχείου ηλεκτρονικού βιβλίου που παρέχει ένα τυπικό ψηφιακό μορφότυπο δημοσίευσης. Δημιουργήθηκε από το International Digital Publishing Forum (IDPF) και τώρα υποστηρίζεται από πολλούς αναγνώστες e-book και λογισμικές εφαρμογές.

Η μετατροπή αρχείων EPUB σε μορφή PNG μπορεί να είναι χρήσιμη εάν χρειάζεται να ενσωματώσετε αρχεία σε παρουσίαση PowerPoint ή να τα στείλετε μέσω email. Παρακαλούμε μετατρέψτε τα σε μορφή εικόνας και χρησιμοποιήστε τα όπως θέλετε! Μπορείτε να χρησιμοποιήσετε πρόσθετες παραμέτρους μετατροπής για την επίτευξη του επιθυμητού αποτελέσματος.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση Converter που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετες και εύχρηστες. Στον οδηγό EPUB Converter, θα βρείτε τα παρακάτω άρθρα:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Μετατροπή EPUB σε Εικόνα

Για να μετατρέψετε το EPUB σε μορφή αρχείου εικόνας, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Στο παράδειγμα, χρησιμοποιούμε τη μέθοδο OpenRead() της κλάσης System.IO.FileStream για να ανοίξουμε και να διαβάσουμε ένα αρχείο EPUB από το σύστημα αρχείων στην καθορισμένη διαδρομή. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο ImageSaveOptions με το απαιτούμενο ImageFormat. Από προεπιλογή, η ιδιότητα Format είναι PNG. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της κλάσης Converter για να αποθηκεύσετε το EPUB ως εικόνα. Πρέπει να περάσετε το EPUB inputStream, το ImageSaveOptions και τη ροή εξόδου στη μέθοδο ConvertEPUB() για τη μετατροπή EPUB σε εικόνα. Online EPUB converters

Το Aspose.HTML προσφέρει έναν δωρεάν online [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter που μετατρέπει το EPUB σε εικόνα PNG με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Μπορεί επίσης να σας ενδιαφέρει η μετατροπή συγκεκριμένης μορφής εικόνας

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Ανοίξτε το υπάρχον αρχείο για ανάγνωση ως ροή  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  


// Αναφερθείτε στην υλοποίηση της διεπαφής ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  


// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new ImageSaveOptions();    


// Ξεκινήστε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

*ImageSaveOptions supposes PNG format of new formed image.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_34}

Μετατρέψτε την πηγή epub που παρουσιάζεται μέσω διαδρομής αρχείου σε εικόνα. Το αποτέλεσμα είναι αρχείο εικόνας που δημιουργείται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Πηγή EPUB ορισμένη με διαδρομή αρχείου. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου ImageSaveOptions σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| provider | ICreateStreamProvider | Υλοποίηση της διεπαφής, η οποία θα χρησιμοποιηθεί για λήψη ροής εξόδου. Δείτε το παράδειγμα υλοποίησης ICreateStreamProvider στην [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε Εικόνα

Το EPUB είναι μια μορφή αρχείου ηλεκτρονικού βιβλίου που παρέχει ένα τυπικό ψηφιακό μορφότυπο δημοσίευσης. Δημιουργήθηκε από το International Digital Publishing Forum (IDPF) και τώρα υποστηρίζεται από πολλούς αναγνώστες e-book και λογισμικές εφαρμογές.

Η μετατροπή αρχείων EPUB σε μορφή PNG μπορεί να είναι χρήσιμη εάν χρειάζεται να ενσωματώσετε αρχεία σε παρουσίαση PowerPoint ή να τα στείλετε μέσω email. Παρακαλούμε μετατρέψτε τα σε μορφή εικόνας και χρησιμοποιήστε τα όπως θέλετε! Μπορείτε να χρησιμοποιήσετε πρόσθετες παραμέτρους μετατροπής για την επίτευξη του επιθυμητού αποτελέσματος.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση Converter που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετες και εύχρηστες. Στον οδηγό EPUB Converter, θα βρείτε τα παρακάτω άρθρα:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Μετατροπή EPUB σε Εικόνα

Για να μετατρέψετε το EPUB σε μορφή αρχείου εικόνας, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Στο παράδειγμα, χρησιμοποιούμε τη μέθοδο OpenRead() της κλάσης System.IO.FileStream για να ανοίξουμε και να διαβάσουμε ένα αρχείο EPUB από το σύστημα αρχείων στην καθορισμένη διαδρομή. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο ImageSaveOptions με το απαιτούμενο ImageFormat. Από προεπιλογή, η ιδιότητα Format είναι PNG. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της κλάσης Converter για να αποθηκεύσετε το EPUB ως εικόνα. Πρέπει να περάσετε το EPUB inputStream, το ImageSaveOptions και τη ροή εξόδου στη μέθοδο ConvertEPUB() για τη μετατροπή EPUB σε εικόνα. Online EPUB converters

Το Aspose.HTML προσφέρει έναν δωρεάν online [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter που μετατρέπει το EPUB σε εικόνα PNG με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Μπορεί επίσης να σας ενδιαφέρει η μετατροπή συγκεκριμένης μορφής εικόνας

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Διαδρομή αρχείου πηγής φόρμας
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Αναφερθείτε στην υλοποίηση της διεπαφής ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Δημιουργήστε προεπιλεγμένο αντικείμενο ImageSaveOptions
var options = new ImageSaveOptions(); 

// Ξεκινήστε τη διαδικασία μετατροπής με το προεπιλεγμένο αντικείμενο configuration
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_2}

Μετατρέψτε την πηγή epub που παρουσιάζεται μέσω URL σε εικόνα. Το αποτέλεσμα είναι αρχείο εικόνας που δημιουργείται από την υλοποίηση της διεπαφής [ICreateStreamProvider](https://apireference.aspose.com/html/net/aspose.html.io/icreatestreamprovider) interface.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL πηγής EPUB - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | ImageSaveOptions | Η χρήση του αντικειμένου ImageSaveOptions σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| provider | ICreateStreamProvider | Υλοποίηση της διεπαφής, η οποία θα χρησιμοποιηθεί για λήψη ροής εξόδου. Δείτε το παράδειγμα υλοποίησης ICreateStreamProvider στην [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε Εικόνα

Το EPUB είναι μια μορφή αρχείου ηλεκτρονικού βιβλίου που παρέχει ένα τυπικό ψηφιακό μορφότυπο δημοσίευσης. Δημιουργήθηκε από το International Digital Publishing Forum (IDPF) και τώρα υποστηρίζεται από πολλούς αναγνώστες e-book και λογισμικές εφαρμογές.

Η μετατροπή αρχείων EPUB σε μορφή PNG μπορεί να είναι χρήσιμη εάν χρειάζεται να ενσωματώσετε αρχεία σε παρουσίαση PowerPoint ή να τα στείλετε μέσω email. Παρακαλούμε μετατρέψτε τα σε μορφή εικόνας και χρησιμοποιήστε τα όπως θέλετε! Μπορείτε να χρησιμοποιήσετε πρόσθετες παραμέτρους μετατροπής για την επίτευξη του επιθυμητού αποτελέσματος.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση Converter που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετες και εύχρηστες. Στον οδηγό EPUB Converter, θα βρείτε τα παρακάτω άρθρα:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Μετατροπή EPUB σε Εικόνα

Για να μετατρέψετε το EPUB σε μορφή αρχείου εικόνας, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Στο παράδειγμα, χρησιμοποιούμε τη μέθοδο OpenRead() της κλάσης System.IO.FileStream για να ανοίξουμε και να διαβάσουμε ένα αρχείο EPUB από το σύστημα αρχείων στην καθορισμένη διαδρομή. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer δεδομένων εξόδου. Δημιουργήστε ένα νέο αντικείμενο ImageSaveOptions με το απαιτούμενο ImageFormat. Από προεπιλογή, η ιδιότητα Format είναι PNG. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της κλάσης Converter για να αποθηκεύσετε το EPUB ως εικόνα. Πρέπει να περάσετε το EPUB inputStream, το ImageSaveOptions και τη ροή εξόδου στη μέθοδο ConvertEPUB() για τη μετατροπή EPUB σε εικόνα. Online EPUB converters

Το Aspose.HTML προσφέρει έναν δωρεάν online [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) Converter που μετατρέπει το EPUB σε εικόνα PNG με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Μπορεί επίσης να σας ενδιαφέρει η μετατροπή συγκεκριμένης μορφής εικόνας

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...
// Δημιουργήστε URL πηγής από τη διαδρομή εισαγωγής αρχείου
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Αναφερθείτε στην υλοποίηση της διεπαφής ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new ImageSaveOptions();

// Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);

```

*InputFolder - user source file path.

*OutputFolder - user output file path.

*ImageSaveOptions supposes PNG format of new formed image.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, XpsSaveOptions, String) {#convertepub_31}

Μετατρέψτε την πηγή epub που παρουσιάζεται από ροή εισόδου σε xps. Το αποτέλεσμα είναι αρχείο xps που ορίζεται με πλήρη διαδρομή.

```java
public static void ConvertEPUB(Stream stream, XpsSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Ροή εισόδου ως πηγή μετατροπής. Δείτε την προδιαγραφή Stream στην [official source](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0). |
| options | XpsSaveOptions | Επιλογές μετατροπής. Η χρήση του αντικειμένου [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το μέγεθος σελίδας, τα περιθώρια, το CSS κ.λπ. |
| outputPath | String | Πλήρης διαδρομή αρχείου .xps ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε XPS

Ένα αρχείο XPS αντιπροσωπεύει αρχεία διάταξης σελίδων που βασίζονται στις XML Paper Specifications που δημιουργήθηκαν από τη Microsoft. Αναπτύχθηκε ως αντικατάσταση της μορφής αρχείου EMF και είναι παρόμοιο με τη μορφή PDF, αλλά χρησιμοποιεί XML για τη διάταξη, την εμφάνιση και τις πληροφορίες εκτύπωσης ενός εγγράφου.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετες και εύκολες στη χρήση. Στον οδηγό EPUB Converter XPS, θα βρείτε το παρακάτω άρθρο:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Μετατροπή EPUB σε XPS

Για να μετατρέψετε το EPUB σε μορφή αρχείου XPS, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου πηγής ως πρώτο όρισμα της μεθόδου ConvertEPUB. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer δεδομένων εξόδου. Μπορούμε να χρησιμοποιήσουμε πιο απλή εναλλακτική ως διαδρομή αρχείου εξόδου. Δημιουργήστε ένα νέο αντικείμενο XpsSaveOptions με αριθμούς προτιμώμενων παραμέτρων όπως μέγεθος σελίδας, περιθώρια, CSS κ.λπ. Είναι δυνατόν να χρησιμοποιηθεί η προεπιλεγμένη παρουσία της κλάσης XpsSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο xps. Πρέπει να περάσετε την ημερομηνία πηγής EPUB, το XpsSaveOptions και το buffer δεδομένων εξόδου με οποιονδήποτε τρόπο για να ξεκινήσετε τη διαδικασία μετατροπής. Online EPUB to XPS converter

Το Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) Μετατροπέα που μετατρέπει EPUB σε αρχείο XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System.Drawing;
import com.aspose.html.drawing;
...
  // Ανοίξτε ένα υπάρχον αρχείο EPUB για ανάγνωση
  using var stream = File.OpenRead(DataDir + "input.epub");

  // Προετοιμάστε μια διαδρομή για την αποθήκευση του μετατρεπόμενου αρχείου
  String savePath = Path.Combine(OutputDir, "input-options.xps");
   
  // Δημιουργήστε μια παρουσία της κλάσης XpsSaveOptions. Ορίστε το μέγεθος σελίδας και αλλάξτε το χρώμα φόντου σε LightGray
  var options = new XpsSaveOptions()
  {
    PageSetup =
      {
        AnyPage = new Page()
        {
          Size = new com.aspose.html.drawing.Size(Length.FromPixels(500), Length.FromPixels(500))
        }
      },
    BackgroundColor = Color.LightGray
  };
   
  // Καλέστε τη μέθοδο ConvertEPUB για να μετατρέψετε EPUB σε XPS
  Converter.ConvertEPUB(stream, options, savePath); 
```

*DataDir - some user input folder.

*OutputDir - user output folder.

### Δείτε επίσης

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, XpsSaveOptions, String) {#convertepub_47}

Μετατρέψτε την πηγή epub που παρουσιάζεται με διαδρομή αρχείου εισόδου EPUB σε xps. Το αποτέλεσμα είναι αρχείο xps που ορίζεται με πλήρη διαδρομή.

```java
public static void ConvertEPUB(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Διαδρομή αρχείου πηγής EPUB. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να σχηματίσει ένα απόλυτο URL. |
| options | XpsSaveOptions | Επιλογές μετατροπής. Η χρήση του αντικειμένου [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το [`μέγεθος σελίδας`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`περιθώρια`](../../../com.aspose.html.drawing/page/margin/), τον [`τύπο μέσου CSS`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| outputPath | String | Πλήρης διαδρομή αρχείου .xps ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε XPS

Ένα αρχείο XPS αντιπροσωπεύει αρχεία διάταξης σελίδων που βασίζονται στις XML Paper Specifications που δημιουργήθηκαν από τη Microsoft. Αναπτύχθηκε ως αντικατάσταση της μορφής αρχείου EMF και είναι παρόμοιο με τη μορφή PDF, αλλά χρησιμοποιεί XML για τη διάταξη, την εμφάνιση και τις πληροφορίες εκτύπωσης ενός εγγράφου.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετες και εύκολες στη χρήση. Στον οδηγό EPUB Converter XPS, θα βρείτε το παρακάτω άρθρο:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Μετατροπή EPUB σε XPS

Για να μετατρέψετε το EPUB σε μορφή αρχείου XPS, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου πηγής ως πρώτο όρισμα της μεθόδου ConvertEPUB. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer δεδομένων εξόδου. Μπορούμε να χρησιμοποιήσουμε πιο απλή εναλλακτική ως διαδρομή αρχείου εξόδου. Δημιουργήστε ένα νέο αντικείμενο XpsSaveOptions με αριθμούς προτιμώμενων παραμέτρων όπως μέγεθος σελίδας, περιθώρια, CSS κ.λπ. Είναι δυνατόν να χρησιμοποιηθεί η προεπιλεγμένη παρουσία της κλάσης XpsSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο xps. Πρέπει να περάσετε την ημερομηνία πηγής EPUB, το [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/), και το buffer δεδομένων εξόδου με οποιονδήποτε τρόπο για να ξεκινήσετε τη διαδικασία μετατροπής. Online EPUB to XPS converter

Το Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) Μετατροπέα που μετατρέπει EPUB σε αρχείο XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// Διαδρομή αρχείου πηγής φόρμας
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Διαμορφώστε τη διαδρομή εξόδου του αποτελέσματος
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new XpsSaveOptions();

// Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
Converter.ConvertEPUB(sourcePath, options, resultPath);  
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, XpsSaveOptions, String) {#convertepub_15}

Μετατρέψτε την πηγή epub που παρουσιάζεται από URL σε αρχείο xps που ορίζεται με πλήρη διαδρομή. Δείτε το [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/).

```java
public static void ConvertEPUB(Url sourceUrl, XpsSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL πηγής EPUB - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| options | XpsSaveOptions | Επιλογές μετατροπής. Η χρήση του αντικειμένου [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το [`μέγεθος σελίδας`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`περιθώρια`](../../../com.aspose.html.drawing/page/margin/), τον [`τύπο μέσου CSS`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| outputPath | String | Πλήρης διαδρομή αρχείου .xps ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε XPS

Ένα αρχείο XPS αντιπροσωπεύει αρχεία διάταξης σελίδων που βασίζονται στις XML Paper Specifications που δημιουργήθηκαν από τη Microsoft. Αναπτύχθηκε ως αντικατάσταση της μορφής αρχείου EMF και είναι παρόμοιο με τη μορφή PDF, αλλά χρησιμοποιεί XML για τη διάταξη, την εμφάνιση και τις πληροφορίες εκτύπωσης ενός εγγράφου.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετες και εύκολες στη χρήση. Στον οδηγό EPUB Converter XPS, θα βρείτε το παρακάτω άρθρο:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Μετατροπή EPUB σε XPS

Για να μετατρέψετε το EPUB σε μορφή αρχείου XPS, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο παράμετρο της μεθόδου ConvertEPUB. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer δεδομένων εξόδου. Μπορούμε να χρησιμοποιήσουμε πιο απλή εναλλακτική ως διαδρομή εξόδου του αρχείου αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο XpsSaveOptions με αριθμούς προτιμώμενων παραμέτρων όπως το μέγεθος σελίδας, τα περιθώρια, το CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης XpsSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο xps. Πρέπει να περάσετε την ημερομηνία προέλευσης του EPUB, το XpsSaveOptions και το buffer δεδομένων εξόδου σε οποιαδήποτε μορφή για να ξεκινήσετε τη διαδικασία μετατροπής.

Online μετατροπέας EPUB σε XPS

Το Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) Μετατροπέα που μετατρέπει EPUB σε αρχείο XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...
// Δημιουργήστε URL πηγής από τη διαδρομή εισαγωγής αρχείου
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Διαμορφώστε τη διαδρομή εξόδου του αποτελέσματος
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new XpsSaveOptions();

// Ξεκινήστε τη διαδικασία μετατροπής
Converter.ConvertEPUB(sourceUrl, options, resultPath);





*InputFolder - user input directory.

```

*OutputFolder - user output directory.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, XpsSaveOptions, String) {#convertepub_23}

Μετατρέψτε την πηγή epub που παρουσιάζεται από την είσοδο [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) σε xps. Το αποτέλεσμα είναι αρχείο xps που ορίζεται με πλήρη διαδρομή.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή εισόδου ως πηγή μετατροπής. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | XpsSaveOptions | Επιλογές μετατροπής. Η χρήση του αντικειμένου [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το [`μέγεθος σελίδας`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`περιθώρια`](../../../com.aspose.html.drawing/page/margin/), τον [`τύπο μέσου CSS`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| outputPath | String | Πλήρης διαδρομή αρχείου .xps ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε XPS

Ένα αρχείο XPS αντιπροσωπεύει αρχεία διάταξης σελίδων που βασίζονται στις XML Paper Specifications που δημιουργήθηκαν από τη Microsoft. Αναπτύχθηκε ως αντικατάσταση της μορφής αρχείου EMF και είναι παρόμοιο με τη μορφή PDF, αλλά χρησιμοποιεί XML για τη διάταξη, την εμφάνιση και τις πληροφορίες εκτύπωσης ενός εγγράφου.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετες και εύκολες στη χρήση. Στον οδηγό EPUB Converter XPS, θα βρείτε το παρακάτω άρθρο:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Μετατροπή EPUB σε XPS

Για να μετατρέψετε το EPUB σε μορφή αρχείου XPS, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο παράμετρο της μεθόδου ConvertEPUB. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer δεδομένων εξόδου. Μπορούμε να χρησιμοποιήσουμε πιο απλή εναλλακτική ως διαδρομή εξόδου του αρχείου αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο XpsSaveOptions με αριθμούς προτιμώμενων παραμέτρων όπως το μέγεθος σελίδας, τα περιθώρια, το CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης XpsSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο xps. Πρέπει να περάσετε την ημερομηνία προέλευσης του EPUB, το XpsSaveOptions και το buffer δεδομένων εξόδου σε οποιαδήποτε μορφή για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το [`configuration`](../../../com.aspose.html/configuration/) αντικείμενο περιβάλλοντος που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Online μετατροπέας EPUB σε XPS

Το Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) Μετατροπέα που μετατρέπει EPUB σε αρχείο XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...

// Ανοίξτε ένα υπάρχον αρχείο EPUB για ανάγνωση
import var stream = File.OpenRead(DataDir + "input.epub");

// Προετοιμάστε μια διαδρομή για την αποθήκευση του μετατρεπόμενου αρχείου
String savePath = Path.Combine(OutputDir, "input-output.xps");       
   
// Αρχικοποιήστε το XpsSaveOptions
var options = new XpsSaveOptions();
   
// Καλέστε τη μέθοδο ConvertEPUB για να μετατρέψετε EPUB σε XPS
Converter.ConvertEPUB(stream, new Configuration(), options, savePath);





*DataDir - user input folder.

```

*OutputDir - user output folder.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, XpsSaveOptions, String) {#convertepub_39}

Μετατρέψτε την πηγή epub που παρουσιάζεται με διαδρομή αρχείου εισόδου EPUB σε xps. Το αποτέλεσμα είναι αρχείο xps που ορίζεται με πλήρη διαδρομή.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Διαδρομή αρχείου πηγής EPUB. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να σχηματίσει ένα απόλυτο URL. |
| configuration | Configuration | Η διαμόρφωση του περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) context που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | XpsSaveOptions | Επιλογές μετατροπής. Η χρήση του αντικειμένου [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions)σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το μέγεθος σελίδας, τα περιθώρια, το CSS, κ.λπ. |
| outputPath | String | Πλήρης διαδρομή αρχείου .xps ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε XPS

Ένα αρχείο XPS αντιπροσωπεύει αρχεία διάταξης σελίδων που βασίζονται στις XML Paper Specifications που δημιουργήθηκαν από τη Microsoft. Αναπτύχθηκε ως αντικατάσταση της μορφής αρχείου EMF και είναι παρόμοιο με τη μορφή PDF, αλλά χρησιμοποιεί XML για τη διάταξη, την εμφάνιση και τις πληροφορίες εκτύπωσης ενός εγγράφου.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετες και εύκολες στη χρήση. Στον οδηγό EPUB Converter XPS, θα βρείτε το παρακάτω άρθρο:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Μετατροπή EPUB σε XPS

Για να μετατρέψετε το EPUB σε μορφή αρχείου XPS, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο παράμετρο της μεθόδου ConvertEPUB. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer δεδομένων εξόδου. Μπορούμε να χρησιμοποιήσουμε πιο απλή εναλλακτική ως διαδρομή εξόδου του αρχείου αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο XpsSaveOptions με αριθμούς προτιμώμενων παραμέτρων όπως το μέγεθος σελίδας, τα περιθώρια, το CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης XpsSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο xps. Πρέπει να περάσετε την ημερομηνία προέλευσης του EPUB, το XpsSaveOptions και το buffer δεδομένων εξόδου σε οποιαδήποτε μορφή για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το [`configuration`](../../../com.aspose.html/configuration/) αντικείμενο περιβάλλοντος που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Online μετατροπέας EPUB σε XPS

Το Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) Μετατροπέα που μετατρέπει EPUB σε αρχείο XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// Διαδρομή αρχείου πηγής φόρμας
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Διαμορφώστε τη διαδρομή εξόδου του αποτελέσματος
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new XpsSaveOptions();

// Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);  
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

## ConvertEPUB(Url, Configuration, XpsSaveOptions, String) {#convertepub_7}

Μετατρέψτε την πηγή epub που παρουσιάζεται από URL σε αρχείο xps που ορίζεται με πλήρη διαδρομή. Δείτε το [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL πηγής EPUB - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| configuration | Configuration | Η διαμόρφωση του περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) context που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | XpsSaveOptions | Επιλογές μετατροπής. Η χρήση του αντικειμένου [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions)σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το μέγεθος σελίδας, τα περιθώρια, το CSS, κ.λπ. |
| outputPath | String | Πλήρης διαδρομή αρχείου .xps ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε XPS

Ένα αρχείο XPS αντιπροσωπεύει αρχεία διάταξης σελίδων που βασίζονται στις XML Paper Specifications που δημιουργήθηκαν από τη Microsoft. Αναπτύχθηκε ως αντικατάσταση της μορφής αρχείου EMF και είναι παρόμοιο με τη μορφή PDF, αλλά χρησιμοποιεί XML για τη διάταξη, την εμφάνιση και τις πληροφορίες εκτύπωσης ενός εγγράφου.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετες και εύκολες στη χρήση. Στον οδηγό EPUB Converter XPS, θα βρείτε το παρακάτω άρθρο:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Μετατροπή EPUB σε XPS

Για να μετατρέψετε το EPUB σε μορφή αρχείου XPS, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο παράμετρο της μεθόδου ConvertEPUB. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer δεδομένων εξόδου. Μπορούμε να χρησιμοποιήσουμε πιο απλή εναλλακτική ως διαδρομή εξόδου του αρχείου αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο XpsSaveOptions με αριθμούς προτιμώμενων παραμέτρων όπως το μέγεθος σελίδας, τα περιθώρια, το CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης XpsSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο xps. Πρέπει να περάσετε την ημερομηνία προέλευσης του EPUB, το XpsSaveOptions και το buffer δεδομένων εξόδου σε οποιαδήποτε μορφή για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το [`configuration`](../../../com.aspose.html/configuration/) αντικείμενο περιβάλλοντος που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Online μετατροπέας EPUB σε XPS

Το Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) Μετατροπέα που μετατρέπει EPUB σε αρχείο XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// Δημιουργήστε URL πηγής από τη διαδρομή εισαγωγής αρχείου
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Διαμορφώστε τη διαδρομή εξόδου του αποτελέσματος
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new XpsSaveOptions();

// Ξεκινήστε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertepub_30}

Μετατρέψτε την πηγή epub που παρουσιάζεται από την είσοδο [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) σε xps. Το αποτέλεσμα είναι δεδομένα εξόδου xps που ορίζονται από γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή εισόδου ως πηγή μετατροπής. |
| options | XpsSaveOptions | Επιλογές μετατροπής. Η χρήση του αντικειμένου [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/)σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το [`μέγεθος σελίδας`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`περιθώρια`](../../../com.aspose.html.drawing/page/margin/), το [`τύπο μέσου CSS`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| provider | ICreateStreamProvider | Υλοποίηση της διεπαφής, η οποία θα χρησιμοποιηθεί για τη λήψη ενός ρεύματος εξόδου. Δείτε το παράδειγμα υλοποίησης του ICreateStreamProvider στην [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε XPS

Ένα αρχείο XPS αντιπροσωπεύει αρχεία διάταξης σελίδων που βασίζονται στις XML Paper Specifications που δημιουργήθηκαν από τη Microsoft. Αναπτύχθηκε ως αντικατάσταση της μορφής αρχείου EMF και είναι παρόμοιο με τη μορφή PDF, αλλά χρησιμοποιεί XML για τη διάταξη, την εμφάνιση και τις πληροφορίες εκτύπωσης ενός εγγράφου.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετες και εύκολες στη χρήση. Στον οδηγό EPUB Converter XPS, θα βρείτε το παρακάτω άρθρο:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Μετατροπή EPUB σε XPS

Για να μετατρέψετε το EPUB σε μορφή αρχείου XPS, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο παράμετρο της μεθόδου ConvertEPUB. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer δεδομένων εξόδου. Μπορούμε να χρησιμοποιήσουμε πιο απλή εναλλακτική ως διαδρομή εξόδου του αρχείου αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο XpsSaveOptions με αριθμούς προτιμώμενων παραμέτρων όπως το μέγεθος σελίδας, τα περιθώρια, το CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης XpsSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο xps. Πρέπει να περάσετε την ημερομηνία προέλευσης του EPUB, το XpsSaveOptions και το buffer δεδομένων εξόδου σε οποιαδήποτε μορφή για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το [`configuration`](../../../com.aspose.html/configuration/) αντικείμενο περιβάλλοντος που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Online μετατροπέας EPUB σε XPS

Το Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) Μετατροπέα που μετατρέπει EPUB σε αρχείο XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import Aspose.Html;
import System.Linq;
import com.aspose.html.converters;
import com.aspose.html.saving;
...
 // Δημιουργήστε μια παρουσία του MemoryStreamProvider
 using var streamProvider = new MemoryStreamProvider();

 // Ανοίξτε ένα υπάρχον αρχείο EPUB για ανάγνωση
 using var stream = File.OpenRead(DataDir + "input.epub");
  
 // Προετοιμάστε μια διαδρομή για την αποθήκευση του μετατρεπόμενου αρχείου
 String savePath = Path.Combine(OutputDir, "stream-provider.xps");
  
 // Μετατρέψτε το EPUB σε XPS χρησιμοποιώντας την κλάση MemoryStreamProvider
 Converter.ConvertEPUB(stream, new XpsSaveOptions(), streamProvider);
  
 // Αποκτήστε πρόσβαση στη μνήμη ρεύματος που περιέχει τα δεδομένα αποτελέσματος
 var memory = streamProvider.Streams.First();
 memory.Seek(0, SeekOrigin.Begin);

 // Αδειάστε τα δεδομένα αποτελέσματος στο αρχείο εξόδου
 using (FileStream fs = File.Create(savePath))
 {
  memory.CopyTo(fs);
 }
```

*DataDir - user source file path.

*OutputDir- user output file path.

*See MemoryStreamProvider class as ICreateStreamProvider implementation in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers).

### Δείτε επίσης

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, XpsSaveOptions, ICreateStreamProvider) {#convertepub_46}

Μετατρέψτε την πηγή epub που παρουσιάζεται από τη διαδρομή αρχείου EPUB εισόδου σε xps. Το αποτέλεσμα είναι δεδομένα εξόδου xps που ορίζονται από γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider `](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Διαδρομή αρχείου πηγής EPUB. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να σχηματίσει ένα απόλυτο URL. |
| options | XpsSaveOptions | Επιλογές μετατροπής. Η χρήση του αντικειμένου [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions)σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το μέγεθος σελίδας, τα περιθώρια, το CSS, κ.λπ. |
| provider | ICreateStreamProvider | Υλοποίηση της διεπαφής, η οποία θα χρησιμοποιηθεί για τη λήψη ενός ρεύματος εξόδου. Δείτε το προχωρημένο παράδειγμα στην [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε XPS

Ένα αρχείο XPS αντιπροσωπεύει αρχεία διάταξης σελίδων που βασίζονται στις XML Paper Specifications που δημιουργήθηκαν από τη Microsoft. Αναπτύχθηκε ως αντικατάσταση της μορφής αρχείου EMF και είναι παρόμοιο με τη μορφή PDF, αλλά χρησιμοποιεί XML για τη διάταξη, την εμφάνιση και τις πληροφορίες εκτύπωσης ενός εγγράφου.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετες και εύκολες στη χρήση. Στον οδηγό EPUB Converter XPS, θα βρείτε το παρακάτω άρθρο:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Μετατροπή EPUB σε XPS

Για να μετατρέψετε το EPUB σε μορφή αρχείου XPS, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου πηγής ως πρώτο όρισμα της μεθόδου ConvertEPUB. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer δεδομένων εξόδου. Μπορούμε να χρησιμοποιήσουμε πιο απλή εναλλακτική ως διαδρομή αρχείου εξόδου. Δημιουργήστε ένα νέο αντικείμενο XpsSaveOptions με αριθμούς προτιμώμενων παραμέτρων όπως μέγεθος σελίδας, περιθώρια, CSS κ.λπ. Είναι δυνατόν να χρησιμοποιηθεί η προεπιλεγμένη παρουσία της κλάσης XpsSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο xps. Πρέπει να περάσετε την ημερομηνία πηγής EPUB, το XpsSaveOptions και το buffer δεδομένων εξόδου με οποιονδήποτε τρόπο για να ξεκινήσετε τη διαδικασία μετατροπής. Online EPUB to XPS converter

Το Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) Μετατροπέα που μετατρέπει EPUB σε αρχείο XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Διαδρομή αρχείου πηγής φόρμας
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Αναφερθείτε στην υλοποίηση της διεπαφής ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new XpsSaveOptions();

// Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, XpsSaveOptions, ICreateStreamProvider) {#convertepub_14}

Μετατρέψτε την πηγή epub που παρουσιάζεται από URL σε αρχείο xps ορισμένο με πλήρη διαδρομή. Το αποτέλεσμα είναι δεδομένα εξόδου xps που ορίζονται από γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL πηγής EPUB - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| options | XpsSaveOptions | Επιλογές μετατροπής. Η χρήση του αντικειμένου [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/)σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το μέγεθος σελίδας, τα περιθώρια, το CSS, κ.λπ. Δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση της [`διεπαφής`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για τη λήψη ενός ρεύματος εξόδου. Δείτε το προχωρημένο παράδειγμα στην [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε XPS

Ένα αρχείο XPS αντιπροσωπεύει αρχεία διάταξης σελίδων που βασίζονται στις XML Paper Specifications που δημιουργήθηκαν από τη Microsoft. Αναπτύχθηκε ως αντικατάσταση της μορφής αρχείου EMF και είναι παρόμοιο με τη μορφή PDF, αλλά χρησιμοποιεί XML για τη διάταξη, την εμφάνιση και τις πληροφορίες εκτύπωσης ενός εγγράφου.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετες και εύκολες στη χρήση. Στον οδηγό EPUB Converter XPS, θα βρείτε το παρακάτω άρθρο:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Μετατροπή EPUB σε XPS

Για να μετατρέψετε το EPUB σε μορφή αρχείου XPS, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο παράμετρο της μεθόδου ConvertEPUB. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη διεπαφή [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Μπορούμε να χρησιμοποιήσουμε πιο απλή εναλλακτική ως διαδρομή εξόδου του αρχείου αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο XpsSaveOptions με αριθμούς προτιμώμενων παραμέτρων όπως το μέγεθος σελίδας, τα περιθώρια, το CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης XpsSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο xps. Πρέπει να περάσετε την ημερομηνία προέλευσης του EPUB, το XpsSaveOptions και το buffer δεδομένων εξόδου σε οποιαδήποτε μορφή για να ξεκινήσετε τη διαδικασία μετατροπής. Online μετατροπέας EPUB σε XPS

Το Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) Μετατροπέα που μετατρέπει EPUB σε αρχείο XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Δημιουργήστε URL πηγής από τη διαδρομή εισαγωγής αρχείου
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Αναφερθείτε στην υλοποίηση της διεπαφής ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new XpsSaveOptions();

// Ξεκινήστε τη διαδικασία μετατροπής
Converter.ConvertEPUB(sourceUrl, options, sp);
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

## ConvertEPUB(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_22}

Μετατρέψτε την πηγή epub που παρουσιάζεται από την είσοδο [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) σε xps. Το αποτέλεσμα είναι δεδομένα εξόδου xps που ορίζονται από γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή εισόδου ως πηγή μετατροπής. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | XpsSaveOptions | Επιλογές μετατροπής. Η χρήση του αντικειμένου [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/)σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το [`μέγεθος σελίδας`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`περιθώρια`](../../../com.aspose.html.drawing/page/margin/), το [`τύπο μέσου CSS`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. |
| provider | ICreateStreamProvider | Υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για τη λήψη ενός ρεύματος εξόδου. Δείτε το προχωρημένο παράδειγμα στην [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε XPS

Ένα αρχείο XPS αντιπροσωπεύει αρχεία διάταξης σελίδων που βασίζονται στις XML Paper Specifications που δημιουργήθηκαν από τη Microsoft. Αναπτύχθηκε ως αντικατάσταση της μορφής αρχείου EMF και είναι παρόμοιο με τη μορφή PDF, αλλά χρησιμοποιεί XML για τη διάταξη, την εμφάνιση και τις πληροφορίες εκτύπωσης ενός εγγράφου.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετες και εύκολες στη χρήση. Στον οδηγό EPUB Converter XPS, θα βρείτε το παρακάτω άρθρο:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Μετατροπή EPUB σε XPS

Για να μετατρέψετε το EPUB σε μορφή αρχείου XPS, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο παράμετρο της μεθόδου ConvertEPUB. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη διεπαφή [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) ως buffer δεδομένων εξόδου. Μπορούμε να χρησιμοποιήσουμε πιο απλή εναλλακτική ως διαδρομή εξόδου του αρχείου αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο XpsSaveOptions με αριθμούς προτιμώμενων παραμέτρων όπως το μέγεθος σελίδας, τα περιθώρια, το CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης XpsSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο xps. Πρέπει να περάσετε την ημερομηνία προέλευσης του EPUB, το XpsSaveOptions και το buffer δεδομένων εξόδου σε οποιαδήποτε μορφή για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το [`configuration`](../../../com.aspose.html/configuration/) αντικείμενο περιβάλλοντος που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Online μετατροπέας EPUB σε XPS

Το Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) Μετατροπέα που μετατρέπει EPUB σε αρχείο XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Ανοίξτε το υπάρχον αρχείο για ανάγνωση ως ροή  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Αναφερθείτε στην υλοποίηση της διεπαφής ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new XpsSaveOptions();

// Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
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

## ConvertEPUB(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_38}

Μετατρέψτε την πηγή epub που παρουσιάζεται από τη διαδρομή αρχείου EPUB εισόδου σε xps. Το αποτέλεσμα είναι δεδομένα εξόδου xps που ορίζονται από γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Διαδρομή αρχείου πηγής EPUB. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να σχηματίσει ένα απόλυτο URL. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | XpsSaveOptions | Επιλογές μετατροπής. Η χρήση του αντικειμένου [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το μέγεθος σελίδας, τα περιθώρια, το CSS κ.λπ. |
| provider | ICreateStreamProvider | Υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για τη λήψη ενός ρεύματος εξόδου. Δείτε το προχωρημένο παράδειγμα στην [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε XPS

Ένα αρχείο XPS αντιπροσωπεύει αρχεία διάταξης σελίδων που βασίζονται στις XML Paper Specifications που δημιουργήθηκαν από τη Microsoft. Αναπτύχθηκε ως αντικατάσταση της μορφής αρχείου EMF και είναι παρόμοιο με τη μορφή PDF, αλλά χρησιμοποιεί XML για τη διάταξη, την εμφάνιση και τις πληροφορίες εκτύπωσης ενός εγγράφου.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετες και εύκολες στη χρήση. Στον οδηγό EPUB Converter XPS, θα βρείτε το παρακάτω άρθρο:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Μετατροπή EPUB σε XPS

Για να μετατρέψετε το EPUB σε μορφή αρχείου XPS, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο παράμετρο της μεθόδου ConvertEPUB. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer δεδομένων εξόδου. Μπορούμε να χρησιμοποιήσουμε πιο απλή εναλλακτική ως διαδρομή εξόδου του αρχείου αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο XpsSaveOptions με αριθμούς προτιμώμενων παραμέτρων όπως το μέγεθος σελίδας, τα περιθώρια, το CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης XpsSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο xps. Πρέπει να περάσετε την ημερομηνία προέλευσης του EPUB, το XpsSaveOptions και το buffer δεδομένων εξόδου σε οποιαδήποτε μορφή για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το [`configuration`](../../../com.aspose.html/configuration/) αντικείμενο περιβάλλοντος που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Online μετατροπέας EPUB σε XPS

Το Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) Μετατροπέα που μετατρέπει EPUB σε αρχείο XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Διαδρομή αρχείου πηγής φόρμας
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Αναφερθείτε στην υλοποίηση της διεπαφής ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new XpsSaveOptions();

// Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_6}

Μετατρέψτε την πηγή epub που παρουσιάζεται από URL σε αρχείο xps ορισμένο με πλήρη διαδρομή. Το αποτέλεσμα είναι δεδομένα εξόδου xps που ορίζονται από γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL πηγής EPUB - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | XpsSaveOptions | Επιλογές μετατροπής. Η χρήση του αντικειμένου [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/)σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το [`μέγεθος σελίδας`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`περιθώρια`](../../../com.aspose.html.drawing/page/margin/), το [`τύπο μέσου CSS`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. Δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/), η οποία θα χρησιμοποιηθεί για τη λήψη ενός ρεύματος εξόδου. Δείτε το προχωρημένο παράδειγμα στην [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε XPS

Ένα αρχείο XPS αντιπροσωπεύει αρχεία διάταξης σελίδων που βασίζονται στις XML Paper Specifications που δημιουργήθηκαν από τη Microsoft. Αναπτύχθηκε ως αντικατάσταση της μορφής αρχείου EMF και είναι παρόμοιο με τη μορφή PDF, αλλά χρησιμοποιεί XML για τη διάταξη, την εμφάνιση και τις πληροφορίες εκτύπωσης ενός εγγράφου.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετες και εύκολες στη χρήση. Στον οδηγό EPUB Converter XPS, θα βρείτε το παρακάτω άρθρο:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Μετατροπή EPUB σε XPS

Για να μετατρέψετε το EPUB σε μορφή αρχείου XPS, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο παράμετρο της μεθόδου ConvertEPUB. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer δεδομένων εξόδου. Μπορούμε να χρησιμοποιήσουμε πιο απλή εναλλακτική ως διαδρομή εξόδου του αρχείου αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο XpsSaveOptions με αριθμούς προτιμώμενων παραμέτρων όπως το μέγεθος σελίδας, τα περιθώρια, το CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης XpsSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο xps. Πρέπει να περάσετε την ημερομηνία προέλευσης του EPUB, το XpsSaveOptions και το buffer δεδομένων εξόδου σε οποιαδήποτε μορφή για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το [`configuration`](../../../com.aspose.html/configuration/) αντικείμενο περιβάλλοντος που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Online μετατροπέας EPUB σε XPS

Το Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) Μετατροπέα που μετατρέπει EPUB σε αρχείο XPS με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Δημιουργήστε URL πηγής από τη διαδρομή εισαγωγής αρχείου
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Διαμορφώστε τη διαδρομή εξόδου του αποτελέσματος
var resultPath = Path.Combine(OutputFolder, " sample.xps");

// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new XpsSaveOptions();

// Ξεκινήστε τη διαδικασία μετατροπής με προεπιλεγμένη configuration
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, DocSaveOptions, String) {#convertepub_25}

Μετατρέψτε το αρχείο πηγής EPUB που παρέχεται με πλήρη διαδρομή σε DOCX. Το αποτέλεσμα είναι αρχείο docx που ορίζεται με πλήρη διαδρομή.

```java
public static void ConvertEPUB(Stream stream, DocSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Πηγή μετατροπής που παρουσιάζεται από την είσοδο [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0). |
| options | DocSaveOptions | Επιλογές μετατροπής. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) η χρήση του αντικειμένου σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το [`μέγεθος σελίδας`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`περιθώρια`](../../../com.aspose.html.drawing/page/margin/), το [`τύπο μέσου CSS`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. Δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου .docx ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε DOCX

Το DOCX είναι μια ευρέως γνωστή μορφή για έγγραφα Microsoft Word. Αυτή η μορφή είναι δημοφιλής επειδή υποστηρίζει ένα ευρύ φάσμα λειτουργιών μορφοποίησης και προσφέρει στους χρήστες διάφορες επιλογές για τη δημιουργία οποιουδήποτε τύπου εγγράφου. Τα αρχεία DOCX μπορούν να ανοιχτούν με το Word 2007 και παρόμοιες εκδόσεις, αλλά όχι με τις παλαιότερες εκδόσεις του MS Word, που υποστηρίζουν τις επεκτάσεις αρχείων DOC. Η μετατροπή EPUB σε DOCX συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή DOCX για συγκεκριμένα καθήκοντα χρηστών.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας την κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση ώστε να είναι άνετες και εύκολες στη χρήση. Στον οδηγό EPUB Converter για DOCX, θα βρείτε το παρακάτω άρθρο:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Μετατροπή EPUB σε DOCX

Για να μετατρέψετε τη μορφή αρχείου EPUB σε DOCX, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο όρισμα της μεθόδου ConvertEPUB. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer εξόδου δεδομένων. Μπορούμε επίσης να χρησιμοποιήσουμε μια πιο απλή εναλλακτική ως διαδρομή εξόδου του αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο DocSaveOptions με αριθμούς προτιμώμενων παραμέτρων όπως το μέγεθος σελίδας, τα περιθώρια, το CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης DocSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο docx. Πρέπει να περάσετε την πηγή EPUB ως διαδρομή αρχείου ή ροή εισόδου, καθώς και το Url, την παρουσία DocSaveOptions και το buffer εξόδου δεδομένων με οποιονδήποτε τρόπο για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το [`configuration`](../../../com.aspose.html/configuration/) αντικείμενο περιβάλλοντος που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Online EPUB to DOCX converter

Η Aspose.HTML προσφέρει έναν δωρεάν online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Μετατροπέα που μετατρέπει EPUB σε αρχείο DOCX με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Ανοίξτε το υπάρχον αρχείο για ανάγνωση ως ροή  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Διαμορφώστε τη διαδρομή εξόδου του αποτελέσματος
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new DocSaveOptions();   

// Ξεκινήστε τη διαδικασία μετατροπής
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, DocSaveOptions, String) {#convertepub_41}

Μετατρέψτε την πηγή EPUB που παρουσιάζεται με πλήρη διαδρομή αρχείου σε DOCX. Το αποτέλεσμα είναι αρχείο docx που δημιουργείται από τη διαδρομή αρχείου εξόδου.

```java
public static void ConvertEPUB(String sourcePath, DocSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Διαδρομή αρχείου πηγής EPUB ως παράμετρο εισόδου. |
| options | DocSaveOptions | Επιλογές μετατροπής. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) η χρήση του αντικειμένου σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το [`μέγεθος σελίδας`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/),[` περιθώρια`](../../../com.aspose.html.drawing/page/margin/), το [`τύπο μέσου CSS`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. Δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου .docx ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε DOCX

Το DOCX είναι μια ευρέως γνωστή μορφή για έγγραφα Microsoft Word. Αυτή η μορφή είναι δημοφιλής επειδή υποστηρίζει ένα ευρύ φάσμα λειτουργιών μορφοποίησης και προσφέρει στους χρήστες διάφορες επιλογές για τη δημιουργία οποιουδήποτε τύπου εγγράφου. Τα αρχεία DOCX μπορούν να ανοιχτούν με το Word 2007 και παρόμοιες εκδόσεις, αλλά όχι με τις παλαιότερες εκδόσεις του MS Word, που υποστηρίζουν τις επεκτάσεις αρχείων DOC. Η μετατροπή EPUB σε DOCX συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή DOCX για συγκεκριμένα καθήκοντα χρηστών.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας την κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση ώστε να είναι άνετες και εύκολες στη χρήση. Στον οδηγό EPUB Converter για DOCX, θα βρείτε το παρακάτω άρθρο:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Μετατροπή EPUB σε DOCX

Για να μετατρέψετε τη μορφή αρχείου EPUB σε DOCX, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο όρισμα της μεθόδου ConvertEPUB. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer εξόδου δεδομένων. Μπορούμε επίσης να χρησιμοποιήσουμε μια πιο απλή εναλλακτική ως διαδρομή εξόδου του αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο DocSaveOptions με αριθμούς προτιμώμενων παραμέτρων όπως το μέγεθος σελίδας, τα περιθώρια, το CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης DocSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο docx. Πρέπει να περάσετε την πηγή EPUB ως διαδρομή αρχείου ή ροή εισόδου, καθώς και το Url, την παρουσία DocSaveOptions και το buffer εξόδου δεδομένων με οποιονδήποτε τρόπο για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το [`configuration`](../../../com.aspose.html/configuration/) αντικείμενο περιβάλλοντος που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Online EPUB to DOCX converter

Η Aspose.HTML προσφέρει έναν δωρεάν online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Μετατροπέα που μετατρέπει EPUB σε αρχείο DOCX με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Διαδρομή αρχείου πηγής φόρμας
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Διαμορφώστε τη διαδρομή εξόδου του αποτελέσματος
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Δημιουργήστε προεπιλεγμένο αντικείμενο επιλογών
var options = new DocSaveOptions();

// Αυξήστε τη διαδικασία μετατροπής
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, DocSaveOptions, String) {#convertepub_9}

Μετατρέψτε την πηγή EPUB που παρουσιάζεται από URL. Το αποτέλεσμα είναι αρχείο docx που δημιουργείται από τη διαδρομή αρχείου εξόδου.

```java
public static void ConvertEPUB(Url sourceUrl, DocSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL πηγής EPUB - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| options | DocSaveOptions | Η χρήση του [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το [`μέγεθος σελίδας`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`περιθώρια`](../../../com.aspose.html.drawing/page/margin/), τις [`αναλύσεις`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), το [`τύπο μέσου CSS`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. Δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου .docx ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε DOCX

Το DOCX είναι μια ευρέως γνωστή μορφή για έγγραφα Microsoft Word. Αυτή η μορφή είναι δημοφιλής επειδή υποστηρίζει ένα ευρύ φάσμα λειτουργιών μορφοποίησης και προσφέρει στους χρήστες διάφορες επιλογές για τη δημιουργία οποιουδήποτε τύπου εγγράφου. Τα αρχεία DOCX μπορούν να ανοιχτούν με το Word 2007 και παρόμοιες εκδόσεις, αλλά όχι με τις παλαιότερες εκδόσεις του MS Word, που υποστηρίζουν τις επεκτάσεις αρχείων DOC. Η μετατροπή EPUB σε DOCX συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή DOCX για συγκεκριμένα καθήκοντα χρηστών.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας την κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση ώστε να είναι άνετες και εύκολες στη χρήση. Στον οδηγό EPUB Converter για DOCX, θα βρείτε το παρακάτω άρθρο:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Μετατροπή EPUB σε DOCX

Για να μετατρέψετε τη μορφή αρχείου EPUB σε DOCX, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο όρισμα της μεθόδου ConvertEPUB. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer εξόδου δεδομένων. Μπορούμε επίσης να χρησιμοποιήσουμε μια πιο απλή εναλλακτική ως διαδρομή εξόδου του αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο DocSaveOptions με αριθμούς προτιμώμενων παραμέτρων όπως το μέγεθος σελίδας, τα περιθώρια, το CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης DocSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο docx. Πρέπει να περάσετε την πηγή EPUB ως διαδρομή αρχείου ή ροή εισόδου, καθώς και το Url, την παρουσία DocSaveOptions και το buffer εξόδου δεδομένων με οποιονδήποτε τρόπο για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το [`configuration`](../../../com.aspose.html/configuration/) αντικείμενο περιβάλλοντος που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Online EPUB to DOCX converter

Η Aspose.HTML προσφέρει έναν δωρεάν online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Μετατροπέα που μετατρέπει EPUB σε αρχείο DOCX με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Δημιουργήστε URL πηγής από τη διαδρομή εισαγωγής αρχείου
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Διαμορφώστε τη διαδρομή εξόδου του αποτελέσματος
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Δημιουργήστε προεπιλεγμένο αντικείμενο επιλογών
var options = new DocSaveOptions();

// Αυξήστε τη διαδικασία μετατροπής
Converter.ConvertEPUB(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, DocSaveOptions, String) {#convertepub_17}

Μετατρέψτε την πηγή EPUB που παρουσιάζεται από ροή δεδομένων εισόδου. Το αποτέλεσμα είναι αρχείο docx που δημιουργείται από τη διαδρομή αρχείου εξόδου.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή εισόδου ως πηγή μετατροπής. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | DocSaveOptions | Επιλογές μετατροπής. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) η χρήση του αντικειμένου σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το [`μέγεθος σελίδας`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`περιθώρια`](../../../com.aspose.html.drawing/page/margin/), το [`τύπο μέσου CSS`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. Δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου .docx ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε DOCX

Το DOCX είναι μια ευρέως γνωστή μορφή για έγγραφα Microsoft Word. Αυτή η μορφή είναι δημοφιλής επειδή υποστηρίζει ένα ευρύ φάσμα λειτουργιών μορφοποίησης και προσφέρει στους χρήστες διάφορες επιλογές για τη δημιουργία οποιουδήποτε τύπου εγγράφου. Τα αρχεία DOCX μπορούν να ανοιχτούν με το Word 2007 και παρόμοιες εκδόσεις, αλλά όχι με τις παλαιότερες εκδόσεις του MS Word, που υποστηρίζουν τις επεκτάσεις αρχείων DOC. Η μετατροπή EPUB σε DOCX συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή DOCX για συγκεκριμένα καθήκοντα χρηστών.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας την κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση ώστε να είναι άνετες και εύκολες στη χρήση. Στον οδηγό EPUB Converter για DOCX, θα βρείτε το παρακάτω άρθρο:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Μετατροπή EPUB σε DOCX

Για να μετατρέψετε τη μορφή αρχείου EPUB σε DOCX, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο όρισμα της μεθόδου ConvertEPUB. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer εξόδου δεδομένων. Μπορούμε επίσης να χρησιμοποιήσουμε μια πιο απλή εναλλακτική ως διαδρομή εξόδου του αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο DocSaveOptions με αριθμούς προτιμώμενων παραμέτρων όπως το μέγεθος σελίδας, τα περιθώρια, το CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης DocSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο docx. Πρέπει να περάσετε την πηγή EPUB ως διαδρομή αρχείου ή ροή εισόδου, καθώς και το Url, την παρουσία DocSaveOptions και το buffer εξόδου δεδομένων με οποιονδήποτε τρόπο για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το [`configuration`](../../../com.aspose.html/configuration/) αντικείμενο περιβάλλοντος που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Online EPUB to DOCX converter

Η Aspose.HTML προσφέρει έναν δωρεάν online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Μετατροπέα που μετατρέπει EPUB σε αρχείο DOCX με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Ανοίξτε το υπάρχον αρχείο για ανάγνωση ως ροή  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Διαμορφώστε τη διαδρομή εξόδου του αποτελέσματος
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new DocSaveOptions();   

// Ξεκινήστε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);
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

## ConvertEPUB(String, Configuration, DocSaveOptions, String) {#convertepub_33}

Μετατρέψτε την πηγή EPUB που παρουσιάζεται με πλήρη διαδρομή αρχείου σε DOCX. Το αποτέλεσμα είναι αρχείο docx που δημιουργείται από τη διαδρομή αρχείου εξόδου.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Διαδρομή αρχείου πηγής EPUB. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να σχηματίσει ένα απόλυτο URL. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | DocSaveOptions | Επιλογές μετατροπής. [DocSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/docsaveoptions) η χρήση του αντικειμένου σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το μέγεθος σελίδας, τα περιθώρια, το CSS, κ.λπ. Δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου .docx ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε DOCX

Το DOCX είναι μια ευρέως γνωστή μορφή για έγγραφα Microsoft Word. Αυτή η μορφή είναι δημοφιλής επειδή υποστηρίζει ένα ευρύ φάσμα λειτουργιών μορφοποίησης και προσφέρει στους χρήστες διάφορες επιλογές για τη δημιουργία οποιουδήποτε τύπου εγγράφου. Τα αρχεία DOCX μπορούν να ανοιχτούν με το Word 2007 και παρόμοιες εκδόσεις, αλλά όχι με τις παλαιότερες εκδόσεις του MS Word, που υποστηρίζουν τις επεκτάσεις αρχείων DOC. Η μετατροπή EPUB σε DOCX συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή DOCX για συγκεκριμένα καθήκοντα χρηστών.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας την κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση ώστε να είναι άνετες και εύκολες στη χρήση. Στον οδηγό EPUB Converter για DOCX, θα βρείτε το παρακάτω άρθρο:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Μετατροπή EPUB σε DOCX

Για να μετατρέψετε τη μορφή αρχείου EPUB σε DOCX, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο όρισμα της μεθόδου ConvertEPUB. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer εξόδου δεδομένων. Μπορούμε επίσης να χρησιμοποιήσουμε μια πιο απλή εναλλακτική ως διαδρομή εξόδου του αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο DocSaveOptions με αριθμούς προτιμώμενων παραμέτρων όπως το μέγεθος σελίδας, τα περιθώρια, το CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης DocSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο docx. Πρέπει να περάσετε την πηγή EPUB ως διαδρομή αρχείου ή ροή εισόδου, καθώς και το Url, την παρουσία DocSaveOptions και το buffer εξόδου δεδομένων με οποιονδήποτε τρόπο για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το [`configuration`](../../../com.aspose.html/configuration/) αντικείμενο περιβάλλοντος που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Online EPUB to DOCX converter

Η Aspose.HTML προσφέρει έναν δωρεάν online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Μετατροπέα που μετατρέπει EPUB σε αρχείο DOCX με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Διαδρομή αρχείου πηγής φόρμας
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Διαμορφώστε τη διαδρομή εξόδου του αποτελέσματος
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Δημιουργήστε προεπιλεγμένο αντικείμενο επιλογών
var options = new DocSaveOptions();

// Αυξήστε τη διαδικασία μετατροπής με προεπιλεγμένη διαμόρφωση
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);
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

## ConvertEPUB(Url, Configuration, DocSaveOptions, String) {#convertepub_1}

Μετατρέψτε την πηγή EPUB που παρουσιάζεται από URL. Το αποτέλεσμα είναι αρχείο docx που δημιουργείται από τη διαδρομή αρχείου εξόδου.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL πηγής EPUB - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | DocSaveOptions | Η χρήση του [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το [`μέγεθος σελίδας`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`περιθώρια`](../../../com.aspose.html.drawing/page/margin/), τις [`αναλύσεις`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), το [`τύπο μέσου CSS`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. Δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου .docx ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε DOCX

Το DOCX είναι μια ευρέως γνωστή μορφή για έγγραφα Microsoft Word. Αυτή η μορφή είναι δημοφιλής επειδή υποστηρίζει ένα ευρύ φάσμα λειτουργιών μορφοποίησης και προσφέρει στους χρήστες διάφορες επιλογές για τη δημιουργία οποιουδήποτε τύπου εγγράφου. Τα αρχεία DOCX μπορούν να ανοιχτούν με το Word 2007 και παρόμοιες εκδόσεις, αλλά όχι με τις παλαιότερες εκδόσεις του MS Word, που υποστηρίζουν τις επεκτάσεις αρχείων DOC. Η μετατροπή EPUB σε DOCX συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή DOCX για συγκεκριμένα καθήκοντα χρηστών.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας την κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση ώστε να είναι άνετες και εύκολες στη χρήση. Στον οδηγό EPUB Converter για DOCX, θα βρείτε το παρακάτω άρθρο:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Μετατροπή EPUB σε DOCX

Για να μετατρέψετε τη μορφή αρχείου EPUB σε DOCX, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο όρισμα της μεθόδου ConvertEPUB. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer εξόδου δεδομένων. Μπορούμε επίσης να χρησιμοποιήσουμε μια πιο απλή εναλλακτική ως διαδρομή εξόδου του αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο DocSaveOptions με αριθμούς προτιμώμενων παραμέτρων όπως το μέγεθος σελίδας, τα περιθώρια, το CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης DocSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο docx. Πρέπει να περάσετε την πηγή EPUB ως διαδρομή αρχείου ή ροή εισόδου, καθώς και το Url, την παρουσία DocSaveOptions και το buffer εξόδου δεδομένων με οποιονδήποτε τρόπο για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το [`configuration`](../../../com.aspose.html/configuration/) αντικείμενο περιβάλλοντος που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Online EPUB to DOCX converter

Η Aspose.HTML προσφέρει έναν δωρεάν online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Μετατροπέα που μετατρέπει EPUB σε αρχείο DOCX με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Δημιουργήστε URL πηγής από τη διαδρομή εισαγωγής αρχείου
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Διαδρομή αρχείου αποτελέσματος μετατροπής φόρμας
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new DocSaveOptions();

// Ξεκινήστε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, DocSaveOptions, ICreateStreamProvider) {#convertepub_24}

Μετατρέψτε την πηγή EPUB ως ροή εισόδου σε DOCX. Το αποτέλεσμα είναι αρχείο docx που δημιουργείται από την υλοποίηση του ICreateStreamProvider.

```java
public static void ConvertEPUB(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή εισόδου ως πηγή μετατροπής. |
| options | DocSaveOptions | Επιλογές μετατροπής. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) η χρήση του αντικειμένου σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το [`μέγεθος σελίδας`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`περιθώρια`](../../../com.aspose.html.drawing/page/margin/), το [`τύπο μέσου CSS`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. Δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) που θα χρησιμοποιηθεί για τη λήψη ροής εξόδου. Δείτε προχωρημένο παράδειγμα στο [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε DOCX

Το DOCX είναι μια ευρέως γνωστή μορφή για έγγραφα Microsoft Word. Αυτή η μορφή είναι δημοφιλής επειδή υποστηρίζει ένα ευρύ φάσμα λειτουργιών μορφοποίησης και προσφέρει στους χρήστες διάφορες επιλογές για τη δημιουργία οποιουδήποτε τύπου εγγράφου. Τα αρχεία DOCX μπορούν να ανοιχτούν με το Word 2007 και παρόμοιες εκδόσεις, αλλά όχι με τις παλαιότερες εκδόσεις του MS Word, που υποστηρίζουν τις επεκτάσεις αρχείων DOC. Η μετατροπή EPUB σε DOCX συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή DOCX για συγκεκριμένα καθήκοντα χρηστών.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας την κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση ώστε να είναι άνετες και εύκολες στη χρήση. Στον οδηγό EPUB Converter για DOCX, θα βρείτε το παρακάτω άρθρο:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Μετατροπή EPUB σε DOCX

Για να μετατρέψετε τη μορφή αρχείου EPUB σε DOCX, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο όρισμα της μεθόδου ConvertEPUB. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer εξόδου δεδομένων. Μπορούμε επίσης να χρησιμοποιήσουμε μια πιο απλή εναλλακτική ως διαδρομή εξόδου του αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο DocSaveOptions με αριθμούς προτιμώμενων παραμέτρων όπως το μέγεθος σελίδας, τα περιθώρια, το CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης DocSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο docx. Πρέπει να περάσετε την πηγή EPUB ως διαδρομή αρχείου ή ροή εισόδου, καθώς και το Url, την παρουσία DocSaveOptions και το buffer εξόδου δεδομένων με οποιονδήποτε τρόπο για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το [`configuration`](../../../com.aspose.html/configuration/) αντικείμενο περιβάλλοντος που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Online EPUB to DOCX converter

Η Aspose.HTML προσφέρει έναν δωρεάν online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Μετατροπέα που μετατρέπει EPUB σε αρχείο DOCX με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Ανοίξτε το υπάρχον αρχείο για ανάγνωση ως ροή  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Αναφερθείτε στην υλοποίηση της διεπαφής ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new DocSaveOptions();   

// Ξεκινήστε τη διαδικασία μετατροπής
Converter.ConvertEPUB(inputStream, options, sp);
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

## ConvertEPUB(String, DocSaveOptions, ICreateStreamProvider) {#convertepub_40}

Μετατρέψτε την πηγή EPUB που παρουσιάζεται με πλήρη διαδρομή αρχείου σε DOCX. Το αποτέλεσμα είναι δεδομένα εξόδου που σχηματίζονται από την υλοποίηση του [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Διαδρομή αρχείου πηγής EPUB. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να σχηματίσει ένα απόλυτο URL. |
| options | DocSaveOptions | Επιλογές μετατροπής. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) η χρήση του αντικειμένου σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το [`μέγεθος σελίδας`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`περιθώρια`](../../../com.aspose.html.drawing/page/margin/), το [`τύπο μέσου CSS`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. Δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) που θα χρησιμοποιηθεί για τη λήψη ροής εξόδου. Δείτε προχωρημένο παράδειγμα στο [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε DOCX

Το DOCX είναι μια ευρέως γνωστή μορφή για έγγραφα Microsoft Word. Αυτή η μορφή είναι δημοφιλής επειδή υποστηρίζει ένα ευρύ φάσμα λειτουργιών μορφοποίησης και προσφέρει στους χρήστες διάφορες επιλογές για τη δημιουργία οποιουδήποτε τύπου εγγράφου. Τα αρχεία DOCX μπορούν να ανοιχτούν με το Word 2007 και παρόμοιες εκδόσεις, αλλά όχι με τις παλαιότερες εκδόσεις του MS Word, που υποστηρίζουν τις επεκτάσεις αρχείων DOC. Η μετατροπή EPUB σε DOCX συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή DOCX για συγκεκριμένα καθήκοντα χρηστών.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας την κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση ώστε να είναι άνετες και εύκολες στη χρήση. Στον οδηγό EPUB Converter για DOCX, θα βρείτε το παρακάτω άρθρο:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Μετατροπή EPUB σε DOCX

Για να μετατρέψετε τη μορφή αρχείου EPUB σε DOCX, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο όρισμα της μεθόδου ConvertEPUB. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer εξόδου δεδομένων. Μπορούμε επίσης να χρησιμοποιήσουμε μια πιο απλή εναλλακτική ως διαδρομή εξόδου του αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο DocSaveOptions με αριθμούς προτιμώμενων παραμέτρων όπως το μέγεθος σελίδας, τα περιθώρια, το CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης DocSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο docx. Πρέπει να περάσετε την πηγή EPUB ως διαδρομή αρχείου ή ροή εισόδου, καθώς και το Url, την παρουσία DocSaveOptions και το buffer εξόδου δεδομένων με οποιονδήποτε τρόπο για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το [`configuration`](../../../com.aspose.html/configuration/) αντικείμενο περιβάλλοντος που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Online EPUB to DOCX converter

Η Aspose.HTML προσφέρει έναν δωρεάν online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Μετατροπέα που μετατρέπει EPUB σε αρχείο DOCX με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

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
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Αναφερθείτε στην υλοποίηση της διεπαφής ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new DocSaveOptions ();   

// Ξεκινήστε τη διαδικασία μετατροπής  
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, DocSaveOptions, ICreateStreamProvider) {#convertepub_8}

Μετατρέψτε την πηγή EPUB που παρουσιάζεται από URL. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής ICreateStreamProvider.

```java
public static void ConvertEPUB(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL πηγής EPUB - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| options | DocSaveOptions | Η χρήση του [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το μέγεθος σελίδας, τα περιθώρια, τις αναλύσεις, το CSS, κ.λπ. Δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) που θα χρησιμοποιηθεί για τη λήψη ροής εξόδου. Δείτε προχωρημένο παράδειγμα στο [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε DOCX

Το DOCX είναι μια ευρέως γνωστή μορφή για έγγραφα Microsoft Word. Αυτή η μορφή είναι δημοφιλής επειδή υποστηρίζει ένα ευρύ φάσμα λειτουργιών μορφοποίησης και προσφέρει στους χρήστες διάφορες επιλογές για τη δημιουργία οποιουδήποτε τύπου εγγράφου. Τα αρχεία DOCX μπορούν να ανοιχτούν με το Word 2007 και παρόμοιες εκδόσεις, αλλά όχι με τις παλαιότερες εκδόσεις του MS Word, που υποστηρίζουν τις επεκτάσεις αρχείων DOC. Η μετατροπή EPUB σε DOCX συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή DOCX για συγκεκριμένα καθήκοντα χρηστών.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας την κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση ώστε να είναι άνετες και εύκολες στη χρήση. Στον οδηγό EPUB Converter για DOCX, θα βρείτε το παρακάτω άρθρο:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Μετατροπή EPUB σε DOCX

Για να μετατρέψετε τη μορφή αρχείου EPUB σε DOCX, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο όρισμα της μεθόδου ConvertEPUB. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer εξόδου δεδομένων. Μπορούμε επίσης να χρησιμοποιήσουμε μια πιο απλή εναλλακτική ως διαδρομή εξόδου του αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο DocSaveOptions με αριθμούς προτιμώμενων παραμέτρων όπως το μέγεθος σελίδας, τα περιθώρια, το CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης DocSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο docx. Πρέπει να περάσετε την πηγή EPUB ως διαδρομή αρχείου ή ροή εισόδου, καθώς και το Url, την παρουσία DocSaveOptions και το buffer εξόδου δεδομένων με οποιονδήποτε τρόπο για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το [`configuration`](../../../com.aspose.html/configuration/) αντικείμενο περιβάλλοντος που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Online EPUB to DOCX converter

Η Aspose.HTML προσφέρει έναν δωρεάν online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Μετατροπέα που μετατρέπει EPUB σε αρχείο DOCX με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Δημιουργήστε URL πηγής από τη διαδρομή εισαγωγής αρχείου
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Αναφερθείτε στην υλοποίηση της διεπαφής ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new DocSaveOptions ();   

// Ξεκινήστε τη διαδικασία μετατροπής
Converter.ConvertEPUB(sourceUrl, options, sp);





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

## ConvertEPUB(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub_16}

Μετατρέψτε την πηγή EPUB που παρουσιάζεται από ροή δεδομένων εισόδου. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής ICreateStreamProvider.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή εισόδου ως πηγή μετατροπής. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | DocSaveOptions | Η χρήση του [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το [`μέγεθος σελίδας`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`περιθώρια`](../../../com.aspose.html.drawing/page/margin/), τις [`αναλύσεις`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), το [`τύπο μέσου CSS`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. Δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) που θα χρησιμοποιηθεί για τη λήψη ροής εξόδου. Δείτε προχωρημένο παράδειγμα στο [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε DOCX

Το DOCX είναι μια ευρέως γνωστή μορφή για έγγραφα Microsoft Word. Αυτή η μορφή είναι δημοφιλής επειδή υποστηρίζει ένα ευρύ φάσμα λειτουργιών μορφοποίησης και προσφέρει στους χρήστες διάφορες επιλογές για τη δημιουργία οποιουδήποτε τύπου εγγράφου. Τα αρχεία DOCX μπορούν να ανοιχτούν με το Word 2007 και παρόμοιες εκδόσεις, αλλά όχι με τις παλαιότερες εκδόσεις του MS Word, που υποστηρίζουν τις επεκτάσεις αρχείων DOC. Η μετατροπή EPUB σε DOCX συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή DOCX για συγκεκριμένα καθήκοντα χρηστών.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας την κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση ώστε να είναι άνετες και εύκολες στη χρήση. Στον οδηγό EPUB Converter για DOCX, θα βρείτε το παρακάτω άρθρο:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Μετατροπή EPUB σε DOCX

Για να μετατρέψετε τη μορφή αρχείου EPUB σε DOCX, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο όρισμα της μεθόδου ConvertEPUB. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer εξόδου δεδομένων. Μπορούμε επίσης να χρησιμοποιήσουμε μια πιο απλή εναλλακτική ως διαδρομή εξόδου του αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με αριθμούς προτιμώμενων παραμέτρων όπως το μέγεθος σελίδας, τα περιθώρια, το CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης DocSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο docx. Πρέπει να περάσετε την πηγή EPUB ως διαδρομή αρχείου ή ροή εισόδου, καθώς και το Url, την παρουσία DocSaveOptions και το buffer εξόδου δεδομένων με οποιονδήποτε τρόπο για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το [`configuration`](../../../com.aspose.html/configuration/) αντικείμενο περιβάλλοντος που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Online EPUB to DOCX converter

Η Aspose.HTML προσφέρει έναν δωρεάν online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Μετατροπέα που μετατρέπει EPUB σε αρχείο DOCX με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Ανοίξτε το υπάρχον αρχείο για ανάγνωση ως ροή  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Αναφερθείτε στην υλοποίηση της διεπαφής ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new DocSaveOptions();   

// Ξεκινήστε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);





*InputFolder - user source file path.

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

## ConvertEPUB(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub_32}

Μετατρέψτε την πηγή EPUB που παρουσιάζεται με πλήρη διαδρομή αρχείου σε DOCX. Το αποτέλεσμα είναι δεδομένα εξόδου που σχηματίζονται από την υλοποίηση του [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) διεπαφής.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Διαδρομή αρχείου πηγής EPUB. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να σχηματίσει ένα απόλυτο URL. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | DocSaveOptions | Επιλογές μετατροπής. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) η χρήση του αντικειμένου σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το [`μέγεθος σελίδας`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`περιθώρια`](../../../com.aspose.html.drawing/page/margin/), το [`τύπο μέσου CSS`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. Δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) που θα χρησιμοποιηθεί για τη λήψη ροής εξόδου. Δείτε προχωρημένο παράδειγμα στο [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε DOCX

Το DOCX είναι μια ευρέως γνωστή μορφή για έγγραφα Microsoft Word. Αυτή η μορφή είναι δημοφιλής επειδή υποστηρίζει ένα ευρύ φάσμα λειτουργιών μορφοποίησης και προσφέρει στους χρήστες διάφορες επιλογές για τη δημιουργία οποιουδήποτε τύπου εγγράφου. Τα αρχεία DOCX μπορούν να ανοιχτούν με το Word 2007 και παρόμοιες εκδόσεις, αλλά όχι με τις παλαιότερες εκδόσεις του MS Word, που υποστηρίζουν τις επεκτάσεις αρχείων DOC. Η μετατροπή EPUB σε DOCX συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή DOCX για συγκεκριμένα καθήκοντα χρηστών.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας την κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση ώστε να είναι άνετες και εύκολες στη χρήση. Στον οδηγό EPUB Converter για DOCX, θα βρείτε το παρακάτω άρθρο:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Μετατροπή EPUB σε DOCX

Για να μετατρέψετε τη μορφή αρχείου EPUB σε DOCX, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο όρισμα της μεθόδου ConvertEPUB. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer εξόδου δεδομένων. Μπορούμε επίσης να χρησιμοποιήσουμε μια πιο απλή εναλλακτική ως διαδρομή εξόδου του αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με αριθμούς προτιμώμενων παραμέτρων όπως το μέγεθος σελίδας, τα περιθώρια, το CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης DocSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο docx. Πρέπει να περάσετε την πηγή EPUB ως διαδρομή αρχείου ή ροή εισόδου, καθώς και το Url, την παρουσία DocSaveOptions και το buffer εξόδου δεδομένων με οποιονδήποτε τρόπο για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το [`configuration`](../../../com.aspose.html/configuration/) αντικείμενο περιβάλλοντος που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Online EPUB to DOCX converter

Η Aspose.HTML προσφέρει έναν δωρεάν online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Μετατροπέα που μετατρέπει EPUB σε αρχείο DOCX με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

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
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Αναφερθείτε στην υλοποίηση της διεπαφής ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new DocSaveOptions ();   

// Ξεκινήστε τη διαδικασία μετατροπής  
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub}

Μετατρέψτε την πηγή EPUB που παρουσιάζεται με URL. Το αποτέλεσμα είναι δεδομένα εξόδου που σχηματίζονται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL πηγής EPUB - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| configuration | Configuration | Η διαμόρφωση του περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) context που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | DocSaveOptions | Η χρήση του [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το [`μέγεθος σελίδας`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`περιθώρια`](../../../com.aspose.html.drawing/page/margin/), τις [`αναλύσεις`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), το [`τύπο μέσου CSS`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. Δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) που θα χρησιμοποιηθεί για τη λήψη ροής εξόδου. Δείτε προχωρημένο παράδειγμα στο [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε DOCX

Το DOCX είναι μια ευρέως γνωστή μορφή για έγγραφα Microsoft Word. Αυτή η μορφή είναι δημοφιλής επειδή υποστηρίζει ένα ευρύ φάσμα λειτουργιών μορφοποίησης και προσφέρει στους χρήστες διάφορες επιλογές για τη δημιουργία οποιουδήποτε τύπου εγγράφου. Τα αρχεία DOCX μπορούν να ανοιχτούν με το Word 2007 και παρόμοιες εκδόσεις, αλλά όχι με τις παλαιότερες εκδόσεις του MS Word, που υποστηρίζουν τις επεκτάσεις αρχείων DOC. Η μετατροπή EPUB σε DOCX συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή DOCX για συγκεκριμένα καθήκοντα χρηστών.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες σχετικά με τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας την κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση ώστε να είναι άνετες και εύκολες στη χρήση. Στον οδηγό EPUB Converter για DOCX, θα βρείτε το παρακάτω άρθρο:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Μετατροπή EPUB σε DOCX

Για να μετατρέψετε τη μορφή αρχείου EPUB σε DOCX, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο όρισμα της μεθόδου ConvertEPUB. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer εξόδου δεδομένων. Μπορούμε επίσης να χρησιμοποιήσουμε μια πιο απλή εναλλακτική ως διαδρομή εξόδου του αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) με αριθμούς προτιμώμενων παραμέτρων όπως το μέγεθος σελίδας, τα περιθώρια, το CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης DocSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο docx. Πρέπει να περάσετε την πηγή EPUB ως διαδρομή αρχείου ή ροή εισόδου, καθώς και το Url, την παρουσία DocSaveOptions και το buffer εξόδου δεδομένων με οποιονδήποτε τρόπο για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το [`configuration`](../../../com.aspose.html/configuration/) αντικείμενο περιβάλλοντος που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Online EPUB to DOCX converter

Η Aspose.HTML προσφέρει έναν δωρεάν online [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) Μετατροπέα που μετατρέπει EPUB σε αρχείο DOCX με υψηλή ποιότητα, εύκολο και γρήγορο. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

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
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Αναφερθείτε στην υλοποίηση της διεπαφής ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new DocSaveOptions();   

// Ξεκινήστε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);





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

## ConvertEPUB(Stream, PdfSaveOptions, String) {#convertepub_29}

Μετατρέψτε την πηγή EPUB που παρέχεται με ροή δεδομένων εισόδου. Το αποτέλεσμα είναι αρχείο pdf που δημιουργείται με τη διαδρομή εξόδου.

```java
public static void ConvertEPUB(Stream stream, PdfSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Διαδρομή αρχείου πηγής EPUB ως παράμετρο εισόδου. |
| options | PdfSaveOptions | Επιλογές μετατροπής. Το αντικείμενο [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το [`μέγεθος σελίδας`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`περιθώρια`](../../../com.aspose.html.drawing/page/margin/), το [`τύπο μέσου CSS`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. Δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου .pdf ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε PDF

Το EPUB είναι μια μορφή αρχείου ηλεκτρονικού βιβλίου που παρέχει ένα τυποποιημένο ψηφιακό φορμά δημοσίευσης. Δημιουργείται από το International Digital Publishing Forum ([IDPF](http://idpf.org/)) και τώρα υποστηρίζεται από πολλούς αναγνώστες e‑book και λογισμικά. Η μετατροπή EPUB σε PDF συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή PDF. Η μορφή αρχείου PDF έχει πλήρη δυνατότητα να περιέχει πληροφορίες όπως κείμενο, εικόνες, υπερσυνδέσμους, πεδία φόρμας, πλούσιο πολυμέσο, μεταδεδομένα κ.λπ. Τα αρχεία PDF μπορούν να ανοιχτούν στο Adobe Acrobat Reader/Writer και στα περισσότερα σύγχρονα προγράμματα περιήγησης όπως Chrome, Safari, Firefox. Είναι βελτιστοποιημένα για εκτύπωση και είναι ιδανικά για τη δημιουργία φυσικών αντιτύπων των εγγράφων σας· μπορείτε επίσης να διαμορφώσετε τις ρυθμίσεις ασφαλείας για το PDF.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες για τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετη και εύκολη στη χρήση. Στον ειδικό οδηγό EPUB Converter PDF, βρίσκετε το παρακάτω άρθρο:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Μετατροπή EPUB σε PDF

Για να μετατρέψετε το EPUB σε μορφή αρχείου PDF, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο παράμετρο της μεθόδου ConvertEPUB. Εναλλακτικά, μπορούμε να χρησιμοποιήσουμε ροή εισόδου ή αντικείμενο Url. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer δεδομένων εξόδου. Μπορούμε επίσης να χρησιμοποιήσουμε πιο απλή εναλλακτική ως διαδρομή αρχείου εξόδου αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο PdfSaveOptions με αριθμό προτιμώμενων παραμέτρων όπως μέγεθος σελίδας, περιθώρια, CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης PdfSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο pdf. Πρέπει να περάσετε την πηγή του EPUB ως διαδρομή αρχείου ή ροή εισόδου, καθώς και το Url, την παρουσία PdfSaveOptions και το buffer δεδομένων εξόδου με οποιονδήποτε τρόπο για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το αντικείμενο [`configuration`](../../../com.aspose.html/configuration/) περιβάλλον που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Διαδικτυακός μετατροπέας EPUB σε PDF

Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter που μετατρέπει EPUB σε αρχείο PDF με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Ανοίξτε το υπάρχον αρχείο για ανάγνωση ως ροή  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Διαδρομή αρχείου αποτελέσματος φόρμας  
var resultPath = Path.Combine(OutputFolder, "sample.pdf"));  

// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new PdfSaveOptions();   

// Ξεκινήστε τη διαδικασία μετατροπής  
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, PdfSaveOptions, String) {#convertepub_45}

Μετατρέψτε την πηγή EPUB που παρουσιάζεται με πλήρη διαδρομή αρχείου σε PDF. Το αποτέλεσμα είναι αρχείο pdf που δημιουργείται από τη διαδρομή αρχείου εξόδου.

```java
public static void ConvertEPUB(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Διαδρομή αρχείου πηγής EPUB. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να σχηματίσει ένα απόλυτο URL. |
| options | PdfSaveOptions | Επιλογές μετατροπής. Το αντικείμενο [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το [`μέγεθος σελίδας`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`περιθώρια`](../../../com.aspose.html.drawing/page/margin/), το [`τύπο μέσου CSS`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. Δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου .pdf ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε PDF

Το EPUB είναι μια μορφή αρχείου ηλεκτρονικού βιβλίου που παρέχει ένα τυποποιημένο ψηφιακό φορμά δημοσίευσης. Δημιουργείται από το International Digital Publishing Forum ([IDPF](http://idpf.org/)) και τώρα υποστηρίζεται από πολλούς αναγνώστες e‑book και λογισμικά. Η μετατροπή EPUB σε PDF συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή PDF. Η μορφή αρχείου PDF έχει πλήρη δυνατότητα να περιέχει πληροφορίες όπως κείμενο, εικόνες, υπερσυνδέσμους, πεδία φόρμας, πλούσιο πολυμέσο, μεταδεδομένα κ.λπ. Τα αρχεία PDF μπορούν να ανοιχτούν στο Adobe Acrobat Reader/Writer και στα περισσότερα σύγχρονα προγράμματα περιήγησης όπως Chrome, Safari, Firefox. Είναι βελτιστοποιημένα για εκτύπωση και είναι ιδανικά για τη δημιουργία φυσικών αντιτύπων των εγγράφων σας· μπορείτε επίσης να διαμορφώσετε τις ρυθμίσεις ασφαλείας για το PDF.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες για τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετη και εύκολη στη χρήση. Στον ειδικό οδηγό EPUB Converter PDF, βρίσκετε το παρακάτω άρθρο:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Μετατροπή EPUB σε PDF

Για να μετατρέψετε το EPUB σε μορφή αρχείου PDF, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο παράμετρο της μεθόδου ConvertEPUB. Εναλλακτικά, μπορούμε να χρησιμοποιήσουμε ροή εισόδου ή αντικείμενο Url. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer δεδομένων εξόδου. Μπορούμε επίσης να χρησιμοποιήσουμε πιο απλή εναλλακτική ως διαδρομή αρχείου εξόδου αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) με αριθμό προτιμώμενων παραμέτρων όπως μέγεθος σελίδας, περιθώρια, CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης PdfSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης **Converter** για να αποθηκεύσετε το EPUB ως αρχείο pdf. Πρέπει να περάσετε την πηγή του EPUB ως διαδρομή αρχείου ή ροή εισόδου, καθώς και το Url, την παρουσία PdfSaveOptions και το buffer δεδομένων εξόδου με οποιονδήποτε τρόπο για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το αντικείμενο [`configuration`](../../../com.aspose.html/configuration/) περιβάλλον που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Διαδικτυακός μετατροπέας EPUB σε PDF

Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter που μετατρέπει EPUB σε αρχείο PDF με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Διαδρομή αρχείου πηγής φόρμας
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Διαμορφώστε τη διαδρομή εξόδου του αποτελέσματος
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Δημιουργήστε προεπιλεγμένο αντικείμενο επιλογών
var options = new PdfSaveOptions();

// Αυξήστε τη διαδικασία μετατροπής
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Δείτε επίσης

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, PdfSaveOptions, String) {#convertepub_13}

Μετατρέψτε την πηγή EPUB που παρουσιάζεται από URL. Το αποτέλεσμα είναι αρχείο pdf που δημιουργείται από τη διαδρομή αρχείου εξόδου.

```java
public static void ConvertEPUB(Url sourceUrl, PdfSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL πηγής EPUB - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| options | PdfSaveOptions | Η χρήση του [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), τις [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. Δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου .pdf ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε PDF

Το EPUB είναι μια μορφή αρχείου ηλεκτρονικού βιβλίου που παρέχει ένα τυποποιημένο ψηφιακό φορμά δημοσίευσης. Δημιουργείται από το International Digital Publishing Forum ([IDPF](http://idpf.org/)) και τώρα υποστηρίζεται από πολλούς αναγνώστες e‑book και λογισμικά. Η μετατροπή EPUB σε PDF συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή PDF. Η μορφή αρχείου PDF έχει πλήρη δυνατότητα να περιέχει πληροφορίες όπως κείμενο, εικόνες, υπερσυνδέσμους, πεδία φόρμας, πλούσιο πολυμέσο, μεταδεδομένα κ.λπ. Τα αρχεία PDF μπορούν να ανοιχτούν στο Adobe Acrobat Reader/Writer και στα περισσότερα σύγχρονα προγράμματα περιήγησης όπως Chrome, Safari, Firefox. Είναι βελτιστοποιημένα για εκτύπωση και είναι ιδανικά για τη δημιουργία φυσικών αντιτύπων των εγγράφων σας· μπορείτε επίσης να διαμορφώσετε τις ρυθμίσεις ασφαλείας για το PDF.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες για τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετη και εύκολη στη χρήση. Στον ειδικό οδηγό EPUB Converter PDF, βρίσκετε το παρακάτω άρθρο:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Μετατροπή EPUB σε PDF

Για να μετατρέψετε το EPUB σε μορφή αρχείου PDF, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο παράμετρο της μεθόδου ConvertEPUB. Εναλλακτικά, μπορούμε να χρησιμοποιήσουμε ροή εισόδου ή αντικείμενο Url. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer δεδομένων εξόδου. Μπορούμε επίσης να χρησιμοποιήσουμε πιο απλή εναλλακτική ως διαδρομή αρχείου εξόδου αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο PdfSaveOptions με αριθμό προτιμώμενων παραμέτρων όπως μέγεθος σελίδας, περιθώρια, CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης PdfSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο pdf. Πρέπει να περάσετε την πηγή του EPUB ως διαδρομή αρχείου ή ροή εισόδου, καθώς και το Url, την παρουσία PdfSaveOptions και το buffer δεδομένων εξόδου με οποιονδήποτε τρόπο για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το αντικείμενο [`configuration`](../../../com.aspose.html/configuration/) περιβάλλον που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Διαδικτυακός μετατροπέας EPUB σε PDF

Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter που μετατρέπει EPUB σε αρχείο PDF με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.saving;  
import com.aspose.html.converters; 

// Δημιουργήστε Url βάσει διαδρομής αρχείου εισόδου
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Διαμορφώστε τη διαδρομή εξόδου του αποτελέσματος
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Δημιουργήστε προεπιλεγμένο αντικείμενο επιλογών
var options = new com.aspose.html.saving.PdfSaveOptions();

// Αυξήστε τη διαδικασία μετατροπής
Converter.ConvertEPUB(sourceUrl, options, resultPath);
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

## ConvertEPUB(Stream, Configuration, PdfSaveOptions, String) {#convertepub_21}

Μετατρέψτε την πηγή EPUB που παρέχεται με ροή δεδομένων εισόδου. Το αποτέλεσμα είναι αρχείο pdf που δημιουργείται με τη διαδρομή εξόδου.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή εισόδου ως πηγή μετατροπής. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | PdfSaveOptions | Επιλογές μετατροπής. Το αντικείμενο [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το [`μέγεθος σελίδας`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`περιθώρια`](../../../com.aspose.html.drawing/page/margin/), το [`τύπο μέσου CSS`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. Δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου .pdf ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε PDF

Το EPUB είναι μια μορφή αρχείου ηλεκτρονικού βιβλίου που παρέχει ένα τυποποιημένο ψηφιακό φορμά δημοσίευσης. Δημιουργείται από το International Digital Publishing Forum ([IDPF](http://idpf.org/)) και τώρα υποστηρίζεται από πολλούς αναγνώστες e‑book και λογισμικά. Η μετατροπή EPUB σε PDF συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή PDF. Η μορφή αρχείου PDF έχει πλήρη δυνατότητα να περιέχει πληροφορίες όπως κείμενο, εικόνες, υπερσυνδέσμους, πεδία φόρμας, πλούσιο πολυμέσο, μεταδεδομένα κ.λπ. Τα αρχεία PDF μπορούν να ανοιχτούν στο Adobe Acrobat Reader/Writer και στα περισσότερα σύγχρονα προγράμματα περιήγησης όπως Chrome, Safari, Firefox. Είναι βελτιστοποιημένα για εκτύπωση και είναι ιδανικά για τη δημιουργία φυσικών αντιτύπων των εγγράφων σας· μπορείτε επίσης να διαμορφώσετε τις ρυθμίσεις ασφαλείας για το PDF.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες για τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετη και εύκολη στη χρήση. Στον ειδικό οδηγό EPUB Converter PDF, βρίσκετε το παρακάτω άρθρο:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Μετατροπή EPUB σε PDF

Για να μετατρέψετε το EPUB σε μορφή αρχείου PDF, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο παράμετρο της μεθόδου ConvertEPUB. Εναλλακτικά, μπορούμε να χρησιμοποιήσουμε ροή εισόδου ή αντικείμενο Url. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer δεδομένων εξόδου. Μπορούμε επίσης να χρησιμοποιήσουμε πιο απλή εναλλακτική ως διαδρομή αρχείου εξόδου αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο PdfSaveOptions με αριθμό προτιμώμενων παραμέτρων όπως μέγεθος σελίδας, περιθώρια, CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης PdfSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο pdf. Πρέπει να περάσετε την πηγή του EPUB ως διαδρομή αρχείου ή ροή εισόδου, καθώς και το Url, την παρουσία PdfSaveOptions και το buffer δεδομένων εξόδου με οποιονδήποτε τρόπο για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το αντικείμενο [`configuration`](../../../com.aspose.html/configuration/) περιβάλλον που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Διαδικτυακός μετατροπέας EPUB σε PDF

Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter που μετατρέπει EPUB σε αρχείο PDF με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Ανοίξτε το υπάρχον αρχείο για ανάγνωση ως ροή  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Διαδρομή αρχείου αποτελέσματος φόρμας  
var resultPath = Path.Combine(OutputFolder, "sample.pdf"));  

// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new PdfSaveOptions();   

// Ξεκινήστε τη διαδικασία μετατροπής με την προεπιλεγμένη διαμόρφωση
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, PdfSaveOptions, String) {#convertepub_37}

Μετατρέψτε την πηγή EPUB που παρέχεται με ροή δεδομένων εισόδου. Το αποτέλεσμα είναι αρχείο pdf που δημιουργείται με τη διαδρομή εξόδου.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Διαδρομή αρχείου πηγής EPUB. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να σχηματίσει ένα απόλυτο URL. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | PdfSaveOptions | Επιλογές μετατροπής. Το αντικείμενο [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το [`μέγεθος σελίδας`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`περιθώρια`](../../../com.aspose.html.drawing/page/margin/), το [`τύπο μέσου CSS`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. Δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου .pdf ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε PDF

Το EPUB είναι μια μορφή αρχείου ηλεκτρονικού βιβλίου που παρέχει ένα τυποποιημένο ψηφιακό φορμά δημοσίευσης. Δημιουργείται από το International Digital Publishing Forum ([IDPF](http://idpf.org/)) και τώρα υποστηρίζεται από πολλούς αναγνώστες e‑book και λογισμικά. Η μετατροπή EPUB σε PDF συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή PDF. Η μορφή αρχείου PDF έχει πλήρη δυνατότητα να περιέχει πληροφορίες όπως κείμενο, εικόνες, υπερσυνδέσμους, πεδία φόρμας, πλούσιο πολυμέσο, μεταδεδομένα κ.λπ. Τα αρχεία PDF μπορούν να ανοιχτούν στο Adobe Acrobat Reader/Writer και στα περισσότερα σύγχρονα προγράμματα περιήγησης όπως Chrome, Safari, Firefox. Είναι βελτιστοποιημένα για εκτύπωση και είναι ιδανικά για τη δημιουργία φυσικών αντιτύπων των εγγράφων σας· μπορείτε επίσης να διαμορφώσετε τις ρυθμίσεις ασφαλείας για το PDF.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες για τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετη και εύκολη στη χρήση. Στον ειδικό οδηγό EPUB Converter PDF, βρίσκετε το παρακάτω άρθρο:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Μετατροπή EPUB σε PDF

Για να μετατρέψετε το EPUB σε μορφή αρχείου PDF, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο παράμετρο της μεθόδου ConvertEPUB. Εναλλακτικά, μπορούμε να χρησιμοποιήσουμε ροή εισόδου ή αντικείμενο Url. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer δεδομένων εξόδου. Μπορούμε επίσης να χρησιμοποιήσουμε πιο απλή εναλλακτική ως διαδρομή αρχείου εξόδου αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο PdfSaveOptions με αριθμό προτιμώμενων παραμέτρων όπως μέγεθος σελίδας, περιθώρια, CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης PdfSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο pdf. Πρέπει να περάσετε την πηγή του EPUB ως διαδρομή αρχείου ή ροή εισόδου, καθώς και το Url, την παρουσία PdfSaveOptions και το buffer δεδομένων εξόδου με οποιονδήποτε τρόπο για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το αντικείμενο [`configuration`](../../../com.aspose.html/configuration/) περιβάλλον που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Διαδικτυακός μετατροπέας EPUB σε PDF

Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter που μετατρέπει EPUB σε αρχείο PDF με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Διαδρομή αρχείου πηγής φόρμας
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Διαμορφώστε τη διαδρομή εξόδου του αποτελέσματος
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Δημιουργήστε προεπιλεγμένο αντικείμενο επιλογών
var options = new PdfSaveOptions();

// Αυξήστε τη διαδικασία μετατροπής με προεπιλεγμένη διαμόρφωση
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, PdfSaveOptions, String) {#convertepub_5}

Μετατρέψτε την πηγή EPUB που παρουσιάζεται από URL. Το αποτέλεσμα είναι αρχείο pdf που δημιουργείται από τη διαδρομή αρχείου εξόδου.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL πηγής EPUB - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| configuration | Configuration | Η διαμόρφωση του περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) context που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | PdfSaveOptions | Η χρήση του [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), τις [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. Δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Πλήρης διαδρομή αρχείου .pdf ως αποτέλεσμα εξόδου της μετατροπής. |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε PDF

Το EPUB είναι μια μορφή αρχείου ηλεκτρονικού βιβλίου που παρέχει ένα τυποποιημένο ψηφιακό φορμά δημοσίευσης. Δημιουργείται από το International Digital Publishing Forum ([IDPF](http://idpf.org/)) και τώρα υποστηρίζεται από πολλούς αναγνώστες e‑book και λογισμικά. Η μετατροπή EPUB σε PDF συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή PDF. Η μορφή αρχείου PDF έχει πλήρη δυνατότητα να περιέχει πληροφορίες όπως κείμενο, εικόνες, υπερσυνδέσμους, πεδία φόρμας, πλούσιο πολυμέσο, μεταδεδομένα κ.λπ. Τα αρχεία PDF μπορούν να ανοιχτούν στο Adobe Acrobat Reader/Writer και στα περισσότερα σύγχρονα προγράμματα περιήγησης όπως Chrome, Safari, Firefox. Είναι βελτιστοποιημένα για εκτύπωση και είναι ιδανικά για τη δημιουργία φυσικών αντιτύπων των εγγράφων σας· μπορείτε επίσης να διαμορφώσετε τις ρυθμίσεις ασφαλείας για το PDF.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες για τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετη και εύκολη στη χρήση. Στον ειδικό οδηγό EPUB Converter PDF, βρίσκετε το παρακάτω άρθρο:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Μετατροπή EPUB σε PDF

Για να μετατρέψετε το EPUB σε μορφή αρχείου PDF, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο παράμετρο της μεθόδου ConvertEPUB. Εναλλακτικά, μπορούμε να χρησιμοποιήσουμε ροή εισόδου ή αντικείμενο Url. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer δεδομένων εξόδου. Μπορούμε επίσης να χρησιμοποιήσουμε πιο απλή εναλλακτική ως διαδρομή αρχείου εξόδου αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο PdfSaveOptions με αριθμό προτιμώμενων παραμέτρων όπως μέγεθος σελίδας, περιθώρια, CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης PdfSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο pdf. Πρέπει να περάσετε την πηγή του EPUB ως διαδρομή αρχείου ή ροή εισόδου, καθώς και το Url, την παρουσία PdfSaveOptions και το buffer δεδομένων εξόδου με οποιονδήποτε τρόπο για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το αντικείμενο [`configuration`](../../../com.aspose.html/configuration/) περιβάλλον που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Διαδικτυακός μετατροπέας EPUB σε PDF

Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter που μετατρέπει EPUB σε αρχείο PDF με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

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
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Διαμορφώστε τη διαδρομή εξόδου του αποτελέσματος
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Δημιουργήστε προεπιλεγμένο αντικείμενο επιλογών
var options = new PdfSaveOptions();

// Αυξήστε τη διαδικασία μετατροπής με προεπιλεγμένη διαμόρφωση
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.



```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertepub_28}

Μετατρέψτε την πηγή EPUB που παρέχεται από ροή εισόδου δεδομένων. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή εισόδου ως πηγή μετατροπής. |
| options | PdfSaveOptions | Επιλογές μετατροπής. Το αντικείμενο [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το [`μέγεθος σελίδας`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`περιθώρια`](../../../com.aspose.html.drawing/page/margin/), το [`τύπο μέσου CSS`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. Δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Γνωστή (δείτε [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ή προσαρμοσμένη υλοποίηση του interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε PDF

Το EPUB είναι μια μορφή αρχείου ηλεκτρονικού βιβλίου που παρέχει ένα τυποποιημένο ψηφιακό φορμά δημοσίευσης. Δημιουργείται από το International Digital Publishing Forum ([IDPF](http://idpf.org/)) και τώρα υποστηρίζεται από πολλούς αναγνώστες e‑book και λογισμικά. Η μετατροπή EPUB σε PDF συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή PDF. Η μορφή αρχείου PDF έχει πλήρη δυνατότητα να περιέχει πληροφορίες όπως κείμενο, εικόνες, υπερσυνδέσμους, πεδία φόρμας, πλούσιο πολυμέσο, μεταδεδομένα κ.λπ. Τα αρχεία PDF μπορούν να ανοιχτούν στο Adobe Acrobat Reader/Writer και στα περισσότερα σύγχρονα προγράμματα περιήγησης όπως Chrome, Safari, Firefox. Είναι βελτιστοποιημένα για εκτύπωση και είναι ιδανικά για τη δημιουργία φυσικών αντιτύπων των εγγράφων σας· μπορείτε επίσης να διαμορφώσετε τις ρυθμίσεις ασφαλείας για το PDF.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες για τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετη και εύκολη στη χρήση. Στον ειδικό οδηγό EPUB Converter PDF, βρίσκετε το παρακάτω άρθρο:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Μετατροπή EPUB σε PDF

Για να μετατρέψετε το EPUB σε μορφή αρχείου PDF, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο παράμετρο της μεθόδου ConvertEPUB. Εναλλακτικά, μπορούμε να χρησιμοποιήσουμε ροή εισόδου ή αντικείμενο Url. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer δεδομένων εξόδου. Μπορούμε επίσης να χρησιμοποιήσουμε πιο απλή εναλλακτική ως διαδρομή αρχείου εξόδου αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο PdfSaveOptions με αριθμό προτιμώμενων παραμέτρων όπως μέγεθος σελίδας, περιθώρια, CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης PdfSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο pdf. Πρέπει να περάσετε την πηγή του EPUB ως διαδρομή αρχείου ή ροή εισόδου, καθώς και το Url, την παρουσία PdfSaveOptions και το buffer δεδομένων εξόδου με οποιονδήποτε τρόπο για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το αντικείμενο [`configuration`](../../../com.aspose.html/configuration/) περιβάλλον που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Διαδικτυακός μετατροπέας EPUB σε PDF

Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter που μετατρέπει EPUB σε αρχείο PDF με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Ανοίξτε το υπάρχον αρχείο για ανάγνωση ως ροή  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Αναφερθείτε στην υλοποίηση της διεπαφής ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new PdfSaveOptions ();   

// Ξεκινήστε τη διαδικασία μετατροπής  
Converter.ConvertEPUB(inputStream, options, sp);
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

## ConvertEPUB(String, PdfSaveOptions, ICreateStreamProvider) {#convertepub_44}

Μετατρέψτε την πηγή EPUB που παρέχεται από πλήρη διαδρομή αρχείου σε PDF. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Διαδρομή αρχείου πηγής EPUB. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να σχηματίσει ένα απόλυτο URL. |
| options | PdfSaveOptions | Επιλογές μετατροπής. Το αντικείμενο [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το [`μέγεθος σελίδας`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`περιθώρια`](../../../com.aspose.html.drawing/page/margin/), το [`τύπο μέσου CSS`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. Δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) που θα χρησιμοποιηθεί για την απόκτηση ροής εξόδου. Δείτε προχωρημένο παράδειγμα στην [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε PDF

Το EPUB είναι μια μορφή αρχείου ηλεκτρονικού βιβλίου που παρέχει ένα τυποποιημένο ψηφιακό φορμά δημοσίευσης. Δημιουργείται από το International Digital Publishing Forum ([IDPF](http://idpf.org/)) και τώρα υποστηρίζεται από πολλούς αναγνώστες e‑book και λογισμικά. Η μετατροπή EPUB σε PDF συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή PDF. Η μορφή αρχείου PDF έχει πλήρη δυνατότητα να περιέχει πληροφορίες όπως κείμενο, εικόνες, υπερσυνδέσμους, πεδία φόρμας, πλούσιο πολυμέσο, μεταδεδομένα κ.λπ. Τα αρχεία PDF μπορούν να ανοιχτούν στο Adobe Acrobat Reader/Writer και στα περισσότερα σύγχρονα προγράμματα περιήγησης όπως Chrome, Safari, Firefox. Είναι βελτιστοποιημένα για εκτύπωση και είναι ιδανικά για τη δημιουργία φυσικών αντιτύπων των εγγράφων σας· μπορείτε επίσης να διαμορφώσετε τις ρυθμίσεις ασφαλείας για το PDF.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες για τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετη και εύκολη στη χρήση. Στον ειδικό οδηγό EPUB Converter PDF, βρίσκετε το παρακάτω άρθρο:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Μετατροπή EPUB σε PDF

Για να μετατρέψετε το EPUB σε μορφή αρχείου PDF, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο παράμετρο της μεθόδου ConvertEPUB. Εναλλακτικά, μπορούμε να χρησιμοποιήσουμε ροή εισόδου ή αντικείμενο Url. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer δεδομένων εξόδου. Μπορούμε επίσης να χρησιμοποιήσουμε πιο απλή εναλλακτική ως διαδρομή αρχείου εξόδου αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο PdfSaveOptions με αριθμό προτιμώμενων παραμέτρων όπως μέγεθος σελίδας, περιθώρια, CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης PdfSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο pdf. Πρέπει να περάσετε την πηγή του EPUB ως διαδρομή αρχείου ή ροή εισόδου, καθώς και το Url, την παρουσία PdfSaveOptions και το buffer δεδομένων εξόδου με οποιονδήποτε τρόπο για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το αντικείμενο [`configuration`](../../../com.aspose.html/configuration/) περιβάλλον που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Διαδικτυακός μετατροπέας EPUB σε PDF

Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter που μετατρέπει EPUB σε αρχείο PDF με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

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
var sourcePath = Path.Combine(InputFolder, "sample.epub");  

// Αναφερθείτε στην υλοποίηση της διεπαφής ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new PdfSaveOptions();   

// Ξεκινήστε τη διαδικασία μετατροπής  
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, PdfSaveOptions, ICreateStreamProvider) {#convertepub_12}

Μετατρέψτε την πηγή EPUB που παρουσιάζεται με URL. Το αποτέλεσμα είναι δεδομένα εξόδου που σχηματίζονται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL πηγής EPUB - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| options | PdfSaveOptions | Η χρήση του [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), τις [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. Δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση της διεπαφής [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider) που θα χρησιμοποιηθεί για την απόκτηση ροής εξόδου. Δείτε προχωρημένο παράδειγμα στην [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε PDF

Το EPUB είναι μια μορφή αρχείου ηλεκτρονικού βιβλίου που παρέχει ένα τυποποιημένο ψηφιακό φορμά δημοσίευσης. Δημιουργείται από το International Digital Publishing Forum ([IDPF](http://idpf.org/)) και τώρα υποστηρίζεται από πολλούς αναγνώστες e‑book και λογισμικά. Η μετατροπή EPUB σε PDF συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή PDF. Η μορφή αρχείου PDF έχει πλήρη δυνατότητα να περιέχει πληροφορίες όπως κείμενο, εικόνες, υπερσυνδέσμους, πεδία φόρμας, πλούσιο πολυμέσο, μεταδεδομένα κ.λπ. Τα αρχεία PDF μπορούν να ανοιχτούν στο Adobe Acrobat Reader/Writer και στα περισσότερα σύγχρονα προγράμματα περιήγησης όπως Chrome, Safari, Firefox. Είναι βελτιστοποιημένα για εκτύπωση και είναι ιδανικά για τη δημιουργία φυσικών αντιτύπων των εγγράφων σας· μπορείτε επίσης να διαμορφώσετε τις ρυθμίσεις ασφαλείας για το PDF.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες για τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετη και εύκολη στη χρήση. Στον ειδικό οδηγό EPUB Converter PDF, βρίσκετε το παρακάτω άρθρο:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Μετατροπή EPUB σε PDF

Για να μετατρέψετε το EPUB σε μορφή αρχείου PDF, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο παράμετρο της μεθόδου ConvertEPUB. Εναλλακτικά, μπορούμε να χρησιμοποιήσουμε ροή εισόδου ή αντικείμενο Url. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer δεδομένων εξόδου. Μπορούμε επίσης να χρησιμοποιήσουμε πιο απλή εναλλακτική ως διαδρομή αρχείου εξόδου αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο PdfSaveOptions με αριθμό προτιμώμενων παραμέτρων όπως μέγεθος σελίδας, περιθώρια, CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης PdfSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο pdf. Πρέπει να περάσετε την πηγή του EPUB ως διαδρομή αρχείου ή ροή εισόδου, καθώς και το Url, την παρουσία PdfSaveOptions και το buffer δεδομένων εξόδου με οποιονδήποτε τρόπο για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το αντικείμενο [`configuration`](../../../com.aspose.html/configuration/) περιβάλλον που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Διαδικτυακός μετατροπέας EPUB σε PDF

Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter που μετατρέπει EPUB σε αρχείο PDF με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

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
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Αναφερθείτε στην υλοποίηση της διεπαφής ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));

// Δημιουργήστε προεπιλεγμένο αντικείμενο επιλογών
var options = new PdfSaveOptions();

// Ξεκινήστε τη διαδικασία μετατροπής
Converter.ConvertEPUB(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_20}

Μετατρέψτε την πηγή EPUB που παρέχεται από ροή εισόδου δεδομένων. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή εισόδου ως πηγή μετατροπής. |
| configuration | Configuration | Η διαμόρφωση περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο περιβάλλοντος [`configuration`](../../../com.aspose.html/configuration/) που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | PdfSaveOptions | Επιλογές μετατροπής. Το αντικείμενο [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το [`μέγεθος σελίδας`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`περιθώρια`](../../../com.aspose.html.drawing/page/margin/), το [`τύπο μέσου CSS`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. Δείτε [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) που θα χρησιμοποιηθεί για την απόκτηση ροής εξόδου. Δείτε προχωρημένο παράδειγμα στην [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε PDF

Το EPUB είναι μια μορφή αρχείου ηλεκτρονικού βιβλίου που παρέχει ένα τυποποιημένο ψηφιακό φορμά δημοσίευσης. Δημιουργείται από το International Digital Publishing Forum ([IDPF](http://idpf.org/)) και τώρα υποστηρίζεται από πολλούς αναγνώστες e‑book και λογισμικά. Η μετατροπή EPUB σε PDF συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή PDF. Η μορφή αρχείου PDF έχει πλήρη δυνατότητα να περιέχει πληροφορίες όπως κείμενο, εικόνες, υπερσυνδέσμους, πεδία φόρμας, πλούσιο πολυμέσο, μεταδεδομένα κ.λπ. Τα αρχεία PDF μπορούν να ανοιχτούν στο Adobe Acrobat Reader/Writer και στα περισσότερα σύγχρονα προγράμματα περιήγησης όπως Chrome, Safari, Firefox. Είναι βελτιστοποιημένα για εκτύπωση και είναι ιδανικά για τη δημιουργία φυσικών αντιτύπων των εγγράφων σας· μπορείτε επίσης να διαμορφώσετε τις ρυθμίσεις ασφαλείας για το PDF.

Το κύριο χαρακτηριστικό του Aspose.HTML είναι η λειτουργία μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και εκδόσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο [`com.aspose.html.converters`](../) παρέχει εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες για τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετη και εύκολη στη χρήση. Στον ειδικό οδηγό EPUB Converter PDF, βρίσκετε το παρακάτω άρθρο:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Μετατροπή EPUB σε PDF

Για να μετατρέψετε το EPUB σε μορφή αρχείου PDF, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο παράμετρο της μεθόδου ConvertEPUB. Εναλλακτικά, μπορούμε να χρησιμοποιήσουμε ροή εισόδου ή αντικείμενο Url. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer δεδομένων εξόδου. Μπορούμε επίσης να χρησιμοποιήσουμε πιο απλή εναλλακτική ως διαδρομή αρχείου εξόδου αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο PdfSaveOptions με αριθμό προτιμώμενων παραμέτρων όπως μέγεθος σελίδας, περιθώρια, CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης PdfSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο pdf. Πρέπει να περάσετε την πηγή του EPUB ως διαδρομή αρχείου ή ροή εισόδου, καθώς και το Url, την παρουσία PdfSaveOptions και το buffer δεδομένων εξόδου με οποιονδήποτε τρόπο για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το αντικείμενο [`configuration`](../../../com.aspose.html/configuration/) περιβάλλον που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Διαδικτυακός μετατροπέας EPUB σε PDF

Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter που μετατρέπει EPUB σε αρχείο PDF με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Ανοίξτε το υπάρχον αρχείο για ανάγνωση ως ροή  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Αναφερθείτε στην υλοποίηση της διεπαφής ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new PdfSaveOptions ();   

// Ξεκινήστε τη διαδικασία μετατροπής με το προεπιλεγμένο αντικείμενο διαμόρφωσης  
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
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

## ConvertEPUB(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_36}

Μετατρέψτε την πηγή EPUB που παρουσιάζεται με πλήρη διαδρομή αρχείου σε PDF. Το αποτέλεσμα είναι δεδομένα εξόδου που δημιουργούνται από την υλοποίηση της διεπαφής ICreateStreamProvider.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourcePath | String | Διαδρομή αρχείου πηγής EPUB. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να σχηματίσει ένα απόλυτο URL. |
| configuration | Configuration | Η διαμόρφωση του περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) context που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | PdfSaveOptions | Επιλογές μετατροπής. Η χρήση του αντικειμένου [PdfSaveOption](https://apireference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το μέγεθος σελίδας, τα περιθώρια, το CSS, κ.λπ. Δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση της διεπαφής [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider) που θα χρησιμοποιηθεί για την απόκτηση ροής εξόδου. Δείτε προχωρημένο παράδειγμα στην [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε PDF

Το EPUB είναι μια μορφή αρχείου ηλεκτρονικού βιβλίου που παρέχει ένα τυποποιημένο ψηφιακό φορμά δημοσίευσης. Δημιουργείται από το International Digital Publishing Forum ([IDPF](http://idpf.org/)) και τώρα υποστηρίζεται από πολλούς αναγνώστες e‑book και λογισμικά. Η μετατροπή EPUB σε PDF συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή PDF. Η μορφή αρχείου PDF έχει πλήρη δυνατότητα να περιέχει πληροφορίες όπως κείμενο, εικόνες, υπερσυνδέσμους, πεδία φόρμας, πλούσιο πολυμέσο, μεταδεδομένα κ.λπ. Τα αρχεία PDF μπορούν να ανοιχτούν στο Adobe Acrobat Reader/Writer και στα περισσότερα σύγχρονα προγράμματα περιήγησης όπως Chrome, Safari, Firefox. Είναι βελτιστοποιημένα για εκτύπωση και είναι ιδανικά για τη δημιουργία φυσικών αντιτύπων των εγγράφων σας· μπορείτε επίσης να διαμορφώσετε τις ρυθμίσεις ασφαλείας για το PDF.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες για τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετη και εύκολη στη χρήση. Στον ειδικό οδηγό EPUB Converter PDF, βρίσκετε το παρακάτω άρθρο:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Μετατροπή EPUB σε PDF

Για να μετατρέψετε το EPUB σε μορφή αρχείου PDF, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο παράμετρο της μεθόδου ConvertEPUB. Εναλλακτικά, μπορούμε να χρησιμοποιήσουμε ροή εισόδου ή αντικείμενο Url. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer δεδομένων εξόδου. Μπορούμε επίσης να χρησιμοποιήσουμε πιο απλή εναλλακτική ως διαδρομή αρχείου εξόδου αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο PdfSaveOptions με αριθμό προτιμώμενων παραμέτρων όπως μέγεθος σελίδας, περιθώρια, CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης PdfSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο pdf. Πρέπει να περάσετε την πηγή του EPUB ως διαδρομή αρχείου ή ροή εισόδου, καθώς και το Url, την παρουσία PdfSaveOptions και το buffer δεδομένων εξόδου με οποιονδήποτε τρόπο για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το αντικείμενο [`configuration`](../../../com.aspose.html/configuration/) περιβάλλον που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Διαδικτυακός μετατροπέας EPUB σε PDF

Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter που μετατρέπει EPUB σε αρχείο PDF με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

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
var sourcePath = Path.Combine(InputFolder, "sample.epub");  

// Αναφερθείτε στην υλοποίηση της διεπαφής ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Δημιουργήστε προεπιλεγμένη παρουσία επιλογών  
var options = new PdfSaveOptions();   

// Ξεκινήστε τη διαδικασία μετατροπής με το προεπιλεγμένο αντικείμενο διαμόρφωσης 
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);





*InputFolder - user source file path.

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

## ConvertEPUB(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_4}

Μετατρέψτε την πηγή EPUB που παρουσιάζεται με URL. Το αποτέλεσμα είναι δεδομένα εξόδου που σχηματίζονται από την υλοποίηση της διεπαφής [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceUrl | Url | URL πηγής EPUB - παρέχει μια αντικειμενική αναπαράσταση ενός καθολικού αναγνωριστικού (URL). |
| configuration | Configuration | Η διαμόρφωση του περιβάλλοντος. Αντιπροσωπεύει το αντικείμενο [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) context που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. |
| options | PdfSaveOptions | Η χρήση του [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης· μπορείτε να καθορίσετε το [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), τα [`margins`](../../../com.aspose.html.drawing/page/margin/), τις [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), το [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), κ.λπ. Δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Υλοποίηση της διεπαφής [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider) που θα χρησιμοποιηθεί για την απόκτηση ροής εξόδου. Δείτε προχωρημένο παράδειγμα στην [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Παρατηρήσεις

Πώς να μετατρέψετε EPUB σε PDF

Το EPUB είναι μια μορφή αρχείου ηλεκτρονικού βιβλίου που παρέχει ένα τυποποιημένο ψηφιακό φορμά δημοσίευσης. Δημιουργείται από το International Digital Publishing Forum ([IDPF](http://idpf.org/)) και τώρα υποστηρίζεται από πολλούς αναγνώστες e‑book και λογισμικά. Η μετατροπή EPUB σε PDF συχνά απαιτείται για να εκμεταλλευτείτε τη μορφή PDF. Η μορφή αρχείου PDF έχει πλήρη δυνατότητα να περιέχει πληροφορίες όπως κείμενο, εικόνες, υπερσυνδέσμους, πεδία φόρμας, πλούσιο πολυμέσο, μεταδεδομένα κ.λπ. Τα αρχεία PDF μπορούν να ανοιχτούν στο Adobe Acrobat Reader/Writer και στα περισσότερα σύγχρονα προγράμματα περιήγησης όπως Chrome, Safari, Firefox. Είναι βελτιστοποιημένα για εκτύπωση και είναι ιδανικά για τη δημιουργία φυσικών αντιτύπων των εγγράφων σας· μπορείτε επίσης να διαμορφώσετε τις ρυθμίσεις ασφαλείας για το PDF.

Το κύριο χαρακτηριστικό της Aspose.HTML είναι η δυνατότητα μετατροπής. Το EPUB είναι μια ανοιχτή μορφή βασισμένη σε XML για ψηφιακά βιβλία και δημοσιεύσεις, η οποία μπορεί να προβληθεί και να διαβαστεί σε smartphones, tablets και υπολογιστές. Το πακέτο com.aspose.html.converters υλοποιεί εύκολη πρόσβαση σε μεθόδους μετατροπής. Παρέχει μια ευρεία γκάμα μετατροπών [EPUB](https://docs.fileformat.com/ebook/epub/) σε δημοφιλείς μορφές, όπως [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), και [GIF](https://docs.fileformat.com/image/gif/).

Αυτή η ενότητα παρέχει πληροφορίες για τη λίστα των υποστηριζόμενων σεναρίων μετατροπής EPUB και πώς να τα εκτελέσετε χρησιμοποιώντας μια κλάση [`Converter`](../) που ομαδοποιεί όλες τις χαμηλού επιπέδου λειτουργίες μετατροπής σε μία κλάση για να είναι άνετη και εύκολη στη χρήση. Στον ειδικό οδηγό EPUB Converter PDF, βρίσκετε το παρακάτω άρθρο:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Μετατροπή EPUB σε PDF

Για να μετατρέψετε το EPUB σε μορφή αρχείου PDF, πρέπει να ακολουθήσετε μερικά βήματα:

Ανοίξτε ένα υπάρχον αρχείο EPUB. Για παράδειγμα, μπορούμε να ορίσουμε τη διαδρομή του αρχείου προέλευσης ως πρώτο παράμετρο της μεθόδου ConvertEPUB. Εναλλακτικά, μπορούμε να χρησιμοποιήσουμε ροή εισόδου ή αντικείμενο Url. Χρησιμοποιήστε γνωστή ή προσαρμοσμένη υλοποίηση της διεπαφής ICreateStreamProvider ως buffer δεδομένων εξόδου. Μπορούμε επίσης να χρησιμοποιήσουμε πιο απλή εναλλακτική ως διαδρομή αρχείου εξόδου αποτελέσματος. Δημιουργήστε ένα νέο αντικείμενο PdfSaveOptions με αριθμό προτιμώμενων παραμέτρων όπως μέγεθος σελίδας, περιθώρια, CSS κ.λπ. Είναι δυνατόν να χρησιμοποιήσετε την προεπιλεγμένη παρουσία της κλάσης PdfSaveOptions. Χρησιμοποιήστε τη μέθοδο ConvertEPUB() της στατικής κλάσης Converter για να αποθηκεύσετε το EPUB ως αρχείο pdf. Πρέπει να περάσετε την πηγή του EPUB ως διαδρομή αρχείου ή ροή εισόδου, καθώς και το Url, την παρουσία PdfSaveOptions και το buffer δεδομένων εξόδου με οποιονδήποτε τρόπο για να ξεκινήσετε τη διαδικασία μετατροπής. Μπορείτε να χρησιμοποιήσετε τη διαμόρφωση που αντιπροσωπεύει το αντικείμενο [`configuration`](../../../com.aspose.html/configuration/) περιβάλλον που χρησιμοποιείται για τη ρύθμιση των ρυθμίσεων του περιβάλλοντος για την εφαρμογή. Διαδικτυακός μετατροπέας EPUB σε PDF

Aspose.HTML προσφέρει έναν δωρεάν διαδικτυακό [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) Converter που μετατρέπει EPUB σε αρχείο PDF με υψηλή ποιότητα, εύκολα και γρήγορα. Απλώς ανεβάστε, μετατρέψτε τα αρχεία σας και λάβετε τα αποτελέσματα σε λίγα δευτερόλεπτα!

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Παραδείγματα

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Δημιουργήστε Url βάσει διαδρομής αρχείου εισόδου
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Αναφερθείτε στην υλοποίηση της διεπαφής ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));

// Δημιουργήστε προεπιλεγμένο αντικείμενο επιλογών
var options = new PdfSaveOptions();

// Ξεκινήστε τη διαδικασία μετατροπής με το προεπιλεγμένο αντικείμενο configuration
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);
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
