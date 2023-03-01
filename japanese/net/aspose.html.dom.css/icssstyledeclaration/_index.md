---
title: Interface ICSSStyleDeclaration
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Css.ICSSStyleDeclaration インターフェース. CSSStyleDeclaration インターフェイスは単一の CSS 宣言ブロックを表しますこのインターフェイスを使用して現在ブロックに設定されているスタイル プロパティを特定したりブロック内でスタイル プロパティを明示的に設定したりできます
type: docs
weight: 490
url: /ja/net/aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

CSSStyleDeclaration インターフェイスは、単一の CSS 宣言ブロックを表します。このインターフェイスを使用して、現在ブロックに設定されているスタイル プロパティを特定したり、ブロック内でスタイル プロパティを明示的に設定したりできます。

```csharp
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<string>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CSSText](../../aspose.html.dom.css/icssstyledeclaration/csstext/) { get; set; } | 宣言ブロックの解析可能なテキスト表現 (周囲の中括弧を除く)。この属性を設定すると、新しい値が解析され、プロパティの削除または追加を含む宣言ブロック内のすべてのプロパティがリセットされます。 |
| [Item](../../aspose.html.dom.css/icssstyledeclaration/item/) { get; } | この宣言ブロックで明示的に設定されたプロパティを取得するために使用されます。このメソッドを使用して取得されたプロパティの順序は、設定された順序である必要はありません。このメソッドを使用して、この宣言ブロック内のすべてのプロパティを反復処理できます。 |
| [Length](../../aspose.html.dom.css/icssstyledeclaration/length/) { get; } | この宣言ブロックで明示的に設定されたプロパティの数。有効なインデックスの範囲は、0 から長さ 1 までです。 |
| [ParentRule](../../aspose.html.dom.css/icssstyledeclaration/parentrule/) { get; } | この宣言ブロックを含む CSS ルール、またはこの CSSStyleDeclaration が CSSRule に関連付けられていない場合は null。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetPropertyCSSValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(string) | この宣言ブロック内で明示的に設定されている場合、CSS プロパティの値のオブジェクト表現を取得するために使用されます。プロパティが省略形のプロパティの場合、このメソッドは null を返します。 getPropertyValue および setProperty メソッドを使用して、省略形のプロパティ値にのみアクセスし、文字列として変更できます。 |
| [GetPropertyPriority](../../aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(string) | プロパティがこの宣言ブロックで明示的に設定されている場合、CSS プロパティ (「重要な」修飾子など) の優先度を取得するために使用されます。 |
| [GetPropertyValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(string) | この宣言ブロック内で明示的に設定されている場合、CSS プロパティの値を取得するために使用されます。 |
| [RemoveProperty](../../aspose.html.dom.css/icssstyledeclaration/removeproperty/)(string) | この宣言ブロック内で明示的に設定されている場合、CSS プロパティを削除するために使用されます。 |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(string, string) | この宣言ブロック内でデフォルト優先度のプロパティ値を設定するために使用されます。 デフォルト優先度は「重要」ではありません。つまり、String.Empty |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(string, string, string) | この宣言ブロック内でプロパティ値と優先順位を設定するために使用されます。 |

### 関連項目

* interface [ICSS2Properties](../icss2properties/)
* 名前空間 [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* 組み立て [Aspose.HTML](../../)


