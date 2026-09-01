---
title: "ICSS2Properties.Overflow"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "ICSS2Properties property. Cette propriété spécifie si le contenu d'un élément de niveau bloc est découpé lorsqu'il dépasse la boîte de l'élément qui agit comme bloc contenant pour le contenu. Les valeurs ont les significations suivantes"
type: docs

url: /fr/java/com.aspose.html.dom.css/icss2properties/overflow/
---
## ICSS2Properties.Overflow property

Cette propriété spécifie si le contenu d'un élément de niveau bloc est découpé lorsqu'il dépasse la boîte de l'élément (qui agit comme bloc contenant pour le contenu). Les valeurs ont les significations suivantes :

visible - Cette valeur indique que le contenu n'est pas découpé, c.-à-d. qu'il peut être rendu en dehors de la boîte de bloc. hidden - Cette valeur indique que le contenu est découpé et qu'aucun mécanisme de défilement ne doit être fourni pour visualiser le contenu en dehors de la région de découpage ; les utilisateurs n'auront pas accès au contenu découpé. La taille et la forme de la région de découpage sont spécifiées par la propriété ['clip'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#propdef-clip) scroll - Cette valeur indique que le contenu est découpé et que, si l'agent utilisateur utilise un mécanisme de défilement visible à l'écran (comme une barre de défilement ou un pointeur), ce mécanisme doit être affiché pour la boîte, que son contenu soit découpé ou non. Cela évite tout problème d'apparition et de disparition des barres de défilement dans un environnement dynamique. Lorsque cette valeur est spécifiée et que le support cible est « print » ou « projection », le contenu débordant doit être imprimé. auto - Le comportement de la valeur « auto » dépend de l'agent utilisateur, mais doit entraîner la mise à disposition d'un mécanisme de défilement pour les boîtes débordantes.

```java
public String Overflow { get; set; }
```

### Valeur de retour

propriété overflow

### Voir aussi

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
