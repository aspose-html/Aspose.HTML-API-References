---
title: ICSS2Properties.Volume
second_title: Aspose.HTML for .NET API Reference
description: ICSS2Properties property. Volume refers to the median volume of the waveform. In other words a highly inflected voice at a volume of 50 might peak well above that. The overall values are likely to be human adjustable for comfort for example with a physical volume control which would increase both the 0 and 100 values proportionately what this property does is adjust the dynamic range
type: docs
weight: 1170
url: /net/aspose.html.dom.css/icss2properties/volume/
---
## ICSS2Properties.Volume property

Volume refers to the median volume of the waveform. In other words, a highly inflected voice at a volume of 50 might peak well above that. The overall values are likely to be human adjustable for comfort, for example with a physical volume control (which would increase both the 0 and 100 values proportionately); what this property does is adjust the dynamic range.

Values have the following meanings:

'[number](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-number)' - Any number between '0' and '100'. '0' represents the minimum audible volume level and 100 corresponds to the maximum comfortable level.'[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - Percentage values are calculated relative to the inherited value, and are then clipped to the range '0' to '100'.silent - No sound at all. The value '0' does not mean the same as 'silent'.x-soft - Same as '0'.soft - Same as '25'.medium - Same as '50'.loud - Same as '75'.x-loud - Same as '100'.

```csharp
public string Volume { get; set; }
```

### Return Value

volume property

### See Also

* interface [ICSS2Properties](../)
* namespace [Aspose.Html.Dom.Css](../../../aspose.html.dom.css/)
* assembly [Aspose.HTML](../../../)
