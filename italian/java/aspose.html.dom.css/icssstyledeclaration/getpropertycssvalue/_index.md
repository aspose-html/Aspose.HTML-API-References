---
title: "ICSSStyleDeclaration.GetPropertyCSSValue"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo ICSSStyleDeclaration. Utilizzato per recuperare la rappresentazione oggetto del valore di una proprietà CSS se è stata impostata esplicitamente all'interno di questo blocco di dichiarazione. Questo metodo restituisce null se la proprietà è una proprietà abbreviata. I valori delle proprietà abbreviate possono essere accessibili e modificati solo come stringhe usando i metodi getPropertyValue e setProperty."
type: docs

url: /it/java/com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/
---
## ICSSStyleDeclaration.GetPropertyCSSValue method

Utilizzato per recuperare la rappresentazione oggetto del valore di una proprietà CSS se è stata impostata esplicitamente all'interno di questo blocco di dichiarazione. Questo metodo restituisce null se la proprietà è una proprietà abbreviata. I valori delle proprietà abbreviate possono essere accessi e modificati solo come stringhe, utilizzando i metodi getPropertyValue e setProperty.

```java
public CSSValue GetPropertyCSSValue(String propertyName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| propertyName | String | propertyName è una String che rappresenta il nome della proprietà da recuperare. |

### Valore di ritorno

value è un CSSValue che contiene il valore CSS per una proprietà. Se non esiste, restituisce null.

### Vedi anche

* class [CSSValue](../../cssvalue/)
* interface [ICSSStyleDeclaration](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
