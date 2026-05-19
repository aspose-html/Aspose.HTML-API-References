---
title: "ICSS2Properties.WhiteSpace"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICSS2Properties プロパティ。このプロパティは要素内部の空白の処理方法を宣言します。値は以下の意味を持ちます。"
type: docs

url: /ja/java/com.aspose.html.dom.css/icss2properties/whitespace/
---
## ICSS2Properties.WhiteSpace property

このプロパティは要素内部の[空白](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#whitespace)の処理方法を宣言します。値は以下の意味を持ちます：

normal - この値はユーザーエージェントに空白のシーケンスを折りたたませ、行ボックスを埋めるために必要に応じて改行させます。生成されたコンテンツ内の "\A" の出現により追加の改行が作成されることがあります（例: HTML の BR 要素）。pre - この値はユーザーエージェントが空白のシーケンスを折りたたむことを防ぎます。改行はソース中の改行文字、または生成コンテンツ内の "\A" の出現時のみ行われます。nowrap - この値は 'normal' と同様に空白を折りたたみますが、テキスト内の改行は "\A" によって作成されたものを除き抑制します（例: HTML の BR 要素）。

```java
public String WhiteSpace { get; set; }
```

### 戻り値

white-space プロパティ

### 関連項目

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
