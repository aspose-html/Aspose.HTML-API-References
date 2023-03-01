---
title: Interface IStyleSheet
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Css.IStyleSheet gränssnitt. StyleSheetgränssnittet är det abstrakta basgränssnittet för alla typer av stilmall. Den representerar en enda formatmall som är associerad med ett strukturerat dokument.
type: docs
weight: 590
url: /sv/net/aspose.html.dom.css/istylesheet/
---
## IStyleSheet interface

StyleSheet-gränssnittet är det abstrakta basgränssnittet för alla typer av stilmall. Den representerar en enda formatmall som är associerad med ett strukturerat dokument.

```csharp
public interface IStyleSheet
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Disabled](../../aspose.html.dom.css/istylesheet/disabled/) { get; set; } | false om stilmallen tillämpas på dokumentet. sant om det inte är det. Ändring av detta attribut kan orsaka en ny stilupplösning för dokumentet. En stilmall gäller endast om både en lämplig mediumdefinition finns och attributet disabled är falskt. Så om mediet inte gäller den aktuella användaragenten ignoreras attributet disabled. |
| [Href](../../aspose.html.dom.css/istylesheet/href/) { get; } | Om formatmallen är en länkad formatmall är värdet på dess attribut dess plats. För inline stilmallar är värdet på detta attribut null. |
| [Media](../../aspose.html.dom.css/istylesheet/media/) { get; } | Det avsedda målmediet för stilinformation. |
| [OwnerNode](../../aspose.html.dom.css/istylesheet/ownernode/) { get; } | Noden som associerar denna stilmall med dokumentet. För HTML kan detta vara motsvarande LINK- eller STYLE-element. För XML kan det vara länkningsbearbetningsinstruktionen. För formatmallar som ingår i andra formatmallar är värdet på detta attribut null. |
| [ParentStyleSheet](../../aspose.html.dom.css/istylesheet/parentstylesheet/) { get; } | För stilmallsspråk som stöder konceptet med stilmallsinkludering, representerar detta attribut inkluderande stilmall, om en sådan finns. Om formatmallen är en formatmall på toppnivå, eller om formatmallens språk inte stöder inkludering, är värdet på det här attributet null. |
| [Title](../../aspose.html.dom.css/istylesheet/title/) { get; } | Den rådgivande titeln. |
| [Type](../../aspose.html.dom.css/istylesheet/type/) { get; } | Detta anger stilmallsspråket för denna stilmall. Stilmallsspråket anges som en innehållstyp (t.ex. "text/css"). |

### Se även

* namnutrymme [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* hopsättning [Aspose.HTML](../../)


