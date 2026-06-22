---
title: "com.aspose.html.accessibility"
second_title: "Справочник API Aspose.HTML для Java"
description: "Пакет com.aspose.html.accessibility предназначен для всех манипуляций, связанных с веб‑доступностью. Соответствует международным стандартам W3C Web Accessibility Initiative."
type: docs

url: /ru/java/com.aspose.html.accessibility/
---
Пакет **com.aspose.html.accessibility** предназначен для всех манипуляций, связанных с веб‑доступностью. Соответствует международным стандартам W3C Web Accessibility Initiative.

## Классы

| Класс | Описание |
| --- | --- |
| [AccessibilityRules](./accessibilityrules/) | Быстрый справочник по требованиям (критериям успеха) и техникам Руководства по доступности веб‑контента (WCAG) 2. Содержит список принципов. https://www.w3.org/WAI/WCAG21/quickref/ |
| [AccessibilityValidator](./accessibilityvalidator/) | Класс validator обрабатывает правила быстрого справочника. Содержит метод Validate для проверки доступности. |
| [Criterion](./criterion/) | Для каждой рекомендации предоставляются проверяемые критерии успеха, чтобы WCAG 2.0 можно было применять в областях, где требуется тестирование соответствия. https://www.w3.org/WAI/WCAG21/Understanding/understanding-techniques |
| [Guideline](./guideline/) | Руководства — следующий уровень после принципов. Они не подлежат тестированию, но описывают структуры и общие цели, помогающие авторам понять критерии успеха и лучше применять техники. Руководства представляют собой список критериев приемки с типом RuleDirectory{Criterion}. |
| [Principle](./principle/) | Принцип доступности — высший уровень, обеспечивающий основу веб‑доступности, содержит список руководств с типом RuleCollection{Guideline}. Создание объекта вне сборки не допускается. https://www.w3.org/WAI/fundamentals/accessibility-principles/ |
| [Rule](./rule/) | Абстрактный класс, определяющий характеристики правила и реализующий интерфейс IRule. |
| [Target](./target/) | Класс содержит элемент html или css, где была обнаружена ошибка. |
| [ValidationBuilder](./validationbuilder/) | Класс ValidationBuilder предоставляет конкретные реализации шагов конфигурации. Определяет методы и настройки для класса ValidationSettings. |
| [WebAccessibility](./webaccessibility/) | Объект к требованиям (критериям успеха) и техникам Руководства по доступности веб‑контента (WCAG) 2. https://www.w3.org/WAI/WCAG21/quickref/ |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IError](./ierror/) | Интерфейс описывает ошибку валидации. |
| [IRule](./irule/) | Интерфейс, описывающий основные свойства правил. |
| [ITechniqueResult](./itechniqueresult/) | Описывает результат проверки техники. |
## Перечисление

| Перечисление | Описание |
| --- | --- |
| [TargetTypes](./targettypes/) | Перечисление типов результирующего объекта из HTML‑документа, содержащего ошибку.. |
