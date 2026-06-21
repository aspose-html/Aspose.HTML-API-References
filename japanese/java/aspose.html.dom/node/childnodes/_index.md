---
title: "Node.ChildNodes"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Node プロパティ。Node インターフェイスの読み取り専用 childNodes プロパティは、指定された要素の子ノードのライブ NodeList を返します。最初の子ノードにはインデックス 0 が割り当てられます。子ノードには要素、テキスト、コメントが含まれます。"
type: docs

url: /ja/java/com.aspose.html.dom/node/childnodes/
---
## Node.ChildNodes property

Node インターフェイスの読み取り専用 childNodes プロパティは、指定された要素の子ノードのライブ [`NodeList`](../../../com.aspose.html.collections/nodelist/) を返します。最初の子ノードにはインデックス 0 が割り当てられます。子ノードには要素、テキスト、コメントが含まれます。

注: ライブな [`NodeList`](../../../com.aspose.html.collections/nodelist/) とは、新しい子が追加または削除されるたびにその内容が変化することを意味します。

```java
public NodeList ChildNodes { get; }
```

### Property Value

ノードの子を含むライブ [`NodeList`](../../../com.aspose.html.collections/nodelist/)。

注: childNodes を複数回呼び出すと、同じ [`NodeList`](../../../com.aspose.html.collections/nodelist/) が返されます。

## 備考

参照:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-childnodes](https://dom.spec.whatwg.org/#dom-node-childnodes).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### 関連項目

* class [NodeList](../../../com.aspose.html.collections/nodelist/)
* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
