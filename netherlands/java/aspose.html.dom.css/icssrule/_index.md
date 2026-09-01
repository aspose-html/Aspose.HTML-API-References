---
title: "ICSSRule interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.css.ICSSRule interface. De CSSRule interface is de abstracte basisinterface voor elk type CSS‑statement. Dit omvat zowel regelsets als at‑rules. Van een implementatie wordt verwacht alle regels die in een CSS‑stylesheet zijn gespecificeerd te behouden, zelfs als de regel niet wordt herkend door de parser. Niet‑herkende regels worden weergegeven met behulp van de interface."
type: docs

url: /nl/java/com.aspose.html.dom.css/icssrule/
---
## ICSSRule interface

De CSSRule‑interface is de abstracte basis‑interface voor elk type CSS‑statement. Dit omvat zowel regelsets als at‑rules. Van een implementatie wordt verwacht dat deze alle regels die in een CSS‑stijlblad zijn gespecificeerd behoudt, zelfs als de regel niet wordt herkend door de parser. Niet‑herkende regels worden weergegeven met behulp van de interface.

```java
public interface ICSSRule
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
[getCSSText]
[setCSSText] The cssText property of the `CSSRule` interface returns the actual text of a [`CSSStyleSheet`](../icssstylesheet/) style-rule. |
| [getParentRule](../../com.aspose.html.dom.css/icssrule/parentrule/) Als deze regel zich binnen een andere regel bevindt (bijv. een stijlregel binnen een @media‑blok), is dit de omvattende regel. Als deze regel niet genest is binnen andere regels, retourneert dit null. |
| [getParentStyleSheet](../../com.aspose.html.dom.css/icssrule/parentstylesheet/) De parentStyleSheet‑eigenschap van de `CSSRule` interface retourneert het [`StyleSheet`](../istylesheet/) object waarin de huidige regel is gedefinieerd. |
| [getType](../../com.aspose.html.dom.css/icssrule/type/) Het type van de regel, zoals gedefinieerd in [CSSOM # dom-cssrule-type](https://drafts.csswg.org/cssom/#dom-cssrule-type). Er wordt verwacht dat bindings‑specifieke cast‑methoden kunnen worden gebruikt om van een instantie van de CSSRule interface naar de specifieke afgeleide interface te casten die door het type wordt geïmpliceerd. |

### Zie ook

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
