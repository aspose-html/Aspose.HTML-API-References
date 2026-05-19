---
title: "IUrlSearchParams 인터페이스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.IUrlSearchParams 인터페이스. URL의 쿼리 문자열을 작업하기 위한 메서드를 제공합니다."
type: docs

url: /ko/java/com.aspose.html/iurlsearchparams/
---
## IUrlSearchParams interface

URL 쿼리 문자열을 다루는 메서드를 제공합니다.

```java
public interface IUrlSearchParams : IEnumerable<String[]>
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [append](../../com.aspose.html/iurlsearchparams/append/)(String, String) | `name`이라는 이름과 `value`라는 값을 갖는 새로운 이름-값 쌍을 추가합니다. |
| [delete](../../com.aspose.html/iurlsearchparams/delete/)(String) | `name`이라는 이름을 가진 모든 이름-값 쌍을 제거합니다. |
| [get](../../com.aspose.html/iurlsearchparams/get/)(String) | `name`이라는 이름을 가진 첫 번째 이름-값 쌍의 값을 반환합니다. |
| [getAll](../../com.aspose.html/iurlsearchparams/getall/)(String) | `name`이라는 이름을 가진 모든 값들을 반환합니다. |
| [has](../../com.aspose.html/iurlsearchparams/has/)(String) | 목록에 `name`이라는 이름을 가진 이름-값 쌍이 있는지 확인합니다. |
| [set](../../com.aspose.html/iurlsearchparams/set/)(String, String) | 찾은 첫 번째 이름-값 쌍의 값을 지정된 값으로 설정하고 다른 쌍들을 제거합니다. 지정된 이름을 가진 이름-값 쌍이 없으면 새 쌍이 목록에 추가됩니다. |
| [sort](../../com.aspose.html/iurlsearchparams/sort/)() | 존재하는 모든 이름-값 쌍을 이름별로 정렬합니다. |

### 또 보기

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
