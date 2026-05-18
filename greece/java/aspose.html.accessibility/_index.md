---
title: "com.aspose.html.accessibility"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Το πακέτο com.aspose.html.accessibility προορίζεται για όλες τις σχετικές με την προσβασιμότητα ιστού χειρονομίες. Συμμορφώνεται με τα διεθνή πρότυπα του W3C Web Accessibility Initiative"
type: docs

url: /el/java/com.aspose.html.accessibility/
---
Το **com.aspose.html.accessibility** πακέτο είναι για όλες τις σχετικές με την προσβασιμότητα ιστού επεμβάσεις. Συμμορφώνεται με τα διεθνή πρότυπα W3C Web Accessibility Initiative

## Κλάσεις

| Κλάση | Περιγραφή |
| --- | --- |
| [AccessibilityRules](./accessibilityrules/) | Γρήγορη αναφορά στις Οδηγίες Προσβασιμότητας Περιεχομένου Ιστού (WCAG) 2 απαιτήσεις (κριτήρια επιτυχίας) και τεχνικές. Περιέχει μια λίστα αρχών. https://www.w3.org/WAI/WCAG21/quickref/ |
| [AccessibilityValidator](./accessibilityvalidator/) | Η κλάση validator διαχειρίζεται τους κανόνες γρήγορης αναφοράς. Περιέχει μια μέθοδο Validate για να ελέγξει την προσβασιμότητα. |
| [Criterion](./criterion/) | Παρέχονται επαληθεύσιμα κριτήρια επιτυχίας για κάθε σύσταση, ώστε το WCAG 2.0 να μπορεί να εφαρμοστεί σε περιοχές όπου απαιτείται έλεγχος συμμόρφωσης. https://www.w3.org/WAI/WCAG21/Understanding/understanding-techniques |
| [Guideline](./guideline/) | Οδηγίες - το επόμενο επίπεδο μετά τις αρχές. Δεν είναι δοκιμαστικές, αλλά περιγράφουν πλαίσια και γενικούς στόχους που βοηθούν τους συγγραφείς να κατανοήσουν τα κριτήρια επιτυχίας και να εφαρμόσουν καλύτερα τις τεχνικές. Οι οδηγίες είναι μια λίστα κριτηρίων αποδοχής με τύπο RuleDirectory{Criterion}. |
| [Principle](./principle/) | Αρχή Προσβασιμότητας - Τα υψηλότερα επίπεδα που παρέχουν τη βάση της προσβασιμότητας ιστού, περιέχουν μια λίστα οδηγιών με τύπο RuleCollection{Guideline}. Το αντικείμενο δεν επιτρέπεται να δημιουργηθεί εκτός του assembly. https://www.w3.org/WAI/fundamentals/accessibility-principles/ |
| [Rule](./rule/) | Μια αφηρημένη κλάση που ορίζει τα χαρακτηριστικά ενός Rule και υλοποιεί τη διεπαφή IRule |
| [Target](./target/) | Η κλάση περιέχει το στοιχείο html ή css όπου βρέθηκε το σφάλμα. |
| [ValidationBuilder](./validationbuilder/) | Η κλάση ValidationBuilder παρέχει συγκεκριμένες υλοποιήσεις των βημάτων διαμόρφωσης. Ορίζει μεθόδους και ρυθμίσεις για μια κλάση ValidationSettings. |
| [WebAccessibility](./webaccessibility/) | Αντικείμενο για τις Οδηγίες Προσβασιμότητας Περιεχομένου Ιστού (WCAG) 2 απαιτήσεις (κριτήρια επιτυχίας) και τεχνικές. https://www.w3.org/WAI/WCAG21/quickref/ |
## Διεπαφές

| Διεπαφή | Περιγραφή |
| --- | --- |
| [IError](./ierror/) | Η διεπαφή περιγράφει το σφάλμα της επικύρωσης |
| [IRule](./irule/) | Διεπαφή που περιγράφει τις κύριες ιδιότητες των κανόνων. |
| [ITechniqueResult](./itechniqueresult/) | Περιγράφει το αποτέλεσμα της επικύρωσης της τεχνικής. |
## Απαρίθμηση

| Απαρίθμηση | Περιγραφή |
| --- | --- |
| [TargetTypes](./targettypes/) | Απαρίθμηση τύπων του αντικειμένου που προκύπτει από το έγγραφο html που περιέχει το σφάλμα. |
