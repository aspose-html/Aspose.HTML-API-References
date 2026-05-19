---
title: "Document.Navigate"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Document メソッド。指定された Uniform Resource Locator URL のドキュメントを現在のインスタンスに読み込み、以前のコンテンツを置き換えます。"
type: docs

url: /ja/java/com.aspose.html.dom/document/navigate/
---
## Navigate(String) {#navigate_4}

指定された Uniform Resource Locator（URL）からドキュメントを現在のインスタンスに読み込み、以前の内容を置き換えます。

```java
public void Navigate(String address)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| アドレス | 文字列 | ドキュメントのアドレスです。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |

### 関連項目

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Url) {#navigate_1}

指定された Uniform Resource Locator（URL）からドキュメントを現在のインスタンスに読み込み、以前の内容を置き換えます。

```java
public void Navigate(Url url)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | ドキュメントの URL。 |

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, String) {#navigate_6}

指定されたコンテンツからドキュメントを読み込み、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。

```java
public void Navigate(String content, String baseUri)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | ドキュメントの内容。 |
| baseUri | 文字列 | 相対リソースを解決するためのベース URI です。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | `baseUri` は `null` です。 |

### 関連項目

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, Url) {#navigate_5}

指定されたコンテンツからドキュメントを読み込み、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。

```java
public void Navigate(String content, Url baseUri)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | ドキュメントの内容。 |
| baseUri | Url | 相対リソースを解決するためのベース URI です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | `baseUri` は `null` です。 |

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, String) {#navigate_3}

指定されたコンテンツからドキュメントを読み込み、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。ドキュメントの読み込みはストリームの現在位置から開始されます。

```java
public void Navigate(Stream content, String baseUri)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | ストリーム | ドキュメントの内容。 |
| baseUri | 文字列 | 相対リソースを解決するためのベース URI です。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | `baseUri` は `null` です。 |

### 関連項目

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, Url) {#navigate_2}

指定されたコンテンツからドキュメントを読み込み、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。ドキュメントの読み込みはストリームの現在位置から開始されます。

```java
public void Navigate(Stream content, Url baseUri)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | ストリーム | ドキュメントの内容。 |
| baseUri | Url | 相対リソースを解決するためのベース URI です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | `baseUri` は `null` です。 |

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(RequestMessage) {#navigate}

指定されたリクエストオブジェクトに基づいてドキュメントをロードし、以前の内容を置き換えます。

```java
public void Navigate(RequestMessage request)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| リクエスト | RequestMessage | ドキュメントコンテンツの読み込みに使用されるリクエストオブジェクトです。 |

### 関連項目

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
