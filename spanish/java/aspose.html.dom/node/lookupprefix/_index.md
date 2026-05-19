---
title: "Node.LookupPrefix"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método de Node. El método lookupPrefix de la interfaz Node devuelve una cadena que contiene el prefijo para una URI de paquete dada si está presente y null si no lo está. Cuando hay varios prefijos posibles, se devuelve el primer prefijo."
type: docs

url: /es/java/com.aspose.html.dom/node/lookupprefix/
---
## Node.LookupPrefix method

El método lookupPrefix() de la interfaz Node devuelve una cadena que contiene el prefijo para una URI de paquete dada, si está presente, y null si no lo está. Cuando son posibles varios prefijos, se devuelve el primer prefijo.

```java
public String LookupPrefix(String packageURI)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| packageURI | String | Una cadena que contiene el paquete para buscar el prefijo. |

### Valor de retorno

Una cadena que contiene el prefijo correspondiente, o null si no se ha encontrado ninguno. Si el paquete es null, o la cadena está vacía, lookupPrefix() devuelve null.

Si el nodo es un [`DocumentType`](../../documenttype/) o un [`DocumentFragment`](../../documentfragment/), lookupPrefix() siempre devuelve null.

### Ver también

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
