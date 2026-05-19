---
title: "ResourceHandler.HandleResourceReference"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo ResourceHandler. Questo metodo è responsabile della gestione del riferimento alla risorsa. In questo metodo è possibile impostare l'aspetto del riferimento alla risorsa gestita."
type: docs

url: /it/java/com.aspose.html.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

Questo metodo è responsabile della gestione del riferimento alla risorsa. In questo metodo, è possibile impostare come apparirà il riferimento alla risorsa gestita.

```java
public String HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| resource | Resource | Il [`Resource`](../../../com.aspose.html.saving/resource/) che verrà gestito. |
| contesto | ResourceHandlingContext | Contesto di gestione delle risorse. |

### Valore di ritorno

Una stringa che verrà scritta nella risorsa padre e che rappresenta un riferimento alla risorsa attualmente gestita.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| InvalidOperationException | Generato se [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) è `null` e [`Status`](../../../com.aspose.html.saving/resource/status/) è Saved. [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) dovrebbe essere specificato per la risorsa salvata perché altrimenti è impossibile specificare il riferimento corretto nelle risorse che fanno riferimento a questa. |

### Vedi anche

* class [Resource](../../../com.aspose.html.saving/resource/)
* class [ResourceHandlingContext](../../../com.aspose.html.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* package [com.aspose.html.saving.ResourceHandlers](../../../com.aspose.html.saving.resourcehandlers/)
* package [Aspose.HTML](../../../)
