---
title: "IStyleSheet.ParentStyleSheet"
second_title: "Aspose.HTML för Java API-referens"
description: "IStyleSheet property. För stilmallspråk som stödjer konceptet med stilmallsinkludering representerar detta attribut den inkluderande stilmallen om en sådan finns. Om stilmallen är en överordnad stilmall eller om stilmallspråket inte stödjer inkludering är värdet för detta attribut null"
type: docs

url: /sv/java/com.aspose.html.dom.css/istylesheet/parentstylesheet/
---
## IStyleSheet.ParentStyleSheet property

För stilmallspråk som stödjer konceptet med stilmallsinkludering representerar detta attribut den inkluderande stilmallen, om en sådan finns. Om stilmallen är en överordnad stilmall, eller om stilmallspråket inte stödjer inkludering, är värdet för detta attribut null.

```java
public IStyleSheet ParentStyleSheet { get; }
```

### Property Value

parentStyleSheet‑attributet måste returnera den överordnade [`CSS style sheet`](../../icssstylesheet/).

## Anmärkningar

Denna egenskap returnerar null om den aktuella stilmallen är en överordnad stilmall eller om stilmallsinkludering inte stöds.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referens

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-parentstylesheet](https://drafts.csswg.org/cssom/#dom-stylesheet-parentstylesheet) – The CSSOM definition.

### Se även

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
