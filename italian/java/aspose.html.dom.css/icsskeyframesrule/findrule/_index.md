---
title: "ICSSKeyframesRule.FindRule"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo ICSSKeyframesRule. Il metodo findRule restituisce la regola con una chiave corrispondente alla chiave passata. Se non esiste alcuna regola, viene restituito un valore null."
type: docs

url: /it/java/com.aspose.html.dom.css/icsskeyframesrule/findrule/
---
## ICSSKeyframesRule.FindRule method

Il metodo findRule restituisce la regola con una chiave corrispondente a quella fornita. Se non esiste alcuna regola del genere, viene restituito un valore null.

```java
public ICSSKeyframeRule FindRule(String key)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | String | La chiave che descrive la regola da trovare. La chiave deve risolvere a un numero compreso tra 0 e 1, altrimenti la regola è ignorata. |

### Valore di ritorno

Restituisce l'ultimo [`CSSKeyframeRule`](../../icsskeyframerule/) dichiarato che corrisponde al selettore di keyframe specificato. Se non esiste alcuna regola corrispondente, il metodo non fa nulla.

### Vedi anche

* interface [ICSSKeyframeRule](../../icsskeyframerule/)
* interface [ICSSKeyframesRule](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
