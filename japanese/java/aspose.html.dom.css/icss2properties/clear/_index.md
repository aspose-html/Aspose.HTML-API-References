---
title: "ICSS2Properties.Clear"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICSS2Properties プロパティ。このプロパティは要素のボックスのどの側が以前のフロートボックスに隣接できないかを示します。要素自体にフロートした子要素がある場合、clear プロパティはそれらには影響しません。"
type: docs

url: /ja/java/com.aspose.html.dom.css/icss2properties/clear/
---
## ICSS2Properties.Clear property

このプロパティは要素のボックス（複数可）のどの側が以前のフロートボックスに隣接できないかを示します。（要素自体にフロートした子要素がある場合、'clear' プロパティはそれらには影響しません。）

このプロパティはブロックレベル要素（フロートを含む）にのみ指定できます。コンパクトボックスやランインボックスの場合、このプロパティはそれらが属する最終ブロックボックスに適用されます。

非フロートブロックボックスに適用された場合、値は以下の意味を持ちます:

left - 生成されたボックスの上マージンが十分に増加し、上部のボーダーエッジが、ソース文書の前方要素から生成された左フロートボックスの下部外側エッジの下に位置します。right - 生成されたボックスの上マージンが十分に増加し、上部のボーダーエッジが、ソース文書の前方要素から生成された右フロートボックスの下部外側エッジの下に位置します。both - 生成されたボックスが、ソース文書の前方要素のすべてのフロートボックスの下に移動します。none - フロートに対するボックスの位置に制約はありません。

```java
public String Clear { get; set; }
```

### 戻り値

clear プロパティ

### 関連項目

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
