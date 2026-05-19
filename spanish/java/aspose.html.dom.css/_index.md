---
title: "com.aspose.html.dom.css"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Proporciona interfaces para la especificación de estilo DOM Nivel 2. Cascading Style Sheets CSS es un lenguaje de hojas de estilo que permite a autores y usuarios adjuntar estilos, por ejemplo fuentes y espaciado, a documentos estructurados, por ejemplo documentos HTML y aplicaciones XML. Soporta hojas de estilo específicas para medios, de modo que los autores puedan adaptar la presentación de sus documentos a navegadores visuales, dispositivos auditivos, impresoras, dispositivos braille, dispositivos portátiles, etc. También soporta posicionamiento de contenido, características de diseño de tablas para internacionalización y algunas propiedades relacionadas con la interfaz de usuario. Al separar el estilo de presentación de los documentos del contenido de los documentos, CSS simplifica la autoría web y el mantenimiento del sitio."
type: docs

url: /es/java/com.aspose.html.dom.css/
---
Proporciona interfaces para la especificación de estilo DOM Nivel 2. Las Hojas de Estilo en Cascada (CSS) son un lenguaje de hojas de estilo que permite a autores y usuarios aplicar estilos (p. ej., fuentes y espaciado) a documentos estructurados (p. ej., documentos HTML y aplicaciones XML). Soporta hojas de estilo específicas para medios, de modo que los autores puedan adaptar la presentación de sus documentos a navegadores visuales, dispositivos auditivos, impresoras, dispositivos braille, dispositivos portátiles, etc. También soporta posicionamiento de contenido, diseño de tablas, características para la internacionalización y algunas propiedades relacionadas con la interfaz de usuario. Al separar el estilo de presentación de los documentos de su contenido, CSS simplifica la creación de sitios web y su mantenimiento.

## Clases

