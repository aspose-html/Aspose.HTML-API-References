---
title: Event.PreventDefault
second_title: Référence de l'API Aspose.HTML pour .NET
description: Event méthode. Si un événement est annulable lePreventDefault est utilisée pour signifier que lévénement doit être annulé ce qui signifie que toute action par défaut normalement entreprise par limplémentation à la suite de lévénement ne se produira pas.
type: docs
weight: 120
url: /fr/net/aspose.html.dom.events/event/preventdefault/
---
## Event.PreventDefault method

Si un événement est annulable, le`PreventDefault` est utilisée pour signifier que l'événement doit être annulé, ce qui signifie que toute action par défaut normalement entreprise par l'implémentation à la suite de l'événement ne se produira pas.

```csharp
public void PreventDefault()
```

### Remarques

Si, à n'importe quelle étape du flux d'événements, le`PreventDefault`est appelée, l'événement est annulé. Toute action par défaut associée à l'événement ne se produira pas. L'appel de cette méthode pour un événement non annulable n'a aucun effet. Une fois`PreventDefault` a été appelé, il restera en vigueur pendant le reste de la propagation de l'événement. Cette méthode peut être utilisée à n'importe quelle étape du flux d'événements.

### Voir également

* class [Event](../)
* espace de noms [Aspose.Html.Dom.Events](../../event/)
* Assemblée [Aspose.HTML](../../../)


