---
title: "com.aspose.html.dom.svg"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.svg 包中的所有类均基于 w3c SVG2 推荐。使用此包，您可以根据需求加载、导航或渲染 SVG 文件。"
type: docs

url: /zh/java/com.aspose.html.dom.svg/
---
**com.aspose.html.dom.svg** 包中的所有类均基于 W3C SVG2 推荐。使用此包，您可以根据需求加载、导航或渲染 SVG 文件。

## 类

| 类 | 描述 |
| --- | --- |
| [SVGAElement](./svgaelement/) | SVGAElement 接口对应于 ‘a’ 元素。 |
| [SVGAnimateElement](./svganimateelement/) | SVGAnimateElement 接口对应于 ‘animate’ 元素。通过 SVG DOM 进行面向对象的访问以获取 ‘animate’ 元素的属性不可用。 |
| [SVGAnimateMotionElement](./svganimatemotionelement/) | SVGAnimateMotionElement 接口对应于 ‘animateMotion’ 元素。通过 SVG DOM 进行面向对象的访问以获取 ‘animateMotion’ 元素的属性不可用。 |
| [SVGAnimateTransformElement](./svganimatetransformelement/) | SVGAnimateTransformElement 接口对应于 ‘animateTransform’ 元素。通过 SVG DOM 进行面向对象的访问以获取 ‘animateTransform’ 元素的属性不可用。 |
| [SVGAnimationElement](./svganimationelement/) | SVGAnimationElement 接口是所有动画元素接口的基础接口：SVGAnimateElement、SVGSetElement、SVGAnimateColorElement、SVGAnimateMotionElement 和 SVGAnimateTransformElement。 |
| [SVGCircleElement](./svgcircleelement/) | SVGCircleElement 接口对应于 ‘circle’ 元素。 |
| [SVGClipPathElement](./svgclippathelement/) | SVGClipPathElement 接口对应于 ‘clipPath’ 元素。 |
| [SVGComponentTransferFunctionElement](./svgcomponenttransferfunctionelement/) | 此接口定义了一个供组件传输函数接口使用的基础接口。 |
| [SVGCursorElement](./svgcursorelement/) | SVGCursorElement 接口对应于 ‘cursor’ 元素。 |
| [SVGDefsElement](./svgdefselement/) | SVGDefsElement 接口对应于 ‘defs’ 元素。 |
| [SVGDescElement](./svgdescelement/) | SVGDescElement 接口对应于 ‘desc’ 元素。 |
| [SVGDocument](./svgdocument/) | `SVGDocument` 是 SVG 层次结构的根，保存整个内容。除了提供对层次结构的访问外，它还提供了一些便利方法，用于从文档中获取特定信息集。当 ‘svg’ 元素以内联方式作为来自其他包的文档的组件嵌入时，例如当 ‘svg’ 元素以内联方式嵌入 XHTML 文档 [XHTML] 中时，将不存在 SVGDocument 对象；相反，文档对象层次结构中的根对象将是其他类型的 Document 对象，例如 HTMLDocument 对象。然而，当 XML 文档层次结构的根元素是 ‘svg’ 元素时（例如查看独立的 SVG 文件，即 MIME 类型为 \"image/svg+xml\" 的文件），SVGDocument 对象确实会存在。在这种情况下，SVGDocument 对象将是文档对象模型层次结构的根对象。 |
| [SVGElement](./svgelement/) | 所有直接对应于 SVG 语言中元素的 SVG DOM 接口（例如对应 ‘path’ 元素的 SVGPathElement 接口）均继承自 SVGElement 接口。 |
| [SVGElementInstance](./svgelementinstance/) | 每个 use 元素影子树的根对象实现了 SVGUseElementShadowRoot 接口。该接口目前未对 ShadowRoot 接口和 DocumentOrShadowRoot 混入中定义的属性和方法进行任何扩展。然而，从作者脚本的角度来看，以此节点为根的树是完全只读的。 |
| [SVGEllipseElement](./svgellipseelement/) | SVGEllipseElement 接口对应于 ‘ellipse’ 元素。 |
| [SVGException](./svgexception/) | 当特定的 SVG 操作无法执行时，会抛出此异常。 |
| [SVGFilterElement](./svgfilterelement/) | SVGFilterElement 接口对应于 ‘filter’ 元素。 |
| [SVGForeignObjectElement](./svgforeignobjectelement/) | SVGForeignObjectElement 接口对应于 ‘foreignObject’ 元素。 |
| [SVGGElement](./svggelement/) | SVGGElement 接口对应于 ‘g’ 元素。 |
| [SVGGeometryElement](./svggeometryelement/) | SVGGeometryElement 接口表示其渲染由几何形状及等价路径定义且可以填充和描边的 SVG 元素。这包括路径和基本形状。 |
| [SVGGradientElement](./svggradientelement/) | SVGGradientElement 接口是 SVGLinearGradientElement 和 SVGRadialGradientElement 使用的基础接口。 |
| [SVGGraphicsElement](./svggraphicselement/) | SVGGraphicsElement 接口表示其主要目的是直接在组中渲染图形的 SVG 元素。 |
| [SVGImageElement](./svgimageelement/) | SVGImageElement 接口对应于 ‘image’ 元素。 |
| [SVGLinearGradientElement](./svglineargradientelement/) | SVGLinearGradientElement 接口对应于 ‘linearGradient’ 元素。 |
| [SVGLineElement](./svglineelement/) | SVGLineElement 接口对应于 ‘line’ 元素。 |
| [SVGMarkerElement](./svgmarkerelement/) | 该 SVGMarkerElement 接口对应于 ‘marker’ 元素。 |
| [SVGMaskElement](./svgmaskelement/) | 该 SVGMaskElement 接口对应于 ‘mask’ 元素。 |
| [SVGMetadataElement](./svgmetadataelement/) | 该 SVGMetadataElement 接口对应于 ‘metadata’ 元素。 |
| [SVGMPathElement](./svgmpathelement/) | 该 SVGMPathElement 接口对应于 ‘mpath’ 元素。 |
| [SVGPathElement](./svgpathelement/) | 该 SVGPathElement 接口对应于 ‘path’ 元素。 |
| [SVGPatternElement](./svgpatternelement/) | 该 SVGPatternElement 接口对应于 ‘pattern’ 元素。 |
| [SVGPolygonElement](./svgpolygonelement/) | 该 SVGPolygonElement 接口对应于 ‘polygon’ 元素。 |
| [SVGPolylineElement](./svgpolylineelement/) | 该 SVGPolylineElement 接口对应于 ‘polyline’ 元素。 |
| [SVGRadialGradientElement](./svgradialgradientelement/) | 该 SVGRadialGradientElement 接口对应于 ‘radialGradient’ 元素。 |
| [SVGRectElement](./svgrectelement/) | 该 SVGRectElement 接口对应于 ‘rect’ 元素。 |
| [SVGScriptElement](./svgscriptelement/) | 该 SVGScriptElement 接口对应于 ‘script’ 元素。 |
| [SVGSetElement](./svgsetelement/) | 该 SVGSetElement 接口对应于 ‘set’ 元素。通过 SVG DOM 对 ‘set’ 元素属性的面向对象访问不可用。 |
| [SVGStopElement](./svgstopelement/) | 该 SVGStopElement 接口对应于 ‘stop’ 元素。 |
| [SVGStyleElement](./svgstyleelement/) | 该 SVGStyleElement 接口对应于 ‘style’ 元素。 |
| [SVGSVGElement](./svgsvgelement/) | 关键的接口定义是 SVGSVGElement 接口，它是对应于 ‘svg’ 元素的接口。该接口包含各种常用的实用方法，例如矩阵运算以及控制可视渲染设备重绘时间的能力。 |
| [SVGSwitchElement](./svgswitchelement/) | 该 SVGSwitchElement 接口对应于 ‘switch’ 元素。 |
| [SVGSymbolElement](./svgsymbolelement/) | 该 SVGSymbolElement 接口对应于 ‘symbol’ 元素。 |
| [SVGTextContentElement](./svgtextcontentelement/) | SVGTextContentElement 被各种文本相关接口继承，例如 SVGTextElement、SVGTSpanElement、SVGTRefElement、SVGAltGlyphElement 和 SVGTextPathElement。对于该接口中引用字符索引或字符数量的方法，这些引用应解释为 UTF-16 代码单元的索引或 UTF-16 代码单元的数量。这是为了与 DOM Level 2 Core 保持一致，在 CharacterData 接口的方法中使用 UTF-16 代码单元作为字符数据中的索引和计数。例如，如果 ‘text’ 元素的文本内容是单个非 BMP 字符，例如 U+10000，则对该元素调用 getNumberOfChars 将返回 2，因为表示该字符需要两个 UTF-16 代码单元（代理对）。 |
| [SVGTextElement](./svgtextelement/) | 该 SVGTextElement 接口对应于 ‘text’ 元素。 |
| [SVGTextPathElement](./svgtextpathelement/) | 该 SVGTextPathElement 接口对应于 ‘textPath’ 元素。 |
| [SVGTextPositioningElement](./svgtextpositioningelement/) | 该 SVGTextPositioningElement 接口被文本相关接口继承：SVGTextElement、SVGTSpanElement、SVGTRefElement 和 SVGAltGlyphElement。 |
| [SVGTitleElement](./svgtitleelement/) | 该 SVGTitleElement 接口对应于 ‘title’ 元素。 |
| [SVGTSpanElement](./svgtspanelement/) | 该 SVGTSpanElement 接口对应于 ‘tspan’ 元素。 |
| [SVGUseElement](./svguseelement/) | 该 SVGUseElement 接口对应于 ‘use’ 元素。 |
| [SVGViewElement](./svgviewelement/) | 该 SVGViewElement 接口对应于 ‘view’ 元素。 |
## 接口

