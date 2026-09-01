---
title: "ICSS2Properties.Clear"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Propriété ICSS2Properties. Cette propriété indique quels côtés des boîtes d'un élément ne peuvent pas être adjacents à une boîte flottante antérieure. Il se peut que l'élément lui‑même possède des descendants flottants ; la propriété clear n'a aucun effet sur ceux‑ci."
type: docs

url: /fr/java/com.aspose.html.dom.css/icss2properties/clear/
---
## ICSS2Properties.Clear property

Cette propriété indique quels côtés de la ou des boîtes d'un élément ne peuvent pas être adjacents à une boîte flottante antérieure. (Il se peut que l'élément lui‑même possède des descendants flottants ; la propriété « clear » n'a aucun effet sur ceux‑ci.)

Cette propriété ne peut être spécifiée que pour les éléments de type bloc (y compris les flottants). Pour les boîtes compactes et en‑ligne, cette propriété s'applique à la boîte bloc finale à laquelle la boîte compacte ou en‑ligne appartient.

Les valeurs ont les significations suivantes lorsqu'elles sont appliquées à des boîtes de bloc non flottantes :

left - La marge supérieure de la boîte générée est augmentée suffisamment pour que le bord supérieur soit en dessous du bord extérieur inférieur de toutes les boîtes flottantes à gauche résultant d'éléments précédents dans le document source. right - La marge supérieure de la boîte générée est augmentée suffisamment pour que le bord supérieur soit en dessous du bord extérieur inférieur de toutes les boîtes flottantes à droite résultant d'éléments précédents dans le document source. both - La boîte générée est déplacée sous toutes les boîtes flottantes des éléments antérieurs dans le document source. none - Aucune contrainte sur la position de la boîte par rapport aux flottants.

```java
public String Clear { get; set; }
```

### Valeur de retour

propriété clear

### Voir aussi

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
