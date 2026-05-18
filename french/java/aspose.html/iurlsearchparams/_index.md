---
title: "IUrlSearchParams Interface"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "com.aspose.html.IUrlSearchParams interface. Fournit des méthodes pour travailler avec la chaîne de requête des URL"
type: docs

url: /fr/java/com.aspose.html/iurlsearchparams/
---
## IUrlSearchParams interface

Fournit des méthodes pour travailler avec la chaîne de requête des URL.

```java
public interface IUrlSearchParams : IEnumerable<String[]>
```

## Méthodes

| Nom | Description |
| --- | --- |
| [append](../../com.aspose.html/iurlsearchparams/append/)(String, String) | Ajoute une nouvelle paire nom-valeur dont le nom est `name` et la valeur est `value`. |
| [delete](../../com.aspose.html/iurlsearchparams/delete/)(String) | Supprime toutes les paires nom-valeur dont le nom est `name`. |
| [get](../../com.aspose.html/iurlsearchparams/get/)(String) | Renvoie la valeur de la première paire nom-valeur dont le nom est `name`. |
| [getAll](../../com.aspose.html/iurlsearchparams/getall/)(String) | Renvoie toutes les valeurs dont le nom est `name`. |
| [has](../../com.aspose.html/iurlsearchparams/has/)(String) | Vérifie s'il existe une paire nom-valeur dont le nom est `name` dans la liste. |
| [set](../../com.aspose.html/iurlsearchparams/set/)(String, String) | Définit la valeur de la première paire nom-valeur trouvée à la valeur spécifiée et supprime les autres. Si aucune paire nom-valeur avec le nom spécifié n'est trouvée, une nouvelle sera ajoutée à la liste. |
| [sort](../../com.aspose.html/iurlsearchparams/sort/)() | Trie toutes les paires nom-valeur, le cas échéant, par leurs noms. |

### Voir aussi

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
