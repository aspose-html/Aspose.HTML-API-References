---
title: "Interface IUserAgentService"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Interface com.aspose.html.services.IUserAgentService. Une interface qui décrit un environnement d’agent utilisateur"
type: docs

url: /fr/java/com.aspose.html.services/iuseragentservice/
---
## IUserAgentService interface

Une interface qui décrit un environnement d'agent utilisateur.

```java
public interface IUserAgentService
```

## Propriétés

| Nom | Description |
| --- | --- |
[getCharSet]
[setCharSet] Gets or sets the primary character-set for a document. |
[getCSSEngineMode]
[setCSSEngineMode] Gets or sets mode in which CSS engine works. |
| [getFontsSettings](../../com.aspose.html.services/iuseragentservice/fontssettings/) Obtient un objet [`FontsSettings`](../../com.aspose.html/fontssettings/) qui est utilisé pour la configuration de la gestion des polices. |
[getLanguage]
[setLanguage] The [`Language`](./language/) specifies the primary language for the element's contents and for any of the element's attributes that contain text. Its value must be a valid BCP 47 () language tag, or the empty String. Setting the attribute to the empty String indicates that the primary language is unknown. |
[getShowImagePlaceholders]
[setShowImagePlaceholders] Images can have fallback content: content that should be used when an external resource cannot be used (for example, because it is in an unsupported format). The property [`ShowImagePlaceholders`](./showimageplaceholders/) specifies whether to display the fallback image (default is true) |
[getUserStyleSheet]
[setUserStyleSheet] Allows to specify style information for a particular document |

### Voir aussi

* package [com.aspose.html.services](../../com.aspose.html.services/)
* package [Aspose.HTML](../../)
