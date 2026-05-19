---
title: "DocDevice.DocGraphicContext-klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.rendering.doc.DocDeviceDocGraphicContext-klasse. Bevat de huidige grafische controleparameters voor de DocDevice. Deze parameters definiëren het globale kader waarbinnen de grafische operatoren worden uitgevoerd"
type: docs

url: /nl/java/com.aspose.html.rendering.doc/docdevice.docgraphiccontext/
---
## DocDevice.DocGraphicContext class

Bevat de huidige grafische controleparameters voor de DocDevice. Deze parameters definiëren het globale kader waarbinnen de grafische operatoren worden uitgevoerd.

```java
public class DocGraphicContext : GraphicContext
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [docGraphicContext](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/.ctor)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [characterSpacing](../../com.aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | Stelt de tekenafstand in of haalt deze op. |
| [fillBrush](../../com.aspose.html.rendering/graphiccontext/fillbrush/) { get; set; } | Stelt het penseelobject in of haalt het op dat wordt gebruikt om de binnenkant van paden te vullen. |
| [font](../../com.aspose.html.rendering/graphiccontext/font/) { get; set; } | Stelt het TrueType-lettertypeobject in of haalt het op dat wordt gebruikt voor het renderen van tekst. |
| [fontSize](../../com.aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | Stelt de lettergrootte van de tekst in of haalt deze op. |
| [fontStyle](../../com.aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | Stelt de letterstijl van de tekst in of haalt deze op. |
| [lineCap](../../com.aspose.html.rendering/graphiccontext/linecap/) { get; set; } | Stelt de code in of haalt deze op die de vorm van de eindpunten specificeert voor elk open pad dat wordt getekend. |
| [lineDashOffset](../../com.aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | Stelt de faseverschuiving in of haalt deze op van het huidige stippellijnpatroon. |
| [lineDashPattern](../../com.aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | Stelt de beschrijving in of haalt deze op van het stippellijnpatroon dat wordt gebruikt wanneer paden worden getekend. |
| [lineJoin](../../com.aspose.html.rendering/graphiccontext/linejoin/) { get; set; } | Stelt de code in of haalt deze op die de vorm van de verbindingen tussen verbonden segmenten van een getekend pad specificeert. |
| [lineWidth](../../com.aspose.html.rendering/graphiccontext/linewidth/) { get; set; } | Stelt de dikte in of haalt deze op van paden die getekend moeten worden. |
| [miterLimit](../../com.aspose.html.rendering/graphiccontext/miterlimit/) { get; set; } | Stelt de maximale lengte in of haalt deze op van verstekte lijnverbindingen voor getekende paden. Deze parameter beperkt de lengte van \"spikes\" die ontstaan wanneer lijnsegmenten samenkomen onder scherpe hoeken. |
| [strokeBrush](../../com.aspose.html.rendering/graphiccontext/strokebrush/) { get; set; } | Stelt het penseelobject in of haalt het op dat wordt gebruikt voor getekende paden. |
| [getTextInfo](../../com.aspose.html.rendering/graphiccontext/textinfo/) Haalt een [`TextInfo`](../../com.aspose.html.rendering/textinfo/) object op dat informatie bevat over gerenderde tekst. |
| [transformationMatrix](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/transformationmatrix) { get; set; } | Stelt de transformatie-matrix in of haalt deze op. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [clone](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/clone)() | Maakt een nieuw exemplaar van een [`GraphicContext`](../../com.aspose.html.rendering/graphiccontext/) klasse met dezelfde eigenschapswaarden als een bestaand exemplaar. |
| [transform](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/transform)(IMatrix) | Wijzig de huidige transformatie-matrix door de opgegeven matrix te vermenigvuldigen. |

### Zie ook

* class [GraphicContext](../../com.aspose.html.rendering/graphiccontext/)
* class [DocDevice](../docdevice/)
* package [com.aspose.html.rendering.doc](../../com.aspose.html.rendering.doc/)
* package [Aspose.HTML](../../)
