---
title: "ICSS2Properties.Speak"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICSS2Properties プロパティ。このプロパティは、テキストが音声でレンダリングされるかどうか、そしてその場合どのような方法で行われるかを、display プロパティにやや類似した形で指定します。可能な値は次のとおりです"
type: docs

url: /ja/java/com.aspose.html.dom.css/icss2properties/speak/
---
## ICSS2Properties.Speak property

このプロパティは、テキストが音声でレンダリングされるかどうか、そしてその場合どのような方法で行われるかを（['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) プロパティにやや類似して）指定します。可能な値は次のとおりです：

none - 音声レンダリングを抑制し、要素がレンダリングに時間を要しないようにします。ただし、子孫要素はこの値を上書きでき、音声で読み上げられることがあります。（要素とその子孫のレンダリングを確実に抑制するには、['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) プロパティを使用してください）。normal - 言語依存の発音規則を使用して要素とその子要素をレンダリングします。spell-out - テキストを1文字ずつ綴ります（頭字語や略語に便利です）。

```java
public String Speak { get; set; }
```

### 戻り値

speak プロパティ

### 関連項目

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
