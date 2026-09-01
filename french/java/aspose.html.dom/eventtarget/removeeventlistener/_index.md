---
title: "EventTarget.RemoveEventListener"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode EventTarget. Cette méthode permet la suppression des écouteurs d'événements de la cible d'événement. Si un écouteur est retiré d'une cible pendant qu'elle traite un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événements ne peuvent jamais être invoqués après avoir été supprimés"
type: docs

url: /fr/java/com.aspose.html.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(String, DOMEventHandler, bool) {#removeeventlistener}

Cette méthode permet la suppression des écouteurs d'événements de la cible d'événement. Si un écouteur est supprimé pendant le traitement d'un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événements ne peuvent jamais être invoqués après avoir été supprimés.

```java
public void RemoveEventListener(String type, DOMEventHandler handler, bool useCapture)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| type | String | Spécifie le type d'événement de l'élément à supprimer. |
| gestionnaire | DOMEventHandler | Le paramètre indique l'élément à supprimer. |
| useCapture | Boolean | Spécifie si l'EventListener qui est supprimé a été enregistré en tant qu'écouteur capturant ou non. Si un écouteur a été enregistré deux fois, une fois avec capture et une fois sans, chacun doit être supprimé séparément. La suppression d'un écouteur capturant n'affecte pas la version non capturante du même écouteur, et vice‑versa. |

### Voir aussi

* delegate [DOMEventHandler](../../../com.aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener) {#removeeventlistener_1}

Cette méthode permet la suppression des écouteurs d'événements de la cible d'événement. Si un écouteur est supprimé pendant le traitement d'un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événements ne peuvent jamais être invoqués après avoir été supprimés.

```java
public void RemoveEventListener(String type, IEventListener listener)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| type | String | Spécifie le type d'événement de l'élément à supprimer. |
| écouteur | IEventListener | Le paramètre indique l'élément à supprimer. |

### Voir aussi

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener, bool) {#removeeventlistener_2}

Cette méthode permet la suppression des écouteurs d'événements de la cible d'événement. Si un écouteur est supprimé pendant le traitement d'un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événements ne peuvent jamais être invoqués après avoir été supprimés.

```java
public void RemoveEventListener(String type, IEventListener listener, bool useCapture)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| type | String | Spécifie le type d'événement de l'élément à supprimer. |
| écouteur | IEventListener | Le paramètre indique l'élément à supprimer. |
| useCapture | Boolean | Spécifie si l'EventListener qui est supprimé a été enregistré en tant qu'écouteur capturant ou non. Si un écouteur a été enregistré deux fois, une fois avec capture et une fois sans, chacun doit être supprimé séparément. La suppression d'un écouteur capturant n'affecte pas la version non capturante du même écouteur, et vice‑versa. |

### Voir aussi

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
