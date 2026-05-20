---
title: "IXPathResult.IterateNext"
second_title: "Aspose.HTML för Java API-referens"
description: "IXPathResult metod. Itererar och returnerar nästa nod från nodmängden eller null om det inte finns fler noder"
type: docs

url: /sv/java/com.aspose.html.dom.xpath/ixpathresult/iteratenext/
---
## IXPathResult.IterateNext method

Itererar och returnerar nästa nod från nodmängden eller `null` om det inte finns fler noder.

```java
public Node IterateNext()
```

### Returvärde

Returnerar nästa nod.

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: uppstår om `resultType` inte är av typen `UnorderedNodeIterator` eller `OrderedNodeIterator`. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_STATE_ERR: Dokumentet har förändrats sedan resultatet returnerades. |

### Se även

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
