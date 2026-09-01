---
title: "Resource.Embed"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo Resource. Incorpora questa risorsa nel suo genitore codificandola in Base64. Il risultato della codifica sarà scritto in OutputUrl"
type: docs

url: /it/java/com.aspose.html.saving/resource/embed/
---
## Resource.Embed method

Incorpora questa risorsa nel suo genitore codificandola in Base64. Il risultato della codifica sarà scritto in [`OutputUrl`](../outputurl/).

```java
public Resource Embed(ResourceHandlingContext context)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contesto | ResourceHandlingContext | Contesto di gestione delle risorse. |

### Valore di ritorno

Questa risorsa per consentire la concatenazione delle chiamate.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| InvalidOperationException | Generato se non esiste [`ParentResource`](../../resourcehandlingcontext/parentresource/) perché non c'è alcun luogo dove incorporare il risultato. |

### Vedi anche

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)
