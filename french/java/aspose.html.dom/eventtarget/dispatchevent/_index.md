---
title: "EventTarget.DispatchEvent"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode EventTarget. Déclenche un événement sur l'EventTarget spécifié en invoquant de manière synchrone les EventListeners affectés dans l'ordre approprié. Les règles normales de traitement des événements, y compris les phases de capture et de bouillonnement optionnelle, s'appliquent également aux événements déclenchés manuellement avec dispatchEvent"
type: docs

url: /fr/java/com.aspose.html.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

Déclenche un événement sur le [`EventTarget`](../../../com.aspose.html.dom.events/ieventtarget/), (de manière synchrone) en invoquant les EventListeners affectés dans l'ordre approprié. Les règles normales de traitement des événements (y compris les phases de capture et de bouillonnement optionnelle) s'appliquent également aux événements déclenchés manuellement avec [`dispatchEvent()`](../../../com.aspose.html.dom.events/ieventtarget/dispatchevent/).

```java
public bool DispatchEvent(Event @event)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| événement | Événement | Spécifie le type d'événement, le comportement et les informations contextuelles à utiliser lors du traitement de l'événement. |

### Valeur de retour

La valeur de retour de indique si l'un des écouteurs qui ont traité l'événement a été appelé. Si a été appelé, la valeur est false, sinon la valeur est true.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../domexception/) |  |

## Remarques

Les événements déclenchés de cette manière auront le même comportement de capture et de bouillonnement que les événements déclenchés directement par l'implémentation. La cible de l'événement est le on qui est appelé.

### Voir aussi

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
