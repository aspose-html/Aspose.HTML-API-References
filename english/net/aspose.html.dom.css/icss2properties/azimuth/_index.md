---
title: ICSS2Properties.Azimuth
second_title: Aspose.HTML for .NET API Reference
description: ICSS2Properties property. Spatial audio is an important stylistic property for aural presentation. It provides a natural way to tell several voices apart as in real life people rarely all stand in the same spot in a room
type: docs
weight: 10
url: /net/aspose.html.dom.css/icss2properties/azimuth/
---
## ICSS2Properties.Azimuth property

Spatial audio is an important stylistic property for aural presentation. It provides a natural way to tell several voices apart, as in real life (people rarely all stand in the same spot in a room).

```csharp
public string Azimuth { get; set; }
```

### Return Value

The azimuth property

### Property Value

Values have the following meanings:

angle - Position is described in terms of an angle within the range '-360deg' to '360deg'. The value '0deg' means directly ahead in the center of the sound stage. '90deg' is to the right, '180deg' behind, and '270deg' (or, equivalently and more conveniently, '-90deg') to the left.

left-side - Same as '270deg'. With 'behind', '270deg'.

far-left - Same as '300deg'. With 'behind', '240deg'.

left - Same as '320deg'. With 'behind', '220deg'.

center-left - Same as '340deg'. With 'behind', '200deg'.

center - Same as '0deg'. With 'behind', '180deg'.

center-right - Same as '20deg'. With 'behind', '160deg'.

right - Same as '40deg'. With 'behind', '140deg'.

far-right - Same as '60deg'. With 'behind', '120deg'.

right-side - Same as '90deg'. With 'behind', '90deg'.

leftwards - Moves the sound to the left, relative to the current angle. More precisely, subtracts 20 degrees. Arithmetic is carried out modulo 360 degrees. Note that 'leftwards' is more accurately described as "turned counter-clockwise," since it always subtracts 20 degrees, even if the inherited azimuth is already behind the listener (in which case the sound actually appears to move to the right).

rightwards - Moves the sound to the right, relative to the current angle. More precisely, adds 20 degrees. See 'leftwards' for arithmetic.

### See Also

* interface [ICSS2Properties](../)
* namespace [Aspose.Html.Dom.Css](../../../aspose.html.dom.css/)
* assembly [Aspose.HTML](../../../)
