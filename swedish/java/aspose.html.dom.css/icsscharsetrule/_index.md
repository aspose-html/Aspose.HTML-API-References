---
title: "ICSSCharsetRule‑gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.css.ICSSCharsetRule‑gränssnitt. CSSCharsetRule‑gränssnittet representerar en teckenkodningsregel i ett CSS‑formatark. Värdet på encoding‑attributet påverkar inte kodningen av textdata i DOM‑objekten; denna kodning är alltid UTF-16. Efter att ett formatark har laddats är värdet på encoding‑attributet det som finns i charset‑regeln. Om det inte fanns någon charset i originaldokumentet skapas ingen CSSCharsetRule. Värdet på encoding‑attributet kan också användas som en ledtråd för kodningen som används vid serialisering av formatarket."
type: docs

url: /sv/java/com.aspose.html.dom.css/icsscharsetrule/
---
## ICSSCharsetRule interface

CSSCharsetRule‑gränssnittet representerar en @charset‑regel i ett CSS‑stilmall. Värdet på kodningsattributet påverkar inte kodningen av textdata i DOM‑objekten; denna kodning är alltid UTF-16. Efter att en stilmall har lästs in är värdet på kodningsattributet det värde som hittas i @charset‑regeln. Om det inte fanns någon @charset i det ursprungliga dokumentet skapas ingen CSSCharsetRule. Värdet på kodningsattributet kan också användas som en ledtråd för den kodning som används vid serialisering av stilmallen.

```java
public interface ICSSCharsetRule : ICSSRule
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
[getEncoding]
[setEncoding] The encoding information associated with the current stylesheet used in this @charset rule. |

### Se även

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
