---
title: "ICSS2Properties.Speak"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICSS2Properties プロパティ。このプロパティは、テキストが音声でレンダリングされるかどうか、そしてその場合どのようにレンダリングされるかを、display プロパティにやや類似した形で指定します。可能な値は以下のとおりです"
type: docs

url: /ja/java/com.aspose.html.dom.css/icss2properties/speak/
---
## ICSS2Properties.Speak property

このプロパティは、テキストが音声でレンダリングされるかどうか、そしてその場合どのようにレンダリングされるかを（display プロパティにやや類似して）指定します。可能な値は次のとおりです：

none - 要素の音声レンダリングを抑制し、レンダリングに時間がかからないようにします。ただし、子孫要素はこの値を上書きでき、発音されることがあります。（要素とその子孫のレンダリングを確実に抑制するには、['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) プロパティを使用してください）。normal - 要素とその子要素のレンダリングに言語依存の発音規則を使用します。spell-out - テキストを1文字ずつ綴ります（頭字語や略語に便利です）。

```java
public String Speak { get; set; }
```

### 戻り値

speak プロパティ

### 関連項目

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
