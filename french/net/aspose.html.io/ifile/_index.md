---
title: Interface IFile
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.IO.IFile interface. Un objet File est un objet Blob avec un attribut name qui est une chaîne  il peut être créé dans lapplication Web via un constructeur ou est une référence à une séquence doctets dun fichier du système de fichiers sousjacent OS.
type: docs
weight: 3720
url: /fr/net/aspose.html.io/ifile/
---
## IFile interface

Un objet File est un objet Blob avec un attribut name, qui est une chaîne ; il peut être créé dans l'application Web via un constructeur, ou est une référence à une séquence d'octets d'un fichier du système de fichiers sous-jacent (OS).

```csharp
public interface IFile : IBlob
```

## Propriétés

| Nom | La description |
| --- | --- |
| [LastModified](../../aspose.html.io/ifile/lastmodified/) { get; } | La date de la dernière modification du fichier. Lors de l'obtention, si les agents utilisateurs peuvent rendre ces informations disponibles, cela doit renvoyer un long ensemble long à l'heure à laquelle le fichier a été modifié pour la dernière fois en nombre de millisecondes depuis l'époque Unix. |
| [Name](../../aspose.html.io/ifile/name/) { get; } | Le nom du fichier. Lors de l'obtention, cela doit renvoyer le nom du fichier sous forme de chaîne. |

### Voir également

* interface [IBlob](../iblob/)
* espace de noms [Aspose.Html.IO](../../aspose.html.io/)
* Assemblée [Aspose.HTML](../../)


