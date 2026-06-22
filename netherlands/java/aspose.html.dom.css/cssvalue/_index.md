---
title: "CSSValue Class"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.css.CSSValue class. Vertegenwoordigt een eenvoudige of een complexe waarde. Een CSSValue‑object komt alleen voor in de context van een CSS‑eigenschap"
type: docs

url: /nl/java/com.aspose.html.dom.css/cssvalue/
---
## CSSValue class

Vertegenwoordigt een eenvoudige of een complexe waarde. Een CSSValue-object komt alleen voor in de context van een CSS‑eigenschap.

```java
public abstract class CSSValue : DOMObject
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | De cssText‑eigenschap van de `CSSValue`‑interface vertegenwoordigt de huidige berekende CSS‑eigenschapwaarde. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) Een code die het type van de waarde definieert. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | Bepaalt of het opgegeven object gelijk is aan deze instantie. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | Retourneert een hashcode voor dit exemplaar. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | Retourneert een String die dit exemplaar vertegenwoordigt. |
| [operator ==](../../com.aspose.html.dom.css/cssvalue/op_equality/) |  |
| [operator !=](../../com.aspose.html.dom.css/cssvalue/op_inequality/) |  |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [CSS_CUSTOM](../../com.aspose.html.dom.css/cssvalue/css_custom/) | De waarde is een aangepaste waarde. |
| const [CSS_INHERIT](../../com.aspose.html.dom.css/cssvalue/css_inherit/) | De waarde is geërfd en de cssText bevat "inherit". |
| const [CSS_PRIMITIVE_VALUE](../../com.aspose.html.dom.css/cssvalue/css_primitive_value/) | De waarde is een primitieve waarde en een instantie van de CSSPrimitiveValue‑interface kan worden verkregen door bindingspecifieke cast‑methoden te gebruiken op deze instantie van de CSSValue‑interface. |
| const [CSS_VALUE_LIST](../../com.aspose.html.dom.css/cssvalue/css_value_list/) | De waarde is een CSSValue-lijst en een instantie van de CSSValueList-interface kan worden verkregen door bindingspecifieke castmethoden te gebruiken op deze instantie van de CSSValue-interface. |

### Zie ook

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
