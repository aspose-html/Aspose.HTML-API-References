---
title: "Sandbox‑enum"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.Sandbox‑enum. Een set sandbox‑vlaggen is een verzameling van nul of meer van de volgende vlaggen die worden gebruikt om de mogelijkheden van potentieel onbetrouwbare bronnen te beperken"
type: docs

url: /nl/java/com.aspose.html/sandbox/
---
## Sandbox enumeration

Een sandbox-vlagset is een set van nul of meer van de volgende vlaggen, die worden gebruikt om de mogelijkheden van potentieel onbetrouwbare bronnen te beperken.

```java
[Flags]
public enum Sandbox
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| None | `0` | Er is geen vlag ingesteld, elke sandbox‑functie wordt geaccepteerd |
| Navigation | `1` | Deze vlag voorkomt dat inhoud andere browse‑contexten navigeert dan de gesandboxtte browse‑context zelf (of verder geneste browse‑contexten), auxiliaire browse‑contexten (die beschermd worden door de volgende gesandboxtte auxiliaire navigatie‑browse‑context‑vlag), en de top‑level browse‑context (die beschermd wordt door de hieronder gedefinieerde gesandboxtte top‑level navigatie‑browse‑context‑vlag). Als de gesandboxtte auxiliaire navigatie‑browse‑context‑vlag niet is ingesteld, dan staan de beperkingen in bepaalde gevallen toch pop‑ups (nieuwe top‑level browse‑contexten) toe om geopend te worden. Deze browse‑contexten hebben altijd één toegestane gesandboxtte navigator, ingesteld bij het creëren van de browse‑context, die de browse‑context die ze heeft gecreëerd toestaat ze daadwerkelijk te navigeren. (Anders zou de gesandboxtte navigatie‑browse‑context‑vlag voorkomen dat ze genavigeerd worden, zelfs als ze geopend zijn.) |
| AuxiliaryNavigation | `2` | Deze vlag voorkomt dat inhoud nieuwe auxiliaire browse‑contexten creëert, bijv. via het target‑attribuut of de window.open()‑methode. |
| TopLevelNavigation | `4` | Deze vlag voorkomt dat inhoud hun top‑level browse‑context navigeert en voorkomt dat inhoud hun top‑level browse‑context sluit. Wanneer de gesandboxtte top‑level navigatie‑browse‑context‑vlag niet is ingesteld, kan inhoud hun top‑level browse‑context navigeren, maar andere browse‑contexten blijven beschermd door de gesandboxtte navigatie‑browse‑context‑vlag en mogelijk de gesandboxtte auxiliaire navigatie‑browse‑context‑vlag. |
| Plugins | `8` | Deze vlag voorkomt dat inhoud plug‑ins instantiateert, of dit nu gebeurt via het embed‑element, het object‑element, het applet‑element, of via navigatie van een geneste browse‑context, tenzij die plug‑ins beveiligd kunnen worden. |
| Origin | `10` | Deze vlag dwingt inhoud naar een unieke origin, waardoor het voorkomen wordt dat het toegang krijgt tot andere inhoud van dezelfde origin. |
| Forms | `20` | Deze vlag blokkeert het verzenden van formulieren. |
| PointerLock | `40` | Deze vlag schakelt de Pointer Lock‑API uit. |
| Scripts | `80` | Deze vlag blokkeert de uitvoering van scripts. |
| AutomaticFeatures | `100` | Deze vlag blokkeert functies die automatisch worden geactiveerd, zoals het automatisch afspelen van een video of het automatisch focussen van een formulier‑element. |
| Fullscreen | `200` | Deze vlag voorkomt dat inhoud de requestFullscreen()‑methode gebruikt. |
| DocumentDomain | `400` | Deze vlag voorkomt dat inhoud de document.domain‑functie gebruikt om de effectieve script‑origin te wijzigen. |
| Images | `800` | Deze vlag schakelt het laden van afbeeldingen uit. |

### Zie ook

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
