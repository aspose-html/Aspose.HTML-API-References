---
title: "Document.CreateExpression"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Document. Создаёт разобранное XPath-выражение с разрешёнными пакетами. Это полезно, когда выражение будет переиспользоваться в приложении, так как позволяет компилировать строку выражения в более эффективную внутреннюю форму и предварительно разрешать все префиксы пакетов, встречающиеся в выражении."
type: docs

url: /ru/java/com.aspose.html.dom/document/createexpression/
---
## Document.CreateExpression method

Создаёт разобранное XPath‑выражение с разрешёнными пакетами. Это полезно, когда выражение будет переиспользоваться в приложении, так как позволяет скомпилировать строку выражения во более эффективную внутреннюю форму и предварительно разрешить все префиксы пакетов, встречающиеся в выражении.

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| выражение | String | Строка XPath‑выражения, которую нужно разобрать. |
| resolver | IXPathNSResolver | `resolver` позволяет переводить все префиксы, включая префикс пакета `xml`, внутри XPath-выражения в соответствующие URI пакетов. Если указано `null`, любой префикс пакета внутри выражения приведёт к выбросу [`DOMException`](../../domexception/) с кодом `NAMESPACE_ERR`. |

### Возвращаемое значение

Скомпилированная форма XPath‑выражения.

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../domexception/) | INVALID_EXPRESSION_ERR: Вызывается, если выражение не является законным согласно правилам [`IXPathEvaluator`](../../../com.aspose.html.dom.xpath/ixpathevaluator/). |
| [dOMException](../../domexception/) | NAMESPACE_ERR: Вызывается, если выражение содержит префиксы пакетов, которые не могут быть разрешены указанным [`IXPathNSResolver`](../../../com.aspose.html.dom.xpath/ixpathnsresolver/). |

### См. также

* interface [IXPathExpression](../../../com.aspose.html.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
