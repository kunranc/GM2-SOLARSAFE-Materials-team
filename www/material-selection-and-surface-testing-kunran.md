# Material Selection and Surface Testing

Article by Kunran Chen

## Objectives

To identify and evaluate the optimal plastic bag material for the SOLARSAFE solar maize dryer enclosure, focusing on two key questions:

1. Does sodium hypochlorite (bleach), used for cleaning, degrade the plastic?
2. Which plastic best retains moisture inside the sealed drying bag?

Materials must also be transparent (to allow solar heating), low cost, and durable under repeated field use.

## Materials Selection Logic

The selection funnel proceeded as follows:

1. **Eliminate LDPE** — literature confirms *Aspergillus* severely degrades LDPE, and Macri et al. (2021) found highest aflatoxin concentrations in LDPE packaging.
2. **Test PVC, PP, and Nylon** — three shortlisted plastics subjected to NaOCl exposure and moisture retention experiments.
3. **Identify PE and PET as future comparators** — lowest aflatoxin in Macri et al.; not tested in this study due to time constraints.

## Experiment 1: NaOCl Surface Degradation

### Aim

Identify materials that can withstand cleaning and long-term use by assessing chemical changes after NaOCl exposure.

### Method

PVC, PP and Nylon samples were exposed to:
- Water (control)
- 3% NaOCl solution
- 5% NaOCl solution
- 5% NaOCl + heat

Samples were characterised using **ATR-FTIR spectroscopy** and **optical microscopy** (profilometry was unavailable).

### Interpreting ATR-FTIR Spectra

Two spectral zones are diagnostic:
- **Red zones** (~3300 cm⁻¹ O–H stretch; ~1715 cm⁻¹ C=O stretch): new peaks here indicate oxidation or degradation.
- **Green zone** (fingerprint region): the plastic's chemical identity. A vanishing or shifting fingerprint peak = backbone breakdown.

### Results

**PP:** No new peaks in red zones. Backbone fingerprint unchanged. No evidence of NaOCl attack at any concentration.

**PVC:** No new peaks in red zones. Stable spectra across all conditions.

**Nylon:** Signal weaker and noisier. A ~3% drift observed in the red zone under 3% NaOCl only. Inconclusive — further testing recommended.

| Material | NaOCl Resistance | Surface Stability | Verdict |
|----------|-----------------|-------------------|---------|
| PP | No degradation | Stable | Pass |
| PVC | No degradation | Stable | Pass |
| Nylon | Minor drift | Inconclusive | Further testing needed |

## Experiment 2: Moisture Retention

### Aim

Determine which plastic best maintains high internal humidity — a proxy for drying effectiveness inside the SOLARSAFE bag.

### Method

Bags sealed with dried corn and three sensor types (CO2, humidity, temperature). Bags opened on day 3 to replicate real dryer use. Control corn left outside bags throughout.

### Results Summary

**CO2:** Rose in all bags days 1-3; Nylon and PP hit sensor limit first. PVC rose more slowly. After unsealing day 3, CO2 fell. PP highest on day 5.

**Moisture:** Increased in all sealed bags while sealed. Differences observed between materials post-opening. Control moisture declined throughout.

**Temperature:** Small variation overall; no clear link to CO2.

| Material | CO2 Rise | Moisture Retention | Temperature |
|----------|----------|-------------------|-------------|
| PP | High | High | Lowest day 3 |
| Nylon | High | High | Highest day 1 |
| PVC | Moderate | Moderate | Highest day 4 |

## Team Contributions (Kunran)

- Defined materials selection logic and led literature review on aflatoxin/plastic interaction
- Helped design humidity exposure experiment
- Contacted academics and labs
- Supported measurements and result interpretation
- Developed final comparison and recommendation

## Limitations

- Short experiment timescale; lab conditions do not replicate Kenyan field conditions
- Profilometry, ELISA assays, and John Deere moisture tubes were unavailable
- Only one replicate per material

## Final Recommendation

Based on current evidence, **PP** and **PVC** are the strongest candidates. Both passed NaOCl resistance testing and are low cost and transparent. PP showed higher moisture retention. Nylon requires further testing.

## Next Steps

- Longer NaOCl ageing test (weeks-months)
- Profilometer surface analysis
- Field test in Kenya with the SOLARSAFE dryer
- Include PE and PET as comparators
