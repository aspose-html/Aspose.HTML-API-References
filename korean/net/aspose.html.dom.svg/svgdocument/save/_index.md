---
title: SVGDocument.Save
second_title: .NET API 참조용 Aspose.HTML
description: SVGDocument 방법. 지정된 로컬 파일에 문서를 저장합니다.URL 이 문서에 사용된 모든 리소스는 에 인접한 폴더에 저장되며 이름은 output_file_name  _files. 로 구성됩니다.
type: docs
weight: 90
url: /ko/net/aspose.html.dom.svg/svgdocument/save/
---
## Save(Url) {#save_3}

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

* class [Url](../../../aspose.html/url/)
* class [SVGDocument](../)
* 네임스페이스 [Aspose.Html.Dom.Svg](../../svgdocument/)
* 집회 [Aspose.HTML](../../../)

---

## Save(string) {#save_6}

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

* class [SVGDocument](../)
* 네임스페이스 [Aspose.Html.Dom.Svg](../../svgdocument/)
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
* class [SVGDocument](../)
* 네임스페이스 [Aspose.Html.Dom.Svg](../../svgdocument/)
* 집회 [Aspose.HTML](../../../)

---

## Save(string, SVGSaveFormat) {#save_7}

지정된 로컬 파일에 문서를 저장합니다.`길` 이 문서에 사용된 모든 리소스는 에 인접한 폴더에 저장되며 이름은 output_file_name + "_files". 로 구성됩니다.

```csharp
public void Save(string path, SVGSaveFormat saveFormat)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| path | String | 출력 파일의 로컬 경로입니다. |
| saveFormat | SVGSaveFormat | 문서가 저장되는 형식입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentException | 지정된 경우 발생`길` 유효한 로컬 파일 경로가 아닙니다. |

### 또한보십시오

* enum [SVGSaveFormat](../../../aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* 네임스페이스 [Aspose.Html.Dom.Svg](../../svgdocument/)
* 집회 [Aspose.HTML](../../../)

---

## Save(IOutputStorage, SVGSaveFormat) {#save_1}

문서 콘텐츠 및 리소스를 출력 저장소에 저장합니다.

```csharp
public void Save(IOutputStorage outputStorage, SVGSaveFormat saveFormat)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| outputStorage | IOutputStorage | 출력 저장[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveFormat | SVGSaveFormat | 문서가 저장되는 형식입니다. |

### 또한보십시오

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* enum [SVGSaveFormat](../../../aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* 네임스페이스 [Aspose.Html.Dom.Svg](../../svgdocument/)
* 집회 [Aspose.HTML](../../../)

---

## Save(string, SVGSaveOptions) {#save_8}

지정된 로컬 파일에 문서를 저장합니다.`길` 이 문서에 사용된 모든 리소스는 에 인접한 폴더에 저장되며 이름은 output_file_name + "_files". 로 구성됩니다.

```csharp
public void Save(string path, SVGSaveOptions saveOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| path | String | 출력 파일의 로컬 경로입니다. |
| saveOptions | SVGSaveOptions | SVG 저장 옵션. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentException | 지정된 경우 발생`길` 유효한 로컬 파일 경로가 아닙니다. |

### 또한보십시오

* class [SVGSaveOptions](../../../aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* 네임스페이스 [Aspose.Html.Dom.Svg](../../svgdocument/)
* 집회 [Aspose.HTML](../../../)

---

## Save(IOutputStorage, SVGSaveOptions) {#save_2}

문서 콘텐츠 및 리소스를 출력 저장소에 저장합니다.

```csharp
public void Save(IOutputStorage outputStorage, SVGSaveOptions saveOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| outputStorage | IOutputStorage | 출력 저장[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveOptions | SVGSaveOptions | SVG 저장 옵션. |

### 또한보십시오

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* class [SVGSaveOptions](../../../aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* 네임스페이스 [Aspose.Html.Dom.Svg](../../svgdocument/)
* 집회 [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveFormat) {#save_4}

지정된 로컬 파일에 문서를 저장합니다.`URL` 이 문서에 사용된 모든 리소스는 에 인접한 폴더에 저장되며 이름은 output_file_name + "_files". 로 구성됩니다.

```csharp
public void Save(Url url, SVGSaveFormat saveFormat)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| url | Url | 파일을 출력할 로컬 URL입니다. |
| saveFormat | SVGSaveFormat | 문서가 저장되는 형식입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentException | 지정된 경우 발생`URL` 유효한 로컬 파일 URL이 아닙니다. |

### 또한보십시오

* class [Url](../../../aspose.html/url/)
* enum [SVGSaveFormat](../../../aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* 네임스페이스 [Aspose.Html.Dom.Svg](../../svgdocument/)
* 집회 [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveOptions) {#save_5}

지정된 로컬 파일에 문서를 저장합니다.`URL` 이 문서에 사용된 모든 리소스는 에 인접한 폴더에 저장되며 이름은 output_file_name + "_files". 로 구성됩니다.

```csharp
public void Save(Url url, SVGSaveOptions saveOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| url | Url | 파일을 출력할 로컬 URL입니다. |
| saveOptions | SVGSaveOptions | SVG 저장 옵션. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentException | 지정된 경우 발생`URL` 유효한 로컬 파일 URL이 아닙니다. |

### 또한보십시오

* class [Url](../../../aspose.html/url/)
* class [SVGSaveOptions](../../../aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* 네임스페이스 [Aspose.Html.Dom.Svg](../../svgdocument/)
* 집회 [Aspose.HTML](../../../)


