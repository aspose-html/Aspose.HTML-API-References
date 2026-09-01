---
title: "Интерфейс ICSSKeyframesRule"
second_title: "Справочник API Aspose.HTML для Java"
description: "Интерфейс com.aspose.html.dom.css.ICSSKeyframesRule. Свойство name интерфейса CSSKeyframeRule получает и задает имя анимации, используемое свойством animation-name."
type: docs

url: /ru/java/com.aspose.html.dom.css/icsskeyframesrule/
---
## ICSSKeyframesRule interface

Свойство name интерфейса CSSKeyframeRule получает и задаёт имя анимации, используемое в свойстве animation-name.

```java
public interface ICSSKeyframesRule : ICSSRule
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getCSSRules](../../com.aspose.html.dom.css/icsskeyframesrule/cssrules/) Только для чтения свойство cssRules интерфейса [`CSSKeyframeRule`](../icsskeyframerule/) возвращает [`CSSRuleList`](../icssrulelist/), содержащий правила в at‑rule keyframes. |
| [getName](../../com.aspose.html.dom.css/icsskeyframesrule/name/) Свойство name интерфейса [`CSSKeyframeRule`](../icsskeyframerule/) получает и задает имя анимации, используемое свойством animation-name. |

## Методы

| Имя | Описание |
| --- | --- |
| [appendRule](../../com.aspose.html.dom.css/icsskeyframesrule/appendrule/)(String) | Метод appendRule добавляет переданный [`CSSKeyframeRule`](../icsskeyframerule/) в конец коллекции правил keyframes. |
| [deleteRule](../../com.aspose.html.dom.css/icsskeyframesrule/deleterule/)(String) | Метод deleteRule удаляет [`CSSKeyframeRule`](../icsskeyframerule/) с переданным ключом. Если правило с таким ключом не существует, метод ничего не делает. |
| [findRule](../../com.aspose.html.dom.css/icsskeyframesrule/findrule/)(String) | Метод findRule возвращает правило с ключом, совпадающим с переданным. Если такое правило не существует, возвращается значение null. |

### См. также

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
