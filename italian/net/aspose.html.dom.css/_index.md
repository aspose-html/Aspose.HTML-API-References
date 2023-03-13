---
title: Aspose.Html.Dom.Css
second_title: Aspose.HTML per riferimento API .NET
description: Il Aspose.Html.Dom.Css namespace è per tutte le manipolazioni relative ai CSS. Si concentra sul nome della proprietà CSS  coppie di valori specificate dai documenti ufficiali CSS.
type: docs
weight: 70
url: /it/net/aspose.html.dom.css/
---
Il **Aspose.Html.Dom.Css** namespace è per tutte le manipolazioni relative ai CSS. Si concentra sul nome della proprietà CSS - coppie di valori specificate dai documenti ufficiali CSS.

## Classi

| Classe | Descrizione |
| --- | --- |
| [Counter](./counter/) | L'interfaccia Counter viene utilizzata per rappresentare qualsiasi contatore o valore di funzione contatori. Questa interfaccia riflette i valori nella proprietà di stile sottostante. |
| [CSSPrimitiveValue](./cssprimitivevalue/) | L'interfaccia CSSPrimitiveValue rappresenta un singolo valore CSS. Questa interfaccia può essere utilizzata per determinare il valore di una proprietà di stile specifica attualmente impostata in un blocco o per impostare una proprietà di stile specifica in modo esplicito all'interno del blocco. Un'istanza di questa interfaccia potrebbe essere ottenuta dal metodo getPropertyCSSValue dell'interfaccia CSSStyleDeclaration. Un oggetto CSSPrimitiveValue si verifica solo in un contesto di una proprietà CSS. |
| [CSSValue](./cssvalue/) | Rappresenta un valore semplice o complesso. Un oggetto CSSValue si verifica solo in un contesto di una proprietà CSS. |
| [CSSValueList](./cssvaluelist/) | L'interfaccia CSSValueList fornisce l'astrazione di una raccolta ordinata di valori CSS. |
| [Rect](./rect/) | L'interfaccia Rect viene utilizzata per rappresentare qualsiasi valore rect. Questa interfaccia riflette i valori nella proprietà di stile sottostante. Pertanto, le modifiche apportate agli oggetti CSSPrimitiveValue modificano la proprietà style. |
| [RGBColor](./rgbcolor/) | L'interfaccia RGBColor viene utilizzata per rappresentare qualsiasi valore di colore RGB. Questa interfaccia riflette i valori nella proprietà di stile sottostante. Pertanto, le modifiche apportate agli oggetti CSSPrimitiveValue modificano la proprietà style. |
## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [ICSS2Properties](./icss2properties/) | Fornisce un'interfaccia per la manipolazione dei valori impostati delle proprietà CSS2 nel contesto di determinati elementi HTML |
| [ICSSCharsetRule](./icsscharsetrule/) | L'interfaccia CSSCharsetRule rappresenta una regola @charset in un foglio di stile CSS. Il valore dell'attributo encoding non influisce sulla codifica dei dati di testo negli oggetti DOM; questa codifica è sempre UTF-16. Dopo che un foglio di stile è stato caricato, il valore dell'attributo encoding è il valore trovato nella regola @charset. Se non c'era @charset nel documento originale, non viene creata alcuna CSSCharsetRule. Il valore dell'attributo encoding può essere utilizzato anche come suggerimento per la codifica utilizzata nella serializzazione del foglio di stile. |
| [ICSSCounterStyleRule](./icsscounterstylerule/) | La regola @counter-style consente agli autori di definire uno stile contatore personalizzato. |
| [ICSSFontFaceRule](./icssfontfacerule/) | L'interfaccia CSSFontFaceRule rappresenta una regola @font-face in un foglio di stile CSS. La regola @font-face viene utilizzata per contenere una serie di descrizioni dei caratteri. |
| [ICSSImportRule](./icssimportrule/) | L'interfaccia CSSImportRule rappresenta una regola @import all'interno di un foglio di stile CSS. La regola @import viene utilizzata per importare regole di stile da altri fogli di stile. |
| [ICSSKeyframeRule](./icsskeyframerule/) | L'interfaccia CSSKeyframeRule rappresenta la regola di stile per una singola chiave. |
| [ICSSKeyframesRule](./icsskeyframesrule/) | L'interfaccia CSSKeyframesRule rappresenta un set completo di fotogrammi chiave per una singola animazione |
| [ICSSMarginRule](./icssmarginrule/) | L'interfaccia CSSMarginRule rappresenta una regola di margine. |
| [ICSSMediaRule](./icssmediarule/) | L'interfaccia CSSMediaRule rappresenta una regola @media in un foglio di stile CSS. Una regola @media può essere utilizzata per delimitare le regole di stile per tipi di media specifici. |
| [ICSSPageRule](./icsspagerule/) | L'interfaccia CSSPageRule rappresenta una regola @page all'interno di un foglio di stile CSS. La regola @page viene utilizzata per specificare le dimensioni, l'orientamento, i margini, ecc. di una dimensione di pagina per i media impaginati. |
| [ICSSRule](./icssrule/) | L'interfaccia CSSRule è l'interfaccia di base astratta per qualsiasi tipo di istruzione CSS. Ciò include sia i set di regole che le at-rule. Ci si aspetta che un'implementazione conservi tutte le regole specificate in un foglio di stile CSS, anche se la regola non è riconosciuta dal parser. Le regole non riconosciute sono rappresentate utilizzando il!:ICSSUnknownRule interfaccia. |
| [ICSSRuleList](./icssrulelist/) | L'interfaccia CSSRuleList fornisce l'astrazione di una raccolta ordinata di regole CSS. |
| [ICSSStyleDeclaration](./icssstyledeclaration/) | L'interfaccia CSSStyleDeclaration rappresenta un singolo blocco di dichiarazione CSS. Questa interfaccia può essere utilizzata per determinare le proprietà di stile attualmente impostate in un blocco o per impostare le proprietà di stile in modo esplicito all'interno del blocco. |
| [ICSSStyleRule](./icssstylerule/) | L'interfaccia CSSStyleRule rappresenta un singolo set di regole in un foglio di stile CSS. |
| [ICSSStyleSheet](./icssstylesheet/) | L'interfaccia CSSStyleSheet è un'interfaccia concreta usata per rappresentare un foglio di stile CSS, cioè un foglio di stile il cui tipo di contenuto è "text/css". |
| [ICSSUnknownRule](./icssunknownrule/) | L'interfaccia CSSUnknownRule rappresenta una regola non supportata da questo agente utente. |
| [ICSSValueList](./icssvaluelist/) | L'interfaccia fornisce l'astrazione di una raccolta ordinata di valori CSS. |
| [IDocumentCSS](./idocumentcss/) | Questa interfaccia rappresenta un documento con una vista CSS. |
| [IDocumentStyle](./idocumentstyle/) | L'interfaccia DocumentStyle fornisce un meccanismo mediante il quale è possibile recuperare i fogli di stile incorporati in un documento. L'aspettativa è che un'istanza dell'interfaccia DocumentStyle possa essere ottenuta utilizzando metodi di casting specifici dell'associazione su un'istanza dell'interfaccia Document. |
| [IElementCSSInlineStyle](./ielementcssinlinestyle/) | Le informazioni sullo stile in linea associate agli elementi vengono esposte tramite l'attributo style. Rappresenta il contenuto dell'attributo STYLE per gli elementi HTML (o elementi in altri schemi o DTD che utilizzano l'attributo STYLE allo stesso modo). |
| [ILinkStyle](./ilinkstyle/) | L'interfaccia LinkStyle fornisce un meccanismo mediante il quale un foglio di stile può essere recuperato dal nodo responsabile del collegamento in un documento. È possibile ottenere un'istanza dell'interfaccia LinkStyle utilizzando metodi di cast specifici dell'associazione su un'istanza di un nodo di collegamento (HTMLLinkElement, HTMLStyleElement o ProcessingInstruction in DOM Level 2). |
| [IMediaList](./imedialist/) | L'interfaccia MediaList fornisce l'astrazione di una raccolta ordinata di media, senza definire o limitare il modo in cui questa raccolta viene implementata. Una lista vuota è uguale a una lista che contiene il mezzo "all". |
| [IStyleSheet](./istylesheet/) | L'interfaccia StyleSheet è l'interfaccia di base astratta per qualsiasi tipo di foglio di stile. Rappresenta un singolo foglio di stile associato a un documento strutturato. |
| [IStyleSheetList](./istylesheetlist/) | L'interfaccia StyleSheetList fornisce l'astrazione di una raccolta ordinata di fogli di stile. |
| [IViewCSS](./iviewcss/) | Questa interfaccia rappresenta una vista CSS. |
## Enumerazione

| Enumerazione | Descrizione |
| --- | --- |
| [CSSEngineMode](./cssenginemode/) | Specifica la modalità CSSEngine |


