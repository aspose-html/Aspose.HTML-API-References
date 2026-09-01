---
title: "FormEditor.Create"
second_title: "Java용 Aspose.HTML API 참조"
description: "FormEditor 메서드. HTMLFormElement를 기반으로 새 FormEditor를 생성합니다."
type: docs

url: /ko/java/com.aspose.html.forms/formeditor/create/
---
## Create(HTMLFormElement) {#create_2}

새 [`FormEditor`](../)를 [`HTMLFormElement`](../../../com.aspose.html/htmlformelement/)를 기반으로 생성합니다.

```java
public static FormEditor Create(HTMLFormElement form)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 폼 | HTMLFormElement | HTML 폼 요소 |

### 반환 값

새 인스턴스의 [`FormEditor`](../) 클래스를 반환합니다.

### 또 보기

* class [HTMLFormElement](../../../com.aspose.html/htmlformelement/)
* class [FormEditor](../)
* package [com.aspose.html.forms](../../../com.aspose.html.forms/)
* package [Aspose.HTML](../../../)

---

## Create(HTMLDocument, int) {#create}

인덱스로 선택된 [`Forms`](../../../com.aspose.html/htmldocument/forms/) 컬렉션에서 [`HTMLFormElement`](../../../com.aspose.html/htmlformelement/)를 기반으로 새 [`FormEditor`](../)를 생성합니다.

```java
public static FormEditor Create(HTMLDocument document, int index)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 문서 | HTMLDocument | 문서. |
| index | Int32 | 폼 컬렉션 내부의 인덱스입니다. |

### 반환 값

새 인스턴스의 [`FormEditor`](../) 클래스를 반환합니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 인덱스가 범위를 벗어나면 예외가 발생합니다. |

### 또 보기

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [FormEditor](../)
* package [com.aspose.html.forms](../../../com.aspose.html.forms/)
* package [Aspose.HTML](../../../)

---

## Create(HTMLDocument, String) {#create_1}

문서에서 ID로 선택된 [`HTMLFormElement`](../../../com.aspose.html/htmlformelement/)를 기반으로 새 [`FormEditor`](../)를 생성합니다.

```java
public static FormEditor Create(HTMLDocument document, String id)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 문서 | HTMLDocument | 문서. |
| id | String | 식별자입니다. |

### 반환 값

새 인스턴스의 [`FormEditor`](../) 클래스를 반환합니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 지정된 ID의 요소가 없거나 요소가 폼 유형이 아니면 예외가 발생합니다. |

### 또 보기

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [FormEditor](../)
* package [com.aspose.html.forms](../../../com.aspose.html.forms/)
* package [Aspose.HTML](../../../)
