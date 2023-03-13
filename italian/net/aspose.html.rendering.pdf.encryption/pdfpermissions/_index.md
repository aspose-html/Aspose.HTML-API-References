---
title: Enum PdfPermissions
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Rendering.Pdf.Encryption.PdfPermissions enum. Questo enum rappresenta le autorizzazioni dellutente per un pdf.
type: docs
weight: 4420
url: /it/net/aspose.html.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

Questo enum rappresenta le autorizzazioni dell'utente per un pdf.

```csharp
[Flags]
public enum PdfPermissions
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| PrintDocument | `4` | (Gestori di sicurezza della revisione 2) Stampa il documento. (Gestori di sicurezza della revisione 3 o successiva) Stampa il documento (possibilmente non al massimo livello di qualità, a seconda che sia impostato anche PrintingQuality). |
| ModifyContent | `8` | Modifica il contenuto del documento con operazioni diverse da quelle controllate da ModifyTextAnnotations, FillForm e 11. |
| ExtractContent | `10` | Gestori della sicurezza della revisione 2) Copiare o altrimenti estrarre testo e grafica dal documento, inclusa l'estrazione di testo e grafica (a supporto dell'accessibilità agli utenti con disabilità o per altri scopi). (Gestori della sicurezza della revisione 3 o successiva) Copia o altrimenti estrarre testo e grafica dal documento mediante operazioni diverse da quelle controllate da ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | Aggiungere o modificare annotazioni di testo, compilare campi modulo interattivi e, se è impostato anche ModifyContent, creare o modificare campi modulo interattivi (compresi i campi firma). |
| FillForm | `100` | (Gestori di sicurezza della revisione 3 o successiva) Compila i campi del modulo interattivo esistenti (inclusi i campi della firma), anche se ModifyTextAnnotations è chiaro. |
| ExtractContentWithDisabilities | `200` | (Gestori di sicurezza della revisione 3 o superiore) Estrarre testo e grafica (a supporto dell'accessibilità per utenti con disabilità o per altri scopi). |
| AssembleDocument | `400` | (Gestori di sicurezza della revisione 3 o successiva) Assembla il documento (inserisci, ruota o elimina pagine e crea segnalibri o immagini in miniatura), anche se ModifyContent è chiaro. |
| PrintingQuality | `800` | (Gestori di sicurezza della revisione 3 o successiva) Stampa il documento in una rappresentazione da cui potrebbe essere generata una copia digitale fedele del contenuto PDF. Quando questo bit è azzerato (e il bit 3 è impostato), la stampa è limitata a un valore basso rappresentazione a livello dell'aspetto, possibilmente di qualità degradata. |

### Guarda anche

* spazio dei nomi [Aspose.Html.Rendering.Pdf.Encryption](../../aspose.html.rendering.pdf.encryption/)
* assemblea [Aspose.HTML](../../)


