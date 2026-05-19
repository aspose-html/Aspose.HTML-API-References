---
title: "Document.Navigate"
second_title: "Aspose.HTML for Java API 참조"
description: "Document 메서드. 지정된 Uniform Resource Locator URL의 문서를 현재 인스턴스로 로드하여 이전 내용을 교체합니다."
type: docs

url: /ko/java/com.aspose.html.dom/document/navigate/
---
## Navigate(String) {#navigate_4}

지정된 통합 자원 위치(URL)에서 문서를 현재 인스턴스로 로드하여 이전 내용을 교체합니다.

```java
public void Navigate(String address)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 주소 | String | 문서 주소. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |

### 또 보기

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Url) {#navigate_1}

지정된 통합 자원 위치(URL)에서 문서를 현재 인스턴스로 로드하여 이전 내용을 교체합니다.

```java
public void Navigate(Url url)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| url | Url | 문서 URL. |

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, String) {#navigate_6}

지정된 콘텐츠에서 문서를 로드하고 baseUri를 사용하여 상대 리소스를 해결하여 이전 내용을 교체합니다.

```java
public void Navigate(String content, String baseUri)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 내용 | String | 문서 내용. |
| baseUri | String | 상대 리소스를 해결하기 위한 기본 URI입니다. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | `baseUri`는 `null`입니다. |

### 또 보기

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, Url) {#navigate_5}

지정된 콘텐츠에서 문서를 로드하고 baseUri를 사용하여 상대 리소스를 해결하여 이전 내용을 교체합니다.

```java
public void Navigate(String content, Url baseUri)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 내용 | String | 문서 내용. |
| baseUri | Url | 상대 리소스를 해결하기 위한 기본 URI입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | `baseUri`는 `null`입니다. |

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, String) {#navigate_3}

지정된 콘텐츠에서 문서를 로드하고 baseUri를 사용하여 상대 리소스를 해결하여 이전 내용을 교체합니다. 문서 로드는 스트림의 현재 위치에서 시작됩니다.

```java
public void Navigate(Stream content, String baseUri)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 내용 | 스트림 | 문서 내용. |
| baseUri | String | 상대 리소스를 해결하기 위한 기본 URI입니다. 현재 디렉터리 경로와 결합되어 절대 URL을 형성합니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | `baseUri`는 `null`입니다. |

### 또 보기

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, Url) {#navigate_2}

지정된 콘텐츠에서 문서를 로드하고 baseUri를 사용하여 상대 리소스를 해결하여 이전 내용을 교체합니다. 문서 로드는 스트림의 현재 위치에서 시작됩니다.

```java
public void Navigate(Stream content, Url baseUri)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 내용 | 스트림 | 문서 내용. |
| baseUri | Url | 상대 리소스를 해결하기 위한 기본 URI입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | `baseUri`는 `null`입니다. |

### 또 보기

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(RequestMessage) {#navigate}

지정된 요청 객체를 기반으로 문서를 로드하고 이전 내용을 교체합니다.

```java
public void Navigate(RequestMessage request)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 요청 | RequestMessage | 문서 내용을 로드하는 데 사용되는 요청 객체입니다. |

### 또 보기

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
