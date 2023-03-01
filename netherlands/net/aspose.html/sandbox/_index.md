---
title: Enum Sandbox
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Sandbox opsomming. Een sandboxvlaggenset is een set van nul of meer van de volgende vlaggen die worden gebruikt om de mogelijkheden van mogelijk nietvertrouwde bronnen te beperken.
type: docs
weight: 4560
url: /nl/net/aspose.html/sandbox/
---
## Sandbox enumeration

Een sandbox-vlaggenset is een set van nul of meer van de volgende vlaggen, die worden gebruikt om de mogelijkheden van mogelijk niet-vertrouwde bronnen te beperken.

```csharp
[Flags]
public enum Sandbox
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| None | `0` | Er is geen vlag ingesteld, elke sandbox-functie wordt geaccepteerd |
| Navigation | `1` | Deze markering verhindert dat inhoud door andere browsercontexten navigeert dan de browsercontext in de sandbox zelf (of browsercontexten die verder daarin genest zijn), hulpbrowsercontexten (die worden beschermd door de volgende gedefinieerde vlag voor navigatiecontext in de sandbox) en de browsecontext (die wordt beschermd door de navigatiecontextvlag op het hoogste niveau in een sandbox die hieronder wordt gedefinieerd). Als de contextvlag voor extra navigatie in de sandbox niet is ingesteld, staan de beperkingen in bepaalde gevallen toch toe dat pop-ups (nieuwe browsercontexten op het hoogste niveau) worden geopend. Deze browsecontexten hebben altijd één toegestane sandbox-navigator, ingesteld wanneer de browsecontext wordt gemaakt, waardoor de browsecontext die ze heeft gemaakt, er daadwerkelijk doorheen kan navigeren. (Anders zou de browsercontextvlag voor navigatie in een sandbox voorkomen dat er door ze wordt genavigeerd, zelfs niet als ze zijn geopend. |
| AuxiliaryNavigation | `2` | Deze vlag voorkomt dat inhoud nieuwe aanvullende browsercontexten creëert, bijvoorbeeld met behulp van het doelkenmerk of de methode window.open(). |
| TopLevelNavigation | `4` | Deze vlag voorkomt dat inhoud door hun browsercontext op het hoogste niveau navigeert en voorkomt dat inhoud hun browsercontext op het hoogste niveau sluit. Wanneer de browsercontextvlag voor navigatie op het hoogste niveau in een sandbox niet is ingesteld, kan inhoud door de browsercontext op het hoogste niveau navigeren, maar worden andere browsercontexten nog steeds beschermd door de navigatiecontextvlag voor navigatie in een sandbox en mogelijk de contextvlag voor navigatie in een sandbox voor aanvullende navigatie. |
| Plugins | `8` | Deze vlag voorkomt dat inhoud plug-ins instantiseert, of het nu gaat om het embed-element, het object-element, het applet-element of door navigatie van een geneste browsercontext, tenzij die plug-ins kunnen worden beveiligd. |
| Origin | `10` | Deze vlag dwingt inhoud naar een unieke oorsprong, waardoor het geen toegang krijgt tot andere inhoud van dezelfde oorsprong. |
| Forms | `20` | Deze vlag blokkeert het indienen van formulieren. |
| PointerLock | `40` | Deze vlag schakelt de Pointer Lock API uit. |
| Scripts | `80` | Deze vlag blokkeert de uitvoering van scripts. |
| AutomaticFeatures | `100` | Deze vlag blokkeert functies die automatisch worden geactiveerd, zoals het automatisch afspelen van een video of het automatisch scherpstellen van een formulierbesturingselement. |
| Fullscreen | `200` | Deze vlag voorkomt dat inhoud de methode requestFullscreen() gebruikt. |
| DocumentDomain | `400` | Deze vlag voorkomt dat inhoud de functie document.domain gebruikt om de oorspronkelijke scriptoorsprong te wijzigen. |
| Images | `800` | Deze vlag schakelt het laden van afbeeldingen uit. |

### Zie ook

* naamruimte [Aspose.Html](../../aspose.html/)
* montage [Aspose.HTML](../../)


