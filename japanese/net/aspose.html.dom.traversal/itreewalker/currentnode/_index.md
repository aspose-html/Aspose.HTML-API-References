---
title: ITreeWalker.CurrentNode
second_title: Aspose.HTML for .NET API リファレンス
description: ITreeWalker 財産. TreeWalker が現在配置されているノード DOM ツリーの変更により現在のノードが TreeWalker の関連フィルターによって受け入れられなくなる可能性があります currentNode は任意のノードに明示的に設定することもできます ルート ノードによって指定されたサブツリー内にあるかフィルターおよび whatToShow フラグによって受け入れられます要求された方向にフィルタを適用することにより現在のビュー の一部でなくても currentNode に対して相対的にさらにトラバーサルが発生します traversal が不可能な場合currentNode は変更されません
type: docs
weight: 10
url: /ja/net/aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

TreeWalker が現在配置されているノード。 DOM ツリーの変更により、現在のノードが TreeWalker の関連フィルターによって受け入れられなくなる可能性があります。 currentNode は、任意のノードに明示的に設定することもできます。 ルート ノードによって指定されたサブツリー内にあるか、フィルターおよび whatToShow フラグによって受け入れられます。要求された方向にフィルタを適用することにより、現在のビュー の一部でなくても、 currentNode に対して相対的にさらにトラバーサルが発生します。 traversal が不可能な場合、currentNode は変更されません。

```csharp
public Node CurrentNode { get; set; }
```

### プロパティ値

現在のノード。

### 例外

| 例外 | 調子 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: set currentNode を null にしようとした場合に発生します。 |

### 関連項目

* class [Node](../../../aspose.html.dom/node/)
* interface [ITreeWalker](../)
* 名前空間 [Aspose.Html.Dom.Traversal](../../itreewalker/)
* 組み立て [Aspose.HTML](../../../)


