README.md# mcp://thewald — capability server

Ein Kompetenzkatalog im Stil eines MCP-Tool-Manifests statt eines klassischen Lebenslaufs.

**Live:** https://thewald-git.github.io/

---

## Worum es hier geht

Dieses Repository hostet eine private, nicht-kommerzielle GitHub-Pages-Seite, die berufliche
Fähigkeiten als aufrufbare „Tools" im Stil eines MCP-Server-Manifests darstellt — als Analogie,
nicht als funktionierendes Protokoll. Es gibt **keinen echten MCP-Server**, keine API und keinen
Code, der das Model Context Protocol implementiert. `mcp.json` in diesem Repo ist eine
illustrative Beschreibung, keine ausführbare Server-Definition.

## server.describe()

| Feld            | Wert                                              |
|------------------|---------------------------------------------------|
| `name`           | thewald                                            |
| `role`           | Technology Strategist — tandem model               |
| `domains`        | cloud, telco, GenAI, standards, enablement         |
| `operatingMode`  | influence without direct-line authority            |
| `status`         | open to new invocations                            |

## available tools

| Tool                                      | bestInvokedWhen |
|--------------------------------------------|-----------------|
| `thewald::tandem_deal_architect`           | ein Deal braucht technische Tiefe UND kommerzielles Momentum gleichzeitig, aber niemand deckt beides glaubwürdig ab |
| `thewald::standards_consensus_broker`      | mehrere Firmen/Abteilungen müssen sich auf einen Standard, eine Architektur oder ein Framework einigen |
| `thewald::ecosystem_scaler`                | ein Unternehmen hat ein Produkt, aber kein Partner-Netzwerk, das es trägt |
| `thewald::sector_builder_from_zero`        | ein neues, noch unbesetztes Marktsegment existiert, aber niemand hat den ersten Entwurf gemacht |
| `thewald::bleeding_edge_scout`              | eine neue Technologie entsteht und niemand im Haus kann sie glaubwürdig auf Geschäftsrelevanz herunterbrechen |
| `thewald::enablement_coach`                 | Wissen sitzt bei zu wenigen Köpfen und muss skaliert werden |
| `thewald::exec_trust_broker`                | eine Initiative braucht Rückendeckung von Leuten, die dir nicht unterstellt sind |

`knownLimitation`: kein Interesse an Tools, die reine Projektlieferung/Legacy-Betrieb oder
klassische Vertriebsquote abdecken.

Das vollständige Manifest inkl. `evidence` je Tool steht in [`mcp.json`](./mcp.json) und live
gerendert auf der [Seite selbst](https://thewald-git.github.io/).

## server.invoke()

Kontaktformular auf der Seite (öffnet das eigene Mailprogramm mit vorausgefülltem Betreff) oder
direkt per Mail an **thilo.ewald+mcp@gmail.com**.

## Tech-Stack

- Reines HTML/CSS/JS, keine Build-Pipeline, keine Abhängigkeiten
- Hosting: GitHub Pages (`main`-Branch, Root `/`)
- Kontaktweg: `mailto:`-Link — kein Backend, kein Tracking, kein Drittanbieter-Formulardienst

## Dateien

| Datei | Zweck |
|---|---|
| [`index.html`](./index.html) | die eigentliche Seite |
| [`mcp.json`](./mcp.json) | das Kompetenz-Manifest als strukturierte Daten (illustrativ, siehe oben) |
| [`LICENSE`](./LICENSE) | MIT-Lizenz |

## Lizenz

MIT — siehe [LICENSE](./LICENSE).
