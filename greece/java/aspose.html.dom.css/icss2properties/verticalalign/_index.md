---
title: "ICSS2Properties.VerticalAlign"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Ιδιότητα ICSS2Properties. Αυτή η ιδιότητα επηρεάζει την κάθετη τοποθέτηση μέσα σε ένα line box των κουτιών που δημιουργούνται από ένα inline-level element. Οι παρακάτω τιμές έχουν νόημα μόνο σε σχέση με ένα γονικό inline-level element ή με ένα γονικό block-level element εάν το στοιχείο αυτό δημιουργεί anonymous inline boxes· δεν έχουν καμία επίδραση εάν δεν υπάρχει τέτοιος γονέας."
type: docs

url: /el/java/com.aspose.html.dom.css/icss2properties/verticalalign/
---
## ICSS2Properties.VerticalAlign property

Αυτή η ιδιότητα επηρεάζει την κάθετη τοποθέτηση μέσα σε ένα line box των κουτιών που δημιουργούνται από ένα inline-level element. Οι παρακάτω τιμές έχουν νόημα μόνο σε σχέση με ένα γονικό inline-level element ή με ένα γονικό block-level element, εάν το στοιχείο αυτό δημιουργεί [anonymous inline boxes](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#anonymous); δεν έχουν καμία επίδραση εάν δεν υπάρχει τέτοιος γονέας.

Σημείωση. Οι τιμές αυτής της ιδιότητας έχουν ελαφρώς διαφορετικές σημασίες στο πλαίσιο των πινάκων. Παρακαλούμε ανατρέξτε στην ενότητα σχετικά με [table height algorithms](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#height-layout) για λεπτομέρειες. baseline - Ευθυγραμμίζει τη βάση του κουτιού με τη βάση του γονικού κουτιού. Εάν το κουτί δεν έχει βάση, ευθυγραμμίζει το κάτω μέρος του κουτιού με τη βάση του γονέα. middle - Ευθυγραμμίζει το κάθετο μέσο του κουτιού με τη βάση του γονικού κουτιού συν το μισό του x-height του γονέα. sub - Κατεβάζει τη βάση του κουτιού στην κατάλληλη θέση για δείκτες υποσυνόλων του γονικού κουτιού. (Αυτή η τιμή δεν επηρεάζει το μέγεθος γραμματοσειράς του κειμένου του στοιχείου.) super - Σηκώνει τη βάση του κουτιού στην κατάλληλη θέση για εκθέτες του γονικού κουτιού. (Αυτή η τιμή δεν επηρεάζει το μέγεθος γραμματοσειράς του κειμένου του στοιχείου.) text-top - Ευθυγραμμίζει την κορυφή του κουτιού με την κορυφή της γραμματοσειράς του γονικού στοιχείου. text-bottom - Ευθυγραμμίζει το κάτω μέρος του κουτιού με το κάτω μέρος της γραμματοσειράς του γονικού στοιχείου. '[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - Ανεβάζει (θετική τιμή) ή κατεβάζει (αρνητική τιμή) το κουτί κατά αυτήν την απόσταση (ποσοστό του ['line-height'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-line-height) τιμής). Η τιμή '0%' σημαίνει το ίδιο με 'baseline'. '[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' - Ανεβάζει (θετική τιμή) ή κατεβάζει (αρνητική τιμή) το κουτί κατά αυτήν την απόσταση. Η τιμή '0cm' σημαίνει το ίδιο με 'baseline'. top - Ευθυγραμμίζει την κορυφή του κουτιού με την κορυφή του line box. bottom - Ευθυγραμμίζει το κάτω μέρος του κουτιού με το κάτω μέρος του line box.

```java
public String VerticalAlign { get; set; }
```

### Τιμή επιστροφής

ιδιότητα vertical-align

### Δείτε επίσης

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
