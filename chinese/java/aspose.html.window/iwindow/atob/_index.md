---
title: "IWindow.Atob"
second_title: "Aspose.HTML for Java API 参考"
description: "IWindow 方法。接受以 Unicode 字符串形式的输入数据，该字符串包含 base64 编码的二进制数据，解码后返回一个字符串，该字符串由范围 U0000 到 U00FF 的字符组成，每个字符分别表示值为 0x00 到 0xFF 的二进制字节，对应于该二进制数据。"
type: docs

url: /zh/java/com.aspose.html.window/iwindow/atob/
---
## IWindow.Atob method

接受输入数据，形式为包含 base64 编码二进制数据的 Unicode 字符串，解码后返回一个字符串，该字符串由 U+0000 到 U+00FF 范围内的字符组成，每个字符分别表示值为 0x00 到 0xFF 的二进制字节，对应于该二进制数据。

```java
public String Atob(String data)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | String | 包含 base64 编码二进制数据的 Unicode 字符串 |

### 返回值

由范围 U+0000 到 U+00FF 的字符组成的字符串

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 如果输入字符串不是有效的 base64 数据，则抛出 "InvalidCharacterError" DOMException。 |

### 另请参阅

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
