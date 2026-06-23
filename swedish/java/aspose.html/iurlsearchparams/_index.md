---
title: "IUrlSearchParams gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.IUrlSearchParams gränssnitt. Tillhandahåller metoder för att arbeta med URL:ers frågesträng"
type: docs

url: /sv/java/com.aspose.html/iurlsearchparams/
---
## IUrlSearchParams interface

Tillhandahåller metoder för att arbeta med URL‑frågesträngar.

```java
public interface IUrlSearchParams : IEnumerable<String[]>
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [append](../../com.aspose.html/iurlsearchparams/append/)(String, String) | Lägger till ett nytt namn‑värde‑par vars namn är `name` och värde är `value`. |
| [delete](../../com.aspose.html/iurlsearchparams/delete/)(String) | Tar bort alla namn‑värde‑par vars namn är `name`. |
| [get](../../com.aspose.html/iurlsearchparams/get/)(String) | Returnerar värdet för det första namn‑värde‑paret vars namn är `name`. |
| [getAll](../../com.aspose.html/iurlsearchparams/getall/)(String) | Returnerar alla värden vars namn är `name`. |
| [has](../../com.aspose.html/iurlsearchparams/has/)(String) | Kontrollerar om det finns ett namn‑värde‑par vars namn är `name` i listan. |
| [set](../../com.aspose.html/iurlsearchparams/set/)(String, String) | Sätter värdet för det först hittade namn‑värde‑paret till det angivna värdet och tar bort de övriga. Om inga namn‑värde‑par med det angivna namnet hittas, läggs ett nytt till i listan. |
| [sort](../../com.aspose.html/iurlsearchparams/sort/)() | Sorterar alla namn‑värde‑par, om några finns, efter deras namn. |

### Se även

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
