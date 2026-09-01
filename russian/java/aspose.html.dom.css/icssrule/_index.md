---
title: "ICSSRule Интерфейс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.css.ICSSRule интерфейс. Интерфейс CSSRule является абстрактным базовым интерфейсом для любого типа CSS‑оператора. Это включает как наборы правил, так и at‑rules. Ожидается, что реализация сохранит все правила, указанные в таблице стилей CSS, даже если правило не распознано парсером. Нераспознанные правила представлены с помощью этого интерфейса."
type: docs

url: /ru/java/com.aspose.html.dom.css/icssrule/
---
## ICSSRule interface

Интерфейс CSSRule является абстрактным базовым интерфейсом для любого типа оператора CSS. Это включает как наборы правил, так и директивы. Ожидается, что реализация будет сохранять все правила, указанные в таблице стилей CSS, даже если правило не распознано парсером. Нераспознанные правила представляются с помощью этого интерфейса.

```java
public interface ICSSRule
```

## Свойства

| Имя | Описание |
| --- | --- |
[getCSSText]
[setCSSText] The cssText property of the `CSSRule` interface returns the actual text of a [`CSSStyleSheet`](../icssstylesheet/) style-rule. |
| [getParentRule](../../com.aspose.html.dom.css/icssrule/parentrule/) Если это правило находится внутри другого правила (например, правило стиля внутри блока @media), это правило‑контейнер. Если правило не вложено ни в одно другое правило, возвращается null. |
| [getParentStyleSheet](../../com.aspose.html.dom.css/icssrule/parentstylesheet/) Свойство parentStyleSheet интерфейса `CSSRule` возвращает объект [`StyleSheet`](../istylesheet/), в котором определено текущее правило. |
| [getType](../../com.aspose.html.dom.css/icssrule/type/) Тип правила, как определено в [CSSOM # dom-cssrule-type](https://drafts.csswg.org/cssom/#dom-cssrule-type). Ожидается, что методы приведения, специфичные для привязки, могут использоваться для приведения экземпляра интерфейса CSSRule к конкретному производному интерфейсу, подразумеваемому типом. |

### См. также

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
