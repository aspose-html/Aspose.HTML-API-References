---
title: Interface IStyleSheet
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Css.IStyleSheet koppel. De StyleSheetinterface is de abstracte basisinterface voor elk type stijlblad. Het vertegenwoordigt een enkel opmaakmodel dat is gekoppeld aan een gestructureerd document.
type: docs
weight: 590
url: /nl/net/aspose.html.dom.css/istylesheet/
---
## IStyleSheet interface

De StyleSheet-interface is de abstracte basisinterface voor elk type stijlblad. Het vertegenwoordigt een enkel opmaakmodel dat is gekoppeld aan een gestructureerd document.

```csharp
public interface IStyleSheet
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Disabled](../../aspose.html.dom.css/istylesheet/disabled/) { get; set; } | false als het opmaakmodel op het document wordt toegepast. waar als het niet zo is. Het wijzigen van dit attribuut kan leiden tot een nieuwe stijlresolutie voor het document. Een stylesheet is alleen van toepassing als zowel een geschikte mediumdefinitie aanwezig is als het uitgeschakelde attribuut onwaar is. Dus als de media niet van toepassing zijn op de huidige user-agent, wordt het uitgeschakelde kenmerk genegeerd. |
| [Href](../../aspose.html.dom.css/istylesheet/href/) { get; } | Als de stylesheet een gekoppelde stylesheet is, is de waarde van het attribuut de locatie. Voor inline stijlbladen is de waarde van dit attribuut null. |
| [Media](../../aspose.html.dom.css/istylesheet/media/) { get; } | De beoogde bestemmingsmedia voor stijlinformatie. |
| [OwnerNode](../../aspose.html.dom.css/istylesheet/ownernode/) { get; } | Het knooppunt dat deze stijlpagina aan het document koppelt. Voor HTML kan dit het corresponderende LINK- of STYLE-element zijn. Voor XML kan dit de instructie voor koppelingsverwerking zijn. Voor stijlbladen die zijn opgenomen in andere stijlbladen, is de waarde van dit attribuut null. |
| [ParentStyleSheet](../../aspose.html.dom.css/istylesheet/parentstylesheet/) { get; } | Voor stylesheettalen die het concept van stylesheetopname ondersteunen, vertegenwoordigt dit attribuut de include-stylesheet, als die bestaat. Als de stijlpagina een stijlpagina op het hoogste niveau is, of als de taal van de stijlpagina opname niet ondersteunt, is de waarde van dit attribuut null. |
| [Title](../../aspose.html.dom.css/istylesheet/title/) { get; } | De titel van het advies. |
| [Type](../../aspose.html.dom.css/istylesheet/type/) { get; } | Dit specificeert de stijlbladtaal voor dit stijlblad. De stijlbladtaal wordt gespecificeerd als een inhoudstype (bijv. "tekst/css"). |

### Zie ook

* naamruimte [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* montage [Aspose.HTML](../../)


