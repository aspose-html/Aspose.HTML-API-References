---
title: "FormEditor.Create"
second_title: "Aspose.HTML for Java API リファレンス"
description: "FormEditor メソッド。HTMLFormElement に基づいて新しい FormEditor を作成します。"
type: docs

url: /ja/java/com.aspose.html.forms/formeditor/create/
---
## Create(HTMLFormElement) {#create_2}

新しい [`FormEditor`](../) を作成し、[`HTMLFormElement`](../../../com.aspose.html/htmlformelement/) に基づきます。

```java
public static FormEditor Create(HTMLFormElement form)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| フォーム | HTMLFormElement | HTML フォーム要素 |

### 戻り値

[`FormEditor`](../) クラスの新しいインスタンスを返します。

### 関連項目

* class [HTMLFormElement](../../../com.aspose.html/htmlformelement/)
* class [FormEditor](../)
* package [com.aspose.html.forms](../../../com.aspose.html.forms/)
* package [Aspose.HTML](../../../)

---

## Create(HTMLDocument, int) {#create}

インデックスで選択された [`Forms`](../../../com.aspose.html/htmldocument/forms/) コレクションから取得した [`HTMLFormElement`](../../../com.aspose.html/htmlformelement/) に基づいて、新しい [`FormEditor`](../) を作成します。

```java
public static FormEditor Create(HTMLDocument document, int index)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| ドキュメント | HTMLDocument | ドキュメント。 |
| index | Int32 | forms コレクション内のインデックス。 |

### 戻り値

[`FormEditor`](../) クラスの新しいインスタンスを返します。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | インデックスが範囲外の場合に例外が発生します。 |

### 関連項目

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [FormEditor](../)
* package [com.aspose.html.forms](../../../com.aspose.html.forms/)
* package [Aspose.HTML](../../../)

---

## Create(HTMLDocument, String) {#create_1}

ドキュメントから ID で選択された [`HTMLFormElement`](../../../com.aspose.html/htmlformelement/) に基づき、新しい [`FormEditor`](../) を作成します。

```java
public static FormEditor Create(HTMLDocument document, String id)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| ドキュメント | HTMLDocument | ドキュメント。 |
| id | 文字列 | 識別子です。 |

### 戻り値

[`FormEditor`](../) クラスの新しいインスタンスを返します。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 指定された ID の要素が存在しない場合、または要素がフォームタイプでない場合に例外が発生します。 |

### 関連項目

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [FormEditor](../)
* package [com.aspose.html.forms](../../../com.aspose.html.forms/)
* package [Aspose.HTML](../../../)
