---
title: "ICSSRule.ParentRule"
second_title: "Справочник API Aspose.HTML для Java"
description: "Свойство ICSSRule. Если это правило находится внутри другого правила, например правила стиля внутри медиа‑блока, это правило‑контейнер. Если это правило не вложено ни в одно другое правило, возвращается null"
type: docs

url: /ru/java/com.aspose.html.dom.css/icssrule/parentrule/
---
## ICSSRule.ParentRule property

Если это правило находится внутри другого правила (например, правила стиля внутри блока @media), это правило‑контейнер. Если это правило не вложено ни в одно другое правило, возвращается null.

```java
public ICSSRule ParentRule { get; }
```

### Property Value

Объект [`CSSRule`](../), представляющий тип содержащих правил. Если текущее правило находится внутри медиазапроса, будет возвращён [`CSSMediaRule`](../../icssmediarule/). В противном случае возвращается null.

### См. также

* interface [ICSSRule](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
