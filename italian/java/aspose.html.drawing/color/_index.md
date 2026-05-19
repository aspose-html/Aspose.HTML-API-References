---
title: "Classe Color"
second_title: "Riferimento API Aspose.HTML per Java"
description: "classe com.aspose.html.drawing.Color. La classe Color consente di specificare i colori come valori Red-Green-Blue RGB, valori Hue-Saturation-Luminosity HSL, valori Hue-Saturation-Value HSV, valori Hue-Whiteness-Blackness HWB, valori lightness-A-B LAB, valori Luminance-Chroma-Hue LCH, valori Cyan-Magenta-Yellow-Key CMYK, valori Natural colors NCOL o con un nome di colore. È disponibile anche un canale Alpha per indicare la trasparenza."
type: docs

url: /it/java/com.aspose.html.drawing/color/
---
## Color class

La classe Color consente di specificare i colori come valori Red-Green-Blue (RGB), Hue-Saturation-Luminosity (HSL), Hue-Saturation-Value (HSV), Hue-Whiteness-Blackness (HWB), valori lightness-A-B (LAB), Luminance-Chroma-Hue (LCH), Cyan-Magenta-Yellow-Key (CMYK), Natural colors (NCOL) o con un nome di colore. È disponibile anche un canale Alpha per indicare la trasparenza.

