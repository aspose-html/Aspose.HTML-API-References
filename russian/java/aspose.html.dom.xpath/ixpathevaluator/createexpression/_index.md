---
title: "IXPathEvaluator.CreateExpression"
second_title: "Справочник API Aspose.HTML для Java"
description: "IXPathEvaluator метод. Создает разобранное XPath-выражение с разрешенными пакетами. Это полезно, когда выражение будет повторно использоваться в приложении, поскольку позволяет компилировать строку выражения String в более эффективную внутреннюю форму и предварительно разрешать все префиксы пакетов, встречающиеся в выражении."
type: docs

url: /ru/java/com.aspose.html.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

Создаёт разобранное XPath‑выражение с разрешёнными пакетами. Это полезно, когда выражение будет переиспользоваться в приложении, так как позволяет компилировать строку выражения во более эффективную внутреннюю форму и предварительно разрешать все префиксы пакетов, встречающиеся в выражении.

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| выражение | String | Строка XPath-выражения, которую нужно разобрать. |
| resolver | IXPathNSResolver | `resolver` позволяет переводить все префиксы, включая префикс пакета `xml`, внутри XPath-выражения в соответствующие URI пакетов. Если указано `null`, любой префикс пакета внутри выражения приведет к выбросу [`DOMException`](../../../com.aspose.html.dom/domexception/) с кодом `NAMESPACE_ERR`. |

### Возвращаемое значение

Скомпилированная форма XPath-выражения.

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Возникает, если выражение не соответствует правилам [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR: Возникает, если выражение содержит префиксы пакетов, которые не могут быть разрешены указанным [`IXPathNSResolver`](../../ixpathnsresolver/). |

### См. также

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
