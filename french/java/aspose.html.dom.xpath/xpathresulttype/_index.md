---
title: "Enumération XPathResultType"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "com.aspose.html.dom.xpath.XPathResultType enum. Un entier court non signé indiquant le type de résultat. Si un type spécifique est indiqué, le résultat sera renvoyé sous le type correspondant en utilisant les conversions de type XPath lorsque cela est requis et possible."
type: docs

url: /fr/java/com.aspose.html.dom.xpath/xpathresulttype/
---
## XPathResultType enumeration

Un entier court non signé indiquant le type de résultat. Si un `type` spécifique est indiqué, le résultat sera renvoyé sous le type correspondant, en utilisant les conversions de type XPath lorsque cela est requis et possible.

```java
public enum XPathResultType
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Any | `0` | Ce code ne représente pas un type spécifique. L'évaluation d'une expression XPath ne produira jamais ce type. Si ce type est demandé, l'évaluation renvoie le type qui résulte naturellement de l'évaluation de l'expression. Si le résultat naturel est un ensemble de nœuds lorsqu'un type `Any` a été demandé, alors `UnorderedNodeIterator` est toujours le type résultant. Toute autre représentation d'un ensemble de nœuds doit être explicitement demandée. |
| Number | `1` | Le résultat est un nombre tel que défini par [XPath 1.0]. La modification du document n'invalide pas le nombre, mais peut signifier que la réévaluation ne donnera pas le même nombre. |
| String | `2` | Le résultat est une chaîne telle que définie par [XPath 1.0]. La modification du document n'invalide pas la chaîne, mais peut signifier que la chaîne ne correspond plus au document actuel. |
| Boolean | `3` | Le résultat est un booléen tel que défini par [XPath 1.0]. La modification du document n'invalide pas le booléen, mais peut signifier que la réévaluation ne donnera pas le même booléen. |
| UnorderedNodeIterator | `4` | Le résultat est un ensemble de nœuds tel que défini par [XPath 1.0] qui sera accédé de manière itérative, ce qui peut ne pas produire les nœuds dans un ordre particulier. La modification du document invalide l'itération. C'est le type par défaut renvoyé si le résultat est un ensemble de nœuds et que le type `Any` est demandé. |
| OrderedNodeIterator | `5` | Le résultat est un ensemble de nœuds tel que défini par [XPath 1.0] qui sera accédé de manière itérative, ce qui produira des nœuds ordonnés selon le document. La modification du document invalide l'itération. |
| UnorderedNodeSnapshot | `6` | Le résultat est un ensemble de nœuds tel que défini par [XPath 1.0] qui sera accédé sous forme de liste d'instantané de nœuds pouvant ne pas être dans un ordre particulier. La modification du document n'invalide pas l'instantané mais peut signifier que la réévaluation ne donnera pas le même instantané et que les nœuds de l'instantané ont pu être modifiés, déplacés ou supprimés du document. |
| OrderedNodeSnapshot | `7` | Le résultat est un ensemble de nœuds tel que défini par [XPath 1.0] qui sera accédé sous forme de liste d'instantané de nœuds qui seront dans l'ordre original du document. La modification du document n'invalide pas l'instantané mais peut signifier que la réévaluation ne donnera pas le même instantané et que les nœuds de l'instantané ont pu être modifiés, déplacés ou supprimés du document. |
| AnyUnorderedNode | `8` | Le résultat est un ensemble de nœuds tel que défini par [XPath 1.0] et sera accédé comme un nœud unique, qui peut être `null` si l'ensemble de nœuds est vide. La modification du document n'invalide pas le nœud, mais peut signifier que le nœud résultant ne correspond plus au document actuel. C'est une commodité qui permet l'optimisation puisque l'implémentation peut s'arrêter dès qu'un nœud du jeu de résultats a été trouvé. S'il y a plus d'un nœud dans le résultat réel, le nœud unique retourné peut ne pas être le premier dans l'ordre du document. |
| FirstOrderedNode | `9` | Le résultat est un ensemble de nœuds tel que défini par [XPath 1.0] et sera accédé comme un nœud unique, qui peut être `null` si l'ensemble de nœuds est vide. La modification du document n'invalide pas le nœud, mais peut signifier que le nœud résultant ne correspond plus au document actuel. C'est une commodité qui permet l'optimisation puisque l'implémentation peut s'arrêter dès que le premier nœud dans l'ordre du document du jeu de résultats a été trouvé. S'il y a plus d'un nœud dans le résultat réel, le nœud unique retourné sera le premier dans l'ordre du document. |

### Voir aussi

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
