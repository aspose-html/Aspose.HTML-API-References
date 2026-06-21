---
title: "IStyleSheetList インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.css.IStyleSheetList インターフェイス。StyleSheetList インターフェイスは CSSStyleSheet オブジェクトのリストを表します。このオブジェクトのインスタンスは Document.styleSheets によって返されます。"
type: docs

url: /ja/java/com.aspose.html.dom.css/istylesheetlist/
---
## IStyleSheetList interface

StyleSheetList インターフェイスは、[`CSSStyleSheet`](../icssstylesheet/) オブジェクトのリストを表します。このオブジェクトのインスタンスは [`Document.styleSheets`](../../com.aspose.html.dom/document/stylesheets/) によって返されます。

オブジェクトがサポートするプロパティインデックスは、コレクションが表す CSS スタイルシート数の 0 から（数 - 1）までの範囲の数値です。そのような CSS スタイルシートが存在しない場合、サポートされるプロパティインデックスはありません。

```java
public interface IStyleSheetList : IEnumerable<ICSSStyleSheet>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/istylesheetlist/item/) item(index) メソッドは、コレクション内の index 番目の [`CSS style sheet`](../icssstylesheet/) を返す必要があります。コレクションに index 番目のオブジェクトが存在しない場合、メソッドは null を返す必要があります。 |
| [getLength](../../com.aspose.html.dom.css/istylesheetlist/length/) length 属性は、コレクションが表す CSS スタイルシートの数を返す必要があります。有効な子スタイルシートインデックスの範囲は 0 から length-1（含む）です。 |

## 備考

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参照

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # stylesheetlist](https://drafts.csswg.org/cssom/#stylesheetlist) – The CSSOM definition.

### 関連項目

* interface [ICSSStyleSheet](../icssstylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
