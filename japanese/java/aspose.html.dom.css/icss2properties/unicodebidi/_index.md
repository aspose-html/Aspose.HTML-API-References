---
title: "ICSS2Properties.UnicodeBidi"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICSS2Properties プロパティ。このプロパティの値は以下の意味を持ちます。"
type: docs

url: /ja/java/com.aspose.html.dom.css/icss2properties/unicodebidi/
---
## ICSS2Properties.UnicodeBidi property

このプロパティの値は以下の意味を持ちます：

normal - 要素は双方向アルゴリズムに対して追加の埋め込みレベルを開きません。インラインレベルの要素では、暗黙の再順序付けが要素境界を越えて機能します。embed - 要素がインラインレベルの場合、この値は双方向アルゴリズムに対して追加の埋め込みレベルを開きます。この埋め込みレベルの方向は ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction) プロパティで指定されます。要素内部では再順序付けが暗黙的に行われます。これは要素の先頭に LRE (U+202A; 'direction: ltr' 用) または RLE (U+202B; 'direction: rtl' 用) を、末尾に PDF (U+202C) を追加することに相当します。bidi-override - 要素がインラインレベル、またはインライン要素のみを含むブロックレベル要素の場合、これによりオーバーライドが作成されます。これは要素内部の再順序付けが ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction) プロパティに従って厳密に順序付けられ、双方向アルゴリズムの暗黙的な部分が無視されることを意味します。これは要素の先頭に LRO (U+202D; 'direction: ltr' 用) または RLO (U+202E; 'direction: rtl' 用) を、末尾に PDF (U+202C) を追加することに相当します。

```java
public String UnicodeBidi { get; set; }
```

### 戻り値

unicode-bidi プロパティ

### 関連項目

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
