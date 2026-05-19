---
title: "ITreeWalker.CurrentNode"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ITreeWalker プロパティ。TreeWalker が現在位置しているノードです。DOM ツリーの変更により、現在のノードが TreeWalker に関連付けられたフィルタで受け入れられなくなることがあります。currentNode は、ルートノードで指定されたサブツリー内にあるかどうか、またはフィルタと whatToShow フラグで受け入れられるかどうかに関わらず、任意のノードに明示的に設定することもできます。さらに、要求された方向でフィルタを適用することにより、currentNode が現在のビューに含まれていなくても、currentNode を基準にしたトラバーサルが続行されます。トラバーサルが不可能な場合、currentNode は変更されません。"
type: docs

url: /ja/java/com.aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

TreeWalker が現在位置しているノードです。DOM ツリーの変更により、現在のノードが TreeWalker に関連付けられたフィルタで受け入れられなくなることがあります。currentNode は、ルートノードで指定されたサブツリー内にあるかどうか、またはフィルタと whatToShow フラグで受け入れられるかどうかに関わらず、任意のノードに明示的に設定できます。さらに、要求された方向でフィルタを適用することにより、currentNode が現在のビューに含まれていなくても、currentNode を基準にしたトラバーサルが続行されます。トラバーサルが不可能な場合、currentNode は変更されません。

```java
public Node CurrentNode { get; set; }
```

### Property Value

現在のノード。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: currentNode を null に設定しようとした場合に発生します。 |

### 関連項目

* class [Node](../../../com.aspose.html.dom/node/)
* interface [ITreeWalker](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
