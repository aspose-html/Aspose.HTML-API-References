---
title: "IStyleSheet Interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.css.IStyleSheet interface. De StyleSheet interface is de abstracte basisinterface voor elk type stylesheet. Het vertegenwoordigt een enkele stylesheet die is gekoppeld aan een gestructureerd document. In HTML vertegenwoordigt de StyleSheet interface een externe stylesheet die via het HTML LINK‑element is opgenomen of een inline STYLE‑element. In XML vertegenwoordigt deze interface een externe stylesheet die via een stylesheet‑verwerkingsinstructie is opgenomen. CSS‑stylesheets zullen vervolgens de meer gespecialiseerde CSSStyleSheet interface implementeren."
type: docs

url: /nl/java/com.aspose.html.dom.css/istylesheet/
---
## IStyleSheet interface

De StyleSheet interface is de abstracte basisinterface voor elk type stylesheet. Het vertegenwoordigt een enkele stylesheet die is gekoppeld aan een gestructureerd document. In HTML vertegenwoordigt de StyleSheet interface een externe stylesheet, opgenomen via het HTML LINK‑element, of een inline STYLE‑element. In XML vertegenwoordigt deze interface een externe stylesheet, opgenomen via een stylesheet‑verwerkingsinstructie. CSS‑stylesheets zullen vervolgens de meer gespecialiseerde [`CSSStyleSheet`](../icssstylesheet/) interface implementeren.

Zie ook de [CSS Object Model (CSSOM) # StyleSheet Interface Specification](https://drafts.csswg.org/cssom/#the-stylesheet-interface).

```java
public interface IStyleSheet
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
[getDisabled]
[setDisabled] The disabled property of the `StyleSheet` interface determines whether the style sheet is prevented from applying to the document. |
| [getHref](../../com.aspose.html.dom.css/istylesheet/href/) De href‑eigenschap van de `StyleSheet` interface retourneert de locatie van de stylesheet. |
| [getMedia](../../com.aspose.html.dom.css/istylesheet/media/) De media‑eigenschap van de `StyleSheet` interface specificeert het beoogde doel‑media voor stijl‑informatie. Het is een alleen‑lezen, array‑achtig [`MediaList`](../imedialist/) object en kan worden verwijderd met deleteMedium() en toegevoegd met appendMedium(). |
| [getOwnerNode](../../com.aspose.html.dom.css/istylesheet/ownernode/) Het knooppunt dat deze stylesheet aan het document koppelt. Voor HTML kan dit het overeenkomstige LINK‑ of STYLE‑element zijn. Voor XML kan dit de koppelings‑verwerkingsinstructie zijn. Voor stylesheets die door andere stylesheets worden opgenomen, is de waarde van dit attribuut null. |
| [getParentStyleSheet](../../com.aspose.html.dom.css/istylesheet/parentstylesheet/) Voor stylesheet‑talen die het concept van stylesheet‑inclusie ondersteunen, geeft dit attribuut de includerende stylesheet weer, indien aanwezig. Als de stylesheet een top‑level stylesheet is, of de stylesheet‑taal inclusie niet ondersteunt, is de waarde van dit attribuut null. |
| [getTitle](../../com.aspose.html.dom.css/istylesheet/title/) De title‑eigenschap van de `StyleSheet` interface retourneert de adviserende titel van de huidige stylesheet. |
| [getType](../../com.aspose.html.dom.css/istylesheet/type/) Dit specificeert de stylesheet‑taal voor deze stylesheet. De stylesheet‑taal wordt opgegeven als een content‑type (bijv. \"text/css\"). |

## Opmerkingen

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referentie

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[The StyleSheet Interface](https://drafts.csswg.org/cssom/#the-stylesheet-interface) – The official CSSOM definition.

### Zie ook

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
