---
title: CreateExpression
second_title: Справочник по Aspose.HTML для .NET API
description: Создает проанализированное выражение XPath с разрешенными пространствами имен. Это полезно когда выражение будет повторно использоваться в приложении так как это позволяет скомпилировать строку выражения в более эффективную внутреннюю форму и предварительно разрешить все префиксы пространств имен встречающиеся в выражении.
type: docs
weight: 890
url: /ru/net/aspose.html.dom/document/createexpression/
---
## Document.CreateExpression method

Создает проанализированное выражение XPath с разрешенными пространствами имен. Это полезно когда выражение будет повторно использоваться в приложении, так как это позволяет скомпилировать строку выражения в более эффективную внутреннюю форму и предварительно разрешить все префиксы пространств имен, встречающиеся в выражении.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| expression | String | Строка выражения XPath для анализа. |
| resolver | IXPathNSResolver | Преобразователь разрешает перевод всех префиксов, включая префикс пространства имен` xml` в выражении XPath в соответствующие URI пространства имен. Если это указано как` null` , любой префикс пространства имен в выражении приведет к[`DOMException`](../../domexception)be выбрасывается с кодом` NAMESPACE_ERR` . |

### Возвращаемое значение

Скомпилированная форма выражения XPath.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../domexception) | INVALID_EXPRESSION_ERR:Возникает, если выражение не является допустимым согласно к правилам[`IXPathEvaluator`](../../../aspose.html.dom.xpath/ixpathevaluator). |
| [DOMException](../../domexception) | NAMESPACE_ERR:Возникает, если выражение содержит префиксы пространства имен , которые не могут быть разрешены указанными[`IXPathNSResolver`](../../../aspose.html.dom.xpath/ixpathnsresolver). |

### Смотрите также

* interface [IXPathExpression](../../../aspose.html.dom.xpath/ixpathexpression)
* interface [IXPathNSResolver](../../../aspose.html.dom.xpath/ixpathnsresolver)
* class [Document](../../document)
* пространство имен [Aspose.Html.Dom](../../document)
* сборка [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
