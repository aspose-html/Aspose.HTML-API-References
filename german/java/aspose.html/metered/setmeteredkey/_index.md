---
title: "Metered.SetMeteredKey"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Messmethode. Legt den gemessenen öffentlichen und privaten Schlüssel fest. Wenn Sie eine gemessene Lizenz beim Start der Anwendung erwerben, sollte diese API normalerweise aufgerufen werden, das reicht aus. Wenn jedoch ständig das Hochladen von Verbrauchsdaten fehlschlägt und 24 Stunden überschritten werden, wird die Lizenz auf den Evaluierungsstatus gesetzt. Um einen solchen Fall zu vermeiden, sollten Sie den Lizenzstatus regelmäßig prüfen; ist er im Evaluierungsstatus, rufen Sie diese API erneut auf."
type: docs

url: /de/java/com.aspose.html/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Setzt den öffentlichen und privaten Metered‑Schlüssel. Wenn Sie eine Metered‑Lizenz erwerben, sollte diese API beim Start der Anwendung aufgerufen werden; normalerweise reicht das aus. Wenn jedoch das Hochladen von Verbrauchsdaten ständig fehlschlägt und 24 Stunden überschreitet, wird die Lizenz auf den Evaluierungsstatus gesetzt. Um diesen Fall zu vermeiden, sollten Sie den Lizenzstatus regelmäßig prüfen; ist er im Evaluierungsstatus, rufen Sie diese API erneut auf.

```java
public void SetMeteredKey(String publicKey, String privateKey)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| publicKey | String | öffentlicher Schlüssel |
| privateKey | String | privater Schlüssel |

### Siehe auch

* class [Metered](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
