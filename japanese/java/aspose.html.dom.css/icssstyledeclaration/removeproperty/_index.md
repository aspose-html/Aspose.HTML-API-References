---
title: "ICSSStyleDeclaration.RemoveProperty"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICSSStyleDeclaration メソッド。CSSStyleDeclaration.removeProperty メソッドインターフェイスは、CSS スタイル宣言オブジェクトからプロパティを削除します。"
type: docs

url: /ja/java/com.aspose.html.dom.css/icssstyledeclaration/removeproperty/
---
## ICSSStyleDeclaration.RemoveProperty method

CSSStyleDeclaration.removeProperty() メソッドインターフェイスは、CSS スタイル宣言オブジェクトからプロパティを削除します。

```java
public String RemoveProperty(String propertyName)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| propertyName | 文字列 | propertyName は削除対象のプロパティ名を表す文字列です。複数語からなるプロパティ名はハイフンで区切られ、キャメルケースではないことに注意してください。 |

### 戻り値

oldValue は、削除前の CSS プロパティの値に等しい DOMString です。

### 例外

| 例外 | 条件 |
| --- | --- |
| DOMException | NO_MODIFICATION_ALLOWED_ERR: プロパティまたは宣言ブロックが読み取り専用の場合。 |

### 関連項目

* interface [ICSSStyleDeclaration](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
