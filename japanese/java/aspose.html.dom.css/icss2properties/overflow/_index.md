---
title: "ICSS2Properties.Overflow"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICSS2Properties プロパティ。このプロパティは、ブロックレベル要素のコンテンツが、コンテンツの包含ブロックとして機能する要素のボックスをオーバーフローしたときにクリップされるかどうかを指定します。値は次の意味を持ちます。"
type: docs

url: /ja/java/com.aspose.html.dom.css/icss2properties/overflow/
---
## ICSS2Properties.Overflow property

このプロパティは、ブロックレベル要素のコンテンツが要素のボックス（コンテンツの包含ブロックとして機能）をオーバーフローしたときにクリップされるかどうかを指定します。値は次の意味を持ちます：

visible - この値は、コンテンツがクリップされないことを示します。つまり、ブロックボックスの外部に描画される可能性があります。hidden - この値は、コンテンツがクリップされ、クリッピング領域外のコンテンツを表示するためのスクロール機構が提供されないことを示します。ユーザーはクリップされたコンテンツにアクセスできません。クリッピング領域のサイズと形状は、['clip'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#propdef-clip) プロパティで指定されます。scroll - この値は、コンテンツがクリップされ、ユーザーエージェントが画面上に表示されるスクロール機構（スクロールバーやパンナーなど）を使用する場合、その機構がコンテンツがクリップされているかどうかに関わらずボックスに表示されるべきことを示します。これにより、動的環境でスクロールバーが出現・消失する問題を回避します。この値が指定され、対象メディアが 'print' または 'projection' の場合、オーバーフローしたコンテンツは印刷されるべきです。auto - 'auto' の動作はユーザーエージェント依存ですが、オーバーフローしたボックスに対してスクロール機構が提供されるようにすべきです。

```java
public String Overflow { get; set; }
```

### 戻り値

overflow プロパティ

### 関連項目

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
