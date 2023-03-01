---
title: Document.Navigate
second_title: Aspose.HTML for .NET API リファレンス
description: Document 方法. 指定された URL Uniform Resource Locator にあるドキュメントを現在のインスタンスに読み込み以前のコンテンツを置き換えます
type: docs
weight: 1010
url: /ja/net/aspose.html.dom/document/navigate/
---
## Navigate(string) {#navigate_4}

指定された URL (Uniform Resource Locator) にあるドキュメントを現在のインスタンスに読み込み、以前のコンテンツを置き換えます。

```csharp
public void Navigate(string address)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| address | String | ドキュメントのアドレス。現在のディレクトリ パスと組み合わせて、絶対 URL を形成します。 |

### 関連項目

* class [Document](../)
* 名前空間 [Aspose.Html.Dom](../../document/)
* 組み立て [Aspose.HTML](../../../)

---

## Navigate(Url) {#navigate_1}

指定された URL (Uniform Resource Locator) にあるドキュメントを現在のインスタンスに読み込み、以前のコンテンツを置き換えます。

```csharp
public void Navigate(Url url)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| url | Url | ドキュメントの URL。 |

### 関連項目

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* 名前空間 [Aspose.Html.Dom](../../document/)
* 組み立て [Aspose.HTML](../../../)

---

## Navigate(string, string) {#navigate_6}

指定されたコンテンツからドキュメントを読み込み、baseUri を使用して相対リソースを解決し、以前のコンテンツを置き換えます。

```csharp
public void Navigate(string content, string baseUri)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| content | String | ドキュメントの内容。 |
| baseUri | String | 相対リソースを解決するためのベース URI。現在のディレクトリ パスと組み合わせて、絶対 URL を形成します。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | `baseUri`は`ヌル`. |

### 関連項目

* class [Document](../)
* 名前空間 [Aspose.Html.Dom](../../document/)
* 組み立て [Aspose.HTML](../../../)

---

## Navigate(string, Url) {#navigate_5}

指定されたコンテンツからドキュメントを読み込み、baseUri を使用して相対リソースを解決し、以前のコンテンツを置き換えます。

```csharp
public void Navigate(string content, Url baseUri)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| content | String | ドキュメントの内容。 |
| baseUri | Url | 相対リソースを解決するためのベース URI。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | `baseUri`は`ヌル`. |

### 関連項目

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* 名前空間 [Aspose.Html.Dom](../../document/)
* 組み立て [Aspose.HTML](../../../)

---

## Navigate(Stream, string) {#navigate_3}

指定されたコンテンツからドキュメントを読み込み、baseUri を使用して相対リソースを解決し、前のコンテンツを置き換えます。 ドキュメントの読み込みは、ストリーム内の現在の位置から開始されます。

```csharp
public void Navigate(Stream content, string baseUri)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| content | Stream | ドキュメントの内容。 |
| baseUri | String | 相対リソースを解決するためのベース URI。現在のディレクトリ パスと組み合わせて、絶対 URL を形成します。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | `baseUri`は`ヌル`. |

### 関連項目

* class [Document](../)
* 名前空間 [Aspose.Html.Dom](../../document/)
* 組み立て [Aspose.HTML](../../../)

---

## Navigate(Stream, Url) {#navigate_2}

指定されたコンテンツからドキュメントを読み込み、baseUri を使用して相対リソースを解決し、前のコンテンツを置き換えます。 ドキュメントの読み込みは、ストリーム内の現在の位置から開始されます。

```csharp
public void Navigate(Stream content, Url baseUri)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| content | Stream | ドキュメントの内容。 |
| baseUri | Url | 相対リソースを解決するためのベース URI。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | `baseUri`は`ヌル`. |

### 関連項目

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* 名前空間 [Aspose.Html.Dom](../../document/)
* 組み立て [Aspose.HTML](../../../)

---

## Navigate(RequestMessage) {#navigate}

指定されたリクエスト オブジェクトに基づいてドキュメントを読み込み、以前のコンテンツを置き換えます。

```csharp
public void Navigate(RequestMessage request)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| request | RequestMessage | ドキュメント コンテンツの読み込みに使用されるリクエスト オブジェクト。 |

### 関連項目

* class [RequestMessage](../../../aspose.html.net/requestmessage/)
* class [Document](../)
* 名前空間 [Aspose.Html.Dom](../../document/)
* 組み立て [Aspose.HTML](../../../)


