---
title: CustomEvent.InitCustomEvent
second_title: Référence de l'API Aspose.HTML pour .NET
description: CustomEvent méthode. /// LeInitEvent méthode est utilisée pour initialiser la valeur dunEvent créé grâce à laIDocumentEvent interface.
type: docs
weight: 30
url: /fr/net/aspose.html.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// Le[`InitEvent`](../../event/initevent/) méthode est utilisée pour initialiser la valeur d'un[`Event`](../../event/) créé grâce à la[`IDocumentEvent`](../../idocumentevent/) interface.

```csharp
public void InitCustomEvent(string type, bool bubbles, bool cancelable, object detail)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| type | String | Le type d'événement. |
| bubbles | Boolean | si réglé sur`vrai` [bulles]. |
| cancelable | Boolean | si réglé sur`vrai` [annulable]. |
| detail | Object | Les données personnalisées. |

### Remarques

Cette méthode ne peut être appelée qu'avant que l'événement n'ait été envoyé via le[`DispatchEvent`](../../ieventtarget/dispatchevent/) méthode, bien qu'elle puisse être appelée plusieurs fois au cours de cette phase si nécessaire. Si elle est appelée plusieurs fois, l'invocation finale a priorité. Si elle est appelée à partir d'une sous-classe de l'interface Event, seules les valeurs spécifiées dans la méthode initEvent sont modifiées, tous les autres attributs restent inchangés.

### Voir également

* class [CustomEvent](../)
* espace de noms [Aspose.Html.Dom.Events](../../customevent/)
* Assemblée [Aspose.HTML](../../../)