| Clase | Descripción |
| --- | --- |
| [Counter](./counter/) | La interfaz Counter se utiliza para representar cualquier valor de contador o de la función counters. Esta interfaz refleja los valores en la propiedad de estilo subyacente. |
| [CSSPrimitiveValue](./cssprimitivevalue/) | La interfaz CSSPrimitiveValue deriva de la interfaz CSSValue y representa el valor calculado actual de una propiedad CSS. |
| [CSSValue](./cssvalue/) | Representa un valor simple o complejo. Un objeto CSSValue solo aparece en el contexto de una propiedad CSS. |
| [CSSValueList](./cssvaluelist/) | La interfaz CSSValueList proporciona la abstracción de una colección ordenada de valores CSS. |
| [Rect](./rect/) | La interfaz Rect se utiliza para representar cualquier valor rect. Esta interfaz refleja los valores en la propiedad de estilo subyacente. Por lo tanto, las modificaciones realizadas a los objetos [`CSSPrimitiveValue`](../com.aspose.html.dom.css/cssprimitivevalue/) modifican la propiedad de estilo. |
| [RGBColor](./rgbcolor/) | La interfaz RGBColor se utiliza para representar cualquier valor de color RGB. Esta interfaz refleja los valores en la propiedad de estilo subyacente. Por lo tanto, las modificaciones realizadas a los objetos CSSPrimitiveValue modifican la propiedad de estilo. |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [ICSS2Properties](./icss2properties/) | La interfaz CSS2Properties representa un mecanismo de conveniencia para obtener y establecer propiedades dentro de una [`CSSStyleDeclaration`](../com.aspose.html.dom.css/icssstyledeclaration/). Los atributos de esta interfaz corresponden a todas las propiedades especificadas en CSS2. Obtener un atributo de esta interfaz es equivalente a llamar al método getPropertyValue de la interfaz [`CSSStyleDeclaration`](../com.aspose.html.dom.css/icssstyledeclaration/). Establecer un atributo de esta interfaz es equivalente a llamar al método setProperty de la interfaz [`CSSStyleDeclaration`](../com.aspose.html.dom.css/icssstyledeclaration/). |
| [ICSSCharsetRule](./icsscharsetrule/) | La interfaz CSSCharsetRule representa una regla @charset en una hoja de estilo CSS. El valor del atributo encoding no afecta la codificación de los datos de texto en los objetos DOM; esta codificación es siempre UTF-16. Después de cargar una hoja de estilo, el valor del atributo encoding es el valor encontrado en la regla @charset. Si no había @charset en el documento original, entonces no se crea ningún CSSCharsetRule. El valor del atributo encoding también puede usarse como pista para la codificación utilizada al serializar la hoja de estilo. |
| [ICSSCounterStyleRule](./icsscounterstylerule/) | La interfaz CSSCounterStyleRule representa una regla at-rule @counter-style que permite a los autores definir un estilo de contador personalizado. |
| [ICSSFontFaceRule](./icssfontfacerule/) | La interfaz CSSFontFaceRule representa una regla @font-face en una hoja de estilo CSS. La regla @font-face se utiliza para contener un conjunto de descripciones de fuentes. |
| [ICSSImportRule](./icssimportrule/) | La interfaz CSSImportRule representa una regla @import dentro de una hoja de estilo CSS. La regla @import se utiliza para importar reglas de estilo de otras hojas de estilo. |
| [ICSSKeyframeRule](./icsskeyframerule/) | La interfaz [`CSSKeyframeRule`](../com.aspose.html.dom.css/icsskeyframerule/) describe un objeto que representa un conjunto de estilos para un fotograma clave dado. Corresponde al contenido de un único fotograma clave de una regla at-rule @keyframes. |
| [ICSSKeyframesRule](./icsskeyframesrule/) | La propiedad name de la interfaz CSSKeyframeRule obtiene y establece el nombre de la animación utilizado por la propiedad animation-name. |
| [ICSSMarginRule](./icssmarginrule/) | La interfaz CSSMarginRule representa una regla at-rule de margen (p. ej., @top-left) en una regla at-rule @page. |
| [ICSSMediaRule](./icssmediarule/) | La interfaz CSSMediaRule representa una regla @media en una hoja de estilo CSS. Una regla @media puede usarse para delimitar reglas de estilo para tipos de medios específicos. |
| [ICSSPageRule](./icsspagerule/) | La interfaz CSSPageRule representa una regla @page dentro de una hoja de estilo CSS. La regla @page se utiliza para especificar las dimensiones, orientación, márgenes, etc., de una caja de página para medios paginados. |
| [ICSSRule](./icssrule/) | La interfaz CSSRule es la interfaz base abstracta para cualquier tipo de declaración CSS. Esto incluye tanto conjuntos de reglas como at-rules. Se espera que una implementación preserve todas las reglas especificadas en una hoja de estilo CSS, incluso si la regla no es reconocida por el analizador. Las reglas no reconocidas se representan mediante la interfaz. |
| [ICSSRuleList](./icssrulelist/) | Una CSSRuleList representa una colección ordenada de objetos [`CSSRule`](../com.aspose.html.dom.css/icssrule/) de solo lectura. |
| [ICSSStyleDeclaration](./icssstyledeclaration/) | La interfaz CSSStyleDeclaration representa un objeto que es un bloque de declaración CSS, y expone información de estilo y varios métodos y propiedades relacionados con el estilo. |
| [ICSSStyleRule](./icssstylerule/) | La interfaz CSSStyleRule representa una única regla de estilo CSS. El atributo selectorText, al obtenerse, debe devolver el resultado de serializar el grupo de selectores asociado. |
| [ICSSStyleSheet](./icssstylesheet/) | La interfaz CSSStyleSheet representa una única hoja de estilos CSS, y le permite inspeccionar y modificar la lista de reglas contenidas en la hoja de estilos. Hereda propiedades y métodos de su padre, [`IStyleSheet`](../com.aspose.html.dom.css/istylesheet/). |
| [ICSSUnknownRule](./icssunknownrule/) | La interfaz CSSUnknownRule representa una regla at-rule no soportada por este agente de usuario. |
| [ICSSValueList](./icssvaluelist/) | La interfaz CSSValueList deriva de la interfaz [`CSSValue`](../com.aspose.html.dom.css/cssvalue/) y proporciona la abstracción de una colección ordenada de valores CSS. |
| [IDocumentCSS](./idocumentcss/) | Esta interfaz representa un documento con una vista CSS. |
| [IDocumentStyle](./idocumentstyle/) | La interfaz DocumentStyle proporciona un mecanismo mediante el cual se pueden obtener las hojas de estilo incrustadas en un documento. Se espera que una instancia de la interfaz DocumentStyle pueda obtenerse utilizando métodos de casting específicos del enlace en una instancia de la interfaz Document. |
| [IElementCSSInlineStyle](./ielementcssinlinestyle/) | La información de estilo en línea adjunta a los elementos se expone a través del atributo style. Esto representa el contenido del atributo STYLE para elementos HTML (o elementos en otros esquemas o DTD que usan el atributo STYLE de la misma manera). Se espera que una instancia de la interfaz ElementCSSInlineStyle pueda obtenerse utilizando métodos de casting específicos del enlace en una instancia de la interfaz Element cuando el elemento soporta información de estilo CSS en línea. |
| [ILinkStyle](./ilinkstyle/) | La interfaz LinkStyle proporciona un mecanismo mediante el cual una hoja de estilo puede obtenerse del nodo responsable de enlazarla en un documento. Una instancia de la interfaz LinkStyle puede obtenerse utilizando métodos de casting específicos del enlace en una instancia de un nodo de enlace (HTMLLinkElement, |
| [IMediaList](./imedialist/) | La interfaz MediaList proporciona la abstracción de una colección ordenada de medios, sin definir ni restringir cómo se implementa esta colección. Una lista vacía es lo mismo que una lista que contiene el medio "all". |
| [IStyleSheet](./istylesheet/) | La interfaz StyleSheet es la interfaz base abstracta para cualquier tipo de hoja de estilo. Representa una única hoja de estilo asociada a un documento estructurado. En HTML, la interfaz StyleSheet representa ya sea una hoja de estilo externa, incluida mediante el elemento HTML LINK, o un elemento STYLE en línea. En XML, esta interfaz representa una hoja de estilo externa, incluida mediante una instrucción de procesamiento de hoja de estilo. Las hojas de estilo CSS implementarán además la interfaz más especializada [`CSSStyleSheet`](../com.aspose.html.dom.css/icssstylesheet/). |
| [IStyleSheetList](./istylesheetlist/) | La interfaz StyleSheetList representa una lista de objetos [`CSSStyleSheet`](../com.aspose.html.dom.css/icssstylesheet/). Una instancia de este objeto puede devolverse mediante [`Document.styleSheets`](../com.aspose.html.dom/document/stylesheets/). |
| [IViewCSS](./iviewcss/) | La interfaz IViewCSS representa una extensión del objeto Window que brinda acceso a los valores de todas las propiedades CSS de un elemento. |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [CSSEngineMode](./cssenginemode/) | Especifica el modo CSSEngine. Los valores tienen el siguiente significado: |
