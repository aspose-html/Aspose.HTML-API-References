---
title: Class NamedNodeMap
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Collections.NamedNodeMap クラス. 名前でアクセスできる属性のコレクションを表します
type: docs
weight: 40
url: /ja/net/aspose.html.collections/namednodemap/
---
## NamedNodeMap class

名前でアクセスできる属性のコレクションを表します。

```csharp
public class NamedNodeMap : DOMObject, IDisposable, IEnumerable<Attr>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Item](../../aspose.html.collections/namednodemap/item/) { get; } | マップのインデックス番目のアイテムを返します。 index がこのマップ内のノード数以上の場合、null が返されます。 (2 indexers) |
| [Length](../../aspose.html.collections/namednodemap/length/) { get; } | このマップ内のノードの数. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetEnumerator](../../aspose.html.collections/namednodemap/getenumerator/)() | コレクションを反復処理する列挙子を返します。 |
| [GetNamedItem](../../aspose.html.collections/namednodemap/getnameditem/)(string) | 名前で指定されたノードを取得します。 |
| [GetNamedItemNS](../../aspose.html.collections/namednodemap/getnameditemns/)(string, string) | ローカル名と名前空間 URI で指定されたノードを取得します。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | このメソッドは、ECMAScript オブジェクトを取得するために使用されますType. |
| [RemoveNamedItem](../../aspose.html.collections/namednodemap/removenameditem/)(string) | 名前で指定されたノードを削除します。 |
| [RemoveNamedItemNS](../../aspose.html.collections/namednodemap/removenameditemns/)(string, string) | ローカル名と名前空間 URI で指定されたノードを削除します。 |
| [SetNamedItem](../../aspose.html.collections/namednodemap/setnameditem/)(Attr) | nodeName 属性を使用してノードを追加します。その名前のノードがこのマップに既に存在する場合は、新しいノードに置き換えられます。ノードを単独で交換しても効果はありません. |
| [SetNamedItemNS](../../aspose.html.collections/namednodemap/setnameditemns/)(Attr) | namespaceURI と localName を使用してノードを追加します。その名前空間 URI とそのローカル名を持つノードがこのマップに既に存在する場合、それは新しいものに置き換えられます。ノードを単独で交換しても効果はありません. |

### 関連項目

* class [DOMObject](../../aspose.html.dom/domobject/)
* class [Attr](../../aspose.html.dom/attr/)
* 名前空間 [Aspose.Html.Collections](../../aspose.html.collections/)
* 組み立て [Aspose.HTML](../../)


