---
title: "ValidationBuilder 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.accessibility.ValidationBuilder 类。ValidationBuilder 类提供配置步骤的具体实现。定义了类 ValidationSettings 的方法和设置。"
type: docs

url: /zh/java/com.aspose.html.accessibility/validationbuilder/
---
## ValidationBuilder class

ValidationBuilder 类提供配置步骤的具体实现。为 ValidationSettings 类定义方法和设置。

```java
public class ValidationBuilder
```

## 属性

| 名称 | 描述 |
| --- | --- |
| static [getAll](../../com.aspose.html.accessibility/validationbuilder/all/) 包含所有级别和所有技术设置 |
| static [getDefault](../../com.aspose.html.accessibility/validationbuilder/default/) 默认设置：仅使用 General 技术，并针对最低准则级别 |
| static [getNone](../../com.aspose.html.accessibility/validationbuilder/none/) 无设置 - 未指定任何参数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [allLevels](../../com.aspose.html.accessibility/validationbuilder/alllevels/)() | 一个设置所有标准级别的方法。并指示文档将根据所有三个级别的标准进行检查。 |
| [allTechnologies](../../com.aspose.html.accessibility/validationbuilder/alltechnologies/)() | 一个将所有技术设置为测试标准的方法。 |
| [setHTMLTags](../../com.aspose.html.accessibility/validationbuilder/sethtmltags/)(params String[]) | 要检查的 html 标签列表。如果未显式指定标签，则标签数组为空，检查将遍历所有标签。 |
| [useCSS](../../com.aspose.html.accessibility/validationbuilder/usecss/)() | 一个在规则集合中包含 CSS 技术的方法。 |
| [useFailures](../../com.aspose.html.accessibility/validationbuilder/usefailures/)() | 一个在规则集合中包含 Failures 的方法。 |
| [useGeneral](../../com.aspose.html.accessibility/validationbuilder/usegeneral/)() | 一个在规则集合中包含 General 技术的方法。 |
| [useHighestLevel](../../com.aspose.html.accessibility/validationbuilder/usehighestlevel/)() | 在规则中使用准则的最高级别 AAA。 |
| [useHTML](../../com.aspose.html.accessibility/validationbuilder/usehtml/)() | 一个在规则集合中包含 HTML 技术的方法。 |
| [useLowestLevel](../../com.aspose.html.accessibility/validationbuilder/uselowestlevel/)() | 在规则中使用准则的最低级别 A。 |
| [useMiddleLevel](../../com.aspose.html.accessibility/validationbuilder/usemiddlelevel/)() | 在规则中使用准则的中等级别 AA。 |
| [useScript](../../com.aspose.html.accessibility/validationbuilder/usescript/)() | 一个在规则集合中包含 ClientSideScript 技术的方法。 |

### 另请参见

* package [com.aspose.html.accessibility](../../com.aspose.html.accessibility/)
* package [Aspose.HTML](../../)
