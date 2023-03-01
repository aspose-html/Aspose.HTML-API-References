---
title: Aspose.Html.Dom.Css
second_title: Aspose.HTML för .NET API Referens
description: Den Aspose.Html.Dom.Css namnutrymmet är för alla CSSrelaterade manipulationer. Det koncentreras kring CSSegenskapens namn  värde par specificerat av CSS officiella dokument.
type: docs
weight: 70
url: /sv/net/aspose.html.dom.css/
---
Den **Aspose.Html.Dom.Css** namnutrymmet är för alla CSS-relaterade manipulationer. Det koncentreras kring CSS-egenskapens namn - värde par specificerat av CSS officiella dokument.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [Counter](./counter/) | Räknargränssnittet används för att representera alla räknare eller räknarfunktionsvärden. Detta gränssnitt återspeglar värdena i den underliggande stilegenskapen. |
| [CSSPrimitiveValue](./cssprimitivevalue/) | CSSPrimitiveValue-gränssnittet representerar ett enda CSS-värde. Detta gränssnitt kan användas för att bestämma värdet av en specifik stilegenskap som för närvarande är inställd i ett block eller för att ställa in en specifik stilegenskap explicit inom blocket. En instans av detta gränssnitt kan erhållas från metoden getPropertyCSSValue i CSSStyleDeclaration-gränssnittet. Ett CSSPrimitiveValue-objekt förekommer endast i en kontext av en CSS-egenskap. |
| [CSSValue](./cssvalue/) | Representerar ett enkelt eller ett komplext värde. Ett CSSValue-objekt förekommer bara i en kontext av en CSS-egenskap. |
| [CSSValueList](./cssvaluelist/) | CSSValueList-gränssnittet tillhandahåller abstraktionen av en ordnad samling av CSS-värden. |
| [Rect](./rect/) | Rect-gränssnittet används för att representera alla rect-värden. Detta gränssnitt återspeglar värdena i den underliggande stilegenskapen. Därför ändrar modifieringar gjorda av CSSPrimitiveValue-objekten stilegenskapen. |
| [RGBColor](./rgbcolor/) | RGBColor-gränssnittet används för att representera alla RGB-färgvärden. Detta gränssnitt återspeglar värdena i den underliggande stilegenskapen. Därför ändrar modifieringar gjorda av CSSPrimitiveValue-objekten stilegenskapen. |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [ICSS2Properties](./icss2properties/) | Tillhandahåller gränssnitt för manipulering av CSS2-egenskapersuppsättningsvärden i samband med vissa HTML-element |
| [ICSSCharsetRule](./icsscharsetrule/) | CSSCharsetRule-gränssnittet representerar en @charset-regel i en CSS-formatmall. Värdet på kodningsattributet påverkar inte kodningen av textdata i DOM-objekten; denna kodning är alltid UTF-16. När en stilmall har laddats är värdet för kodningsattributet värdet som finns i @charset-regeln. Om det inte fanns någon @charset i originaldokumentet skapas ingen CSSCharsetRule. Värdet på kodningsattributet kan också användas som en ledtråd för kodningen som används vid serialisering av stilmallen. |
| [ICSSCounterStyleRule](./icsscounterstylerule/) | @counter-style-regeln tillåter författare att definiera en anpassad räknarstil. |
| [ICSSFontFaceRule](./icssfontfacerule/) | CSSFontFaceRule-gränssnittet representerar en @font-face-regel i en CSS-stilmall. @font-face-regeln används för att hålla en uppsättning teckensnittsbeskrivningar. |
| [ICSSImportRule](./icssimportrule/) | CSSImportRule-gränssnittet representerar en @import-regel i en CSS-formatmall. @import-regeln används för att importera stilregler från andra stilmallar. |
| [ICSSKeyframeRule](./icsskeyframerule/) | CSSKeyframeRule-gränssnittet representerar stilregeln för en enda nyckel. |
| [ICSSKeyframesRule](./icsskeyframesrule/) | CSSKeyframesRule-gränssnittet representerar en komplett uppsättning nyckelbildrutor för en enda animation |
| [ICSSMarginRule](./icssmarginrule/) | CSSMarginRule-gränssnittet representerar en margin at-rule. |
| [ICSSMediaRule](./icssmediarule/) | CSSMediaRule-gränssnittet representerar en @media-regel i en CSS-stilmall. En @mediaregel kan användas för att avgränsa stilregler för specifika mediatyper. |
| [ICSSPageRule](./icsspagerule/) | CSSPageRule-gränssnittet representerar en @page-regel i en CSS-formatmall. @page-regeln används för att ange dimensioner, orientering, marginaler etc. för en sidruta för sidmedia. |
| [ICSSRule](./icssrule/) | CSSRule-gränssnittet är det abstrakta basgränssnittet för alla typer av CSS-satser. Detta inkluderar både regeluppsättningar och at-regler. En implementering förväntas bevara alla regler som anges i en CSS-stilmall, även om regeln inte känns igen av tolken. Okända regler representeras med hjälp av!:ICSSUnknownRule gränssnitt. |
| [ICSSRuleList](./icssrulelist/) | CSSRuleList-gränssnittet tillhandahåller abstraktionen av en ordnad samling av CSS-regler. |
| [ICSSStyleDeclaration](./icssstyledeclaration/) | CSSStyleDeclaration-gränssnittet representerar ett enda CSS-deklarationsblock. Detta gränssnitt kan användas för att bestämma de stilegenskaper som för närvarande är inställda i ett block eller för att ställa in stilegenskaper uttryckligen inom blocket. |
| [ICSSStyleRule](./icssstylerule/) | CSSStyleRule-gränssnittet representerar en enda regeluppsättning i en CSS-formatmall. |
| [ICSSStyleSheet](./icssstylesheet/) | CSSStyleSheet-gränssnittet är ett konkret gränssnitt som används för att representera en CSS-stilmall, dvs. en stilmall vars innehållstyp är "text/css". |
| [ICSSUnknownRule](./icssunknownrule/) | CSSUnknownRule-gränssnittet representerar en at-regel som inte stöds av denna användaragent. |
| [ICSSValueList](./icssvaluelist/) | Gränssnittet tillhandahåller abstraktionen av en ordnad samling av CSS-värden. |
| [IDocumentCSS](./idocumentcss/) | Detta gränssnitt representerar ett dokument med en CSS-vy. |
| [IDocumentStyle](./idocumentstyle/) | DocumentStyle-gränssnittet tillhandahåller en mekanism genom vilken stilmallarna som är inbäddade i ett dokument kan hämtas. Förväntningen är att en instans av DocumentStyle-gränssnittet kan erhållas genom att använda bindningsspecifika castingmetoder på en instans av Document-gränssnittet. |
| [IElementCSSInlineStyle](./ielementcssinlinestyle/) | Inline stilinformation kopplad till element exponeras genom stilattributet. Detta representerar innehållet i STYLE-attributet för HTML-element (eller element i andra scheman eller DTD:er som använder STYLE-attributet på samma sätt). |
| [ILinkStyle](./ilinkstyle/) | LinkStyle-gränssnittet tillhandahåller en mekanism genom vilken en stilmall kan hämtas från den nod som är ansvarig för att länka den till ett dokument. En instans av LinkStyle-gränssnittet kan erhållas med bindningsspecifika castingmetoder på en instans av en länknod (HTMLLinkElement, HTMLStyleElement eller ProcessingInstruction i DOM Level 2). |
| [IMediaList](./imedialist/) | MediaList-gränssnittet tillhandahåller abstraktionen av en ordnad samling av media, utan att definiera eller begränsa hur denna samling implementeras. En tom lista är detsamma som en lista som innehåller mediet "all". |
| [IStyleSheet](./istylesheet/) | StyleSheet-gränssnittet är det abstrakta basgränssnittet för alla typer av stilmall. Den representerar en enda formatmall som är associerad med ett strukturerat dokument. |
| [IStyleSheetList](./istylesheetlist/) | StyleSheetList-gränssnittet tillhandahåller abstraktionen av en ordnad samling stilmallar. |
| [IViewCSS](./iviewcss/) | Det här gränssnittet representerar en CSS-vy. |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [CSSEngineMode](./cssenginemode/) | Anger CSSEengine mode |


