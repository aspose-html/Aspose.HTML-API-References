---
title: "ICSSStyleSheet.InsertRule"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo ICSSStyleSheet. Il metodo CSSStyleSheet.insertRule inserisce una nuova regola CSS nel foglio di stile corrente con alcune restrizioni"
type: docs

url: /it/java/com.aspose.html.dom.css/icssstylesheet/insertrule/
---
## ICSSStyleSheet.InsertRule method

Il metodo CSSStyleSheet.insertRule() inserisce una nuova regola CSS nel foglio di stile corrente, con alcune restrizioni.

Nota: Sebbene insertRule() sia esclusivamente un metodo di [`CSSStyleSheet`](../), in realtà inserisce la regola in CSSStyleSheet.cssRules — la sua [`CSSRuleList`](../../icssrulelist/) interna.

```java
public long InsertRule(String rule, int index)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| regola | String | Una stringa contenente la regola da inserire. Ciò che la regola inserita deve contenere dipende dal suo tipo: |
| index | Int32 | Un intero positivo minore o uguale a stylesheet.cssRules.length, che rappresenta la posizione della regola appena inserita in CSSStyleSheet.cssRules. Il valore predefinito è 0. |

### Valore di ritorno

L'indice della regola appena inserita nell'elenco delle regole del foglio di stile.

## Osservazioni

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Riferimento

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-cssstylesheet-insertrule](https://drafts.csswg.org/cssom/#dom-cssstylesheet-insertrule) – The CSSOM definition.

### Vedi anche

* interface [ICSSStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
