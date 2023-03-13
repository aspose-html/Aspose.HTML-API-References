---
title: MarkdownSyntaxFactory.InlineLink
second_title: Référence de l'API Aspose.HTML pour .NET
description: MarkdownSyntaxFactory méthode. Crée des objets à laide de InlineLinkSyntax.CreateInstance.
type: docs
weight: 220
url: /fr/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inlinelink/
---
## InlineLink(MarkdownSyntaxToken, MarkdownSyntaxToken, MarkdownSyntaxToken, LinkDestinationSyntaxNode, LinkTitleSyntaxNode, MarkdownSyntaxToken) {#inlinelink}

Crée des objets à l'aide de InlineLinkSyntax.CreateInstance.

```csharp
public InlineLinkSyntaxNode InlineLink(MarkdownSyntaxToken contentOpening, 
    MarkdownSyntaxToken contentClosing, MarkdownSyntaxToken declarationOpening, 
    LinkDestinationSyntaxNode destination, LinkTitleSyntaxNode title, 
    MarkdownSyntaxToken declarationClosing)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| contentOpening | MarkdownSyntaxToken | Le contenuOuverture. |
| contentClosing | MarkdownSyntaxToken | Le contenuClosing. |
| declarationOpening | MarkdownSyntaxToken | La déclarationOuverture. |
| destination | LinkDestinationSyntaxNode | La destination. |
| title | LinkTitleSyntaxNode | Le titre. |
| declarationClosing | MarkdownSyntaxToken | La déclarationClosing. |

### Return_Value

La syntaxe InlineLink.

### Voir également

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxToken](../../markdownsyntaxtoken/)
* class [LinkDestinationSyntaxNode](../../linkdestinationsyntaxnode/)
* class [LinkTitleSyntaxNode](../../linktitlesyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* espace de noms [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* Assemblée [Aspose.HTML](../../../)

---

## InlineLink(string, string, string) {#inlinelink_1}

Crée InlineLink.

```csharp
public InlineLinkSyntaxNode InlineLink(string text, string destination, string title)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| text | String | Le texte du lien. |
| destination | String | La destination de la chaîne. |
| title | String | Le titre de la chaîne. |

### Return_Value

La syntaxe LinkReferenceDefinitionSyntax.

### Voir également

* class [InlineLinkSyntaxNode](../../inlinelinksyntaxnode/)
* class [MarkdownSyntaxFactory](../)
* espace de noms [Aspose.Html.Toolkit.Markdown.Syntax](../../markdownsyntaxfactory/)
* Assemblée [Aspose.HTML](../../../)


