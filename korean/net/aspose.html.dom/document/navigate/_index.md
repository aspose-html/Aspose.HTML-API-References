---
title: Document.Navigate
second_title: .NET API 참조용 Aspose.HTML
description: Document 방법. 지정된 URLUniform Resource Locator의 문서를 현재 인스턴스로 로드하여 이전 콘텐츠를 바꿉니다.
type: docs
weight: 1010
url: /ko/net/aspose.html.dom/document/navigate/
---
## Navigate(string) {#navigate_4}

지정된 URL(Uniform Resource Locator)의 문서를 현재 인스턴스로 로드하여 이전 콘텐츠를 바꿉니다.

```csharp
public void Navigate(string address)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| address | String | 문서 주소입니다. 현재 디렉토리 경로와 결합되어 절대 URL을 형성합니다. |

### 또한보십시오

* class [Document](../)
* 네임스페이스 [Aspose.Html.Dom](../../document/)
* 집회 [Aspose.HTML](../../../)

---

## Navigate(Url) {#navigate_1}

지정된 URL(Uniform Resource Locator)의 문서를 현재 인스턴스로 로드하여 이전 콘텐츠를 바꿉니다.

```csharp
public void Navigate(Url url)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| url | Url | 문서 URL입니다. |

### 또한보십시오

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* 네임스페이스 [Aspose.Html.Dom](../../document/)
* 집회 [Aspose.HTML](../../../)

---

## Navigate(string, string) {#navigate_6}

지정된 콘텐츠에서 문서를 로드하고 baseUri를 사용하여 관련 리소스를 확인하여 이전 콘텐츠를 바꿉니다.

```csharp
public void Navigate(string content, string baseUri)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| content | String | 문서 내용입니다. |
| baseUri | String | 상대 리소스를 확인하기 위한 기본 URI입니다. 현재 디렉토리 경로와 결합되어 절대 URL을 형성합니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | `baseUri` ~이다`없는`. |

### 또한보십시오

* class [Document](../)
* 네임스페이스 [Aspose.Html.Dom](../../document/)
* 집회 [Aspose.HTML](../../../)

---

## Navigate(string, Url) {#navigate_5}

지정된 콘텐츠에서 문서를 로드하고 baseUri를 사용하여 관련 리소스를 확인하여 이전 콘텐츠를 바꿉니다.

```csharp
public void Navigate(string content, Url baseUri)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| content | String | 문서 내용입니다. |
| baseUri | Url | 상대 리소스를 확인하기 위한 기본 URI입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | `baseUri` ~이다`없는`. |

### 또한보십시오

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* 네임스페이스 [Aspose.Html.Dom](../../document/)
* 집회 [Aspose.HTML](../../../)

---

## Navigate(Stream, string) {#navigate_3}

지정된 콘텐츠에서 문서를 로드하고 baseUri를 사용하여 상대 리소스를 확인하고 이전 콘텐츠를 바꿉니다. 문서 로드는 스트림의 현재 위치에서 시작됩니다.

```csharp
public void Navigate(Stream content, string baseUri)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| content | Stream | 문서 내용입니다. |
| baseUri | String | 상대 리소스를 확인하기 위한 기본 URI입니다. 현재 디렉토리 경로와 결합되어 절대 URL을 형성합니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | `baseUri` ~이다`없는`. |

### 또한보십시오

* class [Document](../)
* 네임스페이스 [Aspose.Html.Dom](../../document/)
* 집회 [Aspose.HTML](../../../)

---

## Navigate(Stream, Url) {#navigate_2}

지정된 콘텐츠에서 문서를 로드하고 baseUri를 사용하여 상대 리소스를 확인하고 이전 콘텐츠를 바꿉니다. 문서 로드는 스트림의 현재 위치에서 시작됩니다.

```csharp
public void Navigate(Stream content, Url baseUri)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| content | Stream | 문서 내용입니다. |
| baseUri | Url | 상대 리소스를 확인하기 위한 기본 URI입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | `baseUri` ~이다`없는`. |

### 또한보십시오

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* 네임스페이스 [Aspose.Html.Dom](../../document/)
* 집회 [Aspose.HTML](../../../)

---

## Navigate(RequestMessage) {#navigate}

지정된 요청 개체를 기반으로 문서를 로드하여 이전 내용을 바꿉니다.

```csharp
public void Navigate(RequestMessage request)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| request | RequestMessage | 문서 콘텐츠를 로드하는 데 사용되는 요청 개체입니다. |

### 또한보십시오

* class [RequestMessage](../../../aspose.html.net/requestmessage/)
* class [Document](../)
* 네임스페이스 [Aspose.Html.Dom](../../document/)
* 집회 [Aspose.HTML](../../../)


