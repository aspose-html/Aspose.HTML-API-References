---
title: "Sandbox‑enum"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.Sandbox‑enum. En uppsättning sandbox‑flaggor är en samling av noll eller fler av följande flaggor som används för att begränsa de förmågor som potentiellt icke‑betrodda resurser har"
type: docs

url: /sv/java/com.aspose.html/sandbox/
---
## Sandbox enumeration

En sandbox‑flaggsats är en uppsättning av noll eller fler av följande flaggor, som används för att begränsa de funktioner som potentiellt opålitliga resurser kan ha.

```java
[Flags]
public enum Sandbox
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | `0` | Ingen flagga är satt, alla sandbox‑funktioner accepteras |
| Navigation | `1` | Denna flagga hindrar innehåll från att navigera i andra surfkontexter än den sandboxade surfkontexten själv (eller surfkontexter som är ytterligare inbäddade i den), hjälpsurfkontexter (som skyddas av flaggan för sandboxad hjälpnavigering definierad nedan), och toppnivånsurfkontext (som skyddas av flaggan för sandboxad toppnivånavigering definierad nedan). Om flaggan för sandboxad hjälpnavigering inte är satt, tillåter begränsningarna i vissa fall ändå popup‑fönster (nya toppnivånsurfkontexter) att öppnas. Dessa surfkontexter har alltid en tillåten sandboxad navigator, som sätts när surfkontexten skapas, vilket gör att den surfkontext som skapade dem faktiskt kan navigera dem. (Annars skulle flaggan för sandboxad navigering hindra dem från att navigeras även om de öppnades.) |
| AuxiliaryNavigation | `2` | Denna flagga hindrar innehåll från att skapa nya hjälpsurfkontexter, t.ex. genom att använda target‑attributet eller metoden window.open(). |
| TopLevelNavigation | `4` | Denna flagga hindrar innehåll från att navigera i sin toppnivånsurfkontext och hindrar innehåll från att stänga sin toppnivånsurfkontext. När flaggan för sandboxad toppnivånavigering inte är satt kan innehåll navigera sin toppnivånsurfkontext, men andra surfkontexter är fortfarande skyddade av flaggan för sandboxad navigering och eventuellt flaggan för sandboxad hjälpnavigering. |
| Plugins | `8` | Denna flagga hindrar innehåll från att instansiera plugin‑moduler, oavsett om de används via embed‑elementet, object‑elementet, applet‑elementet eller genom navigering i en inbäddad surfkontext, såvida inte dessa plugin‑moduler kan säkras. |
| Origin | `10` | Denna flagga tvingar innehåll till en unik ursprung, vilket hindrar det från att komma åt annat innehåll från samma ursprung. |
| Forms | `20` | Denna flagga blockerar formulärinlämning. |
| PointerLock | `40` | Denna flagga inaktiverar Pointer Lock‑API:t. |
| Scripts | `80` | Denna flagga blockerar skriptkörning. |
| AutomaticFeatures | `100` | Denna flagga blockerar funktioner som triggas automatiskt, såsom automatisk uppspelning av en video eller automatisk fokusering av ett formulärfält. |
| Fullscreen | `200` | Denna flagga hindrar innehåll från att använda metoden requestFullscreen(). |
| DocumentDomain | `400` | Denna flagga hindrar innehåll från att använda document.domain‑funktionen för att ändra det effektiva skript‑ursprunget. |
| Images | `800` | Denna flagga inaktiverar bildladdning. |

### Se även

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
