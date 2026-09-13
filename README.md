<p align="center">
  <a href="https://git.logicc.ch/"><img src="https://img.shields.io/badge/Labor-git.logicc.ch-0F172A?style=flat-square&logo=githubpages&logoColor=white" alt="Labor"></a>
  <a href="https://github.com/Raffa3l?tab=repositories"><img src="https://img.shields.io/badge/Repositories-GitHub-0F172A?style=flat-square&logo=github&logoColor=white" alt="Repositories"></a>
  <a href="#kontakt"><img src="https://img.shields.io/badge/Kontakt-E--Mail-0F172A?style=flat-square&logo=maildotru&logoColor=white" alt="Kontakt"></a>
</p>

<p align="center">
  <b>Deutsch</b> · <a href="https://github.com/Raffa3l/Raffa3l/blob/main/README.en.md">English</a>
</p>

**Werkzeuge aus der Praxis.**

Raffael ist Ingenieur aus der Schweiz und arbeitet an der Schnittstelle von Architektur, Gebäudetechnik und Daten – dort, wo Normen auf Messwerte treffen und eine Tabelle nicht mehr reicht. Er entwickelt offene, interaktive Werkzeuge, die physikalische Modelle mit Daten und Software verbinden. Unter [logicc.ch](https://logicc.ch) bündelt er seine Arbeit auf Ausführungs- und Forschungsebene.

<p align="center">> Entwickelt, in Betrieb genommen, überprüft, wieder zerlegt – was sich nicht bewährt, fliegt wieder raus.
</p>

<p align="center">Alle Werkzeuge direkt ausprobieren unter
  <a href="https://git.logicc.ch/">git.logicc.ch</a> oder die <a href="https://github.com/Raffa3l?tab=repositories">Repositories</a> ansehen.
</p>

## Ausgewählte Arbeiten

| Projekt | Fokus | Wozu es nützt |
| --- | --- | --- |
| [SIA 180 · Thermische Behaglichkeit](https://github.com/Raffa3l/SIA-180-thermal-comfort) | Gebäudephysik, Normen | Gemessene Raumtemperaturen nach SIA 180:2014 einordnen und Komfortgrenzen sichtbar machen. |
| [Lüftungsassistent](https://github.com/Raffa3l/Lueftungsassistent) | Sommerlicher Wärmeschutz | Stündlich entscheiden, ob Fenster offen oder geschlossen sein sollten – auf Basis von Wetterprognose und Raummodell. |
| [Winterstromlücke 2050](https://github.com/Raffa3l/Winterstromluecke-2050) | Energiesysteme | Erkunden, wie Sanierung, Wärmepumpen und Klima die Schweizer Winterstromlücke verändern. |
| [todo.txt App](https://github.com/Raffa3l/todo.txt-App) | Werkzeug | Aufgaben im offenen Klartextformat verwalten – vollständig im Browser, ohne Backend. |
| [Memex](https://github.com/Raffa3l/Memex) | Wissensmanagement | Ein persönliches Wissenssystem, das ein LLM aus PDFs als Wiki aufbaut und pflegt. |

### SIA 180 · Thermische Behaglichkeit

[![SIA-180-Diagramm mit Raumtemperaturmessungen und Behaglichkeitsgrenzen](assets/sia-180-thermal-comfort.jpg)](https://git.logicc.ch/SIA-180-thermal-comfort/)

**Raumtemperaturen im Zusammenhang mit dem Aussenklima beurteilen.** Die Anwendung setzt gemessene Raumtemperaturen in Beziehung zum gleitenden 48-Stunden-Mittel der Aussentemperatur und zeigt die Behaglichkeitsgrenzen für aktiv und passiv gekühlte Gebäude nach **SIA 180:2014**.

<p>
  <img src="https://img.shields.io/badge/Python-0F172A?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-0F172A?style=flat-square&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/NumPy-0F172A?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/Plotly-0F172A?style=flat-square&logo=plotly&logoColor=white" alt="Plotly">
</p>

[Anwendung öffnen →](https://git.logicc.ch/SIA-180-thermal-comfort/) · [Repository](https://github.com/Raffa3l/SIA-180-thermal-comfort)

### Lüftungsassistent

[![Lüftungsassistent mit Lüftungsempfehlung und prognostiziertem Temperaturverlauf für Zürich](assets/lueftungsassistent.jpg)](https://git.logicc.ch/Lueftungsassistent/)

<sub>Beispielansicht vom 12.09.2026. Wetterdaten und Empfehlungen ändern sich laufend.</sub>

**Sommerlüftung und passive Kühlung gezielt nutzen.** Der Lüftungsassistent verbindet Wetterprognosen mit einem vereinfachten thermischen Raummodell und berücksichtigt Speichermasse, Nutzung, Belegung, Fensterorientierung, solare Gewinne und Sonnenschutz. Gedacht für Wohnungen, Schulzimmer und Büros.

<p>
  <img src="https://img.shields.io/badge/TypeScript-0F172A?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Vite-0F172A?style=flat-square&logo=vite&logoColor=white" alt="Vite">
  <img src="https://img.shields.io/badge/SVG-0F172A?style=flat-square&logo=svg&logoColor=white" alt="SVG">
  <img src="https://img.shields.io/badge/Open--Meteo-0F172A?style=flat-square" alt="Open-Meteo">
</p>

[Anwendung öffnen →](https://git.logicc.ch/Lueftungsassistent/) · [Repository](https://github.com/Raffa3l/Lueftungsassistent)

### Winterstromlücke Schweiz 2050

[![Winterstromanalyse mit einem Basiswert von 10.7 TWh und einem Vergleich der Szenarien](assets/winterstromluecke-2050.jpg)](https://git.logicc.ch/Winterstromluecke-2050/)

**Den Einfluss des Gebäudesektors auf die saisonale Stromversorgung erkunden.** Interaktive Parameteranalyse auf Grundlage der [Studie von Kelevitz et al. (2025)](https://doi.org/10.3390/en18215601): Sanierungsrate, Wärmerückgewinnung beim Warmwasser, Anteil der Erdsonden-Wärmepumpen und Klimaerwärmung werden als additive Näherung kombiniert.

<p>
  <img src="https://img.shields.io/badge/JavaScript-0F172A?style=flat-square&logo=javascript&logoColor=white" alt="JavaScript">
  <img src="https://img.shields.io/badge/Chart.js-0F172A?style=flat-square&logo=chartdotjs&logoColor=white" alt="Chart.js">
</p>

[Anwendung öffnen →](https://git.logicc.ch/Winterstromluecke-2050/) · [Repository](https://github.com/Raffa3l/Winterstromluecke-2050)

## Fachgebiete

| Fachgebiet | Schwerpunkte |
| --- | --- |
| **Gebäudephysik** | Thermische Behaglichkeit, sommerlicher Wärmeschutz, solare Gewinne, Gebäudehülle, Feuchtigkeit und Raumklima |
| **Klima- und Wetterdaten** | Meteorologische Datensätze auswerten und für Gebäudefragen nutzbar machen |
| **Energiesysteme** | Wärmepumpen und Kälteversorgung, Elektrifizierung, Photovoltaik, saisonale Speicherung und Winterstrombedarf |
| **Gebäudetechnik** | Lüftung, Heizung, aktive und passive Kühlung, Nachtkühlung, Warmwasser, Wärmerückgewinnung, Messdaten und Betriebsoptimierung |

Besonders interessieren mich die Wechselwirkungen: Wie verändert das Klima die Anforderungen an Gebäude? Wie wirken sich Entscheidungen im Gebäudepark auf das Energiesystem aus?

## Arbeitsweise

| Prinzip | Was das heisst |
| --- | --- |
| **Physik verständlich machen** | Modelle, Annahmen und Einheiten bleiben nachvollziehbar. |
| **Komplexität begrenzen** | Das einfachste Modell, das zur Fragestellung passt. |
| **Daten prüfbar halten** | Quellen, Annahmen und Verarbeitungsschritte sind dokumentiert. |
| **Infrastruktur bewusst wählen** | So viel Infrastruktur wie nötig, so einfach und effizient wie möglich. |
| **In der Praxis prüfen** | Ein Modell bewährt sich erst an Messwerten und im Betrieb. |
| **Offen teilen** | Quelltext, Annahmen und Ergebnisse so veröffentlichen, dass andere darauf aufbauen können. |

## Werkzeugkasten

| Ebene | Werkzeuge |
| --- | --- |
| **Sprachen** | Python · TypeScript · JavaScript · HTML · CSS |
| **Daten & Visualisierung** | Pandas · NumPy · MATLAB · KNIME · Plotly · Chart.js · SVG |
| **Entwicklung & Veröffentlichung** | Git · Vite · GitHub Actions · GitHub Pages |
| **Arbeitsmodus** | Entwickeln · in Betrieb nehmen · überprüfen · offen teilen |

Die Repositories enthalten Forschungsprototypen ebenso wie Anwendungen für praktische Fragestellungen. Die Dokumentation ist je nach Projekt auf Deutsch oder Englisch verfasst.

## Kontakt

- **Labor:** [git.logicc.ch](https://git.logicc.ch/)
- **Code:** [@Raffa3l auf GitHub](https://github.com/Raffa3l)
- **E-Mail:** hello [at] logicc [dot] ch

## Lizenz

Die Projekte stehen unter der MIT-Lizenz. Massgebend sind die Bedingungen im jeweiligen Repository.
