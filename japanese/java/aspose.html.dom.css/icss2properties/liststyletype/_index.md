---
title: "ICSS2Properties.ListStyleType"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICSS2Properties プロパティ。このプロパティは list-style-image の値が none の場合、または URI が指す画像を表示できない場合のリスト項目マーカーの外観を指定します。値 none はマーカーがないことを示し、それ以外の場合はマーカーは 3 種類、グリフ、番号付けシステム、アルファベットシステムがあります。注：番号付きリストはリストのナビゲーションを容易にし、文書のアクセシビリティを向上させます。"
type: docs

url: /ja/java/com.aspose.html.dom.css/icss2properties/liststyletype/
---
## ICSS2Properties.ListStyleType property

このプロパティは ['list-style-image'](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#propdef-list-style-image) の値が 'none' の場合、または URI が指す画像を表示できない場合のリスト項目マーカーの外観を指定します。値 'none' はマーカーがないことを示し、それ以外の場合はマーカーは 3 種類、グリフ、番号付けシステム、アルファベットシステムがあります。注：番号付きリストはリストのナビゲーションを容易にし、文書のアクセシビリティを向上させます。

グリフは disc、circle、square で指定されます。その正確な描画はユーザーエージェントに依存します。

番号付けシステムは以下で指定されます：

decimal - 1 から始まる十進数。decimal-leading-zero - 先頭にゼロを付加した十進数（例: 01, 02, 03, ..., 98, 99）。lower-roman - 小文字のローマ数字（i, ii, iii, iv, v など）。upper-roman - 大文字のローマ数字（I, II, III, IV, V など）。hebrew - 伝統的なヘブライ数字。georgian - 伝統的なジョージア文字の数字（an, ban, gan, ..., he, tan, in, in-an, ...）。armenian - 伝統的なアルメニア数字。cjk-ideographic - 素の表意文字数字。hiragana - a, i, u, e, o, ka, ki, ...。katakana - A, I, U, E, O, KA, KI, ...。hiragana-iroha - i, ro, ha, ni, ho, he, to, ...。katakana-iroha - I, RO, HA, NI, HO, HE, TO, ...

```java
public String ListStyleType { get; set; }
```

### 戻り値

list-style-type プロパティ

### 関連項目

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
