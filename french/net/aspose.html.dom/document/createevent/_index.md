---
title: Document.CreateEvent
second_title: Référence de l'API Aspose.HTML pour .NET
description: Document méthode. Crée unEvent dun type pris en charge par limplémentation.
type: docs
weight: 880
url: /fr/net/aspose.html.dom/document/createevent/
---
## Document.CreateEvent method

Crée un[`Event`](../../../aspose.html.dom.events/event/) d'un type pris en charge par l'implémentation.

```csharp
public Event CreateEvent(string eventType)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| eventType | String | Le paramètre eventType spécifie le type de[`Event`](../../../aspose.html.dom.events/event/) interface à créer.  Si le[`Event`](../../../aspose.html.dom.events/event/) l'interface spécifiée est prise en charge par l'implémentation cette méthode will retournera un nouveau[`Event`](../../../aspose.html.dom.events/event/) du type d'interface demandé. Si le[`Event`](../../../aspose.html.dom.events/event/)est à expédier via le[`DispatchEvent`](../../../aspose.html.dom.events/ieventtarget/dispatchevent/) la méthode appropriée[`InitEvent`](../../../aspose.html.dom.events/event/initevent/) La méthode doit être appelée après la création afin d'initialiser le[`Event`](../../../aspose.html.dom.events/event/) s valeurs. |

### Return_Value

La nouvelle création[`Event`](../../../aspose.html.dom.events/event/)

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR : déclenché si l'implémentation ne prend pas en charge le type de[`Event`](../../../aspose.html.dom.events/event/) interface demandée |

### Voir également

* class [Event](../../../aspose.html.dom.events/event/)
* class [Document](../)
* espace de noms [Aspose.Html.Dom](../../document/)
* Assemblée [Aspose.HTML](../../../)