```java
public class Color
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Color](color/#constructor)() | Inizializza una nuova istanza della classe `Color`. Per impostazione predefinita il colore è nero. |
| [Color](color/#constructor_1)(byte, byte, byte) | Inizializza una nuova istanza della classe `Color`. Tutti i componenti di colore devono essere nell'intervallo 0-255. |
| [Color](color/#constructor_5)(float, float, float) | Inizializza una nuova istanza della classe `Color`. Tutti i componenti di colore devono essere nell'intervallo 0-1. |
| [Color](color/#constructor_3)(int, int, int) | Inizializza una nuova istanza della classe `Color`. Tutti i componenti di colore devono essere nell'intervallo 0-255. |
| [Color](color/#constructor_2)(byte, byte, byte, byte) | Inizializza una nuova istanza della classe `Color`. Tutti i componenti di colore devono essere nell'intervallo 0-255. |
| [Color](color/#constructor_6)(float, float, float, float) | Inizializza una nuova istanza della classe `Color`. Tutti i componenti di colore devono essere nell'intervallo 0-1. |
| [Color](color/#constructor_4)(int, int, int, int) | Inizializza una nuova istanza della classe `Color`. Tutti i componenti di colore devono essere nell'intervallo 0-255. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getAlpha](../../com.aspose.html.drawing/color/alpha/) Rappresenta il componente alpha del colore. |
| [getBlue](../../com.aspose.html.drawing/color/blue/) Rappresenta il componente blu del colore. |
| [getGreen](../../com.aspose.html.drawing/color/green/) Rappresenta il componente verde del colore. |
| [getRed](../../com.aspose.html.drawing/color/red/) Rappresenta il componente rosso del colore |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromCmyk](../../com.aspose.html.drawing/color/fromcmyk/)(float, float, float, float) | Restituisce un nuovo Color con i valori cyan, magenta, yellow, key (nero) richiesti. |
| static [FromCmyka](../../com.aspose.html.drawing/color/fromcmyka/)(float, float, float, float, float) | Restituisce un nuovo Color con i valori cyan, magenta, yellow, key (nero), alpha richiesti. |
| static [FromGray](../../com.aspose.html.drawing/color/fromgray/)(float) | Restituisce un nuovo Color con il valore di grigio richiesto. |
| static [FromHsl](../../com.aspose.html.drawing/color/fromhsl/)(float, float, float) | Restituisce un nuovo Color con i valori hue, saturation, saturation richiesti. |
| static [FromHsla](../../com.aspose.html.drawing/color/fromhsla/)(float, float, float, float) | Restituisce un nuovo Color con i valori hue, saturation, saturation, alpha richiesti. |
| static [FromHsv](../../com.aspose.html.drawing/color/fromhsv/)(float, float, float) | Restituisce un nuovo Color con i valori hue, saturation, value richiesti. |
| static [FromHsva](../../com.aspose.html.drawing/color/fromhsva/)(float, float, float, float) | Restituisce un nuovo Color con i valori hue, saturation, value, alpha richiesti. |
| static [FromHwb](../../com.aspose.html.drawing/color/fromhwb/)(float, float, float) | Restituisce un nuovo Color con i valori hue, whiteness, blackness richiesti. |
| static [FromHwba](../../com.aspose.html.drawing/color/fromhwba/)(float, float, float, float) | Restituisce un nuovo Color con i valori hue, whiteness, blackness richiesti. |
| static [FromInt](../../com.aspose.html.drawing/color/fromint/)(int) | Restituisce un nuovo Color con il valore ARGB richiesto. |
| static [FromLab](../../com.aspose.html.drawing/color/fromlab/)(float, float, float) | Restituisce un nuovo Color con i valori lightness, A, B richiesti. |
| static [FromLaba](../../com.aspose.html.drawing/color/fromlaba/)(float, float, float, float) | Restituisce un nuovo Color con i valori di luminosità, A, B e alpha richiesti. |
| static [FromLch](../../com.aspose.html.drawing/color/fromlch/)(float, float, float) | Restituisce un nuovo Color con i valori di luminanza, cromaticità e tonalità richiesti. |
| static [FromLcha](../../com.aspose.html.drawing/color/fromlcha/)(float, float, float, float) | Restituisce un nuovo Color con i valori di luminanza, cromaticità, tonalità e alpha richiesti. |
| static [FromOklab](../../com.aspose.html.drawing/color/fromoklab/)(float, float, float) | Restituisce un nuovo Color con i valori di luminosità, A e B richiesti per il modello OKLAB. |
| static [FromOklaba](../../com.aspose.html.drawing/color/fromoklaba/)(float, float, float, float) | Restituisce un nuovo Color con i valori di luminosità, A, B e alpha richiesti per il modello OKLAB. |
| static [FromOklch](../../com.aspose.html.drawing/color/fromoklch/)(float, float, float) | Restituisce un nuovo Color con i valori di luminanza, cromaticità e tonalità richiesti per il modello OKLAB. |
| static [FromOklcha](../../com.aspose.html.drawing/color/fromoklcha/)(float, float, float, float) | Restituisce un nuovo Color con i valori di luminanza, cromaticità, tonalità e alpha richiesti per il modello OKLAB. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb)(byte, byte, byte) | Restituisce un nuovo Color con i valori di ged, verde e blu richiesti. Tutti i componenti del colore devono essere nell'intervallo 0-255. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_2)(float, float, float) | Restituisce un nuovo Color con i valori di ged, verde e blu richiesti. Tutti i componenti del colore devono essere nell'intervallo 0-1. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_1)(int, int, int) | Restituisce un nuovo Color con i valori di ged, verde e blu richiesti. Tutti i componenti del colore devono essere nell'intervallo 0-255. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba)(byte, byte, byte, byte) | Restituisce un nuovo Color con i valori di ged, verde, blu e alpha richiesti. Tutti i componenti del colore devono essere nell'intervallo 0-255. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_2)(float, float, float, float) | Restituisce un nuovo Color con i valori di ged, verde, blu e alpha richiesti. Tutti i componenti del colore devono essere nell'intervallo 0-1. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_1)(int, int, int, int) | Restituisce un nuovo Color con i valori di ged, verde, blu e alpha richiesti. Tutti i componenti del colore devono essere nell'intervallo 0-255. |
| static [FromString](../../com.aspose.html.drawing/color/fromString/)(String) | Analizza una String contenente il colore CSS e restituisce un nuovo Color. |
| static [FromUint](../../com.aspose.html.drawing/color/fromuint/)(uint) | Restituisce un nuovo Color con il valore ARGB richiesto. |
| [addLuminosity](../../com.aspose.html.drawing/color/addluminosity/)(float) | Crea una copia del Color con la somma della sua luminosità e del valore delta. |
| [convert](../../com.aspose.html.drawing/color/convert/)(ColorModel) | Restituisce i componenti del colore nel formato del modello di colore specificato. |
| [equals](../../com.aspose.html.drawing/color/equals/)(object) | Determina se il `Color` specificato è uguale a questa istanza. |
| [getComplementary](../../com.aspose.html.drawing/color/getcomplementary/)() | Restituisce un nuovo colore che si trova sul lato opposto della ruota dei colori rispetto all'originale. |
| [getHashCode](../../com.aspose.html.drawing/color/gethashcode/)() | Restituisce un codice hash. |
| [getHue](../../com.aspose.html.drawing/color/gethue/)() | Restituisce la tonalità del Color. |
| [getLuminosity](../../com.aspose.html.drawing/color/getluminosity/)() | Restituisce la luminosità del Color. |
| [getSaturation](../../com.aspose.html.drawing/color/getsaturation/)() | Restituisce la saturazione del Color. |
| [toInt](../../com.aspose.html.drawing/color/toint/)() | Codifica i componenti ARGB del Color in un int. |
| [toName](../../com.aspose.html.drawing/color/toname/)() | Restituisce il nome del colore se corrisponde a un colore nell'elenco dei colori CSS nominati, altrimenti una String vuota. |
| [toNaturalColorString](../../com.aspose.html.drawing/color/tonaturalcolorString/)(int) | Restituisce un colore Natural (NCol) specificato usando una lettera di colore con un numero per indicare la distanza (in percentuale) dal colore. |
| [toRgbaHexString](../../com.aspose.html.drawing/color/torgbahexString/)() | Restituisce un colore esadecimale specificato con: #RRGGBBAA. |
| [toRgbaString](../../com.aspose.html.drawing/color/torgbaString/)() | Restituisce una String contenente il colore RGBA specificato da: rgba(R, G, B, A). |
| [toRgbHexString](../../com.aspose.html.drawing/color/torgbhexString/)() | Restituisce un colore esadecimale specificato con: #RRGGBB. |
| [toRgbString](../../com.aspose.html.drawing/color/torgbString/)() | Restituisce una stringa contenente il colore RGB specificato da: rgb(R, G, B). |
| [toString](../../com.aspose.html.drawing/color/toString/)() | Restituisce una stringa che consiste nei valori dei componenti RGBA. |
| [toUint](../../com.aspose.html.drawing/color/touint/)() | Codifica i componenti ARGB del colore in un intero senza segno. |
| [withAlpha](../../com.aspose.html.drawing/color/withalpha/)(float) | Crea una copia del colore con il componente alfa specificato. |
| [withHue](../../com.aspose.html.drawing/color/withhue/)(float) | Crea una copia del colore con la tonalità (Hue) specificata. |
| [withLuminosity](../../com.aspose.html.drawing/color/withluminosity/)(float) | Crea una copia del colore con la luminosità specificata. |
| [withSaturation](../../com.aspose.html.drawing/color/withsaturation/)(float) | Crea una copia del colore con la saturazione specificata. |

### Vedi anche

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
