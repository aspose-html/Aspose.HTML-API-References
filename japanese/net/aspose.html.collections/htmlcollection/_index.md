---
title: Class HTMLCollection
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Collections.HTMLCollection クラス. HTMLCollectionの一般的なコレクションを表しますElement.
type: docs
weight: 30
url: /ja/net/aspose.html.collections/htmlcollection/
---
## HTMLCollection class

`HTMLCollection`の一般的なコレクションを表します[`Element`](../../aspose.html.dom/element/).

```csharp
public abstract class HTMLCollection : DOMObject, IEnumerable<Element>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| abstract [Item](../../aspose.html.collections/htmlcollection/item/) { get; } | コレクション内の index 番目のアイテムを返します。 index がリスト内のノード数以上の場合、null が返されます。 |
| abstract [Length](../../aspose.html.collections/htmlcollection/length/) { get; } | リスト内のノード数。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [GetEnumerator](../../aspose.html.collections/htmlcollection/getenumerator/)() | 列挙子を取得します。 |
| override [GetPlatformType](../../aspose.html.collections/htmlcollection/getplatformtype/)() | このメソッドは、ECMAScript オブジェクトを取得するために使用されますType. |
| [NamedItem](../../aspose.html.collections/htmlcollection/nameditem/)(string) | 指定された名前と一致するコレクション内のアイテムを返します. |

### 関連項目

* class [DOMObject](../../aspose.html.dom/domobject/)
* class [Element](../../aspose.html.dom/element/)
* 名前空間 [Aspose.Html.Collections](../../aspose.html.collections/)
* 組み立て [Aspose.HTML](../../)


