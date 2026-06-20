---
title: "Classe TypeInfo"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "classe com.aspose.html.dom.TypeInfo. Le TypeInfo représente un type référencé à partir des nœuds Element ou Attr spécifiés dans les schémas associés au document"
type: docs

url: /fr/java/com.aspose.html.dom/typeinfo/
---
## TypeInfo class

Le TypeInfo représente un type référencé à partir des nœuds Element ou Attr, spécifié dans les schémas associés au document.

```java
public class TypeInfo : DOMObject
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getTypeName](../../com.aspose.html.dom/typeinfo/typename/) Le nom d'un type déclaré pour l'élément ou l'attribut associé, ou null si inconnu. |
| [getTypeNamespace](../../com.aspose.html.dom/typeinfo/typepackage/) Obtient le package du type. Le package du type déclaré pour l'élément ou l'attribut associé ou null si l'élément n'a pas de déclaration ou si aucune information de package n'est disponible. |

## Méthodes

| Nom | Description |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScript. |
| [isDerivedFrom](../../com.aspose.html.dom/typeinfo/isderivedfrom/)(String, String, ulong) | Cette méthode renvoie s'il existe une dérivation entre la définition du type de référence, c'est‑à‑dire le TypeInfo sur lequel la méthode est appelée, et l'autre définition de type, c'est‑à‑dire celle passée en paramètres. |

## Champs

| Nom | Description |
| --- | --- |
| const [DERIVATION_EXTENSION](../../com.aspose.html.dom/typeinfo/derivation_extension/) | Si le schéma du document est un schéma XML [XML Schema Part 1], cette constante représente la dérivation par extension. |
| const [DERIVATION_LIST](../../com.aspose.html.dom/typeinfo/derivation_list/) | Si le schéma du document est un schéma XML [XML Schema Part 1], cette constante représente la liste. |
| const [DERIVATION_RESTRICTION](../../com.aspose.html.dom/typeinfo/derivation_restriction/) | Si le schéma du document est un schéma XML [XML Schema Part 1], cette constante représente la dérivation par restriction lorsque des types complexes sont impliqués, ou une restriction lorsque des types simples sont impliqués. |
| const [DERIVATION_UNION](../../com.aspose.html.dom/typeinfo/derivation_union/) | Si le schéma du document est un schéma XML [XML Schema Part 1], cette constante représente l'union lorsque des types simples sont impliqués. |

### Voir aussi

* class [DOMObject](../domobject/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
