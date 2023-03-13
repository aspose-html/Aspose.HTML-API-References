---
title: TimeEvent.InitTimeEvent
second_title: Référence de l'API Aspose.HTML pour .NET
description: TimeEvent méthode. La méthode initTimeEvent est utilisée pour initialiser la valeur dun TimeEvent créé via linterface DocumentEvent. Cette méthode ne peut être appelée quavant que TimeEvent ait été distribué via la méthode dispatchEvent bien quelle puisse être appelée plusieurs fois au cours de cette phase si nécessaire. Sil est appelé plusieurs fois linvocation finale est prioritaire.
type: docs
weight: 30
url: /fr/net/aspose.html.dom.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

La méthode initTimeEvent est utilisée pour initialiser la valeur d'un TimeEvent créé via l'interface DocumentEvent. Cette méthode ne peut être appelée qu'avant que TimeEvent ait été distribué via la méthode dispatchEvent, bien qu'elle puisse être appelée plusieurs fois au cours de cette phase si nécessaire. S'il est appelé plusieurs fois, l'invocation finale est prioritaire.

```csharp
public void InitTimeEvent(string typeArg, IAbstractView viewArg, long detailArg)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| typeArg | String | Spécifie le type d'événement. |
| viewArg | IAbstractView | Spécifie la vue abstraite de l'événement. |
| detailArg | Int64 | Spécifie le détail de l'événement. |

### Voir également

* interface [IAbstractView](../../../aspose.html.dom.views/iabstractview/)
* class [TimeEvent](../)
* espace de noms [Aspose.Html.Dom.Svg.Events](../../timeevent/)
* Assemblée [Aspose.HTML](../../../)


