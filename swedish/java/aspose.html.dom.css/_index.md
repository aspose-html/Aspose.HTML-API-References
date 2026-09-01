---
title: "com.aspose.html.dom.css"
second_title: "Aspose.HTML för Java API-referens"
description: "Tillhandahåller gränssnitt för DOM Level 2 Style Specification. Cascading Style Sheets CSS är ett stilmallspråk som tillåter författare och användare att bifoga stil, t.ex. teckensnitt och avstånd, till strukturerade dokument, t.ex. HTML-dokument och XML-applikationer. Det stöder mediespecifika stilmallar så att författare kan anpassa presentationen av sina dokument för visuella webbläsare, ljudenheter, skrivare, braille-enheter, handhållna enheter etc. Det stödjer också innehållspositionering, tabelllayoutfunktioner för internationalisering och vissa egenskaper relaterade till användargränssnitt. Genom att separera dokumentens presentationsstil från dokumentens innehåll förenklar CSS webbpublicering och webbplatsunderhåll."
type: docs

url: /sv/java/com.aspose.html.dom.css/
---
Tillhandahåller gränssnitt för DOM Level 2 Style Specification. Cascading Style Sheets (CSS) är ett stilmallspråk som låter författare och användare bifoga stil (t.ex. typsnitt och avstånd) till strukturerade dokument (t.ex. HTML-dokument och XML‑applikationer). Det stödjer mediespecifika stilmallar så att författare kan anpassa presentationen av sina dokument för visuella webbläsare, ljudenheter, skrivare, braille‑enheter, handhållna enheter osv. Det stödjer även innehållspositionering, tabelllayout, funktioner för internationalisering och vissa egenskaper relaterade till användargränssnitt. Genom att separera dokumentens presentationsstil från deras innehåll förenklar CSS webbpublicering och webbplatsunderhåll.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [Counter](./counter/) | Counter‑gränssnittet används för att representera vilket som helst räknar‑ eller räknarfunktion‑värde. Detta gränssnitt speglar värdena i den underliggande stil‑egenskapen. |
| [CSSPrimitiveValue](./cssprimitivevalue/) | CSSPrimitiveValue‑gränssnittet härstammar från CSSValue‑gränssnittet och representerar det aktuella beräknade värdet för en CSS‑egenskap. |
| [CSSValue](./cssvalue/) | Representerar ett enkelt eller ett komplext värde. Ett CSSValue‑objekt förekommer endast i samband med en CSS‑egenskap. |
| [CSSValueList](./cssvaluelist/) | CSSValueList‑gränssnittet tillhandahåller abstraktionen av en ordnad samling av CSS‑värden. |
| [Rect](./rect/) | Rect‑gränssnittet används för att representera vilket som helst rect‑värde. Detta gränssnitt speglar värdena i den underliggande stil‑egenskapen. Därför ändrar modifieringar som görs på [`CSSPrimitiveValue`](../com.aspose.html.dom.css/cssprimitivevalue/)‑objekten stil‑egenskapen. |
| [RGBColor](./rgbcolor/) | RGBColor‑gränssnittet används för att representera vilket som helst RGB‑färgvärde. Detta gränssnitt speglar värdena i den underliggande stil‑egenskapen. Därför ändrar modifieringar som görs på CSSPrimitiveValue‑objekten stil‑egenskapen. |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [ICSS2Properties](./icss2properties/) | CSS2Properties‑gränssnittet representerar en bekvämlighetsmekanism för att hämta och sätta egenskaper inom en [`CSSStyleDeclaration`](../com.aspose.html.dom.css/icssstyledeclaration/). Attributen i detta gränssnitt motsvarar alla egenskaper som specificerats i CSS2. Att hämta ett attribut från detta gränssnitt är ekvivalent med att anropa getPropertyValue‑metoden på [`CSSStyleDeclaration`](../com.aspose.html.dom.css/icssstyledeclaration/)‑gränssnittet. Att sätta ett attribut i detta gränssnitt är ekvivalent med att anropa setProperty‑metoden på [`CSSStyleDeclaration`](../com.aspose.html.dom.css/icssstyledeclaration/)‑gränssnittet. |
| [ICSSCharsetRule](./icsscharsetrule/) | CSSCharsetRule‑gränssnittet representerar en @charset‑regel i ett CSS‑stilmall. Värdet på kodningsattributet påverkar inte kodningen av textdata i DOM‑objekten; denna kodning är alltid UTF-16. Efter att en stilmall har lästs in är värdet på kodningsattributet det värde som hittas i @charset‑regeln. Om det inte fanns någon @charset i det ursprungliga dokumentet skapas ingen CSSCharsetRule. Värdet på kodningsattributet kan också användas som en ledtråd för den kodning som används vid serialisering av stilmallen. |
| [ICSSCounterStyleRule](./icsscounterstylerule/) | CSSCounterStyleRule‑gränssnittet representerar en @counter-style‑at‑regel som tillåter författare att definiera en anpassad räknarstil. |
| [ICSSFontFaceRule](./icssfontfacerule/) | CSSFontFaceRule‑gränssnittet representerar en @font-face‑regel i ett CSS‑stilmall. @font-face‑regeln används för att innehålla en samling av teckensnittsbeskrivningar. |
| [ICSSImportRule](./icssimportrule/) | CSSImportRule‑gränssnittet representerar en @import‑regel i ett CSS‑stilmall. @import‑regeln används för att importera stilregler från andra stilmallar. |
| [ICSSKeyframeRule](./icsskeyframerule/) | Det [`CSSKeyframeRule`](../com.aspose.html.dom.css/icsskeyframerule/)‑gränssnittet beskriver ett objekt som representerar en uppsättning stilar för en given nyckelbildruta. Det motsvarar innehållet i en enskild nyckelbildruta av en @keyframes‑at‑regel. |
| [ICSSKeyframesRule](./icsskeyframesrule/) | name‑egenskapen i CSSKeyframeRule‑gränssnittet hämtar och sätter namnet på animationen som används av animation-name‑egenskapen. |
| [ICSSMarginRule](./icssmarginrule/) | CSSMarginRule‑gränssnittet representerar en margin‑at‑regel (t.ex. @top-left) i en @page‑at‑regel. |
| [ICSSMediaRule](./icssmediarule/) | CSSMediaRule‑gränssnittet representerar en @media‑regel i ett CSS‑stilmall. En @media‑regel kan användas för att avgränsa stilregler för specifika mediatyper. |
| [ICSSPageRule](./icsspagerule/) | CSSPageRule‑gränssnittet representerar en @page‑regel i ett CSS‑stilmall. @page‑regeln används för att specificera dimensioner, orientering, marginaler osv. för en sidlåda i paginerade medier. |
| [ICSSRule](./icssrule/) | CSSRule‑gränssnittet är det abstrakta basgränssnittet för alla typer av CSS‑satser. Detta inkluderar både regeluppsättningar och at‑regler. En implementation förväntas bevara alla regler som specificerats i ett CSS‑stilmall, även om regeln inte känns igen av parsern. Oigenkända regler representeras med hjälp av gränssnittet. |
| [ICSSRuleList](./icssrulelist/) | En CSSRuleList representerar en ordnad samling av skrivskyddade [`CSSRule`](../com.aspose.html.dom.css/icssrule/)‑objekt. |
| [ICSSStyleDeclaration](./icssstyledeclaration/) | CSSStyleDeclaration‑gränssnittet representerar ett objekt som är ett CSS‑deklarationsblock och exponerar stilinformation samt olika stilrelaterade metoder och egenskaper. |
| [ICSSStyleRule](./icssstylerule/) | CSSStyleRule‑gränssnittet representerar en enskild CSS‑stilmall. Attributet selectorText ska, vid hämtning, returnera resultatet av serialisering av den associerade gruppen av selektorer. |
| [ICSSStyleSheet](./icssstylesheet/) | CSSStyleSheet‑gränssnittet representerar ett enskilt CSS‑stilmall och låter dig inspektera och ändra listan med regler som finns i stilmallen. Det ärver egenskaper och metoder från sin förälder, [`IStyleSheet`](../com.aspose.html.dom.css/istylesheet/). |
| [ICSSUnknownRule](./icssunknownrule/) | CSSUnknownRule‑gränssnittet representerar en at‑regel som inte stöds av denna användaragenter. |
| [ICSSValueList](./icssvaluelist/) | CSSValueList‑gränssnittet härstammar från [`CSSValue`](../com.aspose.html.dom.css/cssvalue/)-gränssnittet och tillhandahåller abstraktionen av en ordnad samling av CSS‑värden. |
| [IDocumentCSS](./idocumentcss/) | Detta gränssnitt representerar ett dokument med en CSS‑vy. |
| [IDocumentStyle](./idocumentstyle/) | DocumentStyle‑gränssnittet tillhandahåller en mekanism för att hämta de stilark som är inbäddade i ett dokument. Förväntningen är att en instans av DocumentStyle‑gränssnittet kan erhållas genom att använda bindningsspecifika kastmetoder på en instans av Document‑gränssnittet. |
| [IElementCSSInlineStyle](./ielementcssinlinestyle/) | Inbäddad stilinformation som är knuten till element exponeras via style‑attributet. Detta representerar innehållet i STYLE‑attributet för HTML‑element (eller element i andra scheman eller DTD:er som använder STYLE‑attributet på samma sätt). Förväntningen är att en instans av ElementCSSInlineStyle‑gränssnittet kan erhållas genom att använda bindningsspecifika kastmetoder på en instans av Element‑gränssnittet när elementet stödjer inbäddad CSS‑stilinformations. |
| [ILinkStyle](./ilinkstyle/) | LinkStyle‑gränssnittet tillhandahåller en mekanism för att hämta ett stilark från den nod som ansvarar för att länka in det i ett dokument. En instans av LinkStyle‑gränssnittet kan erhållas med bindningsspecifika kastmetoder på en instans av en länknod (HTMLLinkElement, |
| [IMediaList](./imedialist/) | MediaList‑gränssnittet tillhandahåller abstraktionen av en ordnad samling av media, utan att definiera eller begränsa hur samlingen implementeras. En tom lista är samma som en lista som innehåller mediet "all". |
| [IStyleSheet](./istylesheet/) | StyleSheet‑gränssnittet är det abstrakta basgränssnittet för alla typer av stilark. Det representerar ett enskilt stilark som är kopplat till ett strukturerat dokument. I HTML representerar StyleSheet‑gränssnittet antingen ett externt stilark som inkluderas via HTML‑LINK‑elementet eller ett inbäddat STYLE‑element. I XML representerar detta gränssnitt ett externt stilark som inkluderas via en stilarks‑processinstruktion. CSS‑stilark kommer dessutom att implementera det mer specialiserade [`CSSStyleSheet`](../com.aspose.html.dom.css/icssstylesheet/)-gränssnittet. |
| [IStyleSheetList](./istylesheetlist/) | StyleSheetList‑gränssnittet representerar en lista med [`CSSStyleSheet`](../com.aspose.html.dom.css/icssstylesheet/)-objekt. En instans av detta objekt kan returneras av [`Document.styleSheets`](../com.aspose.html.dom/document/stylesheets/). |
| [IViewCSS](./iviewcss/) | IViewCSS‑gränssnittet representerar en utökning av Window‑objektet som ger åtkomst till värdena för alla CSS‑egenskaper hos ett element. |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [CSSEngineMode](./cssenginemode/) | Anger CSSEngine‑läge. Värdena har följande betydelse: |
