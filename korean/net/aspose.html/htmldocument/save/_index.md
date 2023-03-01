---
title: HTMLDocument.Save
second_title: .NET API 참조용 Aspose.HTML
description: HTMLDocument 방법. 지정된 로컬 파일에 문서를 저장합니다.URL 이 문서에 사용된 모든 리소스는 에 인접한 폴더에 저장되며 이름은 output_file_name  _files. 로 구성됩니다.
type: docs
weight: 130
url: /ko/net/aspose.html/htmldocument/save/
---
## Save(Url) {#save_5}

지정된 로컬 파일에 문서를 저장합니다.`URL` 이 문서에 사용된 모든 리소스는 에 인접한 폴더에 저장되며 이름은 output_file_name + "_files". 로 구성됩니다.

```csharp
public void Save(Url url)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| url | Url | 파일을 출력할 로컬 URL입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentException | 지정된 경우 발생`URL` 유효한 로컬 파일 URL이 아닙니다. |

### 또한보십시오

* class [Url](../../url/)
* class [HTMLDocument](../)
* 네임스페이스 [Aspose.Html](../../htmldocument/)
* 집회 [Aspose.HTML](../../../)

---

## Save(IOutputStorage) {#save}

문서 콘텐츠 및 리소스를 출력 저장소에 저장합니다.

```csharp
public void Save(IOutputStorage outputStorage)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| outputStorage | IOutputStorage | 출력 저장[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |

### 또한보십시오

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* class [HTMLDocument](../)
* 네임스페이스 [Aspose.Html](../../htmldocument/)
* 집회 [Aspose.HTML](../../../)

---

## Save(string) {#save_10}

지정된 로컬 파일에 문서를 저장합니다.`길` 이 문서에 사용된 모든 리소스는 에 인접한 폴더에 저장되며 이름은 output_file_name + "_files". 로 구성됩니다.

```csharp
public void Save(string path)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| path | String | 출력 파일의 로컬 경로입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentException | 지정된 경우 발생`길` 유효한 로컬 파일 경로가 아닙니다. |

### 또한보십시오

* class [HTMLDocument](../)
* 네임스페이스 [Aspose.Html](../../htmldocument/)
* 집회 [Aspose.HTML](../../../)

---

## Save(string, HTMLSaveFormat) {#save_11}

지정된 로컬 파일에 문서를 저장합니다.`길` 이 문서에 사용된 모든 리소스는 에 인접한 폴더에 저장되며 이름은 output_file_name + "_files". 로 구성됩니다.

```csharp
public void Save(string path, HTMLSaveFormat saveFormat)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| path | String | 출력 파일의 로컬 경로입니다. |
| saveFormat | HTMLSaveFormat | 문서가 저장되는 형식입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentException | 지정된 경우 발생`길` 유효한 로컬 파일 경로가 아닙니다. |

### 또한보십시오

* enum [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* 네임스페이스 [Aspose.Html](../../htmldocument/)
* 집회 [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveFormat) {#save_6}

지정된 로컬 파일에 문서를 저장합니다.`URL` 이 문서에 사용된 모든 리소스는 에 인접한 폴더에 저장되며 이름은 output_file_name + "_files". 로 구성됩니다.

```csharp
public void Save(Url url, HTMLSaveFormat saveFormat)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| url | Url | 파일을 출력할 로컬 URL입니다. |
| saveFormat | HTMLSaveFormat | 문서가 저장되는 형식입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentException | 지정된 경우 발생`URL` 유효한 로컬 파일 URL이 아닙니다. |

### 또한보십시오

* class [Url](../../url/)
* enum [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* 네임스페이스 [Aspose.Html](../../htmldocument/)
* 집회 [Aspose.HTML](../../../)

---

## Save(IOutputStorage, HTMLSaveFormat) {#save_1}

문서 콘텐츠 및 리소스를 출력 저장소에 저장합니다.

```csharp
public void Save(IOutputStorage outputStorage, HTMLSaveFormat saveFormat)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| outputStorage | IOutputStorage | 출력 저장[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveFormat | HTMLSaveFormat | 문서가 저장되는 형식입니다. |

### 또한보십시오

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* enum [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* 네임스페이스 [Aspose.Html](../../htmldocument/)
* 집회 [Aspose.HTML](../../../)

---

## Save(string, HTMLSaveOptions) {#save_12}

지정된 로컬 파일에 문서를 저장합니다.`길` 이 문서에 사용된 모든 리소스는 에 인접한 폴더에 저장되며 이름은 output_file_name + "_files". 로 구성됩니다.

```csharp
public void Save(string path, HTMLSaveOptions saveOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| path | String | 출력 파일의 로컬 경로입니다. |
| saveOptions | HTMLSaveOptions | HTML 저장 옵션. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentException | 지정된 경우 발생`길` 유효한 로컬 파일 경로가 아닙니다. |

### 또한보십시오

* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* 네임스페이스 [Aspose.Html](../../htmldocument/)
* 집회 [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveOptions) {#save_7}

지정된 로컬 파일에 문서를 저장합니다.`URL` 이 문서에 사용된 모든 리소스는 에 인접한 폴더에 저장되며 이름은 output_file_name + "_files". 로 구성됩니다.

```csharp
public void Save(Url url, HTMLSaveOptions saveOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| url | Url | 파일을 출력할 로컬 URL입니다. |
| saveOptions | HTMLSaveOptions | HTML 저장 옵션. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentException | 지정된 경우 발생`URL` 유효한 로컬 파일 URL이 아닙니다. |

### 또한보십시오

* class [Url](../../url/)
* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* 네임스페이스 [Aspose.Html](../../htmldocument/)
* 집회 [Aspose.HTML](../../../)

---

## Save(IOutputStorage, HTMLSaveOptions) {#save_2}

문서 콘텐츠 및 리소스를 출력 저장소에 저장합니다.

```csharp
public void Save(IOutputStorage outputStorage, HTMLSaveOptions saveOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| outputStorage | IOutputStorage | 출력 저장[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveOptions | HTMLSaveOptions | HTML 저장 옵션. |

### 또한보십시오

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* 네임스페이스 [Aspose.Html](../../htmldocument/)
* 집회 [Aspose.HTML](../../../)

---

## Save(string, MarkdownSaveOptions) {#save_13}

지정된 로컬 파일에 문서를 저장합니다.`길` 이 문서에 사용된 모든 리소스는 에 인접한 폴더에 저장되며 이름은 output_file_name + "_files". 로 구성됩니다.

```csharp
public void Save(string path, MarkdownSaveOptions saveOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| path | String | 출력 파일의 로컬 경로입니다. |
| saveOptions | MarkdownSaveOptions | 마크다운 저장 옵션. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentException | 지정된 경우 발생`길` 유효한 로컬 파일 경로가 아닙니다. |

### 또한보십시오

* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* 네임스페이스 [Aspose.Html](../../htmldocument/)
* 집회 [Aspose.HTML](../../../)

---

## Save(Url, MarkdownSaveOptions) {#save_8}

지정된 로컬 파일에 문서를 저장합니다.`URL` 이 문서에 사용된 모든 리소스는 에 인접한 폴더에 저장되며 이름은 output_file_name + "_files". 로 구성됩니다.

```csharp
public void Save(Url url, MarkdownSaveOptions saveOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| url | Url | 파일을 출력할 로컬 URL입니다. |
| saveOptions | MarkdownSaveOptions | 마크다운 저장 옵션. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentException | 지정된 경우 발생`URL` 유효한 로컬 파일 URL이 아닙니다. |

### 또한보십시오

* class [Url](../../url/)
* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* 네임스페이스 [Aspose.Html](../../htmldocument/)
* 집회 [Aspose.HTML](../../../)

---

## Save(IOutputStorage, MarkdownSaveOptions) {#save_3}

문서 콘텐츠 및 리소스를 출력 저장소에 저장합니다.

```csharp
public void Save(IOutputStorage outputStorage, MarkdownSaveOptions saveOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| outputStorage | IOutputStorage | 출력 저장[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveOptions | MarkdownSaveOptions | 마크다운 저장 옵션. |

### 또한보십시오

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* 네임스페이스 [Aspose.Html](../../htmldocument/)
* 집회 [Aspose.HTML](../../../)

---

## Save(string, MHTMLSaveOptions) {#save_14}

지정된 로컬 파일에 문서를 저장합니다.`길` 이 문서에 사용된 모든 리소스는 에 인접한 폴더에 저장되며 이름은 output_file_name + "_files". 로 구성됩니다.

```csharp
public void Save(string path, MHTMLSaveOptions saveOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| path | String | 출력 파일의 로컬 경로입니다. |
| saveOptions | MHTMLSaveOptions | MHTML 저장 옵션. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentException | 지정된 경우 발생`길` 유효한 로컬 파일 경로가 아닙니다. |

### 또한보십시오

* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* 네임스페이스 [Aspose.Html](../../htmldocument/)
* 집회 [Aspose.HTML](../../../)

---

## Save(Url, MHTMLSaveOptions) {#save_9}

지정된 로컬 파일에 문서를 저장합니다.`URL` 이 문서에 사용된 모든 리소스는 에 인접한 폴더에 저장되며 이름은 output_file_name + "_files". 로 구성됩니다.

```csharp
public void Save(Url url, MHTMLSaveOptions saveOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| url | Url | 파일을 출력할 로컬 URL입니다. |
| saveOptions | MHTMLSaveOptions | MHTML 저장 옵션. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentException | 지정된 경우 발생`URL` 유효한 로컬 파일 URL이 아닙니다. |

### 또한보십시오

* class [Url](../../url/)
* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* 네임스페이스 [Aspose.Html](../../htmldocument/)
* 집회 [Aspose.HTML](../../../)

---

## Save(IOutputStorage, MHTMLSaveOptions) {#save_4}

문서 콘텐츠 및 리소스를 출력 저장소에 저장합니다.

```csharp
public void Save(IOutputStorage outputStorage, MHTMLSaveOptions saveOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| outputStorage | IOutputStorage | 출력 저장[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveOptions | MHTMLSaveOptions | MHTML 저장 옵션. |

### 또한보십시오

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* 네임스페이스 [Aspose.Html](../../htmldocument/)
* 집회 [Aspose.HTML](../../../)


