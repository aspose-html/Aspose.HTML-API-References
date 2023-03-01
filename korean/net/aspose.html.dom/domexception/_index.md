---
title: Class DOMException
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.DOMException 수업. DOMException 인터페이스는 웹 API의 속성에 접근하거나 메서드를 호출한 결과 발생하는 비정상적인 이벤트예외라고 함를 나타냅니다. 이것은 기본적으로 웹 API에서 오류 조건이 설명되는 방식입니다.
type: docs
weight: 640
url: /ko/net/aspose.html.dom/domexception/
---
## DOMException class

DOMException 인터페이스는 웹 API의 속성에 접근하거나 메서드를 호출한 결과 발생하는 비정상적인 이벤트(예외라고 함)를 나타냅니다. 이것은 기본적으로 웹 API에서 오류 조건이 설명되는 방식입니다.

```csharp
public class DOMException : PlatformException
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [DOMException](domexception/#constructor)(string) | 의 새 인스턴스를 초기화합니다.`DOMException` 클래스. |
| [DOMException](domexception/#constructor_1)(string, string) | 의 새 인스턴스를 초기화합니다.`DOMException` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Code](../../aspose.html.dom/domexception/code/) { get; } | 오류 코드 상수 중 하나를 포함하는 값을 반환하거나 일치하지 않는 경우 0을 반환합니다. 이 필드는 역사적 이유로 사용됩니다. |
| override [Message](../../aspose.html.dom/domexception/message/) { get; } | 지정된 오류 이름과 관련된 메시지 또는 설명을 나타내는 문자열을 반환합니다. |
| [Name](../../aspose.html.dom/domexception/name/) { get; } | 오류 이름과 관련된 문자열 중 하나를 포함하는 문자열을 반환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [ABORT_ERR](../../aspose.html.dom/domexception/abort_err/) | 작업이 중단되었습니다. |
| const [DATA_CLONE_ERR](../../aspose.html.dom/domexception/data_clone_err/) | 개체를 복제할 수 없습니다. |
| const [DOMSTRING_SIZE_ERR](../../aspose.html.dom/domexception/domstring_size_err/) | 지정된 텍스트 범위가 DOMString. 에 맞지 않는 경우 |
| const [HIERARCHY_REQUEST_ERR](../../aspose.html.dom/domexception/hierarchy_request_err/) | 노드가 속하지 않는 위치에 삽입된 경우. |
| const [INDEX_SIZE_ERR](../../aspose.html.dom/domexception/index_size_err/) | 인덱스 또는 크기가 음수이거나 허용된 값보다 큰 경우. |
| const [INUSE_ATTRIBUTE_ERR](../../aspose.html.dom/domexception/inuse_attribute_err/) | 다른 곳에서 이미 사용 중인 속성을 추가하려는 경우. |
| const [INVALID_ACCESS_ERR](../../aspose.html.dom/domexception/invalid_access_err/) | 기본 개체에서 매개 변수 또는 작업을 지원하지 않는 경우. |
| const [INVALID_CHARACTER_ERR](../../aspose.html.dom/domexception/invalid_character_err/) | XML 이름과 같이 유효하지 않거나 잘못된 문자가 지정된 경우. |
| const [INVALID_EXPRESSION_ERR](../../aspose.html.dom/domexception/invalid_expression_err/) | 표현식에 구문 오류가 있거나 specific XPathEvaluator의 규칙에 따른 올바른 표현식이 아니거나 이 구현에서 지원하지 않는 특수 확장 함수 또는 변수가 포함되어 있습니다. |
| const [INVALID_MODIFICATION_ERR](../../aspose.html.dom/domexception/invalid_modification_err/) | 기본 개체의 유형을 수정하려는 경우. |
| const [INVALID_NODE_TYPE_ERR](../../aspose.html.dom/domexception/invalid_node_type_err/) | 제공된 노드가 잘못되었거나 이 작업에 대한 조상이 잘못되었습니다. |
| const [INVALID_STATE_ERR](../../aspose.html.dom/domexception/invalid_state_err/) | 사용할 수 없거나 더 이상 사용할 수 없는 개체를 사용하려는 경우. |
| const [NAMESPACE_ERR](../../aspose.html.dom/domexception/namespace_err/) | 네임스페이스와 관련하여 잘못된 방식으로 개체를 생성하거나 변경하려고 시도한 경우. |
| const [NETWORK_ERR](../../aspose.html.dom/domexception/network_err/) | 네트워크 오류가 발생했습니다. |
| const [NOT_FOUND_ERR](../../aspose.html.dom/domexception/not_found_err/) | 노드가 존재하지 않는 컨텍스트에서 노드를 참조하려고 시도한 경우. |
| const [NOT_SUPPORTED_ERR](../../aspose.html.dom/domexception/not_supported_err/) | 구현이 요청된 개체 또는 작업 유형을 지원하지 않는 경우. |
| const [NO_DATA_ALLOWED_ERR](../../aspose.html.dom/domexception/no_data_allowed_err/) | 데이터를 지원하지 않는 노드에 데이터를 지정한 경우. |
| const [NO_MODIFICATION_ALLOWED_ERR](../../aspose.html.dom/domexception/no_modification_allowed_err/) | 수정이 허용되지 않는 개체를 수정하려고 시도한 경우. |
| const [QUOTA_EXCEEDED_ERR](../../aspose.html.dom/domexception/quota_exceeded_err/) | 할당량이 초과되었습니다. |
| const [SECURITY_ERR](../../aspose.html.dom/domexception/security_err/) | 작업이 안전하지 않습니다. |
| const [SYNTAX_ERR](../../aspose.html.dom/domexception/syntax_err/) | 유효하지 않거나 잘못된 문자열이 지정된 경우. |
| const [TIMEOUT_ERR](../../aspose.html.dom/domexception/timeout_err/) | 작업 시간이 초과되었습니다. |
| const [TYPE_ERR](../../aspose.html.dom/domexception/type_err/) | 지정한 형식을 반환하도록 식을 변환할 수 없습니다. |
| const [TYPE_MISMATCH_ERR](../../aspose.html.dom/domexception/type_mismatch_err/) | 개체 유형이 개체와 관련된 매개 변수의 예상 유형과 호환되지 않는 경우. |
| const [URL_MISMATCH_ERR](../../aspose.html.dom/domexception/url_mismatch_err/) | 주어진 URL이 다른 URL과 일치하지 않습니다. |
| const [VALIDATION_ERR](../../aspose.html.dom/domexception/validation_err/) | insertBefore 또는 removeChild와 같은 메서드에 대한 호출이 "부분 유효성"과 관련하여 노드를 무효화하는 경우 이 예외가 발생하고 작업이 수행되지 않습니다. 이 코드는 [DOM Level 3 Validation]에서 사용됩니다. 자세한 내용은 이 사양을 참조하십시오. |
| const [WRONG_DOCUMENT_ERR](../../aspose.html.dom/domexception/wrong_document_err/) | 노드를 만든 문서가 아닌 다른 문서에서 사용되는 경우(지원하지 않음). |

### 또한보십시오

* class [PlatformException](../../aspose.html/platformexception/)
* 네임스페이스 [Aspose.Html.Dom](../../aspose.html.dom/)
* 집회 [Aspose.HTML](../../)


