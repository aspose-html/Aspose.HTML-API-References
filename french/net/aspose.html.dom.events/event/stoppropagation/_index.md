---
title: Event.StopPropagation
second_title: Référence de l'API Aspose.HTML pour .NET
description: Event méthode. LeStopPropagation méthode est utilisée pour empêcher la propagation ultérieure dun événement pendant le flux dévénements.
type: docs
weight: 140
url: /fr/net/aspose.html.dom.events/event/stoppropagation/
---
## Event.StopPropagation method

Le`StopPropagation` méthode est utilisée pour empêcher la propagation ultérieure d'un événement pendant le flux d'événements.

```csharp
public void StopPropagation()
```

### Remarques

Si cette méthode est appelée par n'importe quel[`IEventListener`](../../ieventlistener/) l'événement cessera de se propager à travers l'arborescence. L'événement terminera la distribution à tous les écouteurs sur le courant[`IEventTarget`](../../ieventtarget/) avant l'arrêt du flux d'événements. Cette méthode peut être utilisée à n'importe quelle étape du flux d'événements.

### Voir également

* class [Event](../)
* espace de noms [Aspose.Html.Dom.Events](../../event/)
* Assemblée [Aspose.HTML](../../../)


