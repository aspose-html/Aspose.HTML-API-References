---
title: "ICSS2Properties.Size"
second_title: "Справочник API Aspose.HTML для Java"
description: "ICSS2Properties свойство. Это свойство указывает размер и ориентацию page box"
type: docs

url: /ru/java/com.aspose.html.dom.css/icss2properties/size/
---
## ICSS2Properties.Size property

Это свойство указывает размер и ориентацию page box.

Размер page box может быть либо "absolute" (фиксированный размер), либо "relative" (масштабируемый, т.е. подгоняющийся под доступные размеры листа). Относительные page box позволяют пользовательским агентам масштабировать документ и оптимально использовать целевой размер.

Три значения свойства ['size'](https://www.w3.org/TR/1998/REC-CSS2-19980512/page.html#propdef-size) создают относительный page box:

auto - page box будет установлен к размеру и ориентации целевого листа.landscape - Переопределяет ориентацию цели. page box имеет тот же размер, что и цель, и более длинные стороны находятся горизонтально.portrait - Переопределяет ориентацию цели. page box имеет тот же размер, что и цель, и более короткие стороны находятся горизонтально.

```java
public String Size { get; set; }
```

### Возвращаемое значение

свойство size

### См. также

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
