---
title: inline_link method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 230
url: /python-net/aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory/inline_link/
is_root: false
---

## inline_link {#str-str-str}

Creates InlineLink.


### Returns 


The LinkReferenceDefinitionSyntax.


```python
def inline_link(self, text, destination, title):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| text | str | The link text. |
| destination | str | The string destination. |
| title | str | The string title. |


## inline_link {#aspose.html.toolkit.markdown.syntax.MarkdownSyntaxToken-aspose.html.toolkit.markdown.syntax.MarkdownSyntaxToken-aspose.html.toolkit.markdown.syntax.MarkdownSyntaxToken-aspose.html.toolkit.markdown.syntax.LinkDestinationSyntaxNode-aspose.html.toolkit.markdown.syntax.LinkTitleSyntaxNode-aspose.html.toolkit.markdown.syntax.MarkdownSyntaxToken}

Creates [`InlineLinkSyntaxNode`](/html/python-net/aspose.html.toolkit.markdown.syntax/inlinelinksyntaxnode).


### Returns 


The InlineLinkSyntax.


```python
def inline_link(self, content_opening, content_closing, declaration_opening, destination, title, declaration_closing):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| content_opening | [`MarkdownSyntaxToken`](/html/python-net/aspose.html.toolkit.markdown.syntax/markdownsyntaxtoken) | The contentOpening. |
| content_closing | [`MarkdownSyntaxToken`](/html/python-net/aspose.html.toolkit.markdown.syntax/markdownsyntaxtoken) | The contentClosing. |
| declaration_opening | [`MarkdownSyntaxToken`](/html/python-net/aspose.html.toolkit.markdown.syntax/markdownsyntaxtoken) | The declarationOpening. |
| destination | [`LinkDestinationSyntaxNode`](/html/python-net/aspose.html.toolkit.markdown.syntax/linkdestinationsyntaxnode) | The destination. |
| title | [`LinkTitleSyntaxNode`](/html/python-net/aspose.html.toolkit.markdown.syntax/linktitlesyntaxnode) | The title. |
| declaration_closing | [`MarkdownSyntaxToken`](/html/python-net/aspose.html.toolkit.markdown.syntax/markdownsyntaxtoken) | The declarationClosing. |



### See Also
* module [`aspose.html.toolkit.markdown.syntax`](../../)
* class [`InlineLinkSyntaxNode`](/html/python-net/aspose.html.toolkit.markdown.syntax/inlinelinksyntaxnode)
* class [`MarkdownSyntaxFactory`](/html/python-net/aspose.html.toolkit.markdown.syntax/markdownsyntaxfactory)
