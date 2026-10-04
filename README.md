<div align="center">

# 🏙️ Courtyard Rise
### Nature-Integrated B+G+9 Mixed-Use Building

*From **"a plot in the city"** to **"a building that breathes"***

![SIH 2026](https://img.shields.io/badge/Smart%20India%20Hackathon-2026-E85A9B?style=for-the-badge)
![PS](https://img.shields.io/badge/Problem%20Statement-SIH26116-B98BE8?style=for-the-badge)
![Theme](https://img.shields.io/badge/Theme-Miscellaneous-F27FBC?style=for-the-badge)
![Category](https://img.shields.io/badge/Category-Software-FCAFDB?style=for-the-badge)

**Team Sirius** · Team ID 123894

</div>

---

## 📌 Problem statement
**SIH26116: Urban Mixed-Use Design Challenge.** Design a centrally located **B+G+9 mixed-use building in Autodesk Revit**.

## 💡 Our idea
A central urban plot must hold lively shops and cafés **and** comfortable homes, while staying cool, bright and green. One landscaped **central courtyard** opens the whole building to light and air. A commercial podium (Basement + Ground + 1st) sits below **8 residential floors (2nd–9th)**, capped by a roof terrace garden with solar.

```
        ┌──────────────────────────────────┐
        │     Roof terrace garden + solar  │
        ├────────────┬────────────┬────────┤
        │            │            │        │
        │  2nd–9th   │  CENTRAL   │ 2nd–9th│   8 residential floors
        │  Homes     │  COURTYARD │ Homes  │
        ├────────────┤            ├────────┤
        │  1st floor │            │ 1st    │   commercial podium
        │  Ground: Retail · Café  │        │
        ├────────────┴────────────┴────────┤
        │  Basement: Parking · EV          │
        └──────────────────────────────────┘
          (schematic concept section, not the Revit model)
```

**Why it works**
- The courtyard pulls daylight and cross-ventilation into every unit
- Shading fins, deep balconies and green terraces answer the climate
- Active ground and 1st floors make the street a destination
- Basement parking with EV charging keeps the podium car-free

**Design flow:** Site study → Massing & courtyard → Facade & climate → Structure & detailing

## ⭐ Five ideas that set Courtyard Rise apart
| # | Idea | In one line |
|---|---|---|
| 1 | **Courtyard-first** | The court decides the plan, airflow, daylight and facade; everything else is arranged around it |
| 2 | **Orientation-tuned skin** | S/W: deep fins and overhangs. N/E: open glazing. Fin depth is checked against sun angle |
| 3 | **Connected green chain** | Plaza, podium deck, planter balconies, roof garden: nature at every level, not only on the roof |
| 4 | **Breathing basement** | A light-and-vent well links the court to the parking level, cutting lighting and fan load; 12 EV bays |
| 5 | **Try it live** | Interactive concept explorer: click floors, switch plan and section, move the sun |

## 🛠️ Technical approach: a Revit-led workflow
| Step | Stage | Tool | What happens |
|---|---|---|---|
| 1 | Site & Context | Autodesk Forma *(optional)* | Sun-path, wind and massing studies fix orientation, courtyard size and setbacks on the assumed 45 × 40 m plot |
| 2 | Massing & Planning | Revit Architecture | Podium, 8 residential floors and courtyard laid out on a 6 m structural grid |
| 3 | Facade & Climate | Revit families + parametrics | Shading fins, balconies and green terraces tuned per orientation for light, heat and ventilation |
| 4 | Structure & Detailing | Revit Structure | Columns, beams, slabs, stairs and tile flooring, with a reinforcement drawing of one floor |
| 5 | Visualise & Present | Revit rendering + sheets | Rendered views, facade studies, diagrams and a 30-second walkthrough |

All modelling is done from scratch by the team: no pre-designed files, no AI-generated content.

## 📐 Design parameters *(all assumed for the concept stage)*

| Parameter | Value |
|---|---|
| Plot | 45,000 × 40,000 mm |
| Building footprint | 36,000 × 30,000 mm |
| Courtyard | 12,000 × 12,000 mm |
| Floor heights | Basement 3,600 · Ground 4,500 · 1st 4,200 · Typical 3,200 |
| Structure | RCC frame on a 6 m grid · columns 600 × 600 mm · beams 300 × 600 mm · 200 mm slabs · raft foundation |
| Parking | ~70 cars including 12 EV bays |
| Typical floor | 4 units |

**Planned built-up area (approx.)**

| Use | Area (m²) |
|---|---|
| Parking (Basement) | 1,350 |
| Commercial (Ground + 1st) | 1,870 |
| Residential (2nd–9th) | 7,490 |
| **Total** | **≈ 10,710** |

*Sanity check from the stated dimensions: the footprint minus the courtyard is 36 × 30 − 12 × 12 = 936 m² per floor, so 8 residential floors ≈ 7,490 m² and 2 commercial floors ≈ 1,870 m², consistent with the table. Above-ground height from the stated floor heights ≈ 34.3 m (4.5 + 4.2 + 8 × 3.2).*

## 🌡️ Challenges → how we handle them
- **West heat gain** → deep balconies and vertical fins
- **Privacy around the court** → offset balconies and planters
- **Basement air and EV load** → ventilation shafts and dedicated EV bays

## 🌍 Impact
| 🏠 Residents: *"My home is bright, cool and green."* | 🏙️ City & community: *"Our street is alive from morning to night."* |
|---|---|
| Daylight and cross-ventilation in every unit | Cafés, shops and community spaces at street level |
| Private balconies and green terraces | Parking and EV charging underground, streets stay open |
| Views onto the courtyard, calm from street noise | Landscaped plaza as a shared public space |
| Lower cooling demand through shading | Greener, cooler urban fabric |

**ACTIVATE → OPEN UP → GREEN UP → COOL DOWN**: *"A building that gives back to the city."* The module is also repeatable on other urban plots.

## 🖥️ Interactive concept explorer (`index.html`)
A self-contained, dependency-free HTML page presenting the concept. Open it in a browser or run `python -m http.server`.
It illustrates the idea; it is **not** the Revit model.

## 📚 Research & references
**Codes & standards:** National Building Code of India 2016 (BIS) · IS 456:2000 (plain and reinforced concrete) · IS 875 Parts 1–5 (design loads) · IS 1893 Part 1 (earthquake-resistant design) · IS 13920:2016 (ductile detailing) · IS 2502 / SP 34 (bar bending and detailing)

**Guidelines & tools:** Energy Conservation Building Code (BEE) · GRIHA Green Building Rating · IGBC Green Buildings · EV Charging Guidelines (Ministry of Power) · UDCPR Maharashtra (setbacks, FSI, parking; to be verified for a real plot) · passive design: courtyard and stack effect (standard bioclimatic practice) · Autodesk Revit · Autodesk Forma · Autodesk Education

---

<div align="center">

**Team Sirius** · Smart India Hackathon 2026

</div>
