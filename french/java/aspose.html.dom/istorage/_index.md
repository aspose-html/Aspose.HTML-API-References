---
title: "Interface IStorage"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "interface com.aspose.html.dom.IStorage. Cette interface de l'API Web Storage fournit l'accès à la session ou au stockage local d'un domaine particulier. Voir la spécification Web Storage https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage"
type: docs

url: /fr/java/com.aspose.html.dom/istorage/
---
## IStorage interface

Cette interface de l'API Web Storage fournit un accès au stockage de session ou local d'un domaine particulier. Voir la spécification Web Storage : [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```java
public interface IStorage
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getLength](../../com.aspose.html.dom/istorage/length/) Retourne le nombre de paires clé/valeur. |

## Méthodes

| Nom | Description |
| --- | --- |
| [clear](../../com.aspose.html.dom/istorage/clear/)() | Supprime toutes les paires clé/valeur, s’il y en a. |
| [getItem](../../com.aspose.html.dom/istorage/getitem/)(String) | Renvoie la valeur actuelle associée à la clé donnée, ou null si la clé donnée n’existe pas. |
| [key](../../com.aspose.html.dom/istorage/key/)(long) | Renvoie le nom de la n‑ième clé, ou null si n est supérieur ou égal au nombre de paires clé/valeur. |
| [removeItem](../../com.aspose.html.dom/istorage/removeitem/)(String) | Supprime la paire clé/valeur correspondant à la clé donnée, si une paire avec cette clé existe. |
| [setItem](../../com.aspose.html.dom/istorage/setitem/)(String, String) | Définit la valeur de la paire identifiée par la clé à la valeur, en créant une nouvelle paire clé/valeur si aucune n’existait auparavant pour cette clé. |

### Voir aussi

* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
