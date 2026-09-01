---
title: "Metered.SetMeteredKey"
second_title: "Aspose.HTML för Java API-referens"
description: "Metered-metoden. Ställer in den mätade offentliga och privata nyckeln. Om du köper en mätt licens när du startar applikationen bör detta API anropas normalt, det räcker. Men om uppladdning av förbrukningsdata alltid misslyckas och överstiger 24 timmar sätts licensen till utvärderingsstatus; för att undvika ett sådant fall bör du regelbundet kontrollera licensstatusen och om den är i utvärderingsstatus anropa detta API igen."
type: docs

url: /sv/java/com.aspose.html/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Ställer in metered offentlig och privat nyckel. Om du köper en metered-licens, bör detta API anropas när applikationen startas; normalt räcker detta. Men om uppladdning av konsumtionsdata alltid misslyckas och överskrider 24 timmar, kommer licensen att sättas till utvärderingsstatus. För att undvika detta bör du regelbundet kontrollera licensstatusen; om den är i utvärderingsstatus, anropa detta API igen.

```java
public void SetMeteredKey(String publicKey, String privateKey)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| publicKey | String | offentlig nyckel |
| privateKey | String | privat nyckel |

### Se även

* class [Metered](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
