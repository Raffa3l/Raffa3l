<p align="center">
  <a href="https://git.logicc.ch/"><img src="https://img.shields.io/badge/Lab-git.logicc.ch-0F172A?style=flat-square&logo=githubpages&logoColor=white" alt="Lab"></a>
  <a href="https://github.com/Raffa3l?tab=repositories"><img src="https://img.shields.io/badge/Repositories-GitHub-0F172A?style=flat-square&logo=github&logoColor=white" alt="Repositories"></a>
  <a href="#contact"><img src="https://img.shields.io/badge/Contact-Email-0F172A?style=flat-square&logo=maildotru&logoColor=white" alt="Contact"></a>
</p>

<p align="center">
  <a href="https://github.com/Raffa3l/Raffa3l/blob/main/README.md">Deutsch</a> · <b>English</b>
</p>

**Tools built for practice.**

Raffael is a Swiss engineer working at the intersection of architecture, MEP and data – where standards meet measurements and a spreadsheet is no longer enough. He develops open, interactive tools that combine physical models with data and software. At [logicc.ch](https://logicc.ch) he brings together his work at the execution and research level.

<p align="center">> Developed, put into operation, reviewed, taken apart again – whatever does not prove itself is dropped.
</p>

<p align="center">Try all tools directly at
  <a href="https://git.logicc.ch/">git.logicc.ch</a> or browse the <a href="https://github.com/Raffa3l?tab=repositories">repositories</a>.
</p>

## Selected Work

| Project | Focus | Why it is useful |
| --- | --- | --- |
| [SIA 180 · Thermal Comfort](https://github.com/Raffa3l/SIA-180-thermal-comfort) | Building physics, standards | Interpret measured room temperatures according to SIA 180:2014 and visualise comfort limits. |
| [Lüftungsassistent · Ventilation Assistant](https://github.com/Raffa3l/Lueftungsassistent) | Summer heat protection | Decide hour by hour whether windows should be open or closed – based on weather forecasts and a room model. |
| [Winterstromlücke 2050 · Swiss Winter Electricity Gap](https://github.com/Raffa3l/Winterstromluecke-2050) | Energy systems | Explore how renovation, heat pumps and climate change the Swiss winter electricity gap. |
| [todo.txt App](https://github.com/Raffa3l/todo.txt-App) | Tool | Manage tasks in the open plain-text format – entirely in the browser, without a backend. |
| [Memex](https://github.com/Raffa3l/Memex) | Knowledge management | A personal knowledge system in which an LLM builds and maintains a wiki from PDFs. |

### SIA 180 · Thermal Comfort

[![SIA 180 chart showing measured room temperatures and thermal comfort limits](assets/sia-180-thermal-comfort.jpg)](https://git.logicc.ch/SIA-180-thermal-comfort/)

**Assessing room temperatures in relation to outdoor conditions.** The application relates measured room temperatures to the 48-hour rolling mean outdoor temperature and displays the comfort limits for actively and passively cooled buildings according to **SIA 180:2014**.

<p>
  <img src="https://img.shields.io/badge/Python-0F172A?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-0F172A?style=flat-square&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/NumPy-0F172A?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/Plotly-0F172A?style=flat-square&logo=plotly&logoColor=white" alt="Plotly">
</p>

[Open App →](https://git.logicc.ch/SIA-180-thermal-comfort/) · [Repository](https://github.com/Raffa3l/SIA-180-thermal-comfort)

### Lüftungsassistent · Ventilation Assistant

[![Ventilation assistant showing a ventilation recommendation and predicted temperature curves for Zurich](assets/lueftungsassistent.jpg)](https://git.logicc.ch/Lueftungsassistent/)

<sub>Example captured on 12 September 2026. Weather data and recommendations change over time.</sub>

**Making effective use of summer ventilation and passive cooling.** The ventilation assistant combines weather forecasts with a simplified thermal room model and considers thermal mass, room use, occupancy, window orientation, solar gains and solar protection. Designed for homes, classrooms and offices.

<p>
  <img src="https://img.shields.io/badge/TypeScript-0F172A?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Vite-0F172A?style=flat-square&logo=vite&logoColor=white" alt="Vite">
  <img src="https://img.shields.io/badge/SVG-0F172A?style=flat-square&logo=svg&logoColor=white" alt="SVG">
  <img src="https://img.shields.io/badge/Open--Meteo-0F172A?style=flat-square" alt="Open-Meteo">
</p>

[Open App →](https://git.logicc.ch/Lueftungsassistent/) · [Repository](https://github.com/Raffa3l/Lueftungsassistent)

### Winterstromlücke Schweiz 2050 · Swiss Winter Electricity Gap

[![Winter electricity analysis showing a baseline of 10.7 TWh and a comparison of scenarios](assets/winterstromluecke-2050.jpg)](https://git.logicc.ch/Winterstromluecke-2050/)

**Exploring how the building sector influences seasonal electricity supply.** Interactive parameter analysis based on the [study by Kelevitz et al. (2025)](https://doi.org/10.3390/en18215601): renovation rate, domestic hot-water heat recovery, share of ground-source heat pumps and climate warming are combined using an additive approximation.

<p>
  <img src="https://img.shields.io/badge/JavaScript-0F172A?style=flat-square&logo=javascript&logoColor=white" alt="JavaScript">
  <img src="https://img.shields.io/badge/Chart.js-0F172A?style=flat-square&logo=chartdotjs&logoColor=white" alt="Chart.js">
</p>

[Open App →](https://git.logicc.ch/Winterstromluecke-2050/) · [Repository](https://github.com/Raffa3l/Winterstromluecke-2050)

## Fields

| Field | Focus |
| --- | --- |
| **Building Physics** | Thermal comfort, summer heat protection, solar gains, building envelope, moisture and indoor climate |
| **Climate and Weather Data** | Analysing meteorological datasets and making them useful for building-related questions |
| **Energy Systems** | Heat pumps and cooling supply, electrification, photovoltaics, seasonal storage and winter electricity demand |
| **MEP** | Ventilation, heating, active and passive cooling, night cooling, domestic hot water, heat recovery, measurement data and operational optimisation |

I am particularly interested in the interactions: How does a changing climate affect building requirements? How do decisions across the building stock affect the energy system?

## Approach

| Principle | What it means |
| --- | --- |
| **Make the physics understandable** | Models, assumptions and units remain transparent. |
| **Limit complexity** | The simplest model that suits the question. |
| **Keep data inspectable** | Sources, assumptions and processing steps are documented. |
| **Choose infrastructure deliberately** | As much infrastructure as necessary, as simple and efficient as possible. |
| **Test against practice** | A model proves itself against measurements and in operation. |
| **Share openly** | Publish source code, assumptions and results so that others can build on them. |

## Toolkit

| Layer | Tools |
| --- | --- |
| **Languages** | Python · TypeScript · JavaScript · HTML · CSS |
| **Data & Visualisation** | Pandas · NumPy · MATLAB · KNIME · Plotly · Chart.js · SVG |
| **Development & Publishing** | Git · Vite · GitHub Actions · GitHub Pages |
| **Working mode** | Develop · put into operation · review · share openly |

The repositories include research prototypes as well as applications for practical questions. Documentation is written in German or English, depending on the project.

## Contact

- **Lab:** [git.logicc.ch](https://git.logicc.ch/)
- **Code:** [@Raffa3l on GitHub](https://github.com/Raffa3l)
- **Email:** hello [at] logicc [dot] ch

## License

The projects are released under the MIT License. The terms in each repository are authoritative.
