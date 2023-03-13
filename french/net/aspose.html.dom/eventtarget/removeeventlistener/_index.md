---
title: EventTarget.RemoveEventListener
second_title: Référence de l'API Aspose.HTML pour .NET
description: EventTarget méthode. Cette méthode permet de supprimer les écouteurs dévénement de la cible de lévénement. Si unIEventListener est retiré dunEventTarget pendant quil traite un événement il ne sera pas déclenché par les actions en cours. Les écouteurs dévénement ne peuvent jamais être invoqués après avoir été supprimés.
type: docs
weight: 40
url: /fr/net/aspose.html.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(string, DOMEventHandler, bool) {#removeeventlistener}

Cette méthode permet de supprimer les écouteurs d'événement de la cible de l'événement. Si un[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) est retiré d'un[`EventTarget`](../) pendant qu'il traite un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événement ne peuvent jamais être invoqués après avoir été supprimés.

```csharp
public void RemoveEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| type | String | Spécifie le type d'événement du[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) en cours de suppression. |
| handler | DOMEventHandler | Le[`DOMEventHandler`](../../../aspose.html.dom.events/domeventhandler/) paramètre indique le[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) à supprimer. |
| useCapture | Boolean | Spécifie si l'EventListener en cours de suppression a été enregistré en tant qu'écouteur de capture ou non. Si un écouteur a été enregistré deux fois, un avec capture et un sans, chacun doit être supprimé séparément. La suppression d'un écouteur de capture n'affecte pas une version sans capture du même auditeur, et vice versa. |

### Voir également

* delegate [DOMEventHandler](../../../aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* espace de noms [Aspose.Html.Dom](../../eventtarget/)
* Assemblée [Aspose.HTML](../../../)

---

## RemoveEventListener(string, IEventListener) {#removeeventlistener_1}

Cette méthode permet de supprimer les écouteurs d'événement de la cible de l'événement. Si un[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) est retiré d'un[`EventTarget`](../) pendant qu'il traite un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événement ne peuvent jamais être invoqués après avoir été supprimés.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| type | String | Spécifie le type d'événement du[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) en cours de suppression. |
| listener | IEventListener | Le[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) paramètre indique le[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) à supprimer. |

### Voir également

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* espace de noms [Aspose.Html.Dom](../../eventtarget/)
* Assemblée [Aspose.HTML](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_2}

Cette méthode permet de supprimer les écouteurs d'événement de la cible de l'événement. Si un[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) est retiré d'un[`EventTarget`](../) pendant qu'il traite un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événement ne peuvent jamais être invoqués après avoir été supprimés.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| type | String | Spécifie le type d'événement du[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) en cours de suppression. |
| listener | IEventListener | Le[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) paramètre indique le[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) à supprimer. |
| useCapture | Boolean | Spécifie si l'EventListener en cours de suppression a été enregistré en tant qu'écouteur de capture ou non. Si un écouteur a été enregistré deux fois, un avec capture et un sans, chacun doit être supprimé séparément. La suppression d'un écouteur de capture n'affecte pas une version sans capture du même auditeur, et vice versa. |

### Voir également

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* espace de noms [Aspose.Html.Dom](../../eventtarget/)
* Assemblée [Aspose.HTML](../../../)


