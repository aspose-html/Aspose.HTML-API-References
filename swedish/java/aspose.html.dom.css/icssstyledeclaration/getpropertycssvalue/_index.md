---
title: "ICSSStyleDeclaration.GetPropertyCSSValue"
second_title: "Aspose.HTML för Java API-referens"
description: "ICSSStyleDeclaration-metoden. Används för att hämta objektrepresentationen av värdet för en CSS-egenskap om den har satts explicit inom detta deklarationsblock. Denna metod returnerar null om egenskapen är en förkortningsegenskap. Värden för förkortningsegenskaper kan endast nås och modifieras som Strängar med hjälp av metoderna getPropertyValue och setProperty."
type: docs

url: /sv/java/com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/
---
## ICSSStyleDeclaration.GetPropertyCSSValue method

Används för att hämta objektrepresentationen av värdet för en CSS‑egenskap om den har satts explicit i detta deklarationsblock. Metoden returnerar null om egenskapen är en förkortningsegenskap. Värden för förkortningsegenskaper kan endast nås och modifieras som strängar via metoderna getPropertyValue och setProperty.

```java
public CSSValue GetPropertyCSSValue(String propertyName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propertyName | String | propertyName är en Sträng som representerar egenskapsnamnet som ska hämtas. |

### Returvärde

value är ett CSSValue som innehåller CSS‑värdet för en egenskap. Om inget finns, returneras null.

### Se även

* class [CSSValue](../../cssvalue/)
* interface [ICSSStyleDeclaration](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
