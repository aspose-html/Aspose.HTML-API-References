---
title: Aspose.Html.Dom.Css
second_title: Aspose.HTML voor .NET API-referentie
description: De Aspose.Html.Dom.Css naamruimte is voor alle CSSgerelateerde manipulaties. Het concentreert zich rond CSSeigenschap naam  waardeparen gespecificeerd door officiële CSSdocumenten.
type: docs
weight: 70
url: /nl/net/aspose.html.dom.css/
---
De **Aspose.Html.Dom.Css** naamruimte is voor alle CSS-gerelateerde manipulaties. Het concentreert zich rond CSS-eigenschap naam - waardeparen gespecificeerd door officiële CSS-documenten.

## Klassen

| Klas | Beschrijving |
| --- | --- |
| [Counter](./counter/) | De tellerinterface wordt gebruikt om elke teller of tellerfunctiewaarde weer te geven. Deze interface weerspiegelt de waarden in de onderliggende stijleigenschap. |
| [CSSPrimitiveValue](./cssprimitivevalue/) | De interface CSSPrimitiveValue vertegenwoordigt een enkele CSS-waarde. Deze interface kan worden gebruikt om de waarde te bepalen van een specifieke stijleigenschap die momenteel in een blok is ingesteld of om een specifieke stijleigenschap expliciet binnen het blok in te stellen. Een exemplaar van deze interface kan worden verkregen via de getPropertyCSSValue-methode van de CSSStyleDeclaration-interface. Een CSSPrimitiveValue-object komt alleen voor in een context van een CSS-eigenschap. |
| [CSSValue](./cssvalue/) | Vertegenwoordigt een eenvoudige of een complexe waarde. Een CSSValue-object komt alleen voor in een context van een CSS-eigenschap. |
| [CSSValueList](./cssvaluelist/) | De interface CSSValueList biedt de abstractie van een geordende verzameling CSS-waarden. |
| [Rect](./rect/) | De Rect-interface wordt gebruikt om elke rect-waarde weer te geven. Deze interface weerspiegelt de waarden in de onderliggende stijleigenschap. Wijzigingen aan de CSSPrimitiveValue-objecten wijzigen dus de eigenschap style. |
| [RGBColor](./rgbcolor/) | De RGBColor-interface wordt gebruikt om elke RGB-kleurwaarde weer te geven. Deze interface weerspiegelt de waarden in de onderliggende stijleigenschap. Wijzigingen aan de CSSPrimitiveValue-objecten wijzigen dus de eigenschap style. |
## Interfaces

