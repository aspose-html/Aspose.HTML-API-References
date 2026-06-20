---
title: "Interface IFile"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "interface com.aspose.html.io.IFile. Un objet File est un objet Blob avec un attribut name qui est une String ; il peut être créé dans l'application web via un constructeur ou être une référence à une séquence d'octets provenant d'un fichier du système de fichiers sous-jacent de l'OS."
type: docs

url: /fr/java/com.aspose.html.io/ifile/
---
## IFile interface

Un objet File est un objet Blob avec un attribut name, qui est une chaîne ; il peut être créé dans l'application web via un constructeur, ou constitue une référence à une séquence d'octets provenant d'un fichier du système de fichiers sous‑jacent (OS).

```java
public interface IFile : IBlob
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getLastModified](../../com.aspose.html.io/ifile/lastmodified/) La date de dernière modification du fichier. Lors de la lecture, si les agents utilisateurs peuvent rendre cette information disponible, cela doit renvoyer un long long correspondant au moment où le fichier a été modifié pour la dernière fois, exprimé en nombre de millisecondes depuis l'époque Unix. |
| [getName](../../com.aspose.html.io/ifile/name/) Le nom du fichier. Lors de la lecture, cela doit renvoyer le nom du fichier sous forme de String. |

### Voir aussi

* interface [IBlob](../iblob/)
* package [com.aspose.html.io](../../com.aspose.html.io/)
* package [Aspose.HTML](../../)
