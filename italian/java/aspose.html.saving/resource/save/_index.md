---
title: "Resource.Save"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo Resource. Salva la risorsa nello stream fornito."
type: docs

url: /it/java/com.aspose.html.saving/resource/save/
---
## Resource.Save method

Salva la risorsa nello stream fornito.

```java
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | Stream | Lo stream in cui la risorsa verrà salvata. |
| contesto | ResourceHandlingContext | Contesto di gestione delle risorse. |

### Valore di ritorno

Questa risorsa consente di concatenare le chiamate.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| InvalidOperationException | Generato se [`OutputUrl`](../outputurl/) è `null`. [`OutputUrl`](../outputurl/) dovrebbe essere specificato prima di salvare la risorsa perché altrimenti è impossibile specificare il riferimento corretto nelle risorse che fanno riferimento a questa. |

### Vedi anche

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)
