---
title: "ICSS2Properties.Speak"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Propriété ICSS2Properties. Cette propriété spécifie si le texte sera rendu de façon auditive et, le cas échéant, de quelle manière, de manière quelque peu analogue à la propriété display. Les valeurs possibles sont"
type: docs

url: /fr/java/com.aspose.html.dom.css/icss2properties/speak/
---
## ICSS2Properties.Speak property

Cette propriété spécifie si le texte sera rendu de façon auditive et, le cas échéant, de quelle manière (quelque peu analogue à la propriété ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) property). Les valeurs possibles sont :

none - Supprime le rendu auditif de sorte que l'élément ne nécessite aucun temps de rendu. Notez toutefois que les descendants peuvent remplacer cette valeur et seront prononcés. (Pour être certain de supprimer le rendu d'un élément et de ses descendants, utilisez la propriété ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) property). normal - Utilise des règles de prononciation dépendant de la langue pour rendre un élément et ses enfants. spell-out - Épelle le texte lettre par lettre (utile pour les acronymes et abréviations).

```java
public String Speak { get; set; }
```

### Valeur de retour

propriété speak

### Voir aussi

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
