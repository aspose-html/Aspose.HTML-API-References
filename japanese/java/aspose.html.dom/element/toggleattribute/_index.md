---
title: "Element.ToggleAttribute"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Element メソッド。force が指定されていない場合、qualifiedName のトグルを行い、存在すれば削除し、存在しなければ追加します。force が true の場合は qualifiedName を追加し、force が false の場合は qualifiedName を削除します。"
type: docs

url: /ja/java/com.aspose.html.dom/element/toggleattribute/
---
## ToggleAttribute(String) {#toggleattribute}

force が指定されていない場合、qualifiedName を「トグル」し、存在すれば削除し、存在しなければ追加します。force が true の場合は qualifiedName を追加し、false の場合は削除します。

```java
public bool ToggleAttribute(String qualifiedName)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| qualifiedName | 文字列 | 属性 QualifiedName。 |

### 戻り値

qualifiedName が現在存在する場合は true を返し、そうでない場合は false を返します。

### 関連項目

* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## ToggleAttribute(String, bool) {#toggleattribute_1}

force が指定されていない場合、qualifiedName を「トグル」し、存在すれば削除し、存在しなければ追加します。force が true の場合は qualifiedName を追加し、false の場合は削除します。

```java
public bool ToggleAttribute(String qualifiedName, bool force)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| qualifiedName | 文字列 | 属性 QualifiedName。 |
| force | Boolean | 属性をトグルするための force オプション。 |

### 戻り値

qualifiedName が現在存在する場合は true を返し、そうでない場合は false を返します。

### 関連項目

* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
