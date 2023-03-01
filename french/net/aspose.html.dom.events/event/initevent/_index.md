---
title: Event.InitEvent
second_title: Référence de l'API Aspose.HTML pour .NET
description: Event méthode. LeInitEvent méthode est utilisée pour initialiser la valeur dunEvent créé via the IDocumentEvent interface.
type: docs
weight: 110
url: /fr/net/aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

Le`InitEvent` méthode est utilisée pour initialiser la valeur d'un[`Event`](../) créé via the [`IDocumentEvent`](../../idocumentevent/) interface.

```csharp
public void InitEvent(string type, bool bubbles, bool cancelable)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| type | String | Le type d'événement. |
| bubbles | Boolean | si réglé sur`vrai` [bulles]. |
| cancelable | Boolean | si réglé sur`vrai` [annulable]. |

### Remarques

Cette méthode ne peut être appelée qu'avant que l'événement n'ait été envoyé via le[`DispatchEvent`](../../ieventtarget/dispatchevent/) méthode, bien qu'elle puisse être appelée plusieurs fois au cours de cette phase si nécessaire. Si elle est appelée plusieurs fois, l'invocation finale a priorité. Si elle est appelée à partir d'une sous-classe de l'interface Event, seules les valeurs spécifiées dans la méthode initEvent sont modifiées, tous les autres attributs restent inchangés.

### Voir également

* class [Event](../)
* espace de noms [Aspose.Html.Dom.Events](../../event/)
* Assemblée [Aspose.HTML](../../../)


