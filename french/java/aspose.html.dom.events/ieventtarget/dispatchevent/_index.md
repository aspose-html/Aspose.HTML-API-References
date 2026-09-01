---
title: "IEventTarget.DispatchEvent"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode IEventTarget. Déclenche un Event sur l'EventTarget spécifié en invoquant de façon synchrone les EventListeners concernés dans l'ordre approprié. Les règles normales de traitement des événements, y compris les phases de capture et de bouillonnement optionnelles, s'appliquent également aux événements déclenchés manuellement avec dispatchEvent."
type: docs

url: /fr/java/com.aspose.html.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

Déclenche un Event sur le EventTarget spécifié, (synchroniquement) en invoquant les EventListeners affectés dans l'ordre approprié. Les règles normales de traitement des événements (y compris les phases de capture et de bouillonnement optionnel) s'appliquent également aux événements déclenchés manuellement avec dispatchEvent().

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
| [dOMException](../../../com.aspose.html.dom/domexception/) | Les exceptions levées par les gestionnaires d'événements sont signalées comme des exceptions non interceptées. Les gestionnaires d'événements s'exécutent sur une pile d'appels imbriquée ; ils bloquent l'appelant jusqu'à leur achèvement, mais les exceptions ne se propagent pas à l'appelant. |

## Remarques

Les événements déclenchés de cette manière auront le même comportement de capture et de bouillonnement que les événements déclenchés directement par l'implémentation. La cible de l'événement est le on qui est appelé.

### Voir aussi

* class [Event](../../event/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
