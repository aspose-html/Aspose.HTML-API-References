---
title: Interface IBlob
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.IO.IBlob interface. Un objet Blob fait référence à une séquence doctets et possède un attribut de taille qui est le nombre total doctets dans la séquence doctets et un attribut de type qui est une chaîne codée en ASCII en minuscules représentant le type de média de la séquence doctets .
type: docs
weight: 3700
url: /fr/net/aspose.html.io/iblob/
---
## IBlob interface

Un objet Blob fait référence à une séquence d'octets et possède un attribut de taille qui est le nombre total d'octets dans la séquence d'octets, et un attribut de type, qui est une chaîne codée en ASCII en minuscules représentant le type de média de la séquence d'octets .

```csharp
public interface IBlob
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Size](../../aspose.html.io/iblob/size/) { get; } | Renvoie la taille de la séquence d'octets en nombre d'octets. Lors de l'obtention, les agents utilisateurs conformes doivent renvoyer le nombre total d'octets pouvant être lus par un objet FileReader ou FileReaderSync, ou 0 si le Blob n'a aucun octet à lire . |
| [Type](../../aspose.html.io/iblob/type/) { get; } | La chaîne encodée en ASCII en minuscules représentant le type de média du Blob. Lors de l'obtention, les agents utilisateurs doivent renvoyer le type d'un Blob sous la forme d'une chaîne encodée en ASCII en minuscules, de sorte que lorsqu'il est converti en un octet séquence, il s'agit d'un type MIME analysable, ou de la chaîne vide - 0 octet - si le type ne peut pas être déterminé. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Slice](../../aspose.html.io/iblob/slice/)(ulong, ulong, string) | Renvoie un nouvel objet Blob avec des octets allant du paramètre facultatif start jusqu'au paramètre facultatif end, et avec un attribut type qui est la valeur du paramètre facultatif contentType. |

### Voir également

* espace de noms [Aspose.Html.IO](../../aspose.html.io/)
* Assemblée [Aspose.HTML](../../)


