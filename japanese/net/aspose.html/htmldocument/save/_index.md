---
title: HTMLDocument.Save
second_title: Aspose.HTML for .NET API リファレンス
description: HTMLDocument 方法. で指定されたローカル ファイルにドキュメントを保存しますURL.このドキュメントで使用されるすべてのリソースは隣接するフォルダーの に保存されその名前は次のように構成されます output_file_name  _files.
type: docs
weight: 130
url: /ja/net/aspose.html/htmldocument/save/
---
## Save(Url) {#save_5}

で指定されたローカル ファイルにドキュメントを保存します。`URL`.このドキュメントで使用されるすべてのリソースは、隣接するフォルダーの に保存され、その名前は次のように構成されます: output_file_name + "_files".

```csharp
public void Save(Url url)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| url | Url | 出力ファイルへのローカル URL。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentException | 指定された場合に発生します`URL`は有効なローカル ファイル URL ではありません。 |

### 関連項目

* class [Url](../../url/)
* class [HTMLDocument](../)
* 名前空間 [Aspose.Html](../../htmldocument/)
* 組み立て [Aspose.HTML](../../../)

---

## Save(IOutputStorage) {#save}

ドキュメントのコンテンツとリソースを出力ストレージに保存します。

```csharp
public void Save(IOutputStorage outputStorage)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| outputStorage | IOutputStorage | 出力ストレージ[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |

### 関連項目

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* class [HTMLDocument](../)
* 名前空間 [Aspose.Html](../../htmldocument/)
* 組み立て [Aspose.HTML](../../../)

---

## Save(string) {#save_10}

で指定されたローカル ファイルにドキュメントを保存します。`道`.このドキュメントで使用されるすべてのリソースは、隣接するフォルダーの に保存され、その名前は次のように構成されます: output_file_name + "_files".

```csharp
public void Save(string path)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| path | String | 出力ファイルへのローカル パス。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentException | 指定された場合に発生します`道`は有効なローカル ファイル パスではありません。 |

### 関連項目

* class [HTMLDocument](../)
* 名前空間 [Aspose.Html](../../htmldocument/)
* 組み立て [Aspose.HTML](../../../)

---

## Save(string, HTMLSaveFormat) {#save_11}

で指定されたローカル ファイルにドキュメントを保存します。`道`.このドキュメントで使用されるすべてのリソースは、隣接するフォルダーの に保存され、その名前は次のように構成されます: output_file_name + "_files".

```csharp
public void Save(string path, HTMLSaveFormat saveFormat)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| path | String | 出力ファイルへのローカル パス。 |
| saveFormat | HTMLSaveFormat | ドキュメントが保存される形式。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentException | 指定された場合に発生します`道`は有効なローカル ファイル パスではありません。 |

### 関連項目

* enum [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* 名前空間 [Aspose.Html](../../htmldocument/)
* 組み立て [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveFormat) {#save_6}

で指定されたローカル ファイルにドキュメントを保存します。`URL`.このドキュメントで使用されるすべてのリソースは、隣接するフォルダーの に保存され、その名前は次のように構成されます: output_file_name + "_files".

```csharp
public void Save(Url url, HTMLSaveFormat saveFormat)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| url | Url | 出力ファイルへのローカル URL。 |
| saveFormat | HTMLSaveFormat | ドキュメントが保存される形式。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentException | 指定された場合に発生します`URL`は有効なローカル ファイル URL ではありません。 |

### 関連項目

* class [Url](../../url/)
* enum [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* 名前空間 [Aspose.Html](../../htmldocument/)
* 組み立て [Aspose.HTML](../../../)

---

## Save(IOutputStorage, HTMLSaveFormat) {#save_1}

ドキュメントのコンテンツとリソースを出力ストレージに保存します。

```csharp
public void Save(IOutputStorage outputStorage, HTMLSaveFormat saveFormat)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| outputStorage | IOutputStorage | 出力ストレージ[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveFormat | HTMLSaveFormat | ドキュメントが保存される形式。 |

### 関連項目

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* enum [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* 名前空間 [Aspose.Html](../../htmldocument/)
* 組み立て [Aspose.HTML](../../../)

---

## Save(string, HTMLSaveOptions) {#save_12}

で指定されたローカル ファイルにドキュメントを保存します。`道`.このドキュメントで使用されるすべてのリソースは、隣接するフォルダーの に保存され、その名前は次のように構成されます: output_file_name + "_files".

```csharp
public void Save(string path, HTMLSaveOptions saveOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| path | String | 出力ファイルへのローカル パス。 |
| saveOptions | HTMLSaveOptions | HTML 保存オプション。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentException | 指定された場合に発生します`道`は有効なローカル ファイル パスではありません。 |

### 関連項目

* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* 名前空間 [Aspose.Html](../../htmldocument/)
* 組み立て [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveOptions) {#save_7}

で指定されたローカル ファイルにドキュメントを保存します。`URL`.このドキュメントで使用されるすべてのリソースは、隣接するフォルダーの に保存され、その名前は次のように構成されます: output_file_name + "_files".

```csharp
public void Save(Url url, HTMLSaveOptions saveOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| url | Url | 出力ファイルへのローカル URL。 |
| saveOptions | HTMLSaveOptions | HTML 保存オプション。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentException | 指定された場合に発生します`URL`は有効なローカル ファイル URL ではありません。 |

### 関連項目

* class [Url](../../url/)
* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* 名前空間 [Aspose.Html](../../htmldocument/)
* 組み立て [Aspose.HTML](../../../)

---

## Save(IOutputStorage, HTMLSaveOptions) {#save_2}

ドキュメントのコンテンツとリソースを出力ストレージに保存します。

```csharp
public void Save(IOutputStorage outputStorage, HTMLSaveOptions saveOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| outputStorage | IOutputStorage | 出力ストレージ[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveOptions | HTMLSaveOptions | HTML 保存オプション。 |

### 関連項目

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* 名前空間 [Aspose.Html](../../htmldocument/)
* 組み立て [Aspose.HTML](../../../)

---

## Save(string, MarkdownSaveOptions) {#save_13}

で指定されたローカル ファイルにドキュメントを保存します。`道`.このドキュメントで使用されるすべてのリソースは、隣接するフォルダーの に保存され、その名前は次のように構成されます: output_file_name + "_files".

```csharp
public void Save(string path, MarkdownSaveOptions saveOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| path | String | 出力ファイルへのローカル パス。 |
| saveOptions | MarkdownSaveOptions | マークダウン保存オプション。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentException | 指定された場合に発生します`道`は有効なローカル ファイル パスではありません。 |

### 関連項目

* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* 名前空間 [Aspose.Html](../../htmldocument/)
* 組み立て [Aspose.HTML](../../../)

---

## Save(Url, MarkdownSaveOptions) {#save_8}

で指定されたローカル ファイルにドキュメントを保存します。`URL`.このドキュメントで使用されるすべてのリソースは、隣接するフォルダーの に保存され、その名前は次のように構成されます: output_file_name + "_files".

```csharp
public void Save(Url url, MarkdownSaveOptions saveOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| url | Url | 出力ファイルへのローカル URL。 |
| saveOptions | MarkdownSaveOptions | マークダウン保存オプション。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentException | 指定された場合に発生します`URL`は有効なローカル ファイル URL ではありません。 |

### 関連項目

* class [Url](../../url/)
* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* 名前空間 [Aspose.Html](../../htmldocument/)
* 組み立て [Aspose.HTML](../../../)

---

## Save(IOutputStorage, MarkdownSaveOptions) {#save_3}

ドキュメントのコンテンツとリソースを出力ストレージに保存します。

```csharp
public void Save(IOutputStorage outputStorage, MarkdownSaveOptions saveOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| outputStorage | IOutputStorage | 出力ストレージ[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveOptions | MarkdownSaveOptions | マークダウン保存オプション。 |

### 関連項目

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* 名前空間 [Aspose.Html](../../htmldocument/)
* 組み立て [Aspose.HTML](../../../)

---

## Save(string, MHTMLSaveOptions) {#save_14}

で指定されたローカル ファイルにドキュメントを保存します。`道`.このドキュメントで使用されるすべてのリソースは、隣接するフォルダーの に保存され、その名前は次のように構成されます: output_file_name + "_files".

```csharp
public void Save(string path, MHTMLSaveOptions saveOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| path | String | 出力ファイルへのローカル パス。 |
| saveOptions | MHTMLSaveOptions | MHTML 保存オプション。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentException | 指定された場合に発生します`道`は有効なローカル ファイル パスではありません。 |

### 関連項目

* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* 名前空間 [Aspose.Html](../../htmldocument/)
* 組み立て [Aspose.HTML](../../../)

---

## Save(Url, MHTMLSaveOptions) {#save_9}

で指定されたローカル ファイルにドキュメントを保存します。`URL`.このドキュメントで使用されるすべてのリソースは、隣接するフォルダーの に保存され、その名前は次のように構成されます: output_file_name + "_files".

```csharp
public void Save(Url url, MHTMLSaveOptions saveOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| url | Url | 出力ファイルへのローカル URL。 |
| saveOptions | MHTMLSaveOptions | MHTML 保存オプション。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentException | 指定された場合に発生します`URL`は有効なローカル ファイル URL ではありません。 |

### 関連項目

* class [Url](../../url/)
* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* 名前空間 [Aspose.Html](../../htmldocument/)
* 組み立て [Aspose.HTML](../../../)

---

## Save(IOutputStorage, MHTMLSaveOptions) {#save_4}

ドキュメントのコンテンツとリソースを出力ストレージに保存します。

```csharp
public void Save(IOutputStorage outputStorage, MHTMLSaveOptions saveOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| outputStorage | IOutputStorage | 出力ストレージ[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveOptions | MHTMLSaveOptions | MHTML 保存オプション。 |

### 関連項目

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* 名前空間 [Aspose.Html](../../htmldocument/)
* 組み立て [Aspose.HTML](../../../)


