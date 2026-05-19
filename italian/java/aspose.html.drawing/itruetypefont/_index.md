---
title: "Interfaccia ITrueTypeFont"
second_title: "Riferimento API Aspose.HTML per Java"
description: "interfaccia com.aspose.html.drawing.ITrueTypeFont. Dichiara i metodi per lavorare con i font TrueType"
type: docs

url: /it/java/com.aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

Dichiara i metodi per lavorare con i font TrueType.

```java
public interface ITrueTypeFont
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getDataSize](../../com.aspose.html.drawing/itruetypefont/datasize/) Restituisce la dimensione dei dati del font in byte |
| [getFamilyName](../../com.aspose.html.drawing/itruetypefont/familyname/) Ottieni il nome della famiglia del font. |
| [getFullFontName](../../com.aspose.html.drawing/itruetypefont/fullfontname/) Questo dovrebbe essere una combinazione di \"FamilyName\" e \"SubFamilyName\". Eccezione: se il font è \"Regular\" come indicato in \"SubFamilyName\", allora usare solo il nome della famiglia contenuto in \"FamilyName\". Un'eccezione alla definizione sopra del nome completo del font riguarda le stringhe della piattaforma Microsoft per i font CFF OpenType: in questo caso, la stringa del nome completo del font deve essere identica al PostScript FontName nell'indice CFF Name INDEX. |
| [getSubFamilyName](../../com.aspose.html.drawing/itruetypefont/subfamilyname/) Il nome della sottoclasse del font distingue il font in un gruppo con lo stesso nome della famiglia del font. Si presume che questo indichi lo stile (italic, oblique) e il peso (light, bold, black, ecc.). Un font senza particolari differenze di peso o stile (ad esempio peso medio, non italic e bit 6 di fsSelection impostato) dovrebbe avere la stringa \"Regular\" memorizzata in questa posizione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getAscent](../../com.aspose.html.drawing/itruetypefont/getascent/)(float) | Restituisce l'ascesa, in punti. |
| [getData](../../com.aspose.html.drawing/itruetypefont/getdata/)() | Apri lo stream con i dati del font. Chi chiama è responsabile della chiusura dello stream. |
| [getDescent](../../com.aspose.html.drawing/itruetypefont/getdescent/)(float) | Restituisce la discesa, in punti. |

### Vedi anche

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
