---
title: "com.aspose.html.accessibility"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.accessibility 包用于所有与网页可访问性相关的操作。符合国际标准 W3C Web Accessibility Initiative。"
type: docs

url: /zh/java/com.aspose.html.accessibility/
---
该 **com.aspose.html.accessibility** 包用于所有 Web 可访问性相关的操作。符合国际标准 W3C Web 可访问性倡议。

## 类

| 类 | 描述 |
| --- | --- |
| [AccessibilityRules](./accessibilityrules/) | 快速参考 Web 内容可访问性指南 (WCAG) 2 的要求（成功准则）和技术。包含原则列表。 https://www.w3.org/WAI/WCAG21/quickref/ |
| [AccessibilityValidator](./accessibilityvalidator/) | 验证器类处理快速参考规则。包含用于检查可访问性的 Validate 方法。 |
| [Criterion](./criterion/) | 为每项建议提供可验证的成功准则，以便在需要合规性测试的领域中应用 WCAG 2.0。 https://www.w3.org/WAI/WCAG21/Understanding/understanding-techniques |
| [Guideline](./guideline/) | 指南 - 原则之后的下一级。它们不可测试，但概述了框架和一般目标，帮助作者理解成功准则并更好地应用技术。指南是具有类型 RuleDirectory{Criterion} 的接受准则列表。 |
| [Principle](./principle/) | 可访问性原则 - 提供网页可访问性基础的最高层级，包含类型为 RuleCollection{Guideline} 的指南列表。该对象不允许在程序集外创建。 https://www.w3.org/WAI/fundamentals/accessibility-principles/ |
| [Rule](./rule/) | 一个定义规则特征并实现 IRule 接口的抽象类。 |
| [Target](./target/) | 类包含发现错误的 html 或 css 元素项。 |
| [ValidationBuilder](./validationbuilder/) | ValidationBuilder 类提供配置步骤的具体实现。为 ValidationSettings 类定义方法和设置。 |
| [WebAccessibility](./webaccessibility/) | 对象对应 Web 内容可访问性指南 (WCAG) 2 的要求（成功准则）和技术。 https://www.w3.org/WAI/WCAG21/quickref/ |
## 接口

| 接口 | 描述 |
| --- | --- |
| [IError](./ierror/) | 该接口描述验证错误。 |
| [IRule](./irule/) | 描述规则主要属性的接口。 |
| [ITechniqueResult](./itechniqueresult/) | 描述技术验证的结果。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [TargetTypes](./targettypes/) | 枚举包含错误的 html 文档中生成对象的类型.. |