| 接口 | 描述 |
| --- | --- |
| [ISVGAnimatedPoints](./isvganimatedpoints/) | SVGAnimatedPoints 接口支持具有 ‘points’ 属性的元素，该属性保存坐标值列表，并支持对该属性进行动画化。此外，通过 XML DOM（例如使用 getAttribute() 方法调用）访问的原始元素上的 ‘points’ 属性将反映对 points 所做的任何更改。 |
| [ISVGFitToViewBox](./isvgfittoviewbox/) | SVGFitToViewBox 接口定义适用于具有 XML 属性 ‘viewBox’ 和 ‘preserveAspectRatio’ 的元素的 DOM 属性。 |
| [ISVGRenderingIntent](./isvgrenderingintent/) | SVGRenderingIntent 接口定义 ‘rendering-intent’ 属性或描述符的可能取值的枚举列表。 |
| [ISVGTests](./isvgtests/) | SVGTests 接口定义适用于所有具有 ‘requiredFeatures’ 、‘requiredExtensions’ 和 ‘systemLanguage’ 属性的元素的接口。 |
| [ISVGUnitTypes](./isvgunittypes/) | SVGUnitTypes 接口定义了一组常用常量，并且是 SVGGradientElement、SVGPatternElement、SVGClipPathElement、SVGMaskElement 和 SVGFilterElement 使用的基础接口。 |
| [ISVGURIReference](./isvgurireference/) | SVGURIReference 接口定义适用于所有具有 XLink 属性集合（例如 ‘xlink:href’）的元素的接口，这些属性定义了 URI 引用。 |
| [ISVGZoomAndPan](./isvgzoomandpan/) | SVGZoomAndPan 接口定义 zoomAndPan 属性及其相关常量。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [SVGRenderingIntent](./svgrenderingintent/) | SVGRenderingIntent 枚举定义 ‘rendering-intent’ 属性或描述符的可能取值的枚举列表。 |
| [SVGUnitTypes](./svgunittypes/) | SVGUnitTypes 枚举定义了一组常用常量，并且是 SVGGradientElement、SVGPatternElement、SVGClipPathElement、SVGMaskElement 和 SVGFilterElement 使用的基础接口。 |
| [SVGZoomAndPan](./svgzoomandpan/) | SVGZoomAndPan 枚举定义 zoomAndPan 属性及其相关常量。 |
