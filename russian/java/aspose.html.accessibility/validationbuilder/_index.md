---
title: "Класс ValidationBuilder"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.accessibility.ValidationBuilder класс. Класс ValidationBuilder предоставляет конкретные реализации шагов конфигурации. Определяет методы и настройки для класса ValidationSettings"
type: docs

url: /ru/java/com.aspose.html.accessibility/validationbuilder/
---
## ValidationBuilder class

Класс ValidationBuilder предоставляет конкретные реализации шагов конфигурации. Определяет методы и настройки для класса ValidationSettings.

```java
public class ValidationBuilder
```

## Свойства

| Имя | Описание |
| --- | --- |
| static [getAll](../../com.aspose.html.accessibility/validationbuilder/all/) Включает все уровни и все настройки технологий |
| static [getDefault](../../com.aspose.html.accessibility/validationbuilder/default/) Настройки по умолчанию: используется только технология General и уровень критерия Lowest |
| static [getNone](../../com.aspose.html.accessibility/validationbuilder/none/) Настройки None — ни один параметр не указан. |

## Методы

| Имя | Описание |
| --- | --- |
| [allLevels](../../com.aspose.html.accessibility/validationbuilder/alllevels/)() | Метод, который устанавливает все уровни критериев. И указывает, что документ будет проверяться согласно критериям всех трёх уровней. |
| [allTechnologies](../../com.aspose.html.accessibility/validationbuilder/alltechnologies/)() | Метод, который устанавливает все технологии для тестового критерия |
| [setHTMLTags](../../com.aspose.html.accessibility/validationbuilder/sethtmltags/)(params String[]) | Список HTML‑тегов для проверки. Если теги не указаны явно, массив тегов пуст, и проверка проходит по всем. |
| [useCSS](../../com.aspose.html.accessibility/validationbuilder/usecss/)() | Метод, который включает технологии CSS в набор правил |
| [useFailures](../../com.aspose.html.accessibility/validationbuilder/usefailures/)() | Метод, который включает Failures в набор правил |
| [useGeneral](../../com.aspose.html.accessibility/validationbuilder/usegeneral/)() | Метод, который включает технологии General в набор правил |
| [useHighestLevel](../../com.aspose.html.accessibility/validationbuilder/usehighestlevel/)() | Использовать высший уровень AAA критерия в правилах |
| [useHTML](../../com.aspose.html.accessibility/validationbuilder/usehtml/)() | Метод, который включает технологии HTML в набор правил |
| [useLowestLevel](../../com.aspose.html.accessibility/validationbuilder/uselowestlevel/)() | Использовать низший уровень A критерия в правилах |
| [useMiddleLevel](../../com.aspose.html.accessibility/validationbuilder/usemiddlelevel/)() | Использовать средний уровень AA критерия в правилах |
| [useScript](../../com.aspose.html.accessibility/validationbuilder/usescript/)() | Метод, который включает технологии ClientSideScript в набор правил |

### См. также

* package [com.aspose.html.accessibility](../../com.aspose.html.accessibility/)
* package [Aspose.HTML](../../)
