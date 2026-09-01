---
title: "Classe XpsDevice"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Classe com.aspose.html.rendering.xps.XpsDevice. Représente le rendu vers un document xps."
type: docs

url: /fr/java/com.aspose.html.rendering.xps/xpsdevice/
---
## XpsDevice class

Représente le rendu d'un document xps.

```java
public class XpsDevice : Device<XpsGraphicContext, XpsRenderingOptions>
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [XpsDevice](xpsdevice/#constructor)(ICreateStreamProvider) | Initialise une nouvelle instance de la classe `XpsDevice`. |
| [XpsDevice](xpsdevice/#constructor_4)(Stream) | Initialise une nouvelle instance de la classe `XpsDevice`. |
| [XpsDevice](xpsdevice/#constructor_5)(String) | Initialise une nouvelle instance de la classe `XpsDevice`. |
| [XpsDevice](xpsdevice/#constructor_1)(XpsRenderingOptions, ICreateStreamProvider) | Initialise une nouvelle instance de la classe `XpsDevice` avec des options de rendu et un fournisseur de flux. |
| [XpsDevice](xpsdevice/#constructor_2)(XpsRenderingOptions, Stream) | Initialise une nouvelle instance de la classe `XpsDevice` avec des options de rendu et un flux de sortie. |
| [XpsDevice](xpsdevice/#constructor_3)(XpsRenderingOptions, String) | Initialise une nouvelle instance de la classe `XpsDevice` avec des options de rendu et le nom du fichier de sortie. |

## Propriétés

| Nom | Description |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## Méthodes

| Nom | Description |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/device-2/addrect/)(RectangleF) |  |
| [beginDocument](../../com.aspose.html.rendering/device-2/begindocument/)(Document) |  |
| [beginElement](../../com.aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) |  |
| [beginPage](../../com.aspose.html.rendering/device-2/beginpage/)(SizeF) |  |
| [clip](../../com.aspose.html.rendering/device-2/clip/)(FillRule) |  |
| [closePath](../../com.aspose.html.rendering/device-2/closepath/)() |  |
| [cubicBezierTo](../../com.aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) |  |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() |  |
| [drawImage](../../com.aspose.html.rendering/device-2/drawimage/)(byte[], WebImageFormat, RectangleF) |  |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() |  |
| [endElement](../../com.aspose.html.rendering/device-2/endelement/)(Element) |  |
| [endPage](../../com.aspose.html.rendering/device-2/endpage/)() |  |
| [fill](../../com.aspose.html.rendering/device-2/fill/)(FillRule) |  |
| [fillText](../../com.aspose.html.rendering/device-2/filltext/)(String, PointF) |  |
| [flush](../../com.aspose.html.rendering/device-2/flush/)() |  |
| [lineTo](../../com.aspose.html.rendering/device-2/lineto/)(PointF) |  |
| [moveTo](../../com.aspose.html.rendering/device-2/moveto/)(PointF) |  |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() |  |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| [stroke](../../com.aspose.html.rendering/device-2/stroke/)() |  |
| [strokeAndFill](../../com.aspose.html.rendering/device-2/strokeandfill/)(FillRule) |  |
| [strokeText](../../com.aspose.html.rendering/device-2/stroketext/)(String, PointF) |  |

## Autres membres

| Nom | Description |
| --- | --- |
| class [XpsGraphicContext](../../com.aspose.html.rendering.xps/xpsdevice.xpsgraphiccontext) | Contient les paramètres de contrôle graphique actuels pour le XpsDevice. Ces paramètres définissent le cadre global dans lequel les opérateurs graphiques s'exécutent. |

### Voir aussi

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [XpsGraphicContext](../xpsdevice.xpsgraphiccontext/)
* class [XpsRenderingOptions](../xpsrenderingoptions/)
* package [com.aspose.html.rendering.xps](../../com.aspose.html.rendering.xps/)
* package [Aspose.HTML](../../)
