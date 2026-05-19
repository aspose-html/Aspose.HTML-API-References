---
title: "IDocumentCSS インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.css.IDocumentCSS インターフェイス。このインターフェイスは、CSS ビューを持つドキュメントを表します。"
type: docs

url: /ja/java/com.aspose.html.dom.css/idocumentcss/
---
## IDocumentCSS interface

このインターフェイスは、CSS ビューを持つドキュメントを表します。

getOverrideStyle メソッドは、DOM 作成者がドキュメントに明示的にリンクされたスタイルシートやスタイルシート内の要素のインラインスタイルを変更せずに、要素のスタイルを即座に変更できる仕組みを提供します。このスタイルシートはカスケードアルゴリズムで作者スタイルシートの後に適用され、オーバーライドスタイルシートと呼ばれます。オーバーライドスタイルシートは作者スタイルシートよりも優先されます。\"!important\" 宣言は通常の宣言よりも依然として優先されます。オーバーライド、作者、ユーザースタイルシートはすべて \"!important\" 宣言を含むことができます。ユーザーの \"!important\" ルールはオーバーライドおよび作者の \"!important\" ルールの両方よりも優先され、オーバーライドの \"!important\" ルールは作者の \"!important\" ルールよりも優先されます。

DocumentCSS インターフェイスのインスタンスは、Document インターフェイスのインスタンスに対してバインディング固有のキャストメソッドを使用することで取得できることが期待されます。

こちらも参照してください: [Document Object Model (DOM) Level 2 Style Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113)。

```java
public interface IDocumentCSS : IDocumentStyle
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getOverrideStyle](../../com.aspose.html.dom.css/idocumentcss/getoverridestyle/)(Element, String) | このメソッドは、指定された要素および指定された疑似要素のオーバーライドスタイル宣言を取得するために使用されます。 |

### 関連項目

* interface [IDocumentStyle](../idocumentstyle/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
