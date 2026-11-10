# 🌐 Ozone Hole Study

**An open, evidence-first look at the Antarctic ozone hole. It tests the standard chlorine explanation and the natural-cycle alternatives against the same public data, and sets out the predictions that will decide between them.**

---

## What this project is

The Antarctic ozone hole is usually presented as a settled story: CFCs went up, the ozone thinned, CFCs were banned, and the ozone is recovering. This project goes back to the data and asks the awkward questions:

- Is 70 years of measurements long enough to rule out natural cycles?
- How reliable are the instruments, given the Antarctic conditions and the gaps in the record?
- Could solar, oceanic or **planetary** cycles, such as the Jupiter–Saturn alignments, explain the record as well as chlorine does?
- Where does the chlorine actually come from, and could natural sources (volcanoes, buried deposits, radioactive decay) matter?
- Has the theory steered how the data is read?

The aim isn't to argue for one side. It's to set out **what is established, what is still open, and which tests could settle the open questions**, so that anyone can check the evidence for themselves.

---

## What it's for

- **Researchers and students** who want a single, sourced overview of the evidence, including the parts that are uncertain.
- **Sceptics and independent investigators** who want to test the mainstream explanation rather than take it on trust.
- **Anyone tracking the next decade of measurements:** the study includes predictions with dates attached that will show which explanation holds up.

---

## What's inside

The core document is **`antarctic-ozone-hole-evidence-review.md`**. It contains:

| Section | Contents |
|---|---|
| **1. What is established** | The Halley station ozone record (1956–), independent cross-checks, stratospheric chlorine measurements, the chemical mechanism, the response to the CFC ban, year-to-year weather effects, and the sizes of natural chlorine sources |
| **2. Findings from this study** | A new test of sunspots, El Niño and planetary-alignment indices against Halley spring ozone, plus published planetary periods (9.1, 11.07, 19.86, 22.14 and 59.6 years) |
| **2.1–2.4 Context** | Published research on the planetary hypothesis (both sides), the wave-cancellation argument, accepted long natural cycles, and notes on statistics |
| **3. What is still open** | The deep past, recovery timing, climate effects, the role of El Niño, undetected emissions, untested cycles, data gaps |
| **4. Where the readings disagree** | The sceptical and mainstream interpretations side by side, and the common ground |
| **5. Tests that could settle it** | Ten tests (T1–T10), each stating what each explanation predicts and when it can be checked |
| **6. Corrections** | Errors and overstatements found and fixed during the analysis |
| **7. Sources** | Data sets and papers, all public |

---

## Key findings at a glance

**The spring ozone record (Halley, Sep–Nov average):**
- 1957–1972: **318 DU** (every spring between 286 and 356 DU)
- 1990–2020: **181 DU** (every spring since 1985 below 260 DU)

**Natural cycles tested against that record:**

| Cycle | Share of the record explained | Notes |
|---|---|---|
| Sunspots, 11-year solar cycle | weak (r = +0.26) | within chance |
| El Niño (Sep–Nov) | none | |
| 9.1 / 11.07 / 19.86 / 22.14-year cycles | ≤ 4% each | within chance |
| All planets on the same side of the sun | r = −0.45 | strong before 2000, fails after |
| **59.6-year cycle (three Jupiter–Saturn conjunctions)** | **67%** | strongest single signal; only about one cycle fits in the record |

**The test to watch (T10):**

> The ~60-year Jupiter–Saturn cycle predicts Antarctic spring ozone back to about **300 DU by around 2030**.
> The chlorine explanation predicts only a slow rise from about **190 DU**.
> The Halley averages for 2028–2032 will separate the two.

---

## Data sources

Every data set used is public:

- **Halley ozone:** British Antarctic Survey, and the gap-filled monthly record from the [dobsonfill-halley](https://github.com/lnz0018/dobsonfill-halley) project (MIT)
- **Sunspots:** [WDC-SILSO](https://www.sidc.be/SILSO/), Royal Observatory of Belgium
- **El Niño:** NOAA CPC Oceanic Niño Index
- **Planetary positions:** calculated with [Astropy](https://www.astropy.org/)'s built-in ephemeris
- **Context:** NASA, NOAA, WMO and peer-reviewed literature (full list in the review document)

---

## Approach

1. **Measurements first.** Claims are graded by how directly they've been measured and how independently they've been confirmed.
2. **Both sides tested with the same rules.** The chlorine explanation and the cycle explanations are judged on whether their predictions held up when tested on later data, not only on how well they fit the past.
3. **Uncertainty kept.** Short records, gaps in the data and untested cycles are stated plainly rather than smoothed over.
4. **Corrections recorded.** Overstatements found along the way are logged, not quietly removed.

---

## Contributing

Contributions are welcome, especially:

- adding the **QBO, PDO, AMO** and longer solar cycles to the cycle analysis (test T4)
- defining a **specific cycle model** (period, phase, delay) to score against future springs (test T3)
- extending the Halley record past 2020 and adding other Antarctic stations
- independently re-analysing the raw data (test T8)

Please open an issue or a pull request, and include sources for any data you add.

---

## 📚 Citation

### Academic Citation

If you use this codebase in your research or project, please cite:

```bibtex
@software{ozone_hole_study,
  title = {Ozone Hole Study: An evidence-first review of the Antarctic ozone hole, testing chlorine and natural-cycle explanations against public data},
  author = {Drift Johnson},
  year = {2026},
  url = {https://github.com/MushroomFleet/ozone-hole-study},
  version = {1.0.0}
}
```

### Donate:

[![Ko-Fi](https://cdn.ko-fi.com/cdn/kofi3.png?v=3)](https://ko-fi.com/driftjohnson)

---

More projects: [MushroomFleet on GitHub][github-url]

[github-url]: https://github.com/MushroomFleet/
