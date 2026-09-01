---
title: "Sandbox‑enum"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.Sandbox‑enum. Een set sandbox‑vlaggen is een verzameling van nul of meer van de volgende vlaggen die worden gebruikt om de mogelijkheden van potentieel onbetrouwbare bronnen te beperken"
type: docs

url: /nl/java/com.aspose.html/sandbox/
---
## Sandbox enumeration

Een sandbox‑vlagset is een verzameling van nul of meer van de volgende vlaggen, die worden gebruikt om de mogelijkheden van potentieel onbetrouwbare bronnen te beperken.

```java
[Flags]
public enum Sandbox
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| None | `0` | Er is geen vlag ingesteld, elke sandbox‑functie wordt geaccepteerd |
| Navigation | `1` | Deze vlag voorkomt dat inhoud navigatie uitvoert naar browse‑contexten anders dan de gesandboxtte browse‑context zelf (of verder geneste browse‑contexten), auxiliaire browse‑contexten (die beschermd worden door de hieronder gedefinieerde sandbox‑auxiliaire navigatie‑browse‑context‑vlag), en de top‑level browse‑context (die beschermd wordt door de hieronder gedefinieerde sandbox‑top‑level navigatie‑browse‑context‑vlag). Als de sandbox‑auxiliaire navigatie‑browse‑context‑vlag niet is ingesteld, dan staan de beperkingen in bepaalde gevallen toch pop‑ups (nieuwe top‑level browse‑contexten) toe om geopend te worden. Deze browse‑contexten hebben altijd één toegestane sandbox‑navigator, ingesteld bij het aanmaken van de browse‑context, die de browse‑context die hen heeft gecreëerd toestaat om ze daadwerkelijk te navigeren. (Anders zou de sandbox‑navigatie‑browse‑context‑vlag voorkomen dat ze genavigeerd worden, zelfs als ze geopend zijn.) |
| AuxiliaryNavigation | `2` | Deze vlag voorkomt dat inhoud nieuwe auxiliaire browse‑contexten creëert, bijv. met het target‑attribuut of de window.open()‑methode. |
| TopLevelNavigation | `4` | Deze vlag voorkomt dat inhoud hun top‑level browse‑context navigeert en voorkomt dat inhoud hun top‑level browse‑context sluit. Wanneer de sandbox‑top‑level navigatie‑browse‑context‑vlag niet is ingesteld, kan inhoud hun top‑level browse‑context navigeren, maar andere browse‑contexten blijven beschermd door de sandbox‑navigatie‑browse‑context‑vlag en mogelijk de sandbox‑auxiliaire navigatie‑browse‑context‑vlag. |
| Plugins | `8` | Deze vlag voorkomt dat inhoud plugins instantiateert, of dit nu gebeurt via het embed‑element, het object‑element, het applet‑element, of via navigatie van een geneste browse‑context, tenzij die plugins beveiligd kunnen worden. |
| Origin | `10` | Deze vlag dwingt inhoud naar een unieke origin, waardoor het voorkomen wordt dat het toegang krijgt tot andere inhoud van dezelfde origin. |
| Forms | `20` | Deze vlag blokkeert het indienen van formulieren. |
| PointerLock | `40` | Deze vlag schakelt de Pointer Lock‑API uit. |
| Scripts | `80` | Deze vlag blokkeert de uitvoering van scripts. |
| AutomaticFeatures | `100` | Deze vlag blokkeert functies die automatisch worden geactiveerd, zoals het automatisch afspelen van een video of het automatisch focussen van een formulier‑element. |
| Fullscreen | `200` | Deze vlag voorkomt dat inhoud de requestFullscreen()‑methode gebruikt. |
| DocumentDomain | `400` | Deze vlag voorkomt dat inhoud de document.domain‑functie gebruikt om de effectieve script‑origin te wijzigen. |
| Images | `800` | Deze vlag schakelt het laden van afbeeldingen uit. |

### Zie ook

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
