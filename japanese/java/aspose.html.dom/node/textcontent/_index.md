---
title: "Node.TextContent"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Node プロパティ。Node インターフェイスの textContent プロパティは、ノードおよびその子孫のテキストコンテンツを表します"
type: docs

url: /ja/java/com.aspose.html.dom/node/textcontent/
---
## Node.TextContent property

[`Node`](../) インターフェイスの textContent プロパティは、ノードおよびその子孫のテキストコンテンツを表します。

```java
public String TextContent { get; set; }
```

### Property Value

文字列、または null。値は状況に依存します：

ノードがドキュメントまたはdoctypeの場合、textContentはnullを返します。注: ドキュメント全体のテキストとCDATAデータをすべて取得するには、document.documentElement.textContentを使用します。ノードがCDATAセクション、コメント、処理命令、またはテキストノードの場合、textContentはノード内のテキストを返すか、設定します。つまり、[`Node.nodeValue`](../nodevalue/)です。他のノードタイプの場合、textContentはコメントや処理命令を除いたすべての子ノードのtextContentを連結して返します。

## Remarks

参照:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-textcontent](https://dom.spec.whatwg.org/#dom-node-textcontent).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### 関連項目

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
