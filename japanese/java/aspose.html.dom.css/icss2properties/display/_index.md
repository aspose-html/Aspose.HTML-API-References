---
title: "ICSS2Properties.Display"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICSS2Properties プロパティ。このプロパティの値は以下の意味を持ちます"
type: docs

url: /ja/java/com.aspose.html.dom.css/icss2properties/display/
---
## ICSS2Properties.Display property

このプロパティの値は以下の意味を持ちます：

block - この値は要素が主ブロックボックスを生成する原因となります。inline - この値は要素が1つ以上のインラインボックスを生成する原因となります。list-item - この値は要素（例：HTML の LI）に主ブロックボックスとリスト項目インラインボックスを生成させます。リストやリスト書式の例については、[lists](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#lists) のセクションをご参照ください。marker - この値はボックスの前後に [generated content](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html) をマーカーとして宣言します。この値はブロックレベル要素に付随する [:before と :after 疑似要素](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#before-after-content) と共に使用すべきです。他の場合、この値は 'inline' と解釈されます。詳細は [markers](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#markers) のセクションをご参照ください。none - この値は要素が [formatting structure](https://www.w3.org/TR/1998/REC-CSS2-19980512/intro.html#formatting-structure) 内にボックスを生成しない原因となります（つまり、要素はレイアウトに影響しません）。子孫要素もボックスを生成せず、この動作は子孫に ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) プロパティを設定しても上書きできません。'none' の display は見えないボックスを作成するのではなく、ボックス自体が作成されません。CSS には、フォーマット構造内にボックスを生成し、フォーマットに影響を与えるが自体は表示されない仕組みが含まれます。詳細は [visibility](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#visibility) のセクションをご参照ください。run-in と compact - これらの値はコンテキストに応じてブロックまたはインラインボックスを生成します。プロパティは最終的なステータス（インラインレベルまたはブロックレベル）に基づいて run‑in と compact ボックスに適用されます。例えば、['white-space'](https://www.w3.org/TR/1998/REC-CSS2-19980512/text.html#propdef-white-space) プロパティはボックスがブロックボックスになる場合にのみ適用されます。table、inline-table、table-row-group、[table‑column](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#value-def-table-column)、table‑column‑group、table‑header‑group、table‑footer‑group、table‑row、table‑cell、table‑caption - これらの値は要素をテーブル要素のように振る舞わせます（[tables](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html) の章で説明されている制限に従います）。

```java
public String Display { get; set; }
```

### 戻り値

display プロパティ

### 関連項目

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
