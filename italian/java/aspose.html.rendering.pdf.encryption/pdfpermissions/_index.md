---
title: "PdfPermissions Enum"
second_title: "Aspose.HTML per Java Riferimento API"
description: "com.aspose.html.rendering.pdf.encryption.PdfPermissions enum. Questo enum rappresenta le autorizzazioni degli utenti per un PDF"
type: docs

url: /it/java/com.aspose.html.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

Questo enum rappresenta i permessi dell'utente per un PDF.

```java
[Flags]
public enum PdfPermissions
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| PrintDocument | `4` | (Gestori di sicurezza della revisione 2) Stampa il documento. (Gestori di sicurezza della revisione 3 o successive) Stampa il documento (potenzialmente non al livello di qualità più alto, a seconda se PrintingQuality è anche impostato). |
| ModifyContent | `8` | Modifica il contenuto del documento mediante operazioni diverse da quelle controllate da ModifyTextAnnotations, FillForm e 11. |
| ExtractContent | `10` | (Gestori di sicurezza della revisione 2) Copia o estrae in altro modo testo e grafica dal documento, includendo l'estrazione di testo e grafica (a supporto dell'accessibilità per utenti con disabilità o per altri scopi). (Gestori di sicurezza della revisione 3 o successive) Copia o estrae in altro modo testo e grafica dal documento mediante operazioni diverse da quelle controllate da ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | Aggiungi o modifica annotazioni di testo, compila campi di modulo interattivi e, se ModifyContent è anche impostato, crea o modifica campi di modulo interattivi (inclusi i campi firma). |
| FillForm | `100` | (Gestori di sicurezza della revisione 3 o successive) Compila i campi di modulo interattivi esistenti (inclusi i campi firma), anche se ModifyTextAnnotations è disattivato. |
| ExtractContentWithDisabilities | `200` | (Gestori di sicurezza della revisione 3 o successive) Estrai testo e grafica (a supporto dell'accessibilità per utenti con disabilità o per altri scopi). |
| AssembleDocument | `400` | (Gestori di sicurezza della revisione 3 o successive) Assembla il documento (inserisci, ruota o elimina pagine e crea segnalibri o miniature), anche se ModifyContent è disattivato. |
| PrintingQuality | `800` | (Gestori di sicurezza della revisione 3 o successive) Stampa il documento in una rappresentazione da cui può essere generata una copia digitale fedele del contenuto PDF. Quando questo bit è disattivato (e il bit 3 è impostato), la stampa è limitata a una rappresentazione di basso livello dell'aspetto, possibilmente di qualità degradata. |

### Vedi anche

* package [com.aspose.html.rendering.pdf.encryption](../../com.aspose.html.rendering.pdf.encryption/)
* package [Aspose.HTML](../../)
