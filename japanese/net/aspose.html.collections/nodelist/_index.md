---
title: Class NodeList
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Collections.NodeList クラス. NodeList はこのコレクションの実装方法を定義または制約することなく順序付けられたノードのコレクションの抽象化を提供します
type: docs
weight: 50
url: /ja/net/aspose.html.collections/nodelist/
---
## NodeList class

NodeList は、このコレクションの実装方法を定義または制約することなく、順序付けられたノードのコレクションの抽象化を提供します。

```csharp
public abstract class NodeList : DOMObject, IEnumerable<Node>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| abstract [Item](../../aspose.html.collections/nodelist/item/) { get; } | メソッドは、コレクション内の index 番目のアイテムを返します。 index がリスト内のノード数以上の場合、null が返されます。 |
| abstract [Length](../../aspose.html.collections/nodelist/length/) { get; } | リスト内のノード数。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [GetEnumerator](../../aspose.html.collections/nodelist/getenumerator/)() | コレクションを反復処理する列挙子を返します。 |
| override [GetPlatformType](../../aspose.html.collections/nodelist/getplatformtype/)() | このメソッドは、ECMAScript オブジェクトを取得するために使用されますType. |

### 関連項目

* class [DOMObject](../../aspose.html.dom/domobject/)
* class [Node](../../aspose.html.dom/node/)
* 名前空間 [Aspose.Html.Collections](../../aspose.html.collections/)
* 組み立て [Aspose.HTML](../../)


