---
title: "IStorage‑gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.IStorage‑gränssnitt. Detta gränssnitt i Web Storage API ger åtkomst till en specifik domäns session‑ eller lokala lagring. Se Web Storage‑specifikationen https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage"
type: docs

url: /sv/java/com.aspose.html.dom/istorage/
---
## IStorage interface

Detta gränssnitt i Web Storage‑API:t ger åtkomst till en specifik domäns session‑ eller lokala lagring. Se Web Storage‑specifikationen: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```java
public interface IStorage
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getLength](../../com.aspose.html.dom/istorage/length/) Returnerar antalet nyckel/värde‑par. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [clear](../../com.aspose.html.dom/istorage/clear/)() | Tar bort alla nyckel/värde-par, om det finns några. |
| [getItem](../../com.aspose.html.dom/istorage/getitem/)(String) | Returnerar det aktuella värdet som är associerat med den angivna nyckeln, eller null om den angivna nyckeln inte finns. |
| [key](../../com.aspose.html.dom/istorage/key/)(long) | Returnerar namnet på den n:te nyckeln, eller null om n är större än eller lika med antalet nyckel/värde-par. |
| [removeItem](../../com.aspose.html.dom/istorage/removeitem/)(String) | Tar bort nyckel/värde-paret med den angivna nyckeln, om ett nyckel/värde-par med den angivna nyckeln finns. |
| [setItem](../../com.aspose.html.dom/istorage/setitem/)(String, String) | Sätter värdet för paret identifierat av nyckeln till värdet, och skapar ett nytt nyckel/värde-par om inget tidigare fanns för nyckeln. |

### Se även

* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
