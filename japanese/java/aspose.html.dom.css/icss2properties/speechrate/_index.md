---
title: "ICSS2Properties.SpeechRate"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICSS2Properties プロパティ。このプロパティは話す速度を指定します。font-size と比較できるように、絶対キーワードと相対キーワードの両方が使用可能です。値は以下の意味を持ちます。"
type: docs

url: /ja/java/com.aspose.html.dom.css/icss2properties/speechrate/
---
## ICSS2Properties.SpeechRate property

このプロパティは話す速度を指定します。絶対キーワードと相対キーワードの両方が使用可能です（['font-size'](https://www.w3.org/TR/1998/REC-CSS2-19980512/fonts.html#propdef-font-size) と比較してください）。値は以下の意味を持ちます：

'[number](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-number)' - 話す速度を毎分単語数で指定します。この数量は言語によって多少変わりますが、音声合成エンジンで広くサポートされています。

x-slow - 毎分 80 語に相当します。

slow - 毎分 120 語に相当します。

中速 - 180〜200語/分 と同じです。

高速 - 300語/分 と同じです。

超高速 - 500語/分 と同じです。

より速く - 現在の音声速度に毎分40語を加えます。

より遅く - 現在の音声速度から毎分40語を減らします。

```java
public String SpeechRate { get; set; }
```

### 戻り値

speech-rate プロパティ

### 関連項目

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
