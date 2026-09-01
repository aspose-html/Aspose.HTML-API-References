---
title: "TypeInfo.IsDerivedFrom"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode TypeInfo. Cette méthode indique s'il existe une dérivation entre la définition de type de référence, c'est‑à‑dire le TypeInfo sur lequel la méthode est appelée, et l'autre définition de type, c'est‑à‑dire celle passée en paramètre"
type: docs

url: /fr/java/com.aspose.html.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

Cette méthode renvoie s'il existe une dérivation entre la définition du type de référence, c'est‑à‑dire le TypeInfo sur lequel la méthode est appelée, et l'autre définition de type, c'est‑à‑dire celle passée en paramètres.

```java
public bool IsDerivedFrom(String typeNamespaceArg, String typeNameArg, ulong derivationMethod)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| typeNamespaceArg | String | le package de l'autre définition de type |
| typeNameArg | String | le nom de l'autre définition de type. |
| derivationMethod | UInt64 | le type de dérivation et les conditions appliquées entre deux types, comme décrit dans la liste des constantes fournie dans cette interface. |

### Valeur de retour

Si le schéma du document est un DTD ou aucun schéma n'est associé au document, cette méthode renverra toujours false. Si le schéma du document est un schéma XML, la méthode renverra true si la définition de type de référence est dérivée de l'autre définition de type selon le paramètre de dérivation. Si la valeur du paramètre est 0 (aucun bit n'est à 1 pour le paramètre derivationMethod), la méthode renverra true si l'autre définition de type peut être atteinte en parcourant récursivement toute combinaison de {base type definition}, {item type definition} ou {member type definitions} à partir de la définition de type de référence.

### Voir aussi

* class [TypeInfo](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
