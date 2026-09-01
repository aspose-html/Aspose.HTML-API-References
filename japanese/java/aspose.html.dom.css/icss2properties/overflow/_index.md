---
title: "ICSS2Properties.Overflow"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICSS2Properties プロパティ。このプロパティは、ブロックレベル要素のコンテンツが、コンテンツの containing block として機能する要素のボックスをオーバーフローしたときにクリップされるかどうかを指定します。値は以下の意味を持ちます。"
type: docs

url: /ja/java/com.aspose.html.dom.css/icss2properties/overflow/
---
## ICSS2Properties.Overflow property

このプロパティは、ブロックレベル要素のコンテンツが要素のボックス（コンテンツの containing block として機能）をオーバーフローしたときにクリップされるかどうかを指定します。値は以下の意味を持ちます：

visible - この値はコンテンツがクリップされないことを示し、つまりブロックボックスの外側に描画される可能性があります。 hidden - この値はコンテンツがクリップされ、クリッピング領域外のコンテンツを表示するスクロール機構を提供すべきでないことを示します。ユーザーはクリップされたコンテンツにアクセスできません。クリッピング領域のサイズと形状は ['clip'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#propdef-clip) プロパティで指定されます。 scroll - この値はコンテンツがクリップされ、ユーザーエージェントが画面上に表示されるスクロール機構（スクロールバーやパンナーなど）を使用する場合、その機構はコンテンツがクリップされているかどうかに関わらずボックスに表示されるべきことを示します。これにより、動的環境でスクロールバーの出現・消失に伴う問題を防ぎます。この値が指定され、対象メディアが 'print' または 'projection' の場合、オーバーフローしたコンテンツは印刷されるべきです。 auto - 'auto' の動作はユーザーエージェントに依存しますが、オーバーフローしたボックスに対してスクロール機構が提供されるべきです。

```java
public String Overflow { get; set; }
```

### 戻り値

overflow プロパティ

### 関連項目

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
