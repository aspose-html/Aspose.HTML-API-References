---
title: Class MultiLineContainerBlockSyntaxNode
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Toolkit.Markdown.Syntax.MultiLineContainerBlockSyntaxNode classe. Implémentation de base dun nœud de syntaxe de bloc conteneur multiligne
type: docs
weight: 5250
url: /fr/net/aspose.html.toolkit.markdown.syntax/multilinecontainerblocksyntaxnode/
---
## MultiLineContainerBlockSyntaxNode class

Implémentation de base d'un nœud de syntaxe de bloc conteneur multiligne

```csharp
public abstract class MultiLineContainerBlockSyntaxNode : ContainerBlockSyntaxNode
```

## Propriétés

| Nom | La description |
| --- | --- |
| [FirstChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) { get; } | Obtenez le premier enfant. |
| [LastChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) { get; } | Obtenez le dernier enfant. |
| [NextSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) { get; } | Obtenez le frère suivant. |
| [Parent](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) { get; } | Obtenir le nœud parent. |
| [PreviousSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) { get; } | Obtenir le frère précédent. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Accept](../../aspose.html.toolkit.markdown.syntax/blocksyntaxnode/accept/)(MarkdownSyntaxVisitor) | Définit l'interface pour accepter le visiteur. |
| [AppendChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | Ajouter un nœud enfant. |
| [ChildNodes](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | Obtenez la collection de nœuds enfants. |
| [GetLeadingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | Obtenez les principales anecdotes. |
| [GetLinesLeadingTrivia](../../aspose.html.toolkit.markdown.syntax/multilinecontainerblocksyntaxnode/getlinesleadingtrivia/)() | Définit l'interface pour obtenir des lignes menant à des anecdotes. |
| [GetSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | Obtenir l'arbre de syntaxe. |
| [GetTrailingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | Obtenez le trivia de fin. |
| [InsertBefore](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Insérer avant le nœud. |
| [RemoveChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | Supprimer l'enfant. |
| [ReplaceChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Remplacer le nœud enfant. |
| override [ToString](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/tostring/)() | Remplacer la méthode ToString. |
| virtual [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | Écrire dans MarkdownTextWriter. |
| [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | Écrire des nœuds dans le rédacteur de texte. |

### Voir également

* class [ContainerBlockSyntaxNode](../containerblocksyntaxnode/)
* espace de noms [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* Assemblée [Aspose.HTML](../../)


