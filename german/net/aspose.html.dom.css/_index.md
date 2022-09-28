---
title: Aspose.Html.Dom.Css
second_title: Aspose.HTML für .NET-API-Referenz
description: Die Aspose.Html.Dom.Css Namespace ist für alle CSSbezogenen Manipulationen. Er konzentriert sich auf CSSEigenschaftsnameWertPaare  die in offiziellen CSSDokumenten angegeben sind.
type: docs
weight: 70
url: /de/net/aspose.html.dom.css/
---
Die **Aspose.Html.Dom.Css** Namespace ist für alle CSS-bezogenen Manipulationen. Er konzentriert sich auf CSS-Eigenschaftsname-Wert-Paare , die in offiziellen CSS-Dokumenten angegeben sind.

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [Counter](./counter) | Die Zählerschnittstelle wird verwendet, um einen beliebigen Zähler- oder Zählerfunktionswert darzustellen. Diese Schnittstelle spiegelt die Werte in der zugrunde liegenden Stileigenschaft wider. |
| [CSSPrimitiveValue](./cssprimitivevalue) | Die CSSPrimitiveValue-Schnittstelle repräsentiert einen einzelnen CSS-Wert. Diese Schnittstelle kann verwendet werden, um den Wert einer bestimmten Stileigenschaft zu bestimmen, die derzeit in einem Block festgelegt ist, oder um eine bestimmte Stileigenschaft explizit innerhalb des Blocks festzulegen. Eine Instanz dieser Schnittstelle kann von der getPropertyCSSValue-Methode der CSSStyleDeclaration-Schnittstelle abgerufen werden. Ein CSSPrimitiveValue-Objekt kommt nur im Kontext einer CSS-Eigenschaft vor. |
| [CSSValue](./cssvalue) | Repräsentiert einen einfachen oder komplexen Wert. Ein CSSValue-Objekt kommt nur im Kontext einer CSS-Eigenschaft vor. |
| [CSSValueList](./cssvaluelist) | Die CSSValueList-Schnittstelle bietet die Abstraktion einer geordneten Sammlung von CSS-Werten. |
| [Rect](./rect) | Die Rect-Schnittstelle wird verwendet, um beliebige Rect-Werte darzustellen. Diese Schnittstelle spiegelt die Werte in der zugrunde liegenden Stileigenschaft wider. Daher ändern Änderungen an den CSSPrimitiveValue-Objekten die Eigenschaft style. |
| [RGBColor](./rgbcolor) | Die RGBColor-Schnittstelle wird verwendet, um beliebige RGB-Farbwerte darzustellen. Diese Schnittstelle spiegelt die Werte in der zugrunde liegenden Stileigenschaft wider. Daher ändern Änderungen an den CSSPrimitiveValue-Objekten die Eigenschaft style. |
## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [ICSS2Properties](./icss2properties) | Stellt eine Schnittstelle für die Manipulation von CSS2-Eigenschaften im Zusammenhang mit bestimmten HTML-Elementen bereit |
| [ICSSCharsetRule](./icsscharsetrule) | Die CSSCharsetRule-Schnittstelle repräsentiert eine @charset-Regel in einem CSS-Stylesheet. Der Wert des Attributs encoding wirkt sich nicht auf die Codierung von Textdaten in den DOM-Objekten aus; diese Kodierung ist immer UTF-16. Nachdem ein Stylesheet geladen wurde, ist der Wert des Attributs encoding der Wert, der in der @charset-Regel gefunden wird. Wenn im Originaldokument kein @charset vorhanden war, wird keine CSSCharsetRule erstellt. Der Wert des Attributs encoding kann auch als Hinweis auf die Codierung verwendet werden, die bei der Serialisierung des Stylesheets verwendet wird. |
| [ICSSCounterStyleRule](./icsscounterstylerule) | Mit der @counter-style-Regel können Autoren einen benutzerdefinierten Zählerstil definieren. |
| [ICSSFontFaceRule](./icssfontfacerule) | Die CSSFontFaceRule-Schnittstelle repräsentiert eine @font-face-Regel in einem CSS-Stylesheet. Die @font-face-Regel wird verwendet, um eine Reihe von Schriftbeschreibungen zu speichern. |
| [ICSSImportRule](./icssimportrule) | Die CSSImportRule-Schnittstelle repräsentiert eine @import-Regel innerhalb eines CSS-Stylesheets. Die @import-Regel wird verwendet, um Stilregeln aus anderen Stilvorlagen zu importieren. |
| [ICSSKeyframeRule](./icsskeyframerule) | Die Schnittstelle CSSKeyframeRule stellt die Stilregel für einen einzelnen Schlüssel dar. |
| [ICSSKeyframesRule](./icsskeyframesrule) | Die CSSKeyframesRule-Schnittstelle repräsentiert einen vollständigen Satz von Keyframes für eine einzelne Animation |
| [ICSSMarginRule](./icssmarginrule) | Die CSSMarginRule-Schnittstelle repräsentiert eine Randregel. |
| [ICSSMediaRule](./icssmediarule) | Die CSSMediaRule-Schnittstelle repräsentiert eine @media-Regel in einem CSS-Stylesheet. Eine @media-Regel kann verwendet werden, um Stilregeln für bestimmte Medientypen abzugrenzen. |
| [ICSSPageRule](./icsspagerule) | Die CSSPageRule-Schnittstelle repräsentiert eine @page-Regel innerhalb eines CSS-Stylesheets. Die @page-Regel wird verwendet, um die Abmessungen, Ausrichtung, Ränder usw. eines Seitenrahmens für Seitenmedien festzulegen. |
| [ICSSRule](./icssrule) | Die CSSRule-Schnittstelle ist die abstrakte Basisschnittstelle für jede Art von CSS-Anweisung. Dies umfasst sowohl Regelsätze als auch at-Regeln. Von einer Implementierung wird erwartet, dass sie alle in einem CSS-Stylesheet angegebenen Regeln beibehält, selbst wenn die Regel nicht vom Parser erkannt wird. Nicht erkannte Regeln werden mit dargestellt!:ICSSUnknownRule Schnittstelle. |
| [ICSSRuleList](./icssrulelist) | Die Schnittstelle CSSRuleList bietet die Abstraktion einer geordneten Sammlung von CSS-Regeln. |
| [ICSSStyleDeclaration](./icssstyledeclaration) | Die CSSStyleDeclaration-Schnittstelle repräsentiert einen einzelnen CSS-Deklarationsblock. Diese Schnittstelle kann verwendet werden, um die Stileigenschaften zu bestimmen, die derzeit in einem Block festgelegt sind, oder um Stileigenschaften explizit innerhalb des Blocks festzulegen. |
| [ICSSStyleRule](./icssstylerule) | Die CSSStyleRule-Schnittstelle stellt einen einzelnen Regelsatz in einem CSS-Stylesheet dar. |
| [ICSSStyleSheet](./icssstylesheet) | Die CSSStyleSheet-Schnittstelle ist eine konkrete Schnittstelle, die verwendet wird, um ein CSS-Stylesheet darzustellen, dh ein Stylesheet, dessen Inhaltstyp "text/css" ist. |
| [ICSSUnknownRule](./icssunknownrule) | Die CSSUnknownRule-Schnittstelle stellt eine at-Regel dar, die von diesem Benutzeragenten nicht unterstützt wird. |
| [ICSSValueList](./icssvaluelist) | Die Schnittstelle bietet die Abstraktion einer geordneten Sammlung von CSS-Werten. |
| [IDocumentCSS](./idocumentcss) | Diese Schnittstelle repräsentiert ein Dokument mit einer CSS-Ansicht. |
| [IDocumentStyle](./idocumentstyle) | Die DocumentStyle-Schnittstelle bietet einen Mechanismus, mit dem die in ein Dokument eingebetteten Stylesheets abgerufen werden können. Es wird erwartet, dass eine Instanz der DocumentStyle-Schnittstelle abgerufen werden kann, indem bindungsspezifische Umwandlungsmethoden für eine Instanz der Document-Schnittstelle verwendet werden. |
| [IElementCSSInlineStyle](./ielementcssinlinestyle) | Mit Elementen verknüpfte Inline-Stilinformationen werden über das Stilattribut angezeigt. Dies repräsentiert den Inhalt des STYLE-Attributs für HTML-Elemente (oder Elemente in anderen Schemas oder DTDs, die das STYLE-Attribut auf die gleiche Weise verwenden). |
| [ILinkStyle](./ilinkstyle) | Die LinkStyle-Schnittstelle bietet einen Mechanismus, mit dem ein Stylesheet von dem Knoten abgerufen werden kann, der für die Verknüpfung mit einem Dokument verantwortlich ist. Eine Instanz der LinkStyle-Schnittstelle kann mit bindungsspezifischen Casting-Methoden auf eine Instanz eines Verknüpfungsknotens (HTMLLinkElement, HTMLStyleElement oder ProcessingInstruction in DOM Level 2) bezogen werden. |
| [IMediaList](./imedialist) | Die MediaList-Schnittstelle bietet die Abstraktion einer geordneten Sammlung von Medien, ohne zu definieren oder einzuschränken, wie diese Sammlung implementiert wird. Eine leere Liste ist gleichbedeutend mit einer Liste, die das Medium „alle“ enthält. |
| [IStyleSheet](./istylesheet) | Die StyleSheet-Schnittstelle ist die abstrakte Basisschnittstelle für jede Art von Stylesheet. Es stellt ein einzelnes Stylesheet dar, das einem strukturierten Dokument zugeordnet ist. |
| [IStyleSheetList](./istylesheetlist) | Die StyleSheetList-Schnittstelle bietet die Abstraktion einer geordneten Sammlung von Stylesheets. |
| [IViewCSS](./iviewcss) | Diese Schnittstelle stellt eine CSS-Ansicht dar. |
## Aufzählung

| Aufzählung | Beschreibung |
| --- | --- |
| [CSSEngineMode](./cssenginemode) | Gibt den CSSEngine-Modus an |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
