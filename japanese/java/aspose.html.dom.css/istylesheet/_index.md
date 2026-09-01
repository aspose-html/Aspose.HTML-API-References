---
title: "IStyleSheet インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.css.IStyleSheet インターフェイス。StyleSheet インターフェイスは、あらゆるタイプのスタイルシートの抽象基底インターフェイスです。構造化ドキュメントに関連付けられた単一のスタイルシートを表します。HTML では、StyleSheet インターフェイスは HTML LINK 要素を介して含まれる外部スタイルシートまたはインライン STYLE 要素のいずれかを表します。XML では、このインターフェイスはスタイルシート処理命令を介して含まれる外部スタイルシートを表します。CSS スタイルシートは、さらに専門化された CSSStyleSheet インターフェイスを実装します。"
type: docs

url: /ja/java/com.aspose.html.dom.css/istylesheet/
---
## IStyleSheet interface

StyleSheet インターフェイスは、あらゆるタイプのスタイルシートの抽象基底インターフェイスです。構造化ドキュメントに関連付けられた単一のスタイルシートを表します。HTML では、StyleSheet インターフェイスは HTML LINK 要素を介して含まれる外部スタイルシートまたはインライン STYLE 要素のいずれかを表します。XML では、このインターフェイスはスタイルシート処理命令を介して含まれる外部スタイルシートを表します。CSS スタイルシートは、さらに専門化された [`CSSStyleSheet`](../icssstylesheet/) インターフェイスを実装します。

また、[CSS Object Model (CSSOM) # StyleSheet Interface Specification](https://drafts.csswg.org/cssom/#the-stylesheet-interface) も参照してください。

```java
public interface IStyleSheet
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
[getDisabled]
[setDisabled] The disabled property of the `StyleSheet` interface determines whether the style sheet is prevented from applying to the document. |
| [getHref](../../com.aspose.html.dom.css/istylesheet/href/) href プロパティは `StyleSheet` インターフェイスのスタイルシートの場所を返します。 |
| [getMedia](../../com.aspose.html.dom.css/istylesheet/media/) media プロパティは `StyleSheet` インターフェイスのスタイル情報の対象メディアを指定します。これは読み取り専用の配列のような [`MediaList`](../imedialist/) オブジェクトで、deleteMedium() で削除し、appendMedium() で追加できます。 |
| [getOwnerNode](../../com.aspose.html.dom.css/istylesheet/ownernode/) このスタイルシートをドキュメントに関連付けるノードです。HTML の場合、対応する LINK または STYLE 要素になることがあります。XML の場合、リンク処理命令になることがあります。他のスタイルシートによってインクルードされているスタイルシートの場合、この属性の値は null です。 |
| [getParentStyleSheet](../../com.aspose.html.dom.css/istylesheet/parentstylesheet/) スタイルシートのインクルード概念をサポートするスタイルシート言語では、この属性はインクルード元のスタイルシートを表します（存在する場合）。スタイルシートがトップレベルのスタイルシートであるか、インクルードをサポートしない言語の場合、この属性の値は null です。 |
| [getTitle](../../com.aspose.html.dom.css/istylesheet/title/) title プロパティは `StyleSheet` インターフェイスの現在のスタイルシートの助言的タイトルを返します。 |
| [getType](../../com.aspose.html.dom.css/istylesheet/type/) これはこのスタイルシートのスタイルシート言語を指定します。スタイルシート言語はコンテンツタイプ（例：\"text/css\"）として指定されます。 |

## 備考

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参照

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[The StyleSheet Interface](https://drafts.csswg.org/cssom/#the-stylesheet-interface) – The official CSSOM definition.

### 関連項目

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
