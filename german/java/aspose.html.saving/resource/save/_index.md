---
title: "Resource.Save"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Resource-Methode. Speichert die Ressource in den bereitgestellten Stream."
type: docs

url: /de/java/com.aspose.html.saving/resource/save/
---
## Resource.Save method

Speichert die Ressource in den bereitgestellten Stream.

```java
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream, in dem die Ressource gespeichert wird. |
| Kontext | ResourceHandlingContext | Ressourcenverarbeitungskontext. |

### Rückgabewert

Diese Ressource, damit Sie Aufrufe verketten können.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| InvalidOperationException | Ausgelöst, wenn [`OutputUrl`](../outputurl/) `null` ist. [`OutputUrl`](../outputurl/) sollte vor dem Speichern der Ressource angegeben werden, da sonst die korrekte Referenz in den Ressourcen, die diese referenzieren, nicht angegeben werden kann. |

### Siehe auch

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)
