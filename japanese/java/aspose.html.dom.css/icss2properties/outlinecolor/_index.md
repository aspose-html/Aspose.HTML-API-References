---
title: "このプロパティの値は以下の意味があります："
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICSS2Properties プロパティ。outline プロパティで作成されたアウトラインはボックスの上に描画されます。つまり、アウトラインは常に最上位にあり、ボックスや他のボックスの位置やサイズに影響しません。そのため、アウトラインの表示や非表示によりレイアウトの再計算（リフロー）は発生しません。"
type: docs

url: /ja/java/com.aspose.html.dom.css/icss2properties/outlinecolor/
---
## ICSS2Properties.OutlineColor property

outline プロパティで作成されたアウトラインはボックスの"上"に描画されます。つまり、アウトラインは常に最上位にあり、ボックスや他のボックスの位置やサイズに影響しません。そのため、アウトラインの表示や非表示によりリフローは発生しません。

```java
public String OutlineColor { get; set; }
```

### 戻り値

normal - 要素は双方向アルゴリズムに対して追加の埋め込みレベルを開きません。インラインレベルの要素の場合、暗黙の再配置は要素境界を越えて機能します。embed - 要素がインラインレベルの場合、この値は双方向アルゴリズムに対して追加の埋め込みレベルを開きます。この埋め込みレベルの方向は ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction) プロパティで指定されます。要素内部では再配置は暗黙的に行われます。これは要素の先頭に LRE (U+202A; 'direction: ltr' 用) または RLE (U+202B; 'direction: rtl' 用) を、末尾に PDF (U+202C) を追加することに相当します。bidi-override - 要素がインラインレベル、またはインライン要素のみを含むブロックレベル要素の場合、これによりオーバーライドが作成されます。つまり要素内部の再配置は ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction) プロパティに従って厳密に順序通りに行われ、双方向アルゴリズムの暗黙的部分は無視されます。これは要素の先頭に LRO (U+202D; 'direction: ltr' 用) または RLO (U+202E; 'direction: rtl' 用) を、末尾に PDF (U+202C) を追加することに相当します。

### 関連項目

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
