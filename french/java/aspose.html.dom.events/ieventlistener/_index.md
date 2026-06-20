---
title: "Interface IEventListener"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "interface com.aspose.html.dom.events.IEventListener. L'interface est la méthode principale pour gérer les événements. Les utilisateurs implémentent l'interface et enregistrent leur écouteur en utilisant la méthode. Les utilisateurs doivent également le retirer après avoir terminé d'utiliser l'écouteur."
type: docs

url: /fr/java/com.aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

L'interface est la méthode principale pour gérer les événements. Les utilisateurs implémentent l'interface et enregistrent leur écouteur sur un en utilisant la méthode. Les utilisateurs doivent également les supprimer de celui-ci après avoir terminé d'utiliser l'écouteur.

```java
public interface IEventListener
```

## Méthodes

| Nom | Description |
| --- | --- |
| [handleEvent](../../com.aspose.html.dom.events/ieventlistener/handleevent/)(Event) | Cette méthode est appelée chaque fois qu'un événement du type pour lequel l'interface a été enregistrée se produit. |

## Remarques

Lorsque qu'un nœud est copié à l'aide de la méthode cloneNode, les écouteurs d'événements attachés au nœud source ne sont pas attachés au nœud copié. Si l'utilisateur souhaite que les mêmes écouteurs d'événements soient ajoutés à la copie nouvellement créée, il doit les ajouter manuellement.

### Voir aussi

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
