---
title: ICSS2Properties Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.css.ICSS2Properties interface. The CSS2Properties interface represents a convenience mechanism for retrieving and setting properties within a CSSStyleDeclaration. The attributes of this interface correspond to all the properties specified in CSS2. Getting an attribute of this interface is equivalent to calling the getPropertyValue method of the CSSStyleDeclaration interface. Setting an attribute of this interface is equivalent to calling the setProperty method of the CSSStyleDeclaration interface
type: docs

url: /java/com.aspose.html.dom.css/icss2properties/
---
## ICSS2Properties interface

The CSS2Properties interface represents a convenience mechanism for retrieving and setting properties within a [`CSSStyleDeclaration`](../icssstyledeclaration/). The attributes of this interface correspond to all the properties specified in CSS2. Getting an attribute of this interface is equivalent to calling the getPropertyValue method of the [`CSSStyleDeclaration`](../icssstyledeclaration/) interface. Setting an attribute of this interface is equivalent to calling the setProperty method of the [`CSSStyleDeclaration`](../icssstyledeclaration/) interface.

```java
public interface ICSS2Properties
```

## Properties

| Name | Description |
| --- | --- |
[getAzimuth]
[setAzimuth] Spatial audio is an important stylistic property for aural presentation. It provides a natural way to tell several voices apart, as in real life (people rarely all stand in the same spot in a room). |
[getBackground]
[setBackground] The 'background' property is a shorthand property for setting the individual background properties (i.e., 'background-color', 'background-image', 'background-repeat', 'background-attachment' and 'background-position') at the same place in the style sheet. |
[getBackgroundAttachment]
[setBackgroundAttachment] If a background image is specified, this property specifies whether it is fixed with regard to the viewport ('fixed') or scrolls along with the document ('scroll'). |
[getBackgroundColor]
[setBackgroundColor] This property sets the background color of an element, either a value or the keyword 'transparent', to make the underlying colors shine through. |
[getBackgroundImage]
[setBackgroundImage] This property sets the background image of an element. When setting a background image, authors should also specify a background color that will be used when the image is unavailable. When the image is available, it is rendered on top of the background color. (Thus, the color is visible in the transparent parts of the image). |
[getBackgroundPosition]
[setBackgroundPosition] If a background image has been specified, this property specifies its initial position. Values have the following meanings: |
[getBackgroundRepeat]
[setBackgroundRepeat] If a background image is specified, this property specifies whether the image is repeated (tiled), and how. All tiling covers the content and padding areas of a box. Values have the following meanings: |
[getBorder]
[setBorder] The 'border' property is a shorthand property for setting the same width, color, and style for all four borders of a box. Unlike the shorthand 'margin' and 'padding' properties, the 'border' property cannot set different values on the four borders. To do so, one or more of the other border properties must be used. |
[getBorderBottom]
[setBorderBottom] This is a shorthand property for setting the width, style, and color of the top, right, bottom, and left border of a box. |
[getBorderBottomColor]
[setBorderBottomColor] The border color properties specify the color of a box's border. |
[getBorderBottomStyle]
[setBorderBottomStyle] The 'border-style' property sets the style of the four borders. It can have from one to four values, and the values are set on the different sides as for 'border-width' above. |
[getBorderBottomWidth]
[setBorderBottomWidth] This property is a shorthand property for setting 'border-top-width', 'border-right-width', 'border-bottom-width', and 'border-left-width' at the same place in the style sheet. |
[getBorderCollapse]
[setBorderCollapse] This property selects a table's border model. The value 'separate' selects the separated borders border model. The value 'collapse' selects the collapsing borders model. The models are described below. |
[getBorderColor]
[setBorderColor] The 'border-color' property sets the color of the four borders. Values have the following meanings: |
[getBorderLeft]
[setBorderLeft] This is a shorthand property for setting the width, style, and color of the top, right, bottom, and left border of a box. |
[getBorderLeftColor]
[setBorderLeftColor] The 'border-color' property sets the color of the four borders. Values have the following meanings: |
[getBorderLeftStyle]
[setBorderLeftStyle] The 'border-style' property sets the style of the four borders. It can have from one to four values, and the values are set on the different sides as for 'border-width' above. |
[getBorderLeftWidth]
[setBorderLeftWidth] This property is a shorthand property for setting 'border-top-width', 'border-right-width', 'border-bottom-width', and 'border-left-width' at the same place in the style sheet. |
[getBorderRight]
[setBorderRight] This is a shorthand property for setting the width, style, and color of the top, right, bottom, and left border of a box. |
[getBorderRightColor]
[setBorderRightColor] The 'border-color' property sets the color of the four borders. Values have the following meanings: |
[getBorderRightStyle]
[setBorderRightStyle] The 'border-style' property sets the style of the four borders. It can have from one to four values, and the values are set on the different sides as for 'border-width' above. |
[getBorderRightWidth]
[setBorderRightWidth] This property is a shorthand property for setting 'border-top-width', 'border-right-width', 'border-bottom-width', and 'border-left-width' at the same place in the style sheet. |
[getBorderSpacing]
[setBorderSpacing] The lengths specify the distance that separates adjacent cell borders. If one length is specified, it gives both the horizontal and vertical spacing. If two are specified, the first gives the horizontal spacing and the second the vertical spacing. Lengths may not be negative. |
[getBorderStyle]
[setBorderStyle] The 'border-style' property sets the style of the four borders. It can have from one to four values, and the values are set on the different sides as for 'border-width' above. |
[getBorderTop]
[setBorderTop] This is a shorthand property for setting the width, style, and color of the top, right, bottom, and left border of a box. |
[getBorderTopColor]
[setBorderTopColor] The 'border-color' property sets the color of the four borders. Values have the following meanings: |
[getBorderTopStyle]
[setBorderTopStyle] The 'border-style' property sets the style of the four borders. It can have from one to four values, and the values are set on the different sides as for 'border-width' above. |
[getBorderTopWidth]
[setBorderTopWidth] This property is a shorthand property for setting 'border-top-width', 'border-right-width', 'border-bottom-width', and 'border-left-width' at the same place in the style sheet. |
[getBorderWidth]
[setBorderWidth] This property is a shorthand property for setting 'border-top-width', 'border-right-width', 'border-bottom-width', and 'border-left-width' at the same place in the style sheet. |
[getBottom]
[setBottom] This property specifies how far a box's bottom content edge is offset above the bottom of the box's containing block. |
[getCaptionSide]
[setCaptionSide] This property specifies the position of the caption box with respect to the table box. Values have the following meanings: |
[getClear]
[setClear] This property indicates which sides of an element's box(es) may not be adjacent to an earlier floating box. (It may be that the element itself has floating descendants; the 'clear' property has no effect on those.) |
[getClip]
[setClip] The 'clip' property applies to elements that have a 'overflow' property with a value other than 'visible'. |
[getColor]
[setColor] This property describes the foreground color of an element's text content. |
[getContent]
[setContent] This property is used with the :before and :after pseudo-elements to generate content in a document. |
[getCounterIncrement]
[setCounterIncrement] The ['counter-increment'](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#propdef-counter-increment) property accepts one or more names of counters (identifiers), each one optionally followed by an integer. The integer indicates by how much the counter is incremented for every occurrence of the element. The default increment is 1. Zero and negative integers are allowed. |
[getCounterReset]
[setCounterReset] The ['counter-reset'](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#propdef-counter-reset) property also contains a list of one or more names of counters, each one optionally followed by an integer. The integer gives the value that the counter is set to on each occurrence of the element. The default is 0. |
[getCue]
[setCue] The ['cue'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-cue) property is a shorthand for setting ['cue-before'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-cue-before) and ['cue-after'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-cue-after). If two values are given, the first value is ['cue-before'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-cue-before) and the second is ['cue-after'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-cue-after). If only one value is given, it applies to both properties. |
[getCueAfter]
[setCueAfter] Auditory icons are another way to distinguish semantic elements. Sounds may be played before and/or after the element to delimit it. |
[getCueBefore]
[setCueBefore] Auditory icons are another way to distinguish semantic elements. Sounds may be played before and/or after the element to delimit it. |
[getCursor]
[setCursor] This property specifies the type of cursor to be displayed for the pointing device. |
[getDirection]
[setDirection] This property specifies the base writing direction of blocks and the direction of embeddings and overrides (see ['unicode-bidi'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-unicode-bidi)) for the Unicode bidirectional algorithm. In addition, it specifies the direction of [table](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html) column layout, the direction of horizontal [overflow](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#overflow), and the position of an incomplete last line in a block in case of 'text-align: justify'. |
[getDisplay]
[setDisplay] The values of this property have the following meanings: |
[getElevation]
[setElevation] Values of this property have the following meanings: |
[getEmptyCells]
[setEmptyCells] In the separated borders model, this property controls the rendering of borders around cells that have no visible content. Empty cells and cells with the 'visibility' property set to 'hidden' are considered to have no visible content. |
[getFloat]
[setFloat] See the float property definition in CSS2. |
[getFont]
[setFont] The 'font' property is, except as described below, a shorthand property for setting 'font-style', 'font-variant', 'font-weight', 'font-size', 'line-height', and 'font-family', at the same place in the style sheet. The syntax of this property is based on a traditional typographical shorthand notation to set multiple properties related to fonts. |
[getFontFamily]
[setFontFamily] This property specifies a prioritized list of font family names and/or generic family names. To deal with the problem that a single font may not contain glyphs to display all the characters in a document, or that not all fonts are available on all systems, this property allows authors to specify a list of fonts, all of the same style and size, that are tried in sequence to see if they contain a glyph for a certain character. This list is called a font set. |
[getFontSize]
[setFontSize] This property describes the size of the font when set solid. |
[getFontSizeAdjust]
[setFontSizeAdjust] In bicameral scripts, the subjective apparent size and legibility of a font are less dependent on their 'font-size' value than on the value of their 'x-height', or, more usefully, on the ratio of these two values, called the aspect value (font size divided by x-height). The higher the aspect value, the more likely it is that a font at smaller sizes will be legible. Inversely, faces with a lower aspect value will become illegible more rapidly below a given threshold size than faces with a higher aspect value. Straightforward font substitution that relies on font size alone may lead to illegible characters. |
[getFontStretch]
[setFontStretch] The ['font-stretch'](https://www.w3.org/TR/1998/REC-CSS2-19980512/fonts.html#propdef-font-stretch) property selects a normal, condensed, or extended face from a font family. Absolute keyword values have the following ordering, from narrowest to widest : |
[getFontStyle]
[setFontStyle] The 'font-style' property requests normal (sometimes referred to as "roman" or "upright"), italic, and oblique faces within a font family. |
[getFontVariant]
[setFontVariant] In a small-caps font, the glyphs for lowercase letters look similar to the uppercase ones, but in a smaller size and with slightly different proportions. The 'font-variant' property requests such a font for bicameral (having two cases, as with Latin script). This property has no visible effect for scripts that are unicameral (having only one case, as with most of the world's writing systems). |
[getFontWeight]
[setFontWeight] The 'font-weight' property specifies the weight of the font. Values have the following meanings: |
[getHeight]
[setHeight] This property specifies the [content height](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#content-height) of boxes generated by block-level and [replaced](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#replaced-element) elements. |
[getLeft]
[setLeft] This property specifies how far a box's left content edge is offset to the right of the left edge of the box's [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block). |
[getLetterSpacing]
[setLetterSpacing] This property specifies spacing behavior between text characters. Values have the following meanings: |
[getLineHeight]
[setLineHeight] If the property is set on a [block-level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#block-level) element whose content is composed of [inline-level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#inline-level) elements, it specifies the minimal height of each generated inline box. |
[getListStyle]
[setListStyle] The ['list-style'](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#propdef-list-style) property is a shorthand notation for setting the three properties ['list-style-type'](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#propdef-list-style-type), ['list-style-image'](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#propdef-list-style-image), and ['list-style-position'](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#propdef-list-style-position) at the same place in the style sheet. |
[getListStyleImage]
[setListStyleImage] This property sets the image that will be used as the list item marker. When the image is available, it will replace the marker set with the ['list-style-type'](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#propdef-list-style-type) marker. |
[getListStylePosition]
[setListStylePosition] This property specifies the position of the marker box in the principal block box. Values have the following meanings: |
[getListStyleType]
[setListStyleType] This property specifies appearance of the list item marker if ['list-style-image'](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#propdef-list-style-image) has the value 'none' or if the image pointed to by the URI cannot be displayed. The value 'none' specifies no marker, otherwise there are three types of marker: glyphs, numbering systems, and alphabetic systems. Note. Numbered lists improve document accessibility by making lists easier to navigate. |
[getMargin]
[setMargin] The ['margin'](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#propdef-margin) property is a shorthand property for setting ['margin-top'](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#propdef-margin-top), ['margin-right'](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#propdef-margin-right), ['margin-bottom'](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#propdef-margin-bottom), and ['margin-left'](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#propdef-margin-left) at the same place in the style sheet. |
[getMarginBottom]
[setMarginBottom] These properties set the top, right, bottom, and left margin of a box. |
[getMarginLeft]
[setMarginLeft] These properties set the top, right, bottom, and left margin of a box. |
[getMarginRight]
[setMarginRight] These properties set the top, right, bottom, and left margin of a box. |
[getMarginTop]
[setMarginTop] These properties set the top, right, bottom, and left margin of a box. |
[getMarkerOffset]
[setMarkerOffset] This property specifies the distance between the nearest [border edges](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#border-edge) of a marker box and its associated [principal box](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#principal-box). The offset may either be a user-specified ([length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)) or chosen by the UA ('auto'). Lengths may be negative, but there may be implementation-specific limits. |
[getMarks]
[setMarks] In high-quality printing, marks are often added outside the page box. This property specifies whether cross marks or crop marks or both should be rendered just outside the [page box](https://www.w3.org/TR/1998/REC-CSS2-19980512/page.html#page-box) edge. |
[getMaxHeight]
[setMaxHeight] These two properties allow authors to constrain box heights to a certain range. Values have the following meanings: |
[getMaxWidth]
[setMaxWidth] These two properties allow authors to constrain box widths to a certain range. Values have the following meanings: |
[getMinHeight]
[setMinHeight] These two properties allow authors to constrain box heights to a certain range. Values have the following meanings: |
[getMinWidth]
[setMinWidth] These two properties allow authors to constrain box widths to a certain range. Values have the following meanings: |
[getOrphans]
[setOrphans] The ['orphans'](https://www.w3.org/TR/1998/REC-CSS2-19980512/page.html#propdef-orphans) property specifies the minimum number of lines of a paragraph that must be left at the bottom of a page. The ['widows'](https://www.w3.org/TR/1998/REC-CSS2-19980512/page.html#propdef-widows) property specifies the minimum number of lines of a paragraph that must be left at the top of a page. Examples of how they are used to control page breaks are given below. |
[getOutline]
[setOutline] The outline created with the outline properties is drawn "over" a box, i.e., the outline is always on top, and doesn't influence the position or size of the box, or of any other boxes. Therefore, displaying or suppressing outlines does not cause reflow. |
[getOutlineColor]
[setOutlineColor] The outline created with the outline properties is drawn "over" a box, i.e., the outline is always on top, and doesn't influence the position or size of the box, or of any other boxes. Therefore, displaying or suppressing outlines does not cause reflow. |
[getOutlineStyle]
[setOutlineStyle] The outline created with the outline properties is drawn "over" a box, i.e., the outline is always on top, and doesn't influence the position or size of the box, or of any other boxes. Therefore, displaying or suppressing outlines does not cause reflow. |
[getOutlineWidth]
[setOutlineWidth] The outline created with the outline properties is drawn "over" a box, i.e., the outline is always on top, and doesn't influence the position or size of the box, or of any other boxes. Therefore, displaying or suppressing outlines does not cause reflow. |
[getOverflow]
[setOverflow] This property specifies whether the content of a block-level element is clipped when it overflows the element's box (which is acting as a containing block for the content). Values have the following meanings: |
[getPadding]
[setPadding] The ['padding'](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#propdef-padding) property is a shorthand property for setting ['padding-top'](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#propdef-padding-top), ['padding-right'](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#propdef-padding-right), ['padding-bottom'](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#propdef-padding-bottom), and ['padding-left'](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#propdef-padding-left) at the same place in the style sheet. |
[getPaddingBottom]
[setPaddingBottom] These properties set the top, right, bottom, and left padding of a box. |
[getPaddingLeft]
[setPaddingLeft] These properties set the top, right, bottom, and left padding of a box. |
[getPaddingRight]
[setPaddingRight] These properties set the top, right, bottom, and left padding of a box. |
[getPaddingTop]
[setPaddingTop] These properties set the top, right, bottom, and left padding of a box. |
[getPage]
[setPage] The ['page'](https://www.w3.org/TR/1998/REC-CSS2-19980512/page.html#propdef-page) property can be used to specify a particular type of page where an element should be displayed. |
[getPageBreakAfter]
[setPageBreakAfter] Values for these properties have the following meanings: |
[getPageBreakBefore]
[setPageBreakBefore] Values for these properties have the following meanings: |
[getPageBreakInside]
[setPageBreakInside] Values for these properties have the following meanings: |
[getPause]
[setPause] The ['pause'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-pause) property is a shorthand for setting ['pause-before'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-pause-before) and ['pause-after'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-pause-after). If two values are given, the first value is ['pause-before'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-pause-before) and the second is ['pause-after'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-pause-after). If only one value is given, it applies to both properties. |
[getPauseAfter]
[setPauseAfter] These properties specify a pause to be observed before (or after) speaking an element's content. Values have the following meanings: |
[getPauseBefore]
[setPauseBefore] These properties specify a pause to be observed before (or after) speaking an element's content. Values have the following meanings: |
[getPitch]
[setPitch] Specifies the average pitch (a frequency) of the speaking voice. The average pitch of a voice depends on the voice family. For example, the average pitch for a standard male voice is around 120Hz, but for a female voice, it's around 210Hz. |
[getPitchRange]
[setPitchRange] Specifies variation in average pitch. The perceived pitch of a human voice is determined by the fundamental frequency and typically has a value of 120Hz for a male voice and 210Hz for a female voice. Human languages are spoken with varying inflection and pitch; these variations convey additional meaning and emphasis. Thus, a highly animated voice, i.e., one that is heavily inflected, displays a high pitch range. This property specifies the range over which these variations occur, i.e., how much the fundamental frequency may deviate from the average pitch. |
[getPlayDuring]
[setPlayDuring] Similar to the ['cue-before'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-cue-before) and ['cue-after'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-cue-after) properties, this property specifies a sound to be played as a background while an element's content is spoken. |
[getPosition]
[setPosition] The values of this property have the following meanings: |
[getQuotes]
[setQuotes] This property specifies quotation marks for any number of embedded quotations. |
[getRichness]
[setRichness] Specifies the richness, or brightness, of the speaking voice. A rich voice will "carry" in a large room, a smooth voice will not. (The term "smooth" refers to how the wave form looks when drawn.) |
[getRight]
[setRight] This property specifies how far a box's right content edge is offset to the left of the right edge of the box's [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block). |
[getSize]
[setSize] This property specifies the size and orientation of a page box. |
[getSpeak]
[setSpeak] This property specifies whether text will be rendered aurally and if so, in what manner (somewhat analogous to the ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) property). The possible values are: |
[getSpeakHeader]
[setSpeakHeader] This property specifies whether table headers are spoken before every cell, or only before a cell when that cell is associated with a different header than the previous cell. Values have the following meanings: |
[getSpeakNumeral]
[setSpeakNumeral] This property controls how numerals are spoken. Values have the following meanings: |
[getSpeakPunctuation]
[setSpeakPunctuation] This property specifies how punctuation is spoken. Values have the following meanings: |
[getSpeechRate]
[setSpeechRate] This property specifies the speaking rate. Note that both absolute and relative keyword values are allowed (compare with ['font-size'](https://www.w3.org/TR/1998/REC-CSS2-19980512/fonts.html#propdef-font-size)). Values have the following meanings: |
[getStress]
[setStress] Specifies the height of "local peaks" in the intonation contour of a voice. For example, English is a stressed language, and different parts of a sentence are assigned primary, secondary, or tertiary stress. The value of ['stress'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-stress) controls the amount of inflection that results from these stress markers. This property is a companion to the ['pitch-range'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-pitch-range) property and is provided to allow developers to exploit higher-end auditory displays. |
[getTableLayout]
[setTableLayout] The ['table-layout'](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#propdef-table-layout) property controls the algorithm used to lay out the table cells, rows, and columns. Values have the following meaning: |
[getTextAlign]
[setTextAlign] This property describes how inline content of a block is aligned. Values have the following meanings: |
[getTextDecoration]
[setTextDecoration] This property describes decorations that are added to the text of an element. If the property is specified for a [block-level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#block-level) element, it affects all inline-level descendants of the element. If it is specified for (or affects) an [inline-level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#inline-level) element, it affects all boxes generated by the element. If the element has no content or no text content (e.g., the IMG element in HTML), user agents must [ignore](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#ignore) this property. |
[getTextIndent]
[setTextIndent] This property specifies the indentation of the first line of text in a block. More precisely, it specifies the indentation of the first box that flows into the block's first [line box](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#line-box). The box is indented with respect to the left (or right, for right-to-left layout) edge of the line box. User agents should render this indentation as blank space. |
[getTextShadow]
[setTextShadow] This property accepts a comma-separated list of shadow effects to be applied to the text of the element. The shadow effects are applied in the order specified and may thus overlay each other, but they will never overlay the text itself. Shadow effects do not alter the size of a box, but may extend beyond its boundaries. The [stack level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#stack-level) of the shadow effects is the same as for the element itself. |
[getTextTransform]
[setTextTransform] This property controls capitalization effects of an element's text. Values have the following meanings: |
[getTop]
[setTop] This property specifies how far a box's top content edge is offset below the top edge of the box's [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block). |
[getUnicodeBidi]
[setUnicodeBidi] Values for this property have the following meanings: |
[getVerticalAlign]
[setVerticalAlign] This property affects the vertical positioning inside a line box of the boxes generated by an inline-level element. The following values only have meaning with respect to a parent inline-level element, or to a parent block-level element, if that element generates [anonymous inline boxes](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#anonymous); they have no effect if no such parent exists. |
[getVisibility]
[setVisibility] The ['visibility'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#propdef-visibility) property specifies whether the boxes generated by an element are rendered. Invisible boxes still affect layout (set the ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) property to 'none' to suppress box generation altogether). Values have the following meanings: |
[getVoiceFamily]
[setVoiceFamily] The value is a comma-separated, prioritized list of voice family names (compare with ['font-family'](https://www.w3.org/TR/1998/REC-CSS2-19980512/fonts.html#propdef-font-family)). Values have the following meanings: |
[getVolume]
[setVolume] Volume refers to the median volume of the waveform. In other words, a highly inflected voice at a volume of 50 might peak well above that. The overall values are likely to be human adjustable for comfort, for example with a physical volume control (which would increase both the 0 and 100 values proportionately); what this property does is adjust the dynamic range. |
[getWhiteSpace]
[setWhiteSpace] This property declares how [whitespace](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#whitespace) inside the element is handled. Values have the following meanings: |
[getWidows]
[setWidows] The ['orphans'](https://www.w3.org/TR/1998/REC-CSS2-19980512/page.html#propdef-orphans) property specifies the minimum number of lines of a paragraph that must be left at the bottom of a page. The ['widows'](https://www.w3.org/TR/1998/REC-CSS2-19980512/page.html#propdef-widows) property specifies the minimum number of lines of a paragraph that must be left at the top of a page. Examples of how they are used to control page breaks are given below. |
[getWidth]
[setWidth] This property specifies the [content width](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#content-width) of boxes generated by block-level and [replaced](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#replaced-element) elements. |
[getWordSpacing]
[setWordSpacing] This property specifies spacing behavior between words. Values have the following meanings: |
[getZIndex]
[setZIndex] For a positioned box, the ['z-index'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-z-index) property specifies: |

### See Also

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
