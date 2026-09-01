---
title: "FontMatcher.MatchFontFallback"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode FontMatcher. Cette méthode est appelée s'il n'y a aucune police appropriée trouvée dans les dossiers de recherche de polices. Elle doit renvoyer une police TrueType basée sur les fontMatchingProperties qui peut rendre charCode ou null si une telle police n'est pas disponible."
type: docs

url: /fr/java/com.aspose.html.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

Cette méthode est appelée s'il n'y a aucune police appropriée trouvée dans les dossiers de recherche de polices. Elle doit renvoyer une police de type vrai basée sur les *fontMatchingProperties* qui peut rendre le *charCode*, ou `null` si une telle police n'est pas disponible.

```java
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | Propriétés de la police correspondante. |
| charCode | UInt32 | Code du caractère qui sera rendu en utilisant la police correspondante. |

### Valeur de retour

Un tableau d'octets contenant les données des polices ou `null`.

### Voir aussi

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* package [com.aspose.html.rendering.fonts](../../../com.aspose.html.rendering.fonts/)
* package [Aspose.HTML](../../../)
