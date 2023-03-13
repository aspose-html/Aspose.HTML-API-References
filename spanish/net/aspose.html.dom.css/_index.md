---
title: Aspose.Html.Dom.Css
second_title: Referencia de API de Aspose.HTML para .NET
description: El Aspose.Html.Dom.Css El espacio de nombres es para todas las manipulaciones relacionadas con CSS. Se concentra en el nombre de la propiedad CSS  pares de valores especificados por los documentos oficiales de CSS.
type: docs
weight: 70
url: /es/net/aspose.html.dom.css/
---
El **Aspose.Html.Dom.Css** El espacio de nombres es para todas las manipulaciones relacionadas con CSS. Se concentra en el nombre de la propiedad CSS - pares de valores especificados por los documentos oficiales de CSS.

## Clases

| Clase | Descripción |
| --- | --- |
| [Counter](./counter/) | La interfaz de contador se utiliza para representar cualquier valor de función de contador o contadores. Esta interfaz refleja los valores en la propiedad de estilo subyacente. |
| [CSSPrimitiveValue](./cssprimitivevalue/) | La interfaz CSSPrimitiveValue representa un único valor CSS. Esta interfaz se puede usar para determinar el valor de una propiedad de estilo específica establecida actualmente en un bloque o para establecer una propiedad de estilo específica explícitamente dentro del bloque. Se puede obtener una instancia de esta interfaz del método getPropertyCSSValue de la interfaz CSSStyleDeclaration. Un objeto CSSPrimitiveValue solo ocurre en un contexto de una propiedad CSS. |
| [CSSValue](./cssvalue/) | Representa un valor simple o complejo. Un objeto CSSValue solo ocurre en un contexto de una propiedad CSS. |
| [CSSValueList](./cssvaluelist/) | La interfaz CSSValueList proporciona la abstracción de una colección ordenada de valores CSS. |
| [Rect](./rect/) | La interfaz Rect se utiliza para representar cualquier valor rect. Esta interfaz refleja los valores en la propiedad de estilo subyacente. Por lo tanto, las modificaciones realizadas a los objetos CSSPrimitiveValue modifican la propiedad de estilo. |
| [RGBColor](./rgbcolor/) | La interfaz RGBColor se utiliza para representar cualquier valor de color RGB. Esta interfaz refleja los valores en la propiedad de estilo subyacente. Por lo tanto, las modificaciones realizadas a los objetos CSSPrimitiveValue modifican la propiedad de estilo. |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [ICSS2Properties](./icss2properties/) | Proporciona una interfaz para la manipulación de valores establecidos de propiedades CSS2 en el contexto de cierto elemento HTML |
| [ICSSCharsetRule](./icsscharsetrule/) | La interfaz CSSCharsetRule representa una regla @charset en una hoja de estilo CSS. El valor del atributo de codificación no afecta la codificación de datos de texto en los objetos DOM; esta codificación es siempre UTF-16. Después de cargar una hoja de estilo, el valor del atributo de codificación es el valor que se encuentra en la regla @charset. Si no había @charset en el documento original, no se crea CSSCharsetRule. El valor del atributo de codificación también se puede utilizar como sugerencia para la codificación utilizada en la serialización de la hoja de estilo. |
| [ICSSCounterStyleRule](./icsscounterstylerule/) | La regla @counter-style permite a los autores definir un estilo de contador personalizado. |
| [ICSSFontFaceRule](./icssfontfacerule/) | La interfaz CSSFontFaceRule representa una regla @font-face en una hoja de estilo CSS. La regla @font-face se utiliza para contener un conjunto de descripciones de fuentes. |
| [ICSSImportRule](./icssimportrule/) | La interfaz CSSImportRule representa una regla @import dentro de una hoja de estilo CSS. La regla @import se utiliza para importar reglas de estilo de otras hojas de estilo. |
| [ICSSKeyframeRule](./icsskeyframerule/) | La interfaz CSSKeyframeRule representa la regla de estilo para una sola clave. |
| [ICSSKeyframesRule](./icsskeyframesrule/) | La interfaz CSSKeyframesRule representa un conjunto completo de fotogramas clave para una única animación |
| [ICSSMarginRule](./icssmarginrule/) | La interfaz CSSMarginRule representa una regla en el margen. |
| [ICSSMediaRule](./icssmediarule/) | La interfaz CSSMediaRule representa una regla @media en una hoja de estilo CSS. Se puede usar una regla @media para delimitar reglas de estilo para tipos de medios específicos. |
| [ICSSPageRule](./icsspagerule/) | La interfaz CSSPageRule representa una regla @page dentro de una hoja de estilo CSS. La regla @page se usa para especificar las dimensiones, la orientación, los márgenes, etc. de un cuadro de página para medios paginados. |
| [ICSSRule](./icssrule/) | La interfaz CSSRule es la interfaz base abstracta para cualquier tipo de declaración CSS. Esto incluye conjuntos de reglas y reglas at. Se espera que una implementación conserve todas las reglas especificadas en una hoja de estilo CSS, incluso si el analizador no reconoce la regla. Las reglas no reconocidas se representan mediante el!:ICSSUnknownRule interfaz. |
| [ICSSRuleList](./icssrulelist/) | La interfaz CSSRuleList proporciona la abstracción de una colección ordenada de reglas CSS. |
| [ICSSStyleDeclaration](./icssstyledeclaration/) | La interfaz CSSStyleDeclaration representa un solo bloque de declaración CSS. Esta interfaz se puede usar para determinar las propiedades de estilo establecidas actualmente en un bloque o para establecer las propiedades de estilo explícitamente dentro del bloque. |
| [ICSSStyleRule](./icssstylerule/) | La interfaz CSSStyleRule representa un único conjunto de reglas en una hoja de estilo CSS. |
| [ICSSStyleSheet](./icssstylesheet/) | La interfaz CSSStyleSheet es una interfaz concreta que se utiliza para representar una hoja de estilo CSS, es decir, una hoja de estilo cuyo tipo de contenido es "texto/css". |
| [ICSSUnknownRule](./icssunknownrule/) | La interfaz CSSUnknownRule representa una regla at no admitida por este agente de usuario. |
| [ICSSValueList](./icssvaluelist/) | La interfaz proporciona la abstracción de una colección ordenada de valores CSS. |
| [IDocumentCSS](./idocumentcss/) | Esta interfaz representa un documento con una vista CSS. |
| [IDocumentStyle](./idocumentstyle/) | La interfaz DocumentStyle proporciona un mecanismo mediante el cual se pueden recuperar las hojas de estilo incrustadas en un documento. La expectativa es que se pueda obtener una instancia de la interfaz DocumentStyle mediante el uso de métodos de conversión específicos de enlace en una instancia de la interfaz Document. |
| [IElementCSSInlineStyle](./ielementcssinlinestyle/) | La información de estilo en línea adjunta a los elementos se expone a través del atributo de estilo. Esto representa el contenido del atributo ESTILO para elementos HTML (o elementos en otros esquemas o DTD que usan el atributo ESTILO de la misma manera). |
| [ILinkStyle](./ilinkstyle/) | La interfaz LinkStyle proporciona un mecanismo mediante el cual se puede recuperar una hoja de estilo del nodo responsable de vincularla a un documento. Se puede obtener una instancia de la interfaz LinkStyle utilizando métodos de conversión específicos de enlace en una instancia de un nodo de enlace (HTMLLinkElement, HTMLStyleElement o ProcessingInstruction en DOM Nivel 2). |
| [IMediaList](./imedialist/) | La interfaz MediaList proporciona la abstracción de una colección ordenada de medios, sin definir ni restringir cómo se implementa esta colección. Una lista vacía es lo mismo que una lista que contiene el medio "todos". |
| [IStyleSheet](./istylesheet/) | La interfaz StyleSheet es la interfaz base abstracta para cualquier tipo de hoja de estilo. Representa una sola hoja de estilo asociada a un documento estructurado. |
| [IStyleSheetList](./istylesheetlist/) | La interfaz StyleSheetList proporciona la abstracción de una colección ordenada de hojas de estilo. |
| [IViewCSS](./iviewcss/) | Esta interfaz representa una vista CSS. |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [CSSEngineMode](./cssenginemode/) | Especifica el modo CSSEngine |