| Koppel | Beschrijving |
| --- | --- |
| [ICSS2Properties](./icss2properties/) | Biedt een interface voor het manipuleren van CSS2-eigenschappen en stelt waarden in in de context van bepaalde HTML-elementen |
| [ICSSCharsetRule](./icsscharsetrule/) | De CSSCharsetRule-interface vertegenwoordigt een @charset-regel in een CSS-stijlpagina. De waarde van het coderingsattribuut heeft geen invloed op de codering van tekstgegevens in de DOM-objecten; deze codering is altijd UTF-16. Nadat een stylesheet is geladen, is de waarde van het coderingsattribuut de waarde die wordt gevonden in de @charset-regel. Als er geen @charset in het originele document was, wordt er geen CSSCharsetRule gemaakt. De waarde van het coderingsattribuut kan ook worden gebruikt als hint voor de codering die wordt gebruikt bij de serialisatie van het stijlblad. |
| [ICSSCounterStyleRule](./icsscounterstylerule/) | Met de @counter-style-regel kunnen auteurs een aangepaste tellerstijl definiëren. |
| [ICSSFontFaceRule](./icssfontfacerule/) | De CSSFontFaceRule-interface vertegenwoordigt een @font-face-regel in een CSS-stijlblad. De @font-face-regel wordt gebruikt om een reeks lettertypebeschrijvingen vast te houden. |
| [ICSSImportRule](./icssimportrule/) | De interface CSSImportRule vertegenwoordigt een @import-regel binnen een CSS-stijlpagina. De @import-regel wordt gebruikt om stijlregels uit andere stijlbladen te importeren. |
| [ICSSKeyframeRule](./icsskeyframerule/) | De interface CSSKeyframeRule vertegenwoordigt de stijlregel voor een enkele sleutel. |
| [ICSSKeyframesRule](./icsskeyframesrule/) | De CSSKeyframesRule-interface vertegenwoordigt een complete set keyframes voor een enkele animatie |
| [ICSSMarginRule](./icssmarginrule/) | De interface CSSMarginRule vertegenwoordigt een marge op regel. |
| [ICSSMediaRule](./icssmediarule/) | De CSSMediaRule-interface vertegenwoordigt een @media-regel in een CSS-stijlblad. Een @media-regel kan worden gebruikt om stijlregels voor specifieke mediatypen af te bakenen. |
| [ICSSPageRule](./icsspagerule/) | De CSSPageRule-interface vertegenwoordigt een @page-regel binnen een CSS-stijlpagina. De @page-regel wordt gebruikt om de afmetingen, oriëntatie, marges, enz. van een paginavak voor gewisselde media te specificeren. |
| [ICSSRule](./icssrule/) | De CSSRule-interface is de abstracte basisinterface voor elk type CSS-statement. Dit omvat zowel regelsets als at-regels. Van een implementatie wordt verwacht dat deze alle regels behoudt die zijn gespecificeerd in een CSS-stijlblad, zelfs als de regel niet wordt herkend door de parser. Niet-herkende regels worden weergegeven met behulp van de!:ICSSUnknownRule interface. |
| [ICSSRuleList](./icssrulelist/) | De interface CSSRuleList biedt de abstractie van een geordende verzameling CSS-regels. |
| [ICSSStyleDeclaration](./icssstyledeclaration/) | De CSSStyleDeclaration-interface vertegenwoordigt een enkel CSS-declaratieblok. Deze interface kan worden gebruikt om de stijleigenschappen te bepalen die momenteel in een blok zijn ingesteld of om stijleigenschappen expliciet binnen het blok in te stellen. |
| [ICSSStyleRule](./icssstylerule/) | De CSSStyleRule-interface vertegenwoordigt een enkele regelset in een CSS-stijlpagina. |
| [ICSSStyleSheet](./icssstylesheet/) | De CSSStyleSheet-interface is een concrete interface die wordt gebruikt om een CSS-stijlblad weer te geven, dwz een stijlblad waarvan het inhoudstype "tekst/css" is. |
| [ICSSUnknownRule](./icssunknownrule/) | De interface CSSUnknownRule vertegenwoordigt een at-regel die niet wordt ondersteund door deze user-agent. |
| [ICSSValueList](./icssvaluelist/) | De interface biedt de abstractie van een geordende verzameling CSS-waarden. |
| [IDocumentCSS](./idocumentcss/) | Deze interface vertegenwoordigt een document met een CSS-weergave. |
| [IDocumentStyle](./idocumentstyle/) | De DocumentStyle-interface biedt een mechanisme waarmee de stijlbladen die in een document zijn ingesloten, kunnen worden opgehaald. De verwachting is dat een instantie van de DocumentStyle-interface kan worden verkregen door bindingspecifieke castingmethoden te gebruiken op een instantie van de Document-interface. |
| [IElementCSSInlineStyle](./ielementcssinlinestyle/) | Inline stijlinformatie gekoppeld aan elementen wordt weergegeven via het stijlattribuut. Dit vertegenwoordigt de inhoud van het STYLE-attribuut voor HTML-elementen (of elementen in andere schema's of DTD's die het STYLE-attribuut op dezelfde manier gebruiken). |
| [ILinkStyle](./ilinkstyle/) | De LinkStyle-interface biedt een mechanisme waarmee een stijlblad kan worden opgehaald van het knooppunt dat verantwoordelijk is voor het koppelen ervan aan een document. Een exemplaar van de LinkStyle-interface kan worden verkregen met behulp van bindingspecifieke castingmethoden op een exemplaar van een koppelingsknooppunt (HTMLLinkElement, HTMLStyleElement of ProcessingInstruction in DOM Level 2). |
| [IMediaList](./imedialist/) | De MediaList-interface biedt de abstractie van een geordende verzameling media, zonder te definiëren of te beperken hoe deze verzameling wordt geïmplementeerd. Een lege lijst is hetzelfde als een lijst die het medium "all" bevat. |
| [IStyleSheet](./istylesheet/) | De StyleSheet-interface is de abstracte basisinterface voor elk type stijlblad. Het vertegenwoordigt een enkel opmaakmodel dat is gekoppeld aan een gestructureerd document. |
| [IStyleSheetList](./istylesheetlist/) | De interface StyleSheetList biedt de abstractie van een geordende verzameling stijlbladen. |
| [IViewCSS](./iviewcss/) | Deze interface vertegenwoordigt een CSS-weergave. |
## Opsomming

| Opsomming | Beschrijving |
| --- | --- |
| [CSSEngineMode](./cssenginemode/) | Specificeert CSSEngine-modus |


