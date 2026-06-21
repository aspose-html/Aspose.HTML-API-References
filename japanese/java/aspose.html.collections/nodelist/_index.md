---
title: "NodeList クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.collections.NodeList クラス。NodeList は、コレクションがどのように実装されるかを定義または制約せずに、ノードの順序付けられたコレクションの抽象化を提供します。"
type: docs

url: /ja/java/com.aspose.html.collections/nodelist/
---
## NodeList class

NodeList は、ノードの順序付けされたコレクションの抽象化を提供しますが、このコレクションがどのように実装されるかは定義または制約しません。

```java
public abstract class NodeList : DOMObject, IEnumerable<Node>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| 抽象 [getItem](../../com.aspose.html.collections/nodelist/item/) メソッドはコレクション内のインデックス番目の項目を返します。インデックスがリスト内のノード数以上の場合、null を返します。 |
| 抽象 [getLength](../../com.aspose.html.collections/nodelist/length/) リスト内のノード数です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [GetEnumerator](../../com.aspose.html.collections/nodelist/getenumerator/)() | コレクションを反復処理する列挙子を返します。 |
| [getPlatformType](../../com.aspose.html.collections/nodelist/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの Type を取得するために使用されます。 |

### 関連項目

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* class [Node](../../com.aspose.html.dom/node/)
* package [com.aspose.html.collections](../../com.aspose.html.collections/)
* package [Aspose.HTML](../../)
