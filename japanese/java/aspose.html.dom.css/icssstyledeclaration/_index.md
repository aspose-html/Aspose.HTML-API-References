---
title: "ICSSStyleDeclaration インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.css.ICSSStyleDeclaration インターフェイス。CSSStyleDeclaration インターフェイスは、CSS 宣言ブロックであるオブジェクトを表し、スタイル情報やさまざまなスタイル関連のメソッドおよびプロパティを公開します。"
type: docs

url: /ja/java/com.aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

CSSStyleDeclaration インターフェイスは、CSS 宣言ブロックであるオブジェクトを表し、スタイル情報およびさまざまなスタイル関連のメソッドやプロパティを公開します。

CSSStyleDeclaration オブジェクトは、3 つの異なる API を使用して公開できます：

単一要素のインラインスタイルを扱う HTMLElement.style を介して。[`CSSStyleSheet`](../icssstylesheet/) API を介して。例えば、document.styleSheets[0].cssRules[0].style は、ドキュメントの最初のスタイルシート内の最初の CSS ルールに対する `CSSStyleDeclaration` オブジェクトを返します。Window.getComputedStyle() を介して、`CSSStyleDeclaration` オブジェクトを読み取り専用インターフェイスとして公開します。

```java
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<String>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
[getCSSText]
[setCSSText] The parsable textual representation of the declaration block (excluding the surrounding curly braces). Setting this attribute will result in the parsing of the new value and resetting of all the properties in the declaration block including the removal or addition of properties. |
| [getItem](../../com.aspose.html.dom.css/icssstyledeclaration/item/) この宣言ブロックで明示的に設定されたプロパティを取得するために使用されます。このメソッドで取得されるプロパティの順序は、設定された順序と同じである必要はありません。このメソッドは、この宣言ブロック内のすべてのプロパティを反復処理するために使用できます。 |
| [getLength](../../com.aspose.html.dom.css/icssstyledeclaration/length/) 読み取り専用プロパティは、この CSS 宣言ブロックで明示的に設定されたプロパティの数を整数で返します。有効なインデックスの範囲は 0 から length-1（含む）です。 |
| [getParentRule](../../com.aspose.html.dom.css/icssstyledeclaration/parentrule/) CSSStyleDeclaration.parentRule 読み取り専用プロパティは、このスタイルブロックの親である CSSRule を返します。例えば、CSS セレクタのスタイルを表す [`CSSStyleRule`](../icssstylerule/) です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getPropertyCSSValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(String) | この宣言ブロック内で明示的に設定された場合、CSS プロパティの値のオブジェクト表現を取得するために使用されます。プロパティがショートハンドの場合、このメソッドは null を返します。ショートハンドプロパティの値は、getPropertyValue および setProperty メソッドを使用して文字列としてのみアクセス・変更できます。 |
| [getPropertyPriority](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(String) | この宣言ブロックで明示的に設定された場合、CSS プロパティの優先度（例: \"important\" 修飾子）を取得するために使用されます。 |
| [getPropertyValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(String) | CSSStyleDeclaration.getPropertyValue() メソッドインターフェイスは、指定された CSS プロパティの値を含む文字列を返します。 |
| [removeProperty](../../com.aspose.html.dom.css/icssstyledeclaration/removeproperty/)(String) | CSSStyleDeclaration.removeProperty() メソッドインターフェイスは、CSS スタイル宣言オブジェクトからプロパティを削除します。 |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(String, String) | CSSStyleDeclaration.setProperty() メソッドインターフェイスは、この宣言ブロック内でデフォルトの優先度でプロパティ値を設定するために使用されます。デフォルトの優先度は \"important\" ではなく、つまり String.Empty です。 |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(String, String, String) | CSSStyleDeclaration.setProperty() メソッドインターフェイスは、この宣言ブロック内でデフォルトの優先度でプロパティ値を設定するために使用されます。デフォルトの優先度は \"important\" ではなく、つまり String.Empty です。 |

## Remarks

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参照

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstyledeclaration](https://drafts.csswg.org/cssom/#cssstyledeclaration) – The CSSOM definition.

### 関連項目

* interface [ICSS2Properties](../icss2properties/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
