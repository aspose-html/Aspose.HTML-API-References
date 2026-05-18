---
title: "Event.PreventDefault"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode de l'événement. Si un événement est annulable, la méthode PreventDefault est utilisée pour indiquer que l'événement doit être annulé, ce qui signifie que toute action par défaut normalement effectuée par l'implémentation à la suite de l'événement ne se produira pas."
type: docs

url: /fr/java/com.aspose.html.dom.events/event/preventdefault/
---
## Event.PreventDefault method

Si un événement est annulable, la méthode `PreventDefault` est utilisée pour indiquer que l'événement doit être annulé, ce qui signifie que toute action par défaut normalement effectuée par l'implémentation à la suite de l'événement ne se produira pas.

```java
public void PreventDefault()
```

## Remarques

Si, à n'importe quelle étape du flux d'événements, la méthode `PreventDefault` est appelée, l'événement est annulé. Toute action par défaut associée à l'événement ne se produira pas. L'appel de cette méthode pour un événement non annulable n'a aucun effet. Une fois que `PreventDefault` a été appelée, elle restera en vigueur pendant le reste de la propagation de l'événement. Cette méthode peut être utilisée à n'importe quelle étape du flux d'événements.

### Voir aussi

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
