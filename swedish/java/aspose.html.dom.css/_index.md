---
title: "com.aspose.html.dom.css"
second_title: "Aspose.HTML för Java API-referens"
description: "Tillhandahåller gränssnitt för DOM Level 2 Style Specification. Cascading Style Sheets (CSS) är ett stilmallspråk som låter författare och användare bifoga stil, t.ex. typsnitt och avstånd, till strukturerade dokument, t.ex. HTML-dokument och XML-applikationer. Det stöder mediespecifika stilmallar så att författare kan anpassa presentationen av sina dokument för visuella webbläsare, ljudenheter, skrivare, braille-enheter, handhållna enheter etc. Det stödjer också innehållspositionering, tabelllayoutfunktioner för internationalisering och vissa egenskaper relaterade till användargränssnitt. Genom att separera dokumentens presentationsstil från dokumentens innehåll förenklar CSS webbpublicering och webbplatsunderhåll."
type: docs

url: /sv/java/com.aspose.html.dom.css/
---
Tillhandahåller gränssnitt för DOM Level 2 Style Specification. Cascading Style Sheets (CSS) är ett stilmallspråk som låter författare och användare fästa stil (t.ex. teckensnitt och avstånd) på strukturerade dokument (t.ex. HTML‑dokument och XML‑applikationer). Det stödjer mediespecifika stilmallar så att författare kan anpassa presentationen av sina dokument för visuella webbläsare, ljudenheter, skrivare, punktskriftsenheter, handhållna enheter osv. Det stödjer också innehållspositionering, tabelllayout, funktioner för internationalisering och vissa egenskaper relaterade till användargränssnittet. Genom att separera dokumentens presentationsstil från deras innehåll förenklar CSS webbpublicering och webbplatsunderhåll.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [Counter](./counter/) | Counter‑gränssnittet används för att representera vilket som helst räknare‑ eller räknarfunktion‑värde. Detta gränssnitt återspeglar värdena i den underliggande stil‑egenskapen. |
| [CSSPrimitiveValue](./cssprimitivevalue/) | CSSPrimitiveValue‑gränssnittet härstammar från CSSValue‑gränssnittet och representerar det aktuella beräknade värdet för en CSS‑egenskap. |
| [CSSValue](./cssvalue/) | Representerar ett enkelt eller ett komplext värde. Ett CSSValue‑objekt förekommer endast i samband med en CSS‑egenskap. |
| [CSSValueList](./cssvaluelist/) | CSSValueList‑gränssnittet tillhandahåller abstraktionen av en ordnad samling av CSS‑värden. |
| [Rect](./rect/) | Rect‑gränssnittet används för att representera vilket som helst rect‑värde. Detta gränssnitt återspeglar värdena i den underliggande stil‑egenskapen. Därför modifierar ändringar som görs på [`CSSPrimitiveValue`](../com.aspose.html.dom.css/cssprimitivevalue/)-objekten stil‑egenskapen. |
| [RGBColor](./rgbcolor/) | RGBColor‑gränssnittet används för att representera vilket som helst RGB‑färgvärde. Detta gränssnitt återspeglar värdena i den underliggande stil‑egenskapen. Därför modifierar ändringar som görs på CSSPrimitiveValue‑objekten stil‑egenskapen. |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [ICSS2Properties](./icss2properties/) | CSS2Properties‑gränssnittet representerar en bekvämlighetsmekanism för att hämta och sätta egenskaper inom en [`CSSStyleDeclaration`](../com.aspose.html.dom.css/icssstyledeclaration/). Attributen i detta gränssnitt motsvarar alla egenskaper som specificeras i CSS2. Att hämta ett attribut från detta gränssnitt är ekvivalent med att anropa getPropertyValue‑metoden på [`CSSStyleDeclaration`](../com.aspose.html.dom.css/icssstyledeclaration/)-gränssnittet. Att sätta ett attribut i detta gränssnitt är ekvivalent med att anropa setProperty‑metoden på [`CSSStyleDeclaration`](../com.aspose.html.dom.css/icssstyledeclaration/)-gränssnittet. |
| [ICSSCharsetRule](./icsscharsetrule/) | CSSCharsetRule‑gränssnittet representerar en @charset‑regel i ett CSS‑stilmall. Värdet på kodningsattributet påverkar inte kodningen av textdata i DOM‑objekten; denna kodning är alltid UTF-16. Efter att en stilmall har lästs in är värdet på kodningsattributet det värde som finns i @charset‑regeln. Om det inte fanns någon @charset i det ursprungliga dokumentet skapas ingen CSSCharsetRule. Värdet på kodningsattributet kan också användas som en ledtråd för den kodning som används vid serialisering av stilmallen. |
| [ICSSCounterStyleRule](./icsscounterstylerule/) | CSSCounterStyleRule‑gränssnittet representerar en @counter-style‑at‑regel som låter författare definiera en anpassad räknarstil. |
| [ICSSFontFaceRule](./icssfontfacerule/) | CSSFontFaceRule‑gränssnittet representerar en @font-face‑regel i ett CSS‑stilmall. @font-face‑regeln används för att innehålla en uppsättning teckensnittsbeskrivningar. |
| [ICSSImportRule](./icssimportrule/) | CSSImportRule‑gränssnittet representerar en @import‑regel i ett CSS‑stilmall. @import‑regeln används för att importera stilregler från andra stilmallar. |
| [ICSSKeyframeRule](./icsskeyframerule/) | Det [`CSSKeyframeRule`](../com.aspose.html.dom.css/icsskeyframerule/)‑gränssnittet beskriver ett objekt som representerar en uppsättning stilar för en given nyckelram. Det motsvarar innehållet i en enskild nyckelram av en @keyframes‑at‑regel. |
| [ICSSKeyframesRule](./icsskeyframesrule/) | name‑egenskapen i CSSKeyframeRule‑gränssnittet hämtar och sätter namnet på animationen som används av animation-name‑egenskapen. |
| [ICSSMarginRule](./icssmarginrule/) | CSSMarginRule‑gränssnittet representerar en marginal‑at‑regel (t.ex. @top-left) i en @page‑at‑regel. |
| [ICSSMediaRule](./icssmediarule/) | CSSMediaRule‑gränssnittet representerar en @media‑regel i ett CSS‑stilmall. En @media‑regel kan användas för att avgränsa stilregler för specifika mediatyper. |
| [ICSSPageRule](./icsspagerule/) | CSSPageRule‑gränssnittet representerar en @page‑regel i ett CSS‑stilmall. @page‑regeln används för att specificera dimensioner, orientering, marginaler osv. för en sidlåda för paginerade medier. |
| [ICSSRule](./icssrule/) | CSSRule‑gränssnittet är det abstrakta basgränssnittet för alla typer av CSS‑satser. Detta inkluderar både regeluppsättningar och at‑regler. En implementation förväntas bevara alla regler som specificeras i ett CSS‑stilmall, även om regeln inte känns igen av parsern. Oigenkända regler representeras med hjälp av gränssnittet. |
| [ICSSRuleList](./icssrulelist/) | En CSSRuleList representerar en ordnad samling av skrivskyddade [`CSSRule`](../com.aspose.html.dom.css/icssrule/)-objekt. |
| [ICSSStyleDeclaration](./icssstyledeclaration/) | CSSStyleDeclaration‑gränssnittet representerar ett objekt som är ett CSS‑deklarationsblock och exponerar stilinformation samt olika stilrelaterade metoder och egenskaper. |
| [ICSSStyleRule](./icssstylerule/) | CSSStyleRule‑gränssnittet representerar en enskild CSS‑stilsregel. Attributet selectorText måste, vid hämtning, returnera resultatet av serialisering av den associerade gruppen av selektorer. |
| [ICSSStyleSheet](./icssstylesheet/) | CSSStyleSheet‑gränssnittet representerar ett enskilt CSS‑formatmall och låter dig inspektera och ändra listan med regler som finns i formatmallen. Det ärver egenskaper och metoder från sin förälder, [`IStyleSheet`](../com.aspose.html.dom.css/istylesheet/). |
| [ICSSUnknownRule](./icssunknownrule/) | CSSUnknownRule‑gränssnittet representerar en at‑regel som inte stöds av denna användaragenter. |
| [ICSSValueList](./icssvaluelist/) | CSSValueList‑gränssnittet härstammar från [`CSSValue`](../com.aspose.html.dom.css/cssvalue/)‑gränssnittet och tillhandahåller abstraktionen av en ordnad samling av CSS‑värden. |
| [IDocumentCSS](./idocumentcss/) | Detta gränssnitt representerar ett dokument med en CSS‑vy. |
| [IDocumentStyle](./idocumentstyle/) | DocumentStyle‑gränssnittet tillhandahåller en mekanism för att hämta de formatmallar som är inbäddade i ett dokument. Förväntningen är att en instans av DocumentStyle‑gränssnittet kan erhållas genom att använda bindningsspecifika kastmetoder på en instans av Document‑gränssnittet. |
| [IElementCSSInlineStyle](./ielementcssinlinestyle/) | Inbäddad stilinformation som är knuten till element exponeras via style‑attributet. Detta representerar innehållet i STYLE‑attributet för HTML‑element (eller element i andra scheman eller DTD:er som använder STYLE‑attributet på samma sätt). Förväntningen är att en instans av ElementCSSInlineStyle‑gränssnittet kan erhållas genom att använda bindningsspecifika kastmetoder på en instans av Element‑gränssnittet när elementet stöder inbäddad CSS‑stilinformations. |
| [ILinkStyle](./ilinkstyle/) | LinkStyle‑gränssnittet tillhandahåller en mekanism för att hämta en formatmall från den nod som ansvarar för att länka in den i ett dokument. En instans av LinkStyle‑gränssnittet kan erhållas genom att använda bindningsspecifika kastmetoder på en instans av en länknod (HTMLLinkElement, |
| [IMediaList](./imedialist/) | MediaList‑gränssnittet tillhandahåller abstraktionen av en ordnad samling av media, utan att definiera eller begränsa hur samlingen implementeras. En tom lista är densamma som en lista som innehåller mediet \"all\". |
| [IStyleSheet](./istylesheet/) | StyleSheet‑gränssnittet är det abstrakta basgränssnittet för alla typer av formatmallar. Det representerar en enskild formatmall som är associerad med ett strukturerat dokument. I HTML representerar StyleSheet‑gränssnittet antingen en extern formatmall, inkluderad via HTML‑LINK‑elementet, eller ett inbäddat STYLE‑element. I XML representerar detta gränssnitt en extern formatmall, inkluderad via en formatmall‑processinstruktion. CSS‑formatmallar kommer dessutom att implementera det mer specialiserade [`CSSStyleSheet`](../com.aspose.html.dom.css/icssstylesheet/)‑gränssnittet. |
| [IStyleSheetList](./istylesheetlist/) | StyleSheetList‑gränssnittet representerar en lista med [`CSSStyleSheet`](../com.aspose.html.dom.css/icssstylesheet/)‑objekt. En instans av detta objekt kan returneras av [`Document.styleSheets`](../com.aspose.html.dom/document/stylesheets/). |
| [IViewCSS](./iviewcss/) | IViewCSS‑gränssnittet representerar en utökning av Window‑objektet som ger åtkomst till värdena för alla CSS‑egenskaper hos ett element. |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [CSSEngineMode](./cssenginemode/) | Anger CSSEngine‑läge. Värdena har följande betydelse: |
