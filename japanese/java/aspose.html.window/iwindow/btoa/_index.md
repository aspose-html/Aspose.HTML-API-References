---
title: "IWindow.Btoa"
second_title: "Aspose.HTML for Java API リファレンス"
description: "IWindow メソッド。入力データを、範囲 U0000 から U00FF の文字のみを含む Unicode 文字列として受け取り、各文字は 0x00 から 0xFF のバイナリバイトを表し、それを base64 表現に変換して返します。"
type: docs

url: /ja/java/com.aspose.html.window/iwindow/btoa/
---
## IWindow.Btoa method

入力データを、U+0000 から U+00FF の範囲の文字のみを含む Unicode 文字列として受け取り、各文字が 0x00 から 0xFF のバイナリバイトを表すものを、Base64 表現に変換して返します。

```java
public String Btoa(String data)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| データ | 文字列 | 範囲 U+0000 から U+00FF の文字のみを含む Unicode 文字列です。 |

### 戻り値

base64 文字列です。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 入力文字列に範囲外の文字が含まれている場合、"InvalidCharacterError" DOMException 例外をスローします。 |

### 関連項目

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
