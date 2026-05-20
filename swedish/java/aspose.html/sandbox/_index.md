---
title: "Sandbox‑enum"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.Sandbox‑enum. En uppsättning sandbox‑flaggor är en samling av noll eller fler av följande flaggor som används för att begränsa de förmågor som potentiellt opålitliga resurser har"
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
| None | `0` | Ingen flagga är satt, varje sandbox‑funktion accepteras |
| Navigation | `1` | Denna flagga förhindrar att innehåll navigerar i webbläsarkontexter som inte är den sandboxade webbläsarkontexten själv (eller webbläsarkontexter som är ytterligare inbäddade i den), hjälpkontexter (som skyddas av flaggan för sandboxad hjälpnavigering definierad nedan), och toppnivåkontexten (som skyddas av flaggan för sandboxad toppnivånavigering definierad längre ner). Om flaggan för sandboxad hjälpnavigering inte är satt, så tillåter restriktionerna i vissa fall ändå popup‑fönster (nya toppnivåkontexter) att öppnas. Dessa kontexter har alltid en tillåten sandboxad navigator, som sätts när kontexten skapas, och som gör att den kontext som skapade dem faktiskt kan navigera dem. (Annars skulle flaggan för sandboxad navigering förhindra att de navigeras även om de öppnades.) |
| AuxiliaryNavigation | `2` | Denna flagga förhindrar att innehåll skapar nya hjälpkontexter, t.ex. genom att använda target‑attributet eller window.open()-metoden. |
| TopLevelNavigation | `4` | Denna flagga förhindrar att innehåll navigerar sin toppnivå‑webbläsarkontext och förhindrar att innehåll stänger sin toppnivå‑webbläsarkontext. När flaggan för sandboxad toppnivånavigering inte är satt kan innehållet navigera sin toppnivå‑kontext, men andra kontexter är fortfarande skyddade av flaggan för sandboxad navigering och eventuellt av flaggan för sandboxad hjälpnavigering. |
| Plugins | `8` | Denna flagga förhindrar att innehåll instansierar plugin‑moduler, oavsett om embed‑elementet, object‑elementet, applet‑elementet används eller genom navigering i en inbäddad webbläsarkontext, såvida inte dessa plugin‑moduler kan säkras. |
| Origin | `10` | Denna flagga tvingar innehåll till en unik ursprung, vilket förhindrar att det får åtkomst till annat innehåll från samma ursprung. |
| Forms | `20` | Denna flagga blockerar formulärinlämning. |
| PointerLock | `40` | Denna flagga inaktiverar Pointer Lock‑API:t. |
| Scripts | `80` | Denna flagga blockerar skriptkörning. |
| AutomaticFeatures | `100` | Denna flagga blockerar funktioner som triggas automatiskt, såsom automatisk uppspelning av video eller automatisk fokusering av ett formulärfält. |
| Fullscreen | `200` | Denna flagga förhindrar att innehåll använder requestFullscreen()-metoden. |
| DocumentDomain | `400` | Denna flagga förhindrar att innehåll använder document.domain‑funktionen för att ändra det effektiva skript‑ursprunget. |
| Images | `800` | Denna flagga inaktiverar bildladdning. |

### Se även

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
