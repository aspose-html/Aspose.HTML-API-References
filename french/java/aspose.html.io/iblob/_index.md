---
title: "Interface IBlob"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "interface com.aspose.html.io.IBlob. Un objet Blob fait référence à une séquence d'octets et possède un attribut size qui correspond au nombre total d'octets dans la séquence, ainsi qu'un attribut type qui est une String encodée en ASCII en minuscules représentant le type média de la séquence d'octets."
type: docs

url: /fr/java/com.aspose.html.io/iblob/
---
## IBlob interface

Un objet Blob fait référence à une séquence d'octets et possède un attribut size qui correspond au nombre total d'octets dans la séquence, ainsi qu'un attribut type, qui est une chaîne encodée en ASCII en minuscules représentant le type média de la séquence d'octets.

```java
public interface IBlob
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getSize](../../com.aspose.html.io/iblob/size/) Renvoie la taille de la séquence d'octets en nombre d'octets. Lors de la lecture, les agents utilisateurs conformes doivent renvoyer le nombre total d'octets pouvant être lus par un objet FileReader ou FileReaderSync, ou 0 si le Blob ne contient aucun octet à lire. |
| [getType](../../com.aspose.html.io/iblob/type/) La String encodée en ASCII en minuscules représentant le type média du Blob. Lors de la lecture, les agents utilisateurs doivent renvoyer le type d'un Blob sous forme d'une String encodée en ASCII en minuscules, de sorte que lorsqu'elle est convertie en séquence d'octets, elle constitue un type MIME analysable, ou la String vide – 0 octet – si le type ne peut être déterminé. |

## Méthodes

| Nom | Description |
| --- | --- |
| [slice](../../com.aspose.html.io/iblob/slice/)(ulong, ulong, String) | Renvoie un nouvel objet Blob dont les octets s'étendent du paramètre optionnel start jusqu'au paramètre optionnel end (exclu), et avec un attribut type dont la valeur est celle du paramètre optionnel contentType. |

### Voir aussi

* package [com.aspose.html.io](../../com.aspose.html.io/)
* package [Aspose.HTML](../../)
