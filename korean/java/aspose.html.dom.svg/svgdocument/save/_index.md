---
title: "SVGDocument.Save"
second_title: "Aspose.HTML for Java API 참조"
description: "SVGDocument 메서드. url로 지정된 로컬 파일에 문서를 저장합니다. 이 문서에서 사용된 모든 리소스는 output_file_name  _files라는 이름으로 생성되는 인접 폴더에 저장됩니다."
type: docs

url: /ko/java/com.aspose.html.dom.svg/svgdocument/save/
---
## Save(Url) {#save_3}

`url`로 지정된 로컬 파일에 문서를 저장합니다. 이 문서에서 사용된 모든 리소스는 인접 폴더에 저장되며, 폴더 이름은 output_file_name + "_files" 형태로 생성됩니다.

```java
public void Save(Url url)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| url | Url | 출력 파일에 대한 로컬 URL. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 지정된 `url`이 유효한 로컬 파일 URL이 아닌 경우 발생합니다. |

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(String) {#save_6}

`path`로 지정된 로컬 파일에 문서를 저장합니다. 이 문서에서 사용된 모든 리소스는 인접 폴더에 저장되며, 폴더 이름은 output_file_name + "_files" 형태로 생성됩니다.

```java
public void Save(String path)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 경로 | String | 출력 파일에 대한 로컬 경로. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 지정된 `path`가 유효한 로컬 파일 경로가 아닌 경우 발생합니다. |

### 또 보기

* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler) {#save}

[`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)를 사용하여 문서 내용과 리소스를 저장합니다.

```java
public void Save(ResourceHandler resourceHandler)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | 리소스 핸들러 [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |

### 또 보기

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(String, SVGSaveFormat) {#save_7}

`path`로 지정된 로컬 파일에 문서를 저장합니다. 이 문서에서 사용된 모든 리소스는 인접 폴더에 저장되며, 폴더 이름은 output_file_name + "_files" 형태로 생성됩니다.

```java
public void Save(String path, SVGSaveFormat saveFormat)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 경로 | String | 출력 파일에 대한 로컬 경로. |
| saveFormat | SVGSaveFormat | 문서가 저장되는 형식. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 지정된 `path`가 유효한 로컬 파일 경로가 아닌 경우 발생합니다. |

### 또 보기

* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, SVGSaveFormat) {#save_1}

[`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)를 사용하여 문서 내용과 리소스를 저장합니다.

```java
public void Save(ResourceHandler resourceHandler, SVGSaveFormat saveFormat)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | 리소스 핸들러 [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveFormat | SVGSaveFormat | 문서가 저장되는 형식. |

### 또 보기

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(String, SVGSaveOptions) {#save_8}

`path`로 지정된 로컬 파일에 문서를 저장합니다. 이 문서에서 사용된 모든 리소스는 인접 폴더에 저장되며, 폴더 이름은 output_file_name + "_files" 형태로 생성됩니다.

```java
public void Save(String path, SVGSaveOptions saveOptions)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 경로 | String | 출력 파일에 대한 로컬 경로. |
| saveOptions | SVGSaveOptions | SVG 저장 옵션. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 지정된 `path`가 유효한 로컬 파일 경로가 아닌 경우 발생합니다. |

### 또 보기

* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, SVGSaveOptions) {#save_2}

[`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)를 사용하여 문서 내용과 리소스를 저장합니다.

```java
public void Save(ResourceHandler resourceHandler, SVGSaveOptions saveOptions)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | 리소스 핸들러 [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | SVGSaveOptions | SVG 저장 옵션. |

### 또 보기

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveFormat) {#save_4}

`url`로 지정된 로컬 파일에 문서를 저장합니다. 이 문서에서 사용된 모든 리소스는 인접 폴더에 저장되며, 폴더 이름은 output_file_name + "_files" 형태로 생성됩니다.

```java
public void Save(Url url, SVGSaveFormat saveFormat)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| url | Url | 출력 파일에 대한 로컬 URL. |
| saveFormat | SVGSaveFormat | 문서가 저장되는 형식. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 지정된 `url`이 유효한 로컬 파일 URL이 아닌 경우 발생합니다. |

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveOptions) {#save_5}

`url`로 지정된 로컬 파일에 문서를 저장합니다. 이 문서에서 사용된 모든 리소스는 인접 폴더에 저장되며, 폴더 이름은 output_file_name + "_files" 형태로 생성됩니다.

```java
public void Save(Url url, SVGSaveOptions saveOptions)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| url | Url | 출력 파일에 대한 로컬 URL. |
| saveOptions | SVGSaveOptions | SVG 저장 옵션. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 지정된 `url`이 유효한 로컬 파일 URL이 아닌 경우 발생합니다. |

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
