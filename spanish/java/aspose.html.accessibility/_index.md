---
title: "com.aspose.html.accessibility"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "El paquete com.aspose.html.accessibility es para todas las manipulaciones relacionadas con la accesibilidad web. Cumple con los estándares internacionales W3C Web Accessibility Initiative."
type: docs

url: /es/java/com.aspose.html.accessibility/
---
El paquete **com.aspose.html.accessibility** está destinado a todas las manipulaciones relacionadas con la Accesibilidad Web. Cumple con los estándares internacionales W3C Web Accessibility Initiative

## Clases

| Clase | Descripción |
| --- | --- |
| [AccessibilityRules](./accessibilityrules/) | Referencia rápida a los requisitos (criterios de éxito) y técnicas de las Directrices de Accesibilidad al Contenido Web (WCAG) 2. Contiene una lista de Principios. https://www.w3.org/WAI/WCAG21/quickref/ |
| [AccessibilityValidator](./accessibilityvalidator/) | La clase validator maneja reglas de referencia rápida. Contiene un método Validate para comprobar la accesibilidad. |
| [Criterion](./criterion/) | Se proporcionan criterios de éxito verificables para cada recomendación, de modo que WCAG 2.0 pueda aplicarse en áreas donde se requiere pruebas de cumplimiento. https://www.w3.org/WAI/WCAG21/Understanding/understanding-techniques |
| [Guideline](./guideline/) | Directrices - el siguiente nivel después de los principios. No son evaluables, pero describen marcos y objetivos generales que ayudan a los autores a comprender los criterios de éxito y aplicar mejor las técnicas. Las directrices son una lista de criterios de aceptación con tipo RuleDirectory{Criterion}. |
| [Principle](./principle/) | Principio de accesibilidad - Los niveles más altos que proporcionan la base de la accesibilidad web, contienen una lista de directrices con tipo RuleCollection{Guideline}. No se permite crear el objeto fuera del ensamblado. https://www.w3.org/WAI/fundamentals/accessibility-principles/ |
| [Rule](./rule/) | Una clase abstracta que define las características de una Regla e implementa la interfaz IRule. |
| [Target](./target/) | La clase contiene el elemento html o css donde se encontró el error. |
| [ValidationBuilder](./validationbuilder/) | La clase ValidationBuilder proporciona implementaciones concretas de los pasos de configuración. Define métodos y ajustes para la clase ValidationSettings. |
| [WebAccessibility](./webaccessibility/) | Objeto a los requisitos (criterios de éxito) y técnicas de las Directrices de Accesibilidad al Contenido Web (WCAG) 2. https://www.w3.org/WAI/WCAG21/quickref/ |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IError](./ierror/) | La interfaz describe el error de la validación. |
| [IRule](./irule/) | Interfaz que describe las propiedades principales de las reglas. |
| [ITechniqueResult](./itechniqueresult/) | Describe el resultado de la validación de la técnica. |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [TargetTypes](./targettypes/) | Enumeración de tipos del objeto resultante del documento html que contiene el error.. |
