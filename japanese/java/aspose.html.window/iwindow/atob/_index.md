---
title: "IWindow.Atob"
second_title: "Aspose.HTML for Java API リファレンス"
description: "IWindow メソッド。入力データを base64 エンコードされたバイナリデータを含む Unicode 文字列として受け取り、デコードし、範囲 U0000 から U00FF の文字で構成された文字列を返します。各文字は 0x00 から 0xFF のバイナリバイトを表し、元のバイナリデータに対応します。"
type: docs

url: /ja/java/com.aspose.html.window/iwindow/atob/
---
## IWindow.Atob method

入力データを、Base64 エンコードされたバイナリデータを含む Unicode 文字列として受け取り、デコードし、U+0000 から U+00FF の範囲の文字で構成された文字列を返します。各文字は 0x00 から 0xFF のバイナリバイトを表します。

```java
public String Atob(String data)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| データ | 文字列 | base64 エンコードされたバイナリデータを含む Unicode 文字列です。 |

### 戻り値

範囲 U+0000 から U+00FF の文字で構成された文字列です。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 入力文字列が有効な base64 データでない場合、"InvalidCharacterError" DOMException をスローします。 |

### 関連項目

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
