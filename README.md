**Deutsch** · [English](https://github.com/Raffa3l/Raffa3l/blob/main/README.en.md)

**Gebäudephysik · Energiesysteme · Klimadaten · Interaktive Werkzeuge**

**Werkzeuge aus der Praxis.**

Ich bin Ingenieur aus der Schweiz und arbeite an der Schnittstelle von Architektur, Gebäudetechnik und Daten – dort, wo Normen auf Messwerte treffen und eine Tabelle nicht mehr reicht. Ich entwickle Werkzeuge, Modelle und Visualisierungen rund um Gebäude, Raumklima und Energieversorgung und verbinde dabei physikalische Modelle mit Daten und Software, um technische Zusammenhänge verständlich und untersuchbar zu machen.

Was dabei entsteht, steht hier: kleine, offene Anwendungen, die eine Frage beantworten und sonst nichts. Gebaut, in Betrieb genommen, wieder zerlegt – was sich nicht bewährt, fliegt wieder raus. Die Themen reichen von der Auswertung thermischer Behaglichkeit über wettergestützte Lüftungsempfehlungen bis zur Analyse des Schweizer Winterstrombedarfs.

[Projekte](#ausgewählte-projekte) · [Fachgebiete](#fachgebiete) · [Arbeitsweise](#arbeitsweise) · [Kontakt](#kontakt) · [Lizenz](#lizenz)

## Ausgewählte Projekte

### SIA 180 · Thermische Behaglichkeit

[![SIA-180-Diagramm mit Raumtemperaturmessungen und Behaglichkeitsgrenzen](assets/sia-180-thermal-comfort.jpg)](https://git.logicc.ch/SIA-180-thermal-comfort/)

**Raumtemperaturen im Zusammenhang mit dem Aussenklima beurteilen.**

Interaktive Visualisierung der thermischen Behaglichkeit nach **SIA 180:2014**. Die Anwendung setzt gemessene Raumtemperaturen in Beziehung zum gleitenden 48-Stunden-Mittel der Aussentemperatur und zeigt die Behaglichkeitsgrenzen für aktiv und passiv gekühlte Gebäude.

Damit lassen sich Messdaten einordnen und Komfortbedingungen im Gebäude nachvollziehbar darstellen.

**Themen:** Gebäudephysik, thermische Behaglichkeit, Raumklima, Normen  
**Technologie:** Python, Pandas, NumPy, Plotly

[Repository](https://github.com/Raffa3l/SIA-180-thermal-comfort) · [Anwendung öffnen](https://git.logicc.ch/SIA-180-thermal-comfort/)

### Lüftungsassistent

[![Lüftungsassistent mit Lüftungsempfehlung und prognostiziertem Temperaturverlauf für Zürich](assets/lueftungsassistent.jpg)](https://git.logicc.ch/Lueftungsassistent/)

<sub>Beispielansicht vom 12.09.2026. Wetterdaten und Empfehlungen ändern sich laufend.</sub>

**Sommerlüftung und passive Kühlung gezielt nutzen.**

Der Lüftungsassistent verbindet Wetterprognosen mit einem vereinfachten thermischen Raummodell. Er schätzt die Entwicklung der Raumtemperatur ab und unterstützt die Entscheidung, wann das Öffnen der Fenster sinnvoll ist.

Das Modell berücksichtigt unter anderem Speichermasse, Raumnutzung, Belegung, Fensterorientierung, solare Gewinne und Sonnenschutz. Wetterdaten zu Temperatur, Feuchtigkeit und Wind ergänzen die Beurteilung von Lüftung und Nachtkühlung.

Gedacht für Wohnungen, Schulzimmer und Büros.

**Themen:** Sommerlicher Wärmeschutz, passive Kühlung, Gebäudephysik, Wetterdaten  
**Technologie:** TypeScript, Vite, SVG, Open-Meteo

[Repository](https://github.com/Raffa3l/Lueftungsassistent) · [Anwendung öffnen](https://git.logicc.ch/Lueftungsassistent/)

### Winterstromlücke Schweiz 2050

[![Winterstromanalyse mit einem Basiswert von 10.7 TWh und einem Vergleich der Szenarien](assets/winterstromluecke-2050.jpg)](https://git.logicc.ch/Winterstromluecke-2050/)

**Den Einfluss des Gebäudesektors auf die saisonale Stromversorgung erkunden.**

Interaktive Parameteranalyse auf Grundlage der [Studie von Kelevitz et al. (2025)](https://doi.org/10.3390/en18215601). Die Anwendung veranschaulicht, wie vier Einflussgrössen die projizierte Schweizer Winterstromlücke im Jahr 2050 verändern:

- Sanierungsrate der Gebäudehülle
- Wärmerückgewinnung beim Warmwasser
- Anteil der Erdsonden-Wärmepumpen
- Angenommene Klimaerwärmung

Die Berechnung kombiniert die publizierten Einzelszenarien als additive Näherung. So werden Zusammenhänge zwischen Gebäudesanierung, Wärmeversorgung und Strombedarf interaktiv zugänglich.

**Themen:** Energiesysteme, Wärmepumpen, Gebäudepark, Winterstrombedarf  
**Technologie:** JavaScript, Chart.js

[Repository](https://github.com/Raffa3l/Winterstromluecke-2050) · [Anwendung öffnen](https://git.logicc.ch/Winterstromluecke-2050/)

## Fachgebiete

| Fachgebiet | Schwerpunkte |
| :--- | :--- |
| **Gebäudephysik** | Thermische Behaglichkeit, sommerlicher Wärmeschutz, Feuchtigkeit und Raumklima |
| **Klima- und Wetterdaten** | Meteorologische Datensätze auswerten und für Gebäudefragen nutzbar machen |
| **Energiesysteme** | Wärmepumpen, Elektrifizierung, Photovoltaik und saisonaler Strombedarf |
| **Gebäudetechnik** | Lüftung, Heizung, Kühlung und Betriebsoptimierung |

Besonders interessieren mich die Wechselwirkungen zwischen diesen Bereichen: Wie verändert das Klima die Anforderungen an Gebäude? Was leisten Sonnenschutz und Nachtkühlung? Und wie wirken sich Entscheidungen im Gebäudepark auf das Energiesystem aus?

## Weitere Werkzeuge und Experimente

### todo.txt App

Eine Aufgabenverwaltung auf Basis des offenen Klartextformats **todo.txt**. Die Anwendung läuft vollständig im Browser, ohne Backend und Datenbank. Aufgaben können als Textdateien importiert und exportiert werden.

**Technologie:** JavaScript, HTML, CSS

[Repository](https://github.com/Raffa3l/todo.txt-App) · [Anwendung öffnen](https://git.logicc.ch/todo.txt-App/)

Weitere Experimente wie [Memex](https://github.com/Raffa3l/Memex) widmen sich dem persönlichen Wissens- und Informationsmanagement.

[Alle öffentlichen Repositories ansehen](https://github.com/Raffa3l?tab=repositories)

## Arbeitsweise

- **Physik verständlich machen.** Modelle, Annahmen und Einheiten sollen nachvollziehbar bleiben.
- **Zusammenhänge zeigen.** Interaktive Werkzeuge sollen erklären, wie Eingaben die Ergebnisse beeinflussen.
- **Komplexität begrenzen.** Ich suche das einfachste Modell, das zur jeweiligen Fragestellung passt.
- **Daten prüfbar halten.** Quellen, Annahmen und Verarbeitungsschritte sollen möglichst dokumentiert sein.
- **Bedienbarkeit ernst nehmen.** Ein technisches Werkzeug muss verständlich und im Alltag nutzbar sein.
- **Infrastruktur bewusst wählen.** Für viele meiner Projekte genügt eine statische Anwendung ohne Server oder Benutzerkonto.
- **In der Praxis prüfen.** Ein Modell bewährt sich erst an Messwerten und im Betrieb. Dort zeigen sich wirksame Ansätze, unerwartete Ergebnisse und die Fragen, denen nachzugehen sich lohnt.
- **Offen teilen.** Quelltext, Annahmen und Ergebnisse veröffentliche ich so, dass andere darauf aufbauen können.

## Technologie

Die Wahl der Werkzeuge richtet sich nach der technischen Fragestellung.

| Bereich | Werkzeuge |
| :--- | :--- |
| Sprachen | Python, TypeScript, JavaScript, HTML, CSS |
| Daten und Visualisierung | Pandas, NumPy, Plotly, Chart.js, SVG |
| Entwicklung und Veröffentlichung | Git, Vite, GitHub Actions, GitHub Pages |

Meine Repositories enthalten sowohl Forschungsprototypen als auch Anwendungen für praktische Fragestellungen. Die Dokumentation ist je nach Projekt auf Deutsch oder Englisch verfasst.

## Kontakt

**Forschung & Experimente** [logicc.ch](https://logicc.ch)

**GitHub** [github.com/Raffa3l](https://github.com/Raffa3l)

**E-Mail:** hello [at] logicc [dot] ch

## Lizenz

Meine Projekte stehen unter der MIT-Lizenz. Massgebend sind die Bedingungen im jeweiligen Repository.
