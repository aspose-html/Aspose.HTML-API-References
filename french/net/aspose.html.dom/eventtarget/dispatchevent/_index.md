---
title: EventTarget.DispatchEvent
second_title: Référence de l'API Aspose.HTML pour .NET
description: EventTarget méthode. Cette méthode permet de répartir les événements dans le modèle dévénement des implémentations.
type: docs
weight: 20
url: /fr/net/aspose.html.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

Cette méthode permet de répartir les événements dans le modèle d'événement des implémentations.

```csharp
public bool DispatchEvent(Event @event)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| event | Event | Spécifie le type d'événement, le comportement et les informations contextuelles à utiliser lors du traitement de l'événement. |

### Return_Value

La valeur de retour de`DispatchEvent` indique si l'un des écouteurs qui a géré l'événement appelé[`PreventDefault`](../../../aspose.html.dom.events/event/preventdefault/) . Si[`PreventDefault`](../../../aspose.html.dom.events/event/preventdefault/) a été appelé la valeur est fausse, sinon la valeur est vraie.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../domexception/) |  |

### Remarques

Les événements distribués de cette manière auront le même comportement de capture et de propagation que les événements distribués directement par l'implémentation. La cible de l'événement est le[`EventTarget`](../) sur lequel`DispatchEvent` s'appelle.

### Voir également

* class [Event](../../../aspose.html.dom.events/event/)
* class [EventTarget](../)
* espace de noms [Aspose.Html.Dom](../../eventtarget/)
* Assemblée [Aspose.HTML](../../../)


