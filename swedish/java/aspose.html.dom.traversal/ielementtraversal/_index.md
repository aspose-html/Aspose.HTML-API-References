---
title: "IElementTraversal-gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.traversal.IElementTraversal interface. ElementTraversal‑gränssnittet är en uppsättning skrivskyddade attribut som låter en författare enkelt navigera mellan element i ett dokument. I konforme implementationer av Element Traversal måste alla objekt som implementerar Element också implementera ElementTraversal‑gränssnittet."
type: docs

url: /sv/java/com.aspose.html.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

ElementTraversal‑gränssnittet är en uppsättning skrivskyddade attribut som låter en författare enkelt navigera mellan element i ett dokument. I konforme implementationer av Element Traversal måste alla objekt som implementerar Element också implementera ElementTraversal‑gränssnittet.

```java
public interface IElementTraversal
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getChildElementCount](../../com.aspose.html.dom.traversal/ielementtraversal/childelementcount/) Returnerar det aktuella antalet elementnoder som är barn till detta element. 0 om detta element inte har några barnnoder av nodeType 1. |
| [getFirstElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/firstelementchild/) Returnerar den första barn‑elementnoden för detta element. null om detta element inte har några barn‑element. |
| [getLastElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/lastelementchild/) Returnerar den sista barn‑elementnoden för detta element. null om detta element inte har några barn‑element. |
| [getNextElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/nextelementsibling/) Returnerar nästa syskon‑elementnod till detta element. null om detta element inte har några element‑syskonnoder som kommer efter detta i dokumentträdet. |
| [getPreviousElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/previouselementsibling/) Returnerar föregående syskon‑elementnod till detta element. null om detta element inte har några element‑syskonnoder som kommer före detta i dokumentträdet. |

### Se även

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
