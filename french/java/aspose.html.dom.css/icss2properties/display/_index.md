---
title: "ICSS2Properties.Display"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Propriété ICSS2Properties. Les valeurs de cette propriété ont les significations suivantes"
type: docs

url: /fr/java/com.aspose.html.dom.css/icss2properties/display/
---
## ICSS2Properties.Display property

Les valeurs de cette propriété ont les significations suivantes :

block - Cette valeur fait qu'un élément génère une boîte de bloc principale.inline - Cette valeur fait qu'un élément génère une ou plusieurs boîtes en ligne.list-item - Cette valeur fait qu'un élément (par ex., LI en HTML) génère une boîte de bloc principale et une boîte en ligne de type list-item. Pour des informations sur les listes et des exemples de formatage de listes, veuillez consulter la section sur [lists](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#lists).marker - Cette valeur déclare du [generated content](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html) avant ou après une boîte comme étant un marqueur. Cette valeur ne doit être utilisée qu'avec les pseudo‑éléments [:before et :after](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#before-after-content) attachés aux éléments de type bloc. Dans les autres cas, cette valeur est interprétée comme « inline ». Veuillez consulter la section sur [markers](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#markers) pour plus d'informations.none - Cette valeur fait qu'un élément ne génère aucune boîte dans la [formatting structure](https://www.w3.org/TR/1998/REC-CSS2-19980512/intro.html#formatting-structure) (i.e., l'élément n'a aucun effet sur la mise en page). Les éléments descendants ne génèrent aucune boîte non plus ; ce comportement ne peut pas être remplacé en définissant la propriété ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) sur les descendants. Veuillez noter qu'un affichage « none » ne crée pas de boîte invisible ; il ne crée aucune boîte. CSS comprend des mécanismes qui permettent à un élément de générer des boîtes dans la structure de formatage qui affectent le formatage mais ne sont pas visibles elles‑mêmes. Veuillez consulter la section sur [visibility](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#visibility) pour plus de détails.run-in and compact - Ces valeurs créent soit des boîtes de type bloc, soit des boîtes en ligne, selon le contexte. Les propriétés s'appliquent aux boîtes run‑in et compact en fonction de leur statut final (inline‑level ou block‑level). Par exemple, la propriété ['white-space'](https://www.w3.org/TR/1998/REC-CSS2-19980512/text.html#propdef-white-space) ne s'applique que si la boîte devient une boîte de type bloc.table, inline-table, table‑row‑group, [table‑column](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#value-def-table-column), table‑column‑group, table‑header‑group, table‑footer‑group, table‑row, table‑cell, et table‑caption - Ces valeurs font qu'un élément se comporte comme un élément de tableau (sous réserve des restrictions décrites dans le chapitre sur les [tables](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html)).

```java
public String Display { get; set; }
```

### Valeur de retour

propriété display

### Voir aussi

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
