---
title: "DOMException 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.DOMException 클래스. DOMException 인터페이스는 예외라고 하는 비정상적인 이벤트를 나타내며, 이는 웹 API의 메서드를 호출하거나 속성에 접근할 때 발생합니다. 이는 웹 API에서 오류 상태를 설명하는 기본 방식입니다."
type: docs

url: /ko/java/com.aspose.html.dom/domexception/
---
## DOMException class

DOMException 인터페이스는 웹 API의 메서드를 호출하거나 속성에 접근할 때 발생하는 비정상적인 이벤트(예외)를 나타냅니다. 이는 웹 API에서 오류 조건이 설명되는 기본 방식입니다.

```java
public class DOMException : PlatformException
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [DOMException](domexception/#constructor)(String) | `DOMException` 클래스의 새 인스턴스를 초기화합니다. |
| [DOMException](domexception/#constructor_1)(String, String) | `DOMException` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [getCode](../../com.aspose.html.dom/domexception/code/) 오류 코드 상수 중 하나를 포함하는 값을 반환하며, 일치하는 것이 없으면 0을 반환합니다. 이 필드는 과거 호환성을 위해 사용됩니다. |
| [getMessage](../../com.aspose.html.dom/domexception/message/) 주어진 오류 이름과 연관된 메시지 또는 설명을 나타내는 문자열을 반환합니다. |
| [getName](../../com.aspose.html.dom/domexception/name/) 오류 이름과 연관된 문자열 중 하나를 포함하는 문자열을 반환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [ABORT_ERR](../../com.aspose.html.dom/domexception/abort_err/) | 작업이 중단되었습니다. |
| const [DATA_CLONE_ERR](../../com.aspose.html.dom/domexception/data_clone_err/) | 객체를 복제할 수 없습니다. |
| const [DOMSTRING_SIZE_ERR](../../com.aspose.html.dom/domexception/domString_size_err/) | 지정된 텍스트 범위가 DOMString에 들어가지 않을 경우. |
| const [HIERARCHY_REQUEST_ERR](../../com.aspose.html.dom/domexception/hierarchy_request_err/) | 노드가 그에 맞지 않는 위치에 삽입된 경우. |
| const [INDEX_SIZE_ERR](../../com.aspose.html.dom/domexception/index_size_err/) | 인덱스 또는 크기가 음수이거나 허용된 값을 초과한 경우. |
| const [INUSE_ATTRIBUTE_ERR](../../com.aspose.html.dom/domexception/inuse_attribute_err/) | 이미 다른 곳에서 사용 중인 속성을 추가하려는 시도인 경우. |
| const [INVALID_ACCESS_ERR](../../com.aspose.html.dom/domexception/invalid_access_err/) | 기본 객체가 매개변수나 작업을 지원하지 않는 경우. |
| const [INVALID_CHARACTER_ERR](../../com.aspose.html.dom/domexception/invalid_character_err/) | XML 이름 등에서 잘못되었거나 허용되지 않은 문자가 지정된 경우. |
| const [INVALID_EXPRESSION_ERR](../../com.aspose.html.dom/domexception/invalid_expression_err/) | 표현식에 구문 오류가 있거나, 특정 XPathEvaluator의 규칙에 따라 합법적인 표현식이 아니며, 이 구현에서 지원되지 않는 특수 확장 함수나 변수를 포함하고 있습니다. |
| const [INVALID_MODIFICATION_ERR](../../com.aspose.html.dom/domexception/invalid_modification_err/) | 기본 객체의 유형을 수정하려는 시도인 경우. |
| const [INVALID_NODE_TYPE_ERR](../../com.aspose.html.dom/domexception/invalid_node_type_err/) | 제공된 노드가 잘못되었거나 이 작업에 대해 올바르지 않은 조상을 가지고 있는 경우. |
| const [INVALID_STATE_ERR](../../com.aspose.html.dom/domexception/invalid_state_err/) | 사용할 수 없거나 더 이상 사용할 수 없는 객체를 사용하려고 시도하면. |
| const [NAMESPACE_ERR](../../com.aspose.html.dom/domexception/package_err/) | 패키지와 관련하여 잘못된 방식으로 객체를 생성하거나 변경하려고 시도하면. |
| const [NETWORK_ERR](../../com.aspose.html.dom/domexception/network_err/) | 네트워크 오류가 발생했습니다. |
| const [NOT_FOUND_ERR](../../com.aspose.html.dom/domexception/not_found_err/) | 존재하지 않는 컨텍스트에서 노드를 참조하려고 시도하면. |
| const [NOT_SUPPORTED_ERR](../../com.aspose.html.dom/domexception/not_supported_err/) | 구현이 요청된 객체 유형이나 작업을 지원하지 않을 경우. |
| const [NO_DATA_ALLOWED_ERR](../../com.aspose.html.dom/domexception/no_data_allowed_err/) | 데이터를 지원하지 않는 노드에 데이터를 지정하면. |
| const [NO_MODIFICATION_ALLOWED_ERR](../../com.aspose.html.dom/domexception/no_modification_allowed_err/) | 수정이 허용되지 않은 객체를 수정하려고 시도하면. |
| const [QUOTA_EXCEEDED_ERR](../../com.aspose.html.dom/domexception/quota_exceeded_err/) | 쿼터가 초과되었습니다. |
| const [SECURITY_ERR](../../com.aspose.html.dom/domexception/security_err/) | 작업이 안전하지 않습니다. |
| const [SYNTAX_ERR](../../com.aspose.html.dom/domexception/syntax_err/) | 잘못되었거나 불법적인 문자열이 지정되면. |
| const [TIMEOUT_ERR](../../com.aspose.html.dom/domexception/timeout_err/) | 작업이 시간 초과되었습니다. |
| const [TYPE_ERR](../../com.aspose.html.dom/domexception/type_err/) | 식은 지정된 유형을 반환하도록 변환할 수 없습니다. |
| const [TYPE_MISMATCH_ERR](../../com.aspose.html.dom/domexception/type_mismatch_err/) | 객체의 유형이 해당 객체와 연관된 매개변수의 예상 유형과 호환되지 않을 경우. |
| const [URL_MISMATCH_ERR](../../com.aspose.html.dom/domexception/url_mismatch_err/) | 제공된 URL이 다른 URL과 일치하지 않습니다. |
| const [VALIDATION_ERR](../../com.aspose.html.dom/domexception/validation_err/) | insertBefore 또는 removeChild와 같은 메서드 호출이 \"partial validity\"에 대해 노드를 무효화시킬 경우, 이 예외가 발생하고 작업이 수행되지 않습니다. 이 코드는 [DOM Level 3 Validation]에 사용됩니다. 자세한 내용은 이 사양을 참조하십시오. |
| const [WRONG_DOCUMENT_ERR](../../com.aspose.html.dom/domexception/wrong_document_err/) | 노드가 생성된 문서와 다른 문서에서 사용될 경우(지원되지 않는 경우). |

### 또 보기

* class [PlatformException](../../com.aspose.html/platformexception/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
