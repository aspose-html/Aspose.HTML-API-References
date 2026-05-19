---
title: "Clase ValidationBuilder"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.accessibility.ValidationBuilder. La clase ValidationBuilder proporciona implementaciones concretas de los pasos de configuración. Define métodos y ajustes para una clase ValidationSettings"
type: docs

url: /es/java/com.aspose.html.accessibility/validationbuilder/
---
## ValidationBuilder class

La clase ValidationBuilder proporciona implementaciones concretas de los pasos de configuración. Define métodos y ajustes para la clase ValidationSettings.

```java
public class ValidationBuilder
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [getAll](../../com.aspose.html.accessibility/validationbuilder/all/) Incluye todos los niveles y todas las configuraciones de tecnologías |
| static [getDefault](../../com.aspose.html.accessibility/validationbuilder/default/) Configuración predeterminada: solo se utilizan tecnologías Generales y para el nivel de criterio más bajo |
| static [getNone](../../com.aspose.html.accessibility/validationbuilder/none/) Configuración nula - no se especifica ninguno de los parámetros. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [allLevels](../../com.aspose.html.accessibility/validationbuilder/alllevels/)() | Un método que establece todos los niveles de criterios y indica que el documento será verificado según los criterios de los tres niveles. |
| [allTechnologies](../../com.aspose.html.accessibility/validationbuilder/alltechnologies/)() | Un método que establece todas las tecnologías para probar el criterio. |
| [setHTMLTags](../../com.aspose.html.accessibility/validationbuilder/sethtmltags/)(params String[]) | Lista de etiquetas html a comprobar. Si las etiquetas no se especifican explícitamente, entonces la matriz de etiquetas está vacía y la comprobación se realiza en todas. |
| [useCSS](../../com.aspose.html.accessibility/validationbuilder/usecss/)() | Un método que incluye tecnologías CSS en un conjunto de reglas. |
| [useFailures](../../com.aspose.html.accessibility/validationbuilder/usefailures/)() | Un método que incluye Fallos en un conjunto de reglas. |
| [useGeneral](../../com.aspose.html.accessibility/validationbuilder/usegeneral/)() | Un método que incluye tecnologías Generales en un conjunto de reglas. |
| [useHighestLevel](../../com.aspose.html.accessibility/validationbuilder/usehighestlevel/)() | Utilizar el nivel más alto AAA del criterio en las reglas. |
| [useHTML](../../com.aspose.html.accessibility/validationbuilder/usehtml/)() | Un método que incluye tecnologías HTML en un conjunto de reglas. |
| [useLowestLevel](../../com.aspose.html.accessibility/validationbuilder/uselowestlevel/)() | Utilizar el nivel más bajo A del criterio en las reglas. |
| [useMiddleLevel](../../com.aspose.html.accessibility/validationbuilder/usemiddlelevel/)() | Utilizar el nivel medio AA del criterio en las reglas. |
| [useScript](../../com.aspose.html.accessibility/validationbuilder/usescript/)() | Un método que incluye tecnologías ClientSideScript en un conjunto de reglas. |

### Ver también

* package [com.aspose.html.accessibility](../../com.aspose.html.accessibility/)
* package [Aspose.HTML](../../)
