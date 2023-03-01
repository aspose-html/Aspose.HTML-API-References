---
title: Enum Sandbox
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Sandbox uppräkning. En sandlådeflaggauppsättning är en uppsättning av noll eller fler av följande flaggor som används för att begränsa de förmågor som potentiellt otillförlitliga resurser.
type: docs
weight: 4560
url: /sv/net/aspose.html/sandbox/
---
## Sandbox enumeration

En sandlådeflaggauppsättning är en uppsättning av noll eller fler av följande flaggor, som används för att begränsa de förmågor som potentiellt otillförlitliga resurser.

```csharp
[Flags]
public enum Sandbox
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| None | `0` | Ingen flagga är inställd, varje sandlådefunktion accepteras |
| Navigation | `1` | Den här flaggan förhindrar innehåll från att navigera i andra webbläsarkontexter än själva sandlådekontexten (eller webbläsarkontexter som är ytterligare kapslade inuti den), extra surfkontexter (som skyddas av den sandlådebaserade extranavigeringskontextflaggan som definieras härnäst) och toppnivån webbläsarkontext (som skyddas av den sandlådeformade navigeringskontextflaggan på toppnivå som definieras nedan). Om den extra navigeringskontextflaggan i sandlåde inte är inställd, tillåter restriktionerna i vissa fall ändå att popup-fönster (nya webbläsarkontexter på toppnivå) öppnas. Dessa webbläsarkontexter har alltid en tillåten sandlådenavigator, inställd när webbläsarkontexten skapas, vilket gör att webbläsarkontexten som skapade dem faktiskt kan navigera i dem. (Annars skulle den sandlådeformade navigeringskontextflaggan hindra dem från att navigeras även om de öppnades. |
| AuxiliaryNavigation | `2` | Den här flaggan förhindrar innehåll från att skapa nya extra webbläsarkontexter, t.ex. med målattributet eller metoden window.open(). |
| TopLevelNavigation | `4` | Den här flaggan förhindrar innehåll från att navigera i deras webbläsarkontext på toppnivå och förhindrar innehåll från att stänga deras webbläsarkontext på toppnivå. När den sandlådeförsedda toppnivånavigeringskontextflaggan inte är inställd kan innehållet navigera i dess toppnivåsurfningskontext, men andra webbläsarkontexter skyddas fortfarande av den sandlådeförsedda navigeringskontextflaggan och eventuellt sandlådenavigeringskontextflaggan. |
| Plugins | `8` | Den här flaggan förhindrar innehåll från att instansiera insticksprogram, oavsett om du använder embed-elementet, objektelementet, appletelementet eller genom navigering av en kapslad webbläsarkontext, om inte dessa plugins kan säkras. |
| Origin | `10` | Den här flaggan tvingar innehåll till ett unikt ursprung, vilket förhindrar det från att komma åt annat innehåll från samma ursprung. |
| Forms | `20` | Den här flaggan blockerar formulärinlämning. |
| PointerLock | `40` | Denna flagga inaktiverar Pointer Lock API. |
| Scripts | `80` | Denna flagga blockerar skriptexekvering. |
| AutomaticFeatures | `100` | Den här flaggan blockerar funktioner som utlöses automatiskt, som att automatiskt spela upp en video eller automatiskt fokusera en formulärkontroll. |
| Fullscreen | `200` | Den här flaggan förhindrar innehåll från att använda metoden requestFullscreen(). |
| DocumentDomain | `400` | Den här flaggan förhindrar innehåll från att använda funktionen document.domain för att ändra det effektiva skriptets ursprung. |
| Images | `800` | Den här flaggan inaktiverar bildladdning. |

### Se även

* namnutrymme [Aspose.Html](../../aspose.html/)
* hopsättning [Aspose.HTML](../../)


