---
title: "ICSS2Properties.Display"
second_title: "Справочник API Aspose.HTML для Java"
description: "Свойство ICSS2Properties. Значения этого свойства имеют следующее значение"
type: docs

url: /ru/java/com.aspose.html.dom.css/icss2properties/display/
---
## ICSS2Properties.Display property

Значения этого свойства имеют следующее значение:

block — Это значение заставляет элемент создавать основной блочный контейнер.
inline — Это значение заставляет элемент создавать один или несколько строчных контейнеров.
list-item — Это значение заставляет элемент (например, LI в HTML) создавать основной блочный контейнер и строчный контейнер списка. Для информации о списках и примерах форматирования списков, пожалуйста, обратитесь к разделу о [lists](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#lists).
marker — Это значение объявляет [generated content](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html) перед или после контейнера как маркер. Это значение следует использовать только с псевдо‑элементами [:before и :after](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#before-after-content), прикреплёнными к блочным элементам. В остальных случаях это значение интерпретируется как «inline». Пожалуйста, обратитесь к разделу о [markers](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#markers) для получения дополнительной информации.
none — Это значение заставляет элемент не создавать никаких контейнеров в [formatting structure](https://www.w3.org/TR/1998/REC-CSS2-19980512/intro.html#formatting-structure) (т.е. элемент не влияет на раскладку). Потомки также не создают контейнеров; это поведение нельзя переопределить, установив свойство ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) у потомков. Обратите внимание, что display со значением 'none' не создаёт невидимый контейнер; он не создаёт контейнер вовсе. CSS включает механизмы, позволяющие элементу создавать контейнеры в структуре форматирования, которые влияют на форматирование, но сами не видимы. Пожалуйста, обратитесь к разделу о [visibility](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#visibility) для деталей.
run-in и compact — Эти значения создают либо блочные, либо строчные контейнеры в зависимости от контекста. Свойства применяются к контейнерам run‑in и compact в зависимости от их окончательного статуса (строчный или блочный). Например, свойство ['white-space'](https://www.w3.org/TR/1998/REC-CSS2-19980512/text.html#propdef-white-space) применяется только если контейнер становится блочным.
 table, inline-table, table-row-group, [table-column](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#value-def-table-column), table-column-group, table-header-group, table-footer-group, table-row, table-cell и table-caption — Эти значения заставляют элемент вести себя как элемент таблицы (с ограничениями, описанными в главе о [tables](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html)).

```java
public String Display { get; set; }
```

### Возвращаемое значение

свойство display

### См. также

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
