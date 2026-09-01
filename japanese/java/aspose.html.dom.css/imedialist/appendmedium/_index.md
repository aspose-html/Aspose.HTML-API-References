---
title: "IMediaList.AppendMedium"
second_title: "Aspose.HTML for Java API リファレンス"
description: "IMediaList メソッド。新しいメディア newMedium をリストの末尾に追加します。newMedium がすでに使用されている場合は、まず削除されます。"
type: docs

url: /ja/java/com.aspose.html.dom.css/imedialist/appendmedium/
---
## IMediaList.AppendMedium method

newMedium メディアをリストの末尾に追加します。newMedium が既に使用されている場合は、まず削除されます。

```java
public void AppendMedium(String newMedium)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| newMedium | 文字列 | 追加する新しいメディア。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| DOMException | INVALID_CHARACTER_ERR: メディアに基礎となるスタイル言語で無効な文字が含まれている場合。NO_MODIFICATION_ALLOWED_ERR: このリストが読み取り専用の場合に発生します。 |

### 関連項目

* interface [IMediaList](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
