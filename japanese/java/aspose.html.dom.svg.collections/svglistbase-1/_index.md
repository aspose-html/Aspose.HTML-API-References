---
title: "SVGListBaseT クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.svg.collections.SVGListBase1T クラス。このインターフェイスはすべての SVG リストの基本リストを定義します"
type: docs

url: /ja/java/com.aspose.html.dom.svg.collections/svglistbase-1/
---
## SVGListBase&lt;T&gt; class

このインターフェイスは、すべての SVG リストの基本リストを定義します。

```java
public abstract class SVGListBase<T> : SVGValueType, IEnumerable<T>
```

| パラメータ | 説明 |
| --- | --- |
| T | リストに格納される項目の型。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
[getItem]
[setItem] Returns the indexth item in the list. |
| [getLength](../../com.aspose.html.dom.svg.collections/svglistbase-1/length/) リスト内の項目数。 |
| [getNumberOfItems](../../com.aspose.html.dom.svg.collections/svglistbase-1/numberofitems/) リスト内の項目数。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [appendItem](../../com.aspose.html.dom.svg.collections/svglistbase-1/appenditem/)(T) | リストの末尾に新しい項目を挿入します。 |
| [clear](../../com.aspose.html.dom.svg.collections/svglistbase-1/clear/)() | リストから既存のすべての項目をクリアし、結果として空のリストになります。 |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | アンマネージドおよび（オプションで）マネージドリソースを解放します。 |
| [getEnumerator](../../com.aspose.html.dom.svg.collections/svglistbase-1/getenumerator/)() | 列挙子を取得します。 |
| [getItem](../../com.aspose.html.dom.svg.collections/svglistbase-1/getitem/)(ulong) | リストから指定された項目を返します。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [initialize](../../com.aspose.html.dom.svg.collections/svglistbase-1/initialize/)(T) | リストから既存のすべての項目をクリアし、パラメータで指定された単一の項目を保持するようにリストを再初期化します。 |
| [insertItemBefore](../../com.aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/)(T, ulong) | 指定された位置に新しい項目をリストに挿入します。最初の項目は番号 0 です。 |
| [removeItem](../../com.aspose.html.dom.svg.collections/svglistbase-1/removeitem/)(ulong) | リストから既存の項目を削除します。 |
| [replaceItem](../../com.aspose.html.dom.svg.collections/svglistbase-1/replaceitem/)(T, ulong) | リスト内の既存の項目を新しい項目に置き換えます。 |

### 関連項目

* class [SVGValueType](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/)
* package [com.aspose.html.dom.svg.collections](../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../)
