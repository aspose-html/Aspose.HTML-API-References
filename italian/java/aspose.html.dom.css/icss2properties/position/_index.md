---
title: "ICSS2Properties.Position"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Proprietà ICSS2Properties. I valori di questa proprietà hanno i seguenti significati"
type: docs

url: /it/java/com.aspose.html.dom.css/icss2properties/position/
---
## ICSS2Properties.Position property

I valori di questa proprietà hanno i seguenti significati:

static - La casella è una casella normale, disposta secondo il [normal flow](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#normal-flow). Le proprietà ['left'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-left) e ['top'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-top) non si applicano.relative - La posizione della casella è calcolata secondo il [normal flow](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#normal-flow) (questo è chiamato posizione nel flusso normale). Poi la casella è spostata [relative](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#relative-positioning) alla sua posizione normale. Quando una casella B è posizionata in modo relativo, la posizione della casella successiva è calcolata come se B non fosse spostata.absolute - La posizione (e possibilmente le dimensioni) della casella è specificata con le proprietà ['left'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-left), ['right'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-right), ['top'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-top) e ['bottom'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-bottom). Queste proprietà specificano gli offset rispetto al [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block) della casella. Le caselle posizionate assolutamente sono rimosse dal flusso normale. Ciò significa che non influenzano il layout dei fratelli successivi. Inoltre, sebbene le caselle [absolutely positioned](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#absolutely-positioned) abbiano i margini, non [collapse](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#collapsing-margins) con altri margini.fixed - La posizione della casella è calcolata secondo il modello 'absolute', ma in più la casella è [fixed](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#fixed-positioning) rispetto a qualche riferimento. Nel caso dei [continuous media](https://www.w3.org/TR/1998/REC-CSS2-19980512/media.html#continuous-media-group), la casella è fissata rispetto al [viewport](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#viewport) (e non si muove durante lo scorrimento). Nel caso dei [paged media](https://www.w3.org/TR/1998/REC-CSS2-19980512/media.html#paged-media-group), la casella è fissata rispetto alla pagina, anche se quella pagina è visualizzata tramite un [viewport](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#viewport) (ad esempio in anteprima di stampa). Gli autori potrebbero desiderare specificare 'fixed' in modo dipendente dal media.

```java
public String Position { get; set; }
```

### Valore di ritorno

proprietà position

### Vedi anche

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
