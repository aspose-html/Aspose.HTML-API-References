---
title: "com.aspose.html.dom.svg"
second_title: "Aspose.HTML för Java API-referens"
description: "Alla klasser i paketet com.aspose.html.dom.svg är baserade på w3c SVG2‑rekommendationerna. Med detta paket kan du ladda, navigera eller rendera SVG‑filen enligt dina krav."
type: docs

url: /sv/java/com.aspose.html.dom.svg/
---
Alla klasser i paketet **com.aspose.html.dom.svg** är baserade på w3c SVG2‑rekommendationer. Med detta paket kan du läsa in, navigera eller rendera SVG‑filen enligt dina krav.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [SVGAElement](./svgaelement/) | SVGAElement‑gränssnittet motsvarar ‘a’-elementet. |
| [SVGAnimateElement](./svganimateelement/) | SVGAnimateElement‑gränssnittet motsvarar ‘animate’-elementet. Objektorienterad åtkomst till attributen för ‘animate’-elementet via SVG‑DOM är inte tillgänglig. |
| [SVGAnimateMotionElement](./svganimatemotionelement/) | SVGAnimateMotionElement‑gränssnittet motsvarar ‘animateMotion’-elementet. Objektorienterad åtkomst till attributen för ‘animateMotion’-elementet via SVG‑DOM är inte tillgänglig. |
| [SVGAnimateTransformElement](./svganimatetransformelement/) | SVGAnimateTransformElement‑gränssnittet motsvarar ‘animateTransform’-elementet. Objektorienterad åtkomst till attributen för ‘animateTransform’-elementet via SVG‑DOM är inte tillgänglig. |
| [SVGAnimationElement](./svganimationelement/) | SVGAnimationElement‑gränssnittet är basgränssnittet för alla animations‑elementgränssnitt: SVGAnimateElement, SVGSetElement, SVGAnimateColorElement, SVGAnimateMotionElement och SVGAnimateTransformElement. |
| [SVGCircleElement](./svgcircleelement/) | SVGCircleElement‑gränssnittet motsvarar ‘circle’-elementet. |
| [SVGClipPathElement](./svgclippathelement/) | SVGClipPathElement‑gränssnittet motsvarar ‘clipPath’-elementet. |
| [SVGComponentTransferFunctionElement](./svgcomponenttransferfunctionelement/) | Detta gränssnitt definierar ett basgränssnitt som används av komponentöverföringsfunktionsgränssnitten. |
| [SVGCursorElement](./svgcursorelement/) | SVGCursorElement‑gränssnittet motsvarar ‘cursor’-elementet. |
| [SVGDefsElement](./svgdefselement/) | SVGDefsElement‑gränssnittet motsvarar ‘defs’-elementet. |
| [SVGDescElement](./svgdescelement/) | SVGDescElement‑gränssnittet motsvarar ‘desc’-elementet. |
| [SVGDocument](./svgdocument/) | Ett `SVGDocument` är roten i SVG‑hierarkin och innehåller hela innehållet. Förutom att ge åtkomst till hierarkin erbjuder det även några bekvämlighetsmetoder för att hämta vissa informationsuppsättningar från dokumentet. När ett ‘svg’-element bäddas in inline som en komponent i ett dokument från ett annat paket, till exempel när ett ‘svg’-element bäddas in inline i ett XHTML‑dokument [XHTML], kommer ett SVGDocument‑objekt inte att finnas; istället blir rotobjektet i dokumentobjekthierarkin ett Document‑objekt av en annan typ, såsom ett HTMLDocument‑objekt. Ett SVGDocument‑objekt kommer dock att finnas när rot‑elementet i XML‑dokumenthierarkin är ett ‘svg’-element, till exempel vid visning av en fristående SVG‑fil (dvs. en fil med MIME‑typen "image/svg+xml"). I så fall blir SVGDocument‑objektet rotobjektet i dokumentobjektmodellens hierarki. |
| [SVGElement](./svgelement/) | Alla SVG‑DOM‑gränssnitt som motsvarar element direkt i SVG‑språket (t.ex. SVGPathElement‑gränssnittet för ‘path’-elementet) ärver från SVGElement‑gränssnittet. |
| [SVGElementInstance](./svgelementinstance/) | Rotobjektet för varje use‑element skuggträd implementerar SVGUseElementShadowRoot‑gränssnittet. Detta gränssnitt definierar för närvarande inga utökningar av egenskaperna och metoderna som definieras för ShadowRoot‑gränssnittet och DocumentOrShadowRoot‑mixinen. Trädet som är rotat vid denna nod är dock helt skrivskyddat ur författarskriptens perspektiv. |
| [SVGEllipseElement](./svgellipseelement/) | SVGEllipseElement‑gränssnittet motsvarar ‘ellipse’-elementet. |
| [SVGException](./svgexception/) | Detta undantag kastas när en specifik SVG‑operation är omöjlig att utföra. |
| [SVGFilterElement](./svgfilterelement/) | SVGFilterElement‑gränssnittet motsvarar ‘filter’-elementet. |
| [SVGForeignObjectElement](./svgforeignobjectelement/) | SVGForeignObjectElement‑gränssnittet motsvarar ‘foreignObject’-elementet. |
| [SVGGElement](./svggelement/) | SVGGElement‑gränssnittet motsvarar ‘g’-elementet. |
| [SVGGeometryElement](./svggeometryelement/) | Gränssnittet SVGGeometryElement representerar SVG‑element vars rendering definieras av geometri med en motsvarande bana, och som kan fyllas och kontureras. Detta inkluderar banor och de grundläggande formerna. |
| [SVGGradientElement](./svggradientelement/) | SVGGradientElement‑gränssnittet är ett basgränssnitt som används av SVGLinearGradientElement och SVGRadialGradientElement. |
| [SVGGraphicsElement](./svggraphicselement/) | SVGGraphicsElement‑gränssnittet representerar SVG‑element vars primära syfte är att direkt rendera grafik i en grupp. |
| [SVGImageElement](./svgimageelement/) | SVGImageElement‑gränssnittet motsvarar ‘image’-elementet. |
| [SVGLinearGradientElement](./svglineargradientelement/) | SVGLinearGradientElement‑gränssnittet motsvarar ‘linearGradient’-elementet. |
| [SVGLineElement](./svglineelement/) | SVGLineElement‑gränssnittet motsvarar ‘line’-elementet. |
| [SVGMarkerElement](./svgmarkerelement/) | SVGMarkerElement-gränssnittet motsvarar ‘marker’-elementet. |
| [SVGMaskElement](./svgmaskelement/) | SVGMaskElement-gränssnittet motsvarar ‘mask’-elementet. |
| [SVGMetadataElement](./svgmetadataelement/) | SVGMetadataElement-gränssnittet motsvarar ‘metadata’-elementet. |
| [SVGMPathElement](./svgmpathelement/) | SVGMPathElement-gränssnittet motsvarar ‘mpath’-elementet. |
| [SVGPathElement](./svgpathelement/) | SVGPathElement-gränssnittet motsvarar ‘path’-elementet. |
| [SVGPatternElement](./svgpatternelement/) | SVGPatternElement-gränssnittet motsvarar ‘pattern’-elementet. |
| [SVGPolygonElement](./svgpolygonelement/) | SVGPolygonElement-gränssnittet motsvarar ‘polygon’-elementet. |
| [SVGPolylineElement](./svgpolylineelement/) | SVGPolylineElement-gränssnittet motsvarar ‘polyline’-elementet. |
| [SVGRadialGradientElement](./svgradialgradientelement/) | SVGRadialGradientElement-gränssnittet motsvarar ‘radialGradient’-elementet. |
| [SVGRectElement](./svgrectelement/) | SVGRectElement-gränssnittet motsvarar ‘rect’-elementet. |
| [SVGScriptElement](./svgscriptelement/) | SVGScriptElement-gränssnittet motsvarar ‘script’-elementet. |
| [SVGSetElement](./svgsetelement/) | SVGSetElement-gränssnittet motsvarar ‘set’-elementet. Objektorienterad åtkomst till attributen för ‘set’-elementet via SVG-DOM är inte tillgänglig. |
| [SVGStopElement](./svgstopelement/) | SVGStopElement-gränssnittet motsvarar ‘stop’-elementet. |
| [SVGStyleElement](./svgstyleelement/) | SVGStyleElement-gränssnittet motsvarar ‘style’-elementet. |
| [SVGSVGElement](./svgsvgelement/) | En viktig gränssnittsdefinition är SVGSVGElement-gränssnittet, som är gränssnittet som motsvarar ‘svg’-elementet. Detta gränssnitt innehåller olika diverse, ofta använda hjälpfunktioner, såsom matrisoperationer och möjligheten att kontrollera omritningstiden på visuella renderingsenheter. |
| [SVGSwitchElement](./svgswitchelement/) | SVGSwitchElement-gränssnittet motsvarar ‘switch’-elementet. |
| [SVGSymbolElement](./svgsymbolelement/) | SVGSymbolElement-gränssnittet motsvarar ‘symbol’-elementet. |
| [SVGTextContentElement](./svgtextcontentelement/) | SVGTextContentElement ärvs av olika textrelaterade gränssnitt, såsom SVGTextElement, SVGTSpanElement, SVGTRefElement, SVGAltGlyphElement och SVGTextPathElement. För metoderna i detta gränssnitt som refererar till ett index till ett tecken eller ett antal tecken, ska dessa referenser tolkas som ett index till en UTF-16-kod enhet eller ett antal UTF-16-kod enheter, respektive. Detta är för att vara konsekvent med DOM Level 2 Core, där metoderna i CharacterData-gränssnittet använder UTF-16-kod enheter som index och räknare inom teckendatan. Så till exempel, om textinnehållet i ett ‘text’-element är ett enda icke-BMP-tecken, såsom U+10000, kommer ett anrop av getNumberOfChars på det elementet att returnera 2 eftersom två UTF-16-kod enheter (surrogatparet) används för att representera det tecknet. |
| [SVGTextElement](./svgtextelement/) | SVGTextElement-gränssnittet motsvarar ‘text’-elementet. |
| [SVGTextPathElement](./svgtextpathelement/) | SVGTextPathElement-gränssnittet motsvarar ‘textPath’-elementet. |
| [SVGTextPositioningElement](./svgtextpositioningelement/) | SVGTextPositioningElement-gränssnittet ärvs av textrelaterade gränssnitt: SVGTextElement, SVGTSpanElement, SVGTRefElement och SVGAltGlyphElement. |
| [SVGTitleElement](./svgtitleelement/) | SVGTitleElement-gränssnittet motsvarar ‘title’-elementet. |
| [SVGTSpanElement](./svgtspanelement/) | SVGTSpanElement-gränssnittet motsvarar ‘tspan’-elementet. |
| [SVGUseElement](./svguseelement/) | SVGUseElement-gränssnittet motsvarar ‘use’-elementet. |
| [SVGViewElement](./svgviewelement/) | SVGViewElement-gränssnittet motsvarar ‘view’-elementet. |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [ISVGAnimatedPoints](./isvganimatedpoints/) | The SVGAnimatedPoints-gränssnittet stöder element som har ett ‘points’-attribut som innehåller en lista med koordinatvärden och som stödjer möjligheten att animera det attributet. Dessutom kommer ‘points’-attributet på det ursprungliga elementet som nås via XML DOM (t.ex. med getAttribute()-metodanrop) att återspegla eventuella ändringar som gjorts i points. |
| [ISVGFitToViewBox](./isvgfittoviewbox/) | Gränssnittet SVGFitToViewBox definierar DOM-attribut som gäller för element som har XML-attributen ‘viewBox’ och ‘preserveAspectRatio’. |
| [ISVGRenderingIntent](./isvgrenderingintent/) | SVGRenderingIntent-gränssnittet definierar den uppräknade listan med möjliga värden för ‘rendering-intent’-attribut eller -beskrivningar. |
| [ISVGTests](./isvgtests/) | Gränssnittet SVGTests definierar ett gränssnitt som gäller för alla element som har attributen ‘requiredFeatures’, ‘requiredExtensions’ och ‘systemLanguage’. |
| [ISVGUnitTypes](./isvgunittypes/) | SVGUnitTypes-gränssnittet definierar en vanligt använd uppsättning konstanter och är ett basgränssnitt som används av SVGGradientElement, SVGPatternElement, SVGClipPathElement, SVGMaskElement och SVGFilterElement. |
| [ISVGURIReference](./isvgurireference/) | Gränssnittet SVGURIReference definierar ett gränssnitt som gäller för alla element som har samlingen av XLink-attribut, såsom ‘xlink:href’, som definierar en URI-referens. |
| [ISVGZoomAndPan](./isvgzoomandpan/) | SVGZoomAndPan-gränssnittet definierar attributet zoomAndPan och tillhörande konstanter. |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [SVGRenderingIntent](./svgrenderingintent/) | SVGRenderingIntent-uppräkning definierar den uppräknade listan med möjliga värden för ‘rendering-intent’-attribut eller -beskrivningar. |
| [SVGUnitTypes](./svgunittypes/) | SVGUnitTypes-uppräkning definierar en vanligt använd uppsättning konstanter och är ett basgränssnitt som används av SVGGradientElement, SVGPatternElement, SVGClipPathElement, SVGMaskElement och SVGFilterElement. |
| [SVGZoomAndPan](./svgzoomandpan/) | SVGZoomAndPan-uppräkning definierar attributet zoomAndPan och tillhörande konstanter. |
