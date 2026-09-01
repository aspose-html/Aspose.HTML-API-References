---
title: "Interface IMediaList"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "interface com.aspose.html.dom.css.IMediaList. L'interface MediaList fournit l'abstraction d'une collection ordonnée de médias sans définir ni contraindre la façon dont cette collection est implémentée. Une liste vide est équivalente à une liste contenant le média all."
type: docs

url: /fr/java/com.aspose.html.dom.css/imedialist/
---
## IMediaList interface

L'interface MediaList fournit l'abstraction d'une collection ordonnée de médias, sans définir ni contraindre la façon dont cette collection est implémentée. Une liste vide est équivalente à une liste contenant le média "all".

Voir également le [CSS Object Model (CSSOM) # ](https://www.w3.org/TR/cssom-1/#the-medialist-interface)[MediaList](https://www.w3.org/TR/cssom-1/#the-medialist-interface).

```java
public interface IMediaList : IEnumerable<String>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/imedialist/item/) La méthode item(index) doit renvoyer une sérialisation de la requête média dans la collection de requêtes média donnée par l'index, ou null, si l'index est supérieur ou égal au nombre de requêtes média dans la collection. |
| [getLength](../../com.aspose.html.dom.css/imedialist/length/) L'attribut length doit renvoyer le nombre de requêtes média dans la collection de requêtes média. L'intervalle de médias valides est de 0 à length-1 inclus. |
| [getMediaText](../../com.aspose.html.dom.css/imedialist/mediatext/) Un Stringifier qui renvoie un DOMString représentant le MediaList sous forme de texte, et permet également de définir un nouveau MediaList. |

## Méthodes

| Nom | Description |
| --- | --- |
| [appendMedium](../../com.aspose.html.dom.css/imedialist/appendmedium/)(String) | Ajoute le média newMedium à la fin de la liste. Si le newMedium est déjà utilisé, il est d'abord supprimé. |
| [deleteMedium](../../com.aspose.html.dom.css/imedialist/deletemedium/)(String) | Supprime le média indiqué par oldMedium de la liste. |

## Remarques

Remarque : MediaList est une liste dynamique ; la mise à jour de la liste à l'aide des propriétés ou des méthodes listées ci-dessous mettra immédiatement à jour le comportement du document.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Référence

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # medialist](https://drafts.csswg.org/cssom/#medialist) – The CSSOM definition.

## Exemples

Ce qui suit enregistrerait dans la console une représentation textuelle du MediaList de la première feuille de style appliquée au document actuel.

```java
var stylesheets = document.StyleSheets;
var stylesheet = stylesheets[0];
Console.Write(stylesheet.Media.MediaText);
```

### Voir aussi

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
