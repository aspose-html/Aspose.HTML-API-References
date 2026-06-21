---
title: "SVGDocument.Save"
second_title: "Aspose.HTML for Java API リファレンス"
description: "SVGDocument メソッド。url で指定されたローカルファイルにドキュメントを保存します。このドキュメントで使用されたすべてのリソースは、output_file_name  _files という名前の隣接フォルダーに保存されます。"
type: docs

url: /ja/java/com.aspose.html.dom.svg/svgdocument/save/
---
## Save(Url) {#save_3}

`url` で指定されたローカルファイルにドキュメントを保存します。このドキュメントで使用されるすべてのリソースは、隣接フォルダーに保存され、その名前は output_file_name + "_files" のように構成されます。

```java
public void Save(Url url)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| url | Url | 出力ファイルへのローカル URL。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 指定された `url` が有効なローカルファイル URL でない場合に発生します。 |

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(String) {#save_6}

`path` で指定されたローカルファイルにドキュメントを保存します。このドキュメントで使用されるすべてのリソースは、隣接フォルダーに保存され、その名前は output_file_name + "_files" のように構成されます。

```java
public void Save(String path)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| パス | 文字列 | 出力ファイルへのローカルパス。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 指定された `path` が有効なローカルファイルパスでない場合に発生します。 |

### 関連項目

* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler) {#save}

[`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/) を使用してドキュメントの内容とリソースを保存します。

```java
public void Save(ResourceHandler resourceHandler)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | リソースハンドラ [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)。 |

### 関連項目

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(String, SVGSaveFormat) {#save_7}

`path` で指定されたローカルファイルにドキュメントを保存します。このドキュメントで使用されるすべてのリソースは、隣接フォルダーに保存され、その名前は output_file_name + "_files" のように構成されます。

```java
public void Save(String path, SVGSaveFormat saveFormat)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| パス | 文字列 | 出力ファイルへのローカルパス。 |
| saveFormat | SVGSaveFormat | ドキュメントが保存される形式です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 指定された `path` が有効なローカルファイルパスでない場合に発生します。 |

### 関連項目

* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, SVGSaveFormat) {#save_1}

[`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/) を使用してドキュメントの内容とリソースを保存します。

```java
public void Save(ResourceHandler resourceHandler, SVGSaveFormat saveFormat)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | リソースハンドラ [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)。 |
| saveFormat | SVGSaveFormat | ドキュメントが保存される形式です。 |

### 関連項目

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(String, SVGSaveOptions) {#save_8}

`path` で指定されたローカルファイルにドキュメントを保存します。このドキュメントで使用されるすべてのリソースは、隣接フォルダーに保存され、その名前は output_file_name + "_files" のように構成されます。

```java
public void Save(String path, SVGSaveOptions saveOptions)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| パス | 文字列 | 出力ファイルへのローカルパス。 |
| saveOptions | SVGSaveOptions | SVG の保存オプションです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 指定された `path` が有効なローカルファイルパスでない場合に発生します。 |

### 関連項目

* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, SVGSaveOptions) {#save_2}

[`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/) を使用してドキュメントの内容とリソースを保存します。

```java
public void Save(ResourceHandler resourceHandler, SVGSaveOptions saveOptions)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | リソースハンドラ [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)。 |
| saveOptions | SVGSaveOptions | SVG の保存オプションです。 |

### 関連項目

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveFormat) {#save_4}

`url` で指定されたローカルファイルにドキュメントを保存します。このドキュメントで使用されるすべてのリソースは、隣接フォルダーに保存され、その名前は output_file_name + "_files" のように構成されます。

```java
public void Save(Url url, SVGSaveFormat saveFormat)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| url | Url | 出力ファイルへのローカル URL。 |
| saveFormat | SVGSaveFormat | ドキュメントが保存される形式です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 指定された `url` が有効なローカルファイル URL でない場合に発生します。 |

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveOptions) {#save_5}

`url` で指定されたローカルファイルにドキュメントを保存します。このドキュメントで使用されるすべてのリソースは、隣接フォルダーに保存され、その名前は output_file_name + "_files" のように構成されます。

```java
public void Save(Url url, SVGSaveOptions saveOptions)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| url | Url | 出力ファイルへのローカル URL。 |
| saveOptions | SVGSaveOptions | SVG の保存オプションです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 指定された `url` が有効なローカルファイル URL でない場合に発生します。 |

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
