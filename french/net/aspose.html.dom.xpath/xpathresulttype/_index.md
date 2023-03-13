---
title: Enum XPathResultType
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Dom.XPath.XPathResultType énumération. Un court non signé indiquant de quel type de résultat il sagit. Si un spécifiquetaperest spécifié le résultat sera renvoyé en tant que type correspondant en utilisant les conversions de type XPath si nécessaire et possible.
type: docs
weight: 2610
url: /fr/net/aspose.html.dom.xpath/xpathresulttype/
---
## XPathResultType enumeration

Un court non signé indiquant de quel type de résultat il s'agit. Si un spécifique`taper`est spécifié, le résultat sera renvoyé en tant que type correspondant, en utilisant les conversions de type XPath si nécessaire et possible.

```csharp
public enum XPathResultType
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| Any | `0` | Ce code ne représente pas un type spécifique. Une évaluation d'une expression XPath ne produira jamais ce type. Si ce type est demandé, l'évaluation renvoie quel que soit le type résultant naturellement de l'évaluation de l'expression. Si le résultat naturel est un ensemble de nœuds lorsque`N'importe quel` type a été demandé, puis`UnorderedNodeIteratorUnorderedNodeIterator` est toujours le type résultant. Toute autre représentation d'un ensemble de nœuds doit être explicitement demandée. |
| Number | `1` | Le résultat est un nombre tel que défini par [XPath 1.0]. La modification du document n'invalide pas le numéro, mais peut signifier que la réévaluation ne donnerait pas le même numéro. |
| String | `2` | Le résultat est une chaîne telle que définie par [XPath 1.0]. La modification du document n'invalide pas la chaîne, mais peut signifier que la chaîne ne correspond plus au document actuel. |
| Boolean | `3` | Le résultat est un booléen tel que défini par [XPath 1.0]. La modification du document n'invalide pas le booléen, mais peut signifier que la réévaluation ne produirait pas le même booléen. |
| UnorderedNodeIterator | `4` | Le résultat est un ensemble de nœuds tel que défini par [XPath 1.0] qui sera accessible de manière itérative, qui peut ne pas produire de nœuds dans un ordre particulier. La modification du document invalide l'itération . Il s'agit du type par défaut renvoyé si le résultat est un ensemble de nœuds et`N'importe quel` Le type est demandé. |
| OrderedNodeIterator | `5` | Le résultat est un ensemble de nœuds tel que défini par [XPath 1.0] auquel on accédera de manière itérative, qui produira des nœuds ordonnés par document. La modification du document invalide l'itération. |
| UnorderedNodeSnapshot | `6` | Le résultat est un ensemble de nœuds tel que défini par [XPath 1.0] qui sera accessible en tant qu'instantané liste de nœuds qui peuvent ne pas être dans un ordre particulier. La modification du document n'invalide pas l'instantané, mais peut signifier que la réévaluation ne produira pas le même instantané et que les nœuds de l'instantané peuvent avoir été modifiés, déplacés ou supprimés du document. |
| OrderedNodeSnapshot | `7` | Le résultat est un ensemble de nœuds tel que défini par [XPath 1.0] qui sera accessible en tant qu'instantané liste de nœuds qui seront dans l'ordre du document d'origine. La modification du document n'invalide pas l'instantané, mais peut signifier que la réévaluation ne produira pas le même instantané et que les nœuds de l'instantané peuvent avoir été modifiés, déplacés ou supprimés du document. |
| AnyUnorderedNode | `8` | Le résultat est un ensemble de nœuds tel que défini par [XPath 1.0] et sera accessible en tant que nœud unique, qui peut être`nul`si l'ensemble de nœuds est vide. La modification du document n'invalide pas le noeud, mais peut signifier que le noeud résultat ne correspond plus au document courant. C'est une commodité qui permet l'optimisation puisque l'implémentation peut s'arrêter une fois que n'importe quel nœud dans l'ensemble résultant a été trouvé. S'il y a plus d'un nœud dans le résultat réel, le nœud unique renvoyé peut ne pas être le premier dans l'ordre du document. |
| FirstOrderedNode | `9` | Le résultat est un ensemble de nœuds tel que défini par [XPath 1.0] et sera accessible en tant que nœud unique, qui peut être`nul`si l'ensemble de nœuds est vide. La modification du document n'invalide pas le noeud, mais peut signifier que le noeud résultat ne correspond plus au document courant. C'est une commodité qui permet l'optimisation puisque l'implémentation peut s'arrêter une fois que le premier nœud dans l'ordre des documents de l'ensemble résultant a été trouvé. S'il y a plus d'un nœud dans le résultat réel, le nœud unique renvoyé sera le premier dans l'ordre du document. |

### Voir également

* espace de noms [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* Assemblée [Aspose.HTML](../../)


