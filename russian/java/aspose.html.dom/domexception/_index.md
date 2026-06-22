---
title: "Класс DOMException"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.dom.DOMException. Интерфейс DOMException представляет аномальное событие, называемое исключением, которое происходит в результате вызова метода или доступа к свойству веб‑API. По сути, так описываются условия ошибок в веб‑API."
type: docs

url: /ru/java/com.aspose.html.dom/domexception/
---
## DOMException class

Интерфейс DOMException представляет аномальное событие (называемое исключением), которое происходит в результате вызова метода или доступа к свойству веб‑API. По сути, так описываются условия ошибок в веб‑API.

```java
public class DOMException : PlatformException
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DOMException](domexception/#constructor)(String) | Инициализирует новый экземпляр класса `DOMException`. |
| [DOMException](domexception/#constructor_1)(String, String) | Инициализирует новый экземпляр класса `DOMException`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [getCode](../../com.aspose.html.dom/domexception/code/) Возвращает значение, содержащее одну из констант кодов ошибок, или 0, если ни одна не подходит. Это поле используется по историческим причинам. |
| [getMessage](../../com.aspose.html.dom/domexception/message/) Возвращает строку, представляющую сообщение или описание, связанное с указанным именем ошибки. |
| [getName](../../com.aspose.html.dom/domexception/name/) Возвращает строку, содержащую одно из значений, связанных с именем ошибки. |

## Поля

| Имя | Описание |
| --- | --- |
| const [ABORT_ERR](../../com.aspose.html.dom/domexception/abort_err/) | Операция была прервана. |
| const [DATA_CLONE_ERR](../../com.aspose.html.dom/domexception/data_clone_err/) | Объект нельзя клонировать. |
| const [DOMSTRING_SIZE_ERR](../../com.aspose.html.dom/domexception/domString_size_err/) | Если указанный диапазон текста не помещается в DOMString. |
| const [HIERARCHY_REQUEST_ERR](../../com.aspose.html.dom/domexception/hierarchy_request_err/) | Если любой узел вставлен в место, где он не принадлежит. |
| const [INDEX_SIZE_ERR](../../com.aspose.html.dom/domexception/index_size_err/) | Если индекс или размер отрицательны, или превышают допустимое значение. |
| const [INUSE_ATTRIBUTE_ERR](../../com.aspose.html.dom/domexception/inuse_attribute_err/) | Если попытка добавить атрибут, который уже используется в другом месте. |
| const [INVALID_ACCESS_ERR](../../com.aspose.html.dom/domexception/invalid_access_err/) | Если параметр или операция не поддерживается базовым объектом. |
| const [INVALID_CHARACTER_ERR](../../com.aspose.html.dom/domexception/invalid_character_err/) | Если указанный недопустимый или нелегальный символ, например в имени XML. |
| const [INVALID_EXPRESSION_ERR](../../com.aspose.html.dom/domexception/invalid_expression_err/) | Выражение содержит синтаксическую ошибку или иначе не является допустимым выражением согласно правилам конкретного XPathEvaluator, либо содержит специализированные функции расширения или переменные, не поддерживаемые этой реализацией. |
| const [INVALID_MODIFICATION_ERR](../../com.aspose.html.dom/domexception/invalid_modification_err/) | Если попытка изменить тип базового объекта. |
| const [INVALID_NODE_TYPE_ERR](../../com.aspose.html.dom/domexception/invalid_node_type_err/) | Переданный узел некорректен или имеет неверного предка для этой операции. |
| const [INVALID_STATE_ERR](../../com.aspose.html.dom/domexception/invalid_state_err/) | Если была попытка использовать объект, который не является, или более не является, пригодным. |
| const [NAMESPACE_ERR](../../com.aspose.html.dom/domexception/package_err/) | Если была попытка создать или изменить объект способом, который некорректен с точки зрения пакетов. |
| const [NETWORK_ERR](../../com.aspose.html.dom/domexception/network_err/) | Произошла сетевая ошибка. |
| const [NOT_FOUND_ERR](../../com.aspose.html.dom/domexception/not_found_err/) | Если была попытка обратиться к узлу Node в контексте, где он не существует. |
| const [NOT_SUPPORTED_ERR](../../com.aspose.html.dom/domexception/not_supported_err/) | Если реализация не поддерживает запрошенный тип объекта или операцию. |
| const [NO_DATA_ALLOWED_ERR](../../com.aspose.html.dom/domexception/no_data_allowed_err/) | Если данные указаны для узла Node, который не поддерживает данные. |
| const [NO_MODIFICATION_ALLOWED_ERR](../../com.aspose.html.dom/domexception/no_modification_allowed_err/) | Если была попытка изменить объект в месте, где изменения не разрешены. |
| const [QUOTA_EXCEEDED_ERR](../../com.aspose.html.dom/domexception/quota_exceeded_err/) | Квота превышена. |
| const [SECURITY_ERR](../../com.aspose.html.dom/domexception/security_err/) | Операция небезопасна. |
| const [SYNTAX_ERR](../../com.aspose.html.dom/domexception/syntax_err/) | Если указана недопустимая или незаконная строка (String). |
| const [TIMEOUT_ERR](../../com.aspose.html.dom/domexception/timeout_err/) | Время выполнения операции истекло. |
| const [TYPE_ERR](../../com.aspose.html.dom/domexception/type_err/) | Выражение нельзя преобразовать для возврата указанного типа. |
| const [TYPE_MISMATCH_ERR](../../com.aspose.html.dom/domexception/type_mismatch_err/) | Если тип объекта несовместим с ожидаемым типом параметра, связанным с объектом. |
| const [URL_MISMATCH_ERR](../../com.aspose.html.dom/domexception/url_mismatch_err/) | Указанный URL не совпадает с другим URL. |
| const [VALIDATION_ERR](../../com.aspose.html.dom/domexception/validation_err/) | Если вызов метода, такого как insertBefore или removeChild, сделает узел Node недействительным с точки зрения «частичной валидности», будет выброшено исключение, и операция не будет выполнена. Этот код используется в [DOM Level 3 Validation]. Обратитесь к этой спецификации для получения дополнительной информации. |
| const [WRONG_DOCUMENT_ERR](../../com.aspose.html.dom/domexception/wrong_document_err/) | Если узел Node используется в документе, отличном от того, в котором он был создан (который его не поддерживает). |

### См. также

* class [PlatformException](../../com.aspose.html/platformexception/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
