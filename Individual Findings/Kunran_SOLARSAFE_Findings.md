# Kunran_SOLARSAFE_Findings

Article by **Kunran Cui**

## Objectives

This article documents my individual contribution to the SOLARSAFE Materials Team. The aim of my work was to investigate which plastic material is most suitable for a reusable maize drying bag, focusing on:

* how plastic choice may affect aflatoxin risk;
* whether sodium hypochlorite exposure damages candidate plastics;
* whether different plastics create different moisture and gas conditions inside maize bags;
* how future teams can continue the material-testing work.

My main ownership was the material selection logic, the aflatoxin/plastic literature review, procurement research, support for experiment design, and interpretation of the final material recommendation. As my teammate was less familiar with GitHub, I also took responsibility for uploading and organising most of the repository files so that the work was accessible for assessment and future handover. Mirha Kashif contributed substantially to sodium hypochlorite experiment set up, risk assessment, laboratory preparation and experiment procedures. Several parts of the practical work were joint, especially the laboratory observations and result interpretation.

## Brief project context

SOLARSAFE aims to make maize drying safer, more controlled, and more reusable before maize enters storage. Our materials question was:

> Which plastic is most suitable for a reusable maize drying bag?

The current recommendation is to prioritise **PVC** for the next SOLARSAFE drying-bag prototype, while keeping **PP** as a strong comparator and testing **Nylon** further before making a firm conclusion.

## Scope development

At the start of the project, the wider team considered several possible directions. The other subgroup focused more on the mechanical design of the dryer, while Mirha and I were more interested in the material side. We initially explored whether the two directions could be combined. For example, one early idea was to design a lining or filter inside the drying bag, where the material layer might also act as part of a mechanical filtration system.

However, this quickly became too broad for the short project timeframe. A filter or coated lining would require mechanical design, material selection, and a clear understanding of how aflatoxin or fungal material interacts with plastic surfaces. Without first understanding the surface-interaction problem, it would be difficult to justify a specific coating or filter design. We therefore narrowed the project to the material problem itself.

We considered several alternative ideas before reaching the final scope. One idea was to use desiccants to control moisture inside the bag, but we were concerned about whether this would be suitable for direct food crop use without further safety testing. Another idea was to coat the plastic surface so that it would be less likely to retain aflatoxin or related contaminants. However, that again depended on first knowing whether aflatoxin interacts with the plastic surface.

This led to three linked material questions:

1. Does the plastic surface have possible relevance to aflatoxin retention?
2. Does sodium hypochlorite exposure damage the plastic?
3. Does the plastic material affect moisture, CO2 and temperature conditions inside the bag?

The final project therefore became a material screening study rather than a full drying system redesign.

## Material selection

The initial candidate materials included:

* PP;
* PVC;
* LDPE;
* PELA;
* Nylon;
* possible future comparators such as PE and PET.

The final shortlist for testing was:

> **PP, PVC and Nylon**

The materials were selected using four criteria.

| Criterion                           | Reason                                                                             |
| ----------------------------------- | ---------------------------------------------------------------------------------- |
| Aflatoxin or fungal-residue concern | Materials associated with higher contamination or residue risk were deprioritised. |
| Transparency and usability          | SOLARSAFE drying bag needs to be transparent for solar energy.                     |
| Practical availability              | Materials needed to be low cost to make.      |
| Current material relevance          | PVC was kept because it is currently in use as SOLARSAFE drying bags.  |

LDPE was removed from the first shortlist after the literature review suggested a stronger association with aflatoxin levels in plastic-packaged food samples. PE and PET were not rejected permanently, but moved to future work because the project timeframe required a smaller experimental set.

Recommended supporting file:

```text
figures/material_selection_funnel.png
```

## Literature review and expert input

I led the literature review on aflatoxin/plastic and Aspergillus/plastic interaction. This was important because direct testing with aflatoxin or Aspergillus flavus was not feasible in the available time. Such work would require specialist safety procedures, biological samples and equipment such as ELISA or Reveal Q.

We first contacted people who had worked with aflatoxin or related plant-disease problems. Rich Stutt, who works in plant epidemiology, explained that aflatoxin testing is difficult to set up quickly and directed us towards relevant literature and comparable experimental approaches. This helped us avoid designing an unrealistic biological experiment.

We also spoke to Gideon Darko, who had worked with aflatoxin testing in Ghana. He explained that one practical method is to buy samples from markets and test aflatoxin levels using equipment such as Reveal Q. He also highlighted that aflatoxin levels in some crop samples can be far above international safety standards, which makes this not only a health problem but also a trade and food-security problem.

Gideon also introduced us to Aflasafe, a biocontrol product used to reduce aflatoxin risk before harvest. This was interesting because it addresses the problem earlier than our drying-bag material work. However, we learnt that Aspergillus strains differ between regions, so a product suitable for one country may not automatically work in another. For this reason, Aflasafe was treated as an important future direction rather than part of the main material experiment.

Recommended supporting file:

```text
references/literature_review_table.md
```

## Literature review case study 1: aflatoxin levels in different plastic packaging

One of the most useful papers I reviewed was **Macri et al. (2021), *The Occurrence of Aflatoxins in Nuts and Dry Nuts Packed in Four Different Plastic Packaging from the Romanian Market***. This paper was important because it directly compared aflatoxin levels across food products stored in different plastic packaging materials.

The study analysed **64 ready-packed nuts and dried fruits** bought from the Romanian market. The packaging materials compared were:

* LDPE;
* PP;
* PE;
* PET.

The authors used RIDASCREEN FAST ELISA testing which measured both total aflatoxins and aflatoxin B1.

The key finding was that total aflatoxin concentrations were highest in samples packed in **LDPE**, followed by **PP**, then **PE**, and lowest in **PET**. Aflatoxin B1 was detected in all samples packed in LDPE, PP and PE, while most PET-packed samples had aflatoxin B1 concentrations below 1 µg/kg. The authors concluded that nuts stored in LDPE appeared more prone to aflatoxin contamination, while PET was more suitable for maintaining product quality and safety.

For SOLARSAFE, I treated this paper as a screening reference rather than direct proof. The samples were market products, so the study could not fully isolate packaging material from other factors such as storage history, initial contamination, food type, moisture level or handling conditions. It also studied nuts and dried fruits rather than maize. Therefore, it would be too strong to claim that LDPE directly causes aflatoxin contamination.

However, the paper still gave us an important warning: plastic material can be associated with different aflatoxin outcomes during food storage. This supported our decision to remove LDPE from the first experimental shortlist. It also suggested that PET and PE may be worth testing in future work, even though we did not include them in the first round because of time, transparency, flexibility and procurement constraints.

The way I used this paper in the project was:

| Finding from paper                                          | How I used it in SOLARSAFE                                                                 |
| ----------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| LDPE-packed samples had the highest total aflatoxin levels  | Supported filtering out LDPE from the first material shortlist                             |
| PET-packed samples had the lowest aflatoxin levels          | Suggested PET as a useful future comparator                                                |
| PP was not the lowest, but performed better than LDPE       | Supported keeping PP in the shortlist because it also has good cost and practicality       |
| Packaging material appeared to influence aflatoxin outcomes | Strengthened the argument that material choice is relevant, not just mechanical bag design |

This literature review helped move the project away from choosing plastics only based on price or availability. It showed that the surface and storage behaviour of the material could matter for food safety, and this became one of the reasons our final material shortlist focused on PP, PVC and Nylon rather than including LDPE.


## Experiment 1: maize-bag internal conditions study — humidity, CO2 and temperature monitoring

### Objective

This experiment tested whether different plastic bag materials create different internal conditions when maize is enclosed inside them. This mattered because the SOLARSAFE bag is intended to support drying, not simply storage. If moisture builds up in the headspace, the bag may create a humid microclimate around the maize instead of helping it dry.

The tested bags were:

> **PP, PVC and Nylon**

The main measurements were:

* relative humidity inside the bag;
* CO2 level inside the bag;
* moisture content of the maize cobs;
* temperature inside the bag.

The central question was not only which plastic is chemically stable, but also which plastic is less likely to trap moisture and gas during drying.

### Setup

We prepared three bags: one PP bag, one PVC bag and one Nylon bag. Each bag contained two maize cobs. A combined CO2 and humidity sensor was placed inside each bag. We also used a separate moisture-measurement device with probes that could be inserted directly into the maize.

For each maize cob, we took four moisture readings. This was important because moisture can vary locally within the cob, so a single reading would not be reliable enough. After placing the maize and sensor inside each bag, we sealed the bags carefully with tape. Particular attention was given to the interface around the sensor and the bag opening, because leakage at this point would affect the CO2 and humidity readings. Although this was a small-scale laboratory setup, we tried to make the sealing method consistent across PP, PVC and Nylon.

Recommended supporting files:

```text
figures/maize_bag_setup.png
figures/headspace_humidity_by_material.png
figures/headspace_humidity_change.png
figures/headspace_co2_after_opening.png
data/maize_bag_experiment/raw_readings.csv
data/maize_bag_experiment/moisture_summary.csv
```

### Measurement timeline

The internal headspace was monitored from Day 0 to Day 4. On Day 0, we took two readings, one at approximately 11 a.m. and one at approximately 1 p.m. This allowed us to see how quickly the internal environment changed within the first two hours after sealing. We then returned on later days and continued measuring moisture and sensor readings. The bags were opened on Day 3, which provided a useful comparison between sealed and vented conditions.

The Day 3 opening should be treated as an intervention rather than a normal sealed-bag reading. It was useful because it showed whether the accumulated moisture and CO2 could be released by ventilation.

### Humidity results

The clearest result was the rapid rise in relative humidity in every bag:

| Material | Initial relative humidity | Peak relative humidity before opening | Increase from initial to peak | Relative humidity after opening on Day 3 | Drop after opening |
|---|---:|---:|---:|---:|---:|
| PP | 61.3% | 96.7% | +35.4 percentage points | 87.8% | -8.9 percentage points |
| PVC | 66.8% | 88.5% | +21.7 percentage points | 66.5% | -22.0 percentage points |
| Nylon | 56.2% | 94.1% | +37.9 percentage points | 67.5% | -26.6 percentage points |

![Headspace humidity by material](../figures/headspace_humidity_by_material.png)

This is an important result for SOLARSAFE. The maize cobs were releasing moisture, but in a sealed bag that moisture accumulated in the headspace instead of escaping. A drying bag should remove moisture from the maize environment; a sealed bag of any of these polymers risks doing the opposite by creating a near-saturated microclimate.

The material ranking was also informative. PP reached the highest humidity at **96.7%**, Nylon reached **94.1%**, and PVC reached the lowest peak humidity at **88.5%**. PVC's peak humidity was **8.2 percentage points lower than PP** and **5.6 percentage points lower than Nylon**. This suggests that, under our setup, PVC allowed slightly more moisture exchange than PP and Nylon, or at least accumulated less water vapour in the headspace.

The Day 3 opening was especially useful. After the bags were opened, humidity fell from **88.5% to 66.5%** in PVC and from **94.1% to 67.5%** in Nylon. PP also fell, but only from **96.7% to 87.8%**, meaning it remained very humid even after ventilation. This is consistent with PP behaving as the most moisture-trapping bag in our experiment.

![Humidity build-up and drop after opening](../figures/headspace_humidity_change.png)

The key conclusion from the humidity data is that moisture leaves the headspace only when there is an escape path. Passive sealing alone does not dry the maize. Therefore, SOLARSAFE needs ventilation, breathable panels, controlled opening, or a solar-driven airflow path so that evaporated water is carried out rather than trapped around the maize.

### CO2 results

CO2 also rose in all bags. This was likely driven by respiration from the maize and possibly by general biological activity. It should not be interpreted as direct evidence of Aspergillus flavus growth, because we did not perform fungal identification. However, it is still a useful indicator that the internal atmosphere of the sealed bags changed quickly.

PP and Nylon reached the sensor ceiling of **9999 ppm within 24 hours**. PVC accumulated CO2 more slowly and saturated later, which is consistent with PVC allowing slightly more gas exchange than PP and Nylon under our test conditions. After opening, PP retained much more CO2 than the other materials:

| Material | CO2 behaviour before opening | CO2 after opening | Comparison after opening |
|---|---|---:|---|
| PP | Reached sensor ceiling of 9999 ppm within 24 hours | 2396 ppm | Highest retained CO2 |
| PVC | Rose more slowly and saturated later | 994 ppm | 1402 ppm lower than PP |
| Nylon | Reached sensor ceiling of 9999 ppm within 24 hours | 834 ppm | 1562 ppm lower than PP |

![CO2 after opening bags on Day 3](../figures/headspace_co2_after_opening.png)

The post-opening CO2 values show the same broad pattern as humidity. PP retained the most gas after opening: **2396 ppm**, compared with **994 ppm** for PVC and **834 ppm** for Nylon. This means PP retained about **2.4 times** as much CO2 as PVC and about **2.9 times** as much CO2 as Nylon after opening.

The sensor ceiling is an important limitation. Because PP and Nylon exceeded **9999 ppm**, we cannot know their true maximum CO2 values. The correct conclusion is therefore not that their maximum was exactly 9999 ppm, but that they reached at least that value and exceeded the instrument range. A higher-range CO2 sensor would be needed for a stronger follow-up experiment.

The combination of high humidity and high CO2 is concerning for a drying application. It suggests a stagnant, moisture-rich headspace rather than an actively drying environment. For SOLARSAFE, this confirms that the bag should not be designed as a fully sealed container during the drying stage.

### Temperature results

Temperature was not a useful differentiator in this experiment. Across the measurements, it stayed approximately within **20.3--21.7 °C**, giving a spread of less than **1.5 °C**. There was no clear material-to-material temperature difference. The main headspace differences were therefore humidity and CO2, not temperature.

This is useful because it means the humidity and CO2 differences are unlikely to be explained simply by one bag being much warmer than the others. Instead, they are more likely related to moisture and gas retention behaviour.

### Interpretation

This experiment changed how I interpreted the material problem. A material that is chemically stable is not automatically suitable for drying. If the bag traps water vapour and CO2, it can create the damp, stagnant conditions that SOLARSAFE is trying to avoid.

The main design conclusion is:

> **Bag material alone does not solve drying; ventilation does.**

All three polymers built a humid, CO2-rich microclimate when sealed. PP and Nylon appeared more airtight and therefore trapped moisture and gas more strongly. PVC had the lowest peak humidity and slower CO2 accumulation, which supports keeping it as the lead material for the current prototype direction. However, even PVC still reached high humidity, so it should not be used as a fully sealed drying bag without an engineered moisture-escape path.

This is why the final material recommendation should be read together with a design recommendation. PVC is the best current candidate among the tested materials, but the bag should include vents, a breathable section, controlled opening, or a solar-driven airflow/chimney effect. Without this, any plastic bag risks acting more like an incubation chamber than a dryer.

### Limitations

The main limitation was that the CO2 sensor saturated at **9999 ppm**, so the true maximum concentration could not be measured. The sealing method also relied on tape, which may not represent a manufactured drying bag. In addition, each bag contained only two maize cobs, so more replicates would be needed before drawing a strong material conclusion. The Day 3 opening was useful as a ventilation check, but it also means the later readings should be interpreted as post-intervention values rather than purely sealed-bag behaviour.

Another limitation is that the current figures use summary values rather than full time-series data. The repository should therefore include the raw Day 0--Day 4 readings so future teams can replot the curves and calculate rates of humidity and CO2 build-up.

### Future improvements

Future teams should repeat the experiment with:

* a CO2 sensor with a higher measurement range;
* at least three replicate bags for each material;
* standardised bag size, maize mass and sensor position;
* simultaneous temperature measurement;
* sealed, partially ventilated and open-control conditions;
* a controlled vent or breathable panel to compare against fully sealed bags;
* sunlight or simulated solar-dryer conditions;
* full time-series logging so that humidity and CO2 build-up rates can be calculated rather than only compared using summary values.

Suggested data table:

| Material | Day/time | CO2 | Humidity | Maize moisture | Observation |
|---|---|---|---|---|---|
| PP | Day 0, initial | Insert | 61.3% | Insert | Initial reading |
| PP | Peak before opening | >9999 ppm if saturated | 96.7% | Insert | Highest humidity among tested bags |
| PP | After opening | 2396 ppm | 87.8% | Insert | Retained most CO2 and remained very humid |
| PVC | Day 0, initial | Insert | 66.8% | Insert | Initial reading |
| PVC | Peak before opening | Insert / saturated later | 88.5% | Insert | Lowest peak humidity |
| PVC | After opening | 994 ppm | 66.5% | Insert | Large humidity drop after ventilation |
| Nylon | Day 0, initial | Insert | 56.2% | Insert | Initial reading |
| Nylon | Peak before opening | >9999 ppm if saturated | 94.1% | Insert | High humidity and rapid CO2 saturation |
| Nylon | After opening | 834 ppm | 67.5% | Insert | Large humidity drop after ventilation |

## Experiment 2: sodium hypochlorite exposure and surface analysis

### Objective

This experiment tested whether sodium hypochlorite exposure damages candidate drying-bag plastics. This matters because reusable drying bags may come into contact with cleaning or disinfectant residues from treated shelves or nearby surfaces. If the material degrades, it may lose transparency, flexibility or structural integrity.

The tested materials were:

> **PP, PVC and Nylon**

The practical question was not whether sodium hypochlorite makes any visible difference immediately, but whether it creates early surface chemistry or surface morphology changes that would make a material unsuitable for repeated use.

### Exposure and sample handling

The exposure stage was mainly prepared by Mirha. Plastic samples were placed in sodium hypochlorite solutions for the planned exposure period. During the plastic-lab session, we removed the samples from the solutions, rinsed them carefully and dried them before analysis.

This washing and drying step was important because remaining liquid could affect both ATR-FTIR spectroscopy and microscopy. We tried to handle the samples consistently so that any observed differences were more likely to reflect material behaviour rather than preparation differences.

### ATR-FTIR: what we were looking for

The first analysis method was ATR-FTIR spectroscopy. ATR-FTIR is useful here because it samples only the near-surface region of the film, typically on the order of the top 1--2 µm depending on the material and wavenumber. This is the region where chemical attack would be expected to start.

If sodium hypochlorite were oxidising or degrading the polymer, we expected to see one or more diagnostic changes:

| Diagnostic feature | Why it matters |
|---|---|
| New carbonyl band around 1700--1740 cm⁻¹ | C=O formation is a common sign of oxidation and chain scission. |
| Broad hydroxyl/O-H band around 3200--3500 cm⁻¹ | This may indicate introduced hydroxyl groups, hydrolysis, oxidation or water uptake. |
| PVC-specific changes near the C-Cl region around 600--700 cm⁻¹ | This could indicate changes to the PVC backbone or C-Cl bonding environment. |
| Growth of conjugated C=C/polyene bands in PVC | This may accompany dehydrochlorination and bleach-induced discolouration. |

The experiment was therefore a before-vs-after comparison: a clean control film and a bleach-soaked film should look similar unless the surface chemistry has changed.

Before measuring samples, we first collected a background measurement from the ATR-FTIR instrument. This background correction removed the contribution of the instrument and surrounding environment from the final spectrum. Each plastic sample was then placed onto the ATR crystal and measured. The spectra were saved as `.csv` files so that they could be plotted and compared later.

Recommended supporting files:

```text
data/atr/raw/
data/atr/processed/
figures/ATR_results_PP_PVC_Nylon.png
protocols/NaOCl_ATR_protocol.md
```

### ATR-FTIR measurement quality

This part of the experiment was more difficult than expected. Across the three polymers and both sodium hypochlorite concentrations, the spectra often sat on a low, noisy baseline at the milli-absorbance level. The strong polymer fingerprint peaks that would normally be expected were weak or partly lost in noise. For example, the expected CH stretching features of PP, the amide I/II bands of Nylon, and the CH₂/C-Cl features of PVC were not always as sharp or intense as they would be in an ideal ATR-FTIR measurement.

Instead, some spectra showed a large baseline rise or dip below roughly 1200--1300 cm⁻¹, and some also showed atmospheric water-vapour features around 1900--2200 cm⁻¹. We interpreted this mainly as a measurement artefact rather than evidence of polymer chemistry. Thin and slightly curled film offcuts do not always press flat onto the ATR crystal, so optical contact can be poor. When contact is poor, the effective signal becomes weak and the low-wavenumber region can be distorted.

For this reason, some samples were measured more than once. If the first graph looked unusual or inconsistent with the expected polymer fingerprint, we repeated the measurement and tried to improve sample contact. Some heat runs were also attempted to soften or flatten film samples and improve contact with the ATR crystal. This helped slightly, but it did not fully remove the low-signal problem.

This quality issue is important for future interpretation. The ATR-FTIR data are useful for identifying whether obvious degradation markers appeared, but they should not be used for confident quantitative peak-height comparisons.

### ATR-FTIR results

Despite the weak signal, the diagnostic windows for chemical attack were still informative. Across PP, PVC and Nylon, at both tested sodium hypochlorite concentrations, we did not observe the spectral signatures that would indicate clear polymer degradation.

The key findings were:

| Material | ATR-FTIR result after short NaOCl exposure | Interpretation |
|---|---|---|
| PP | No new carbonyl band around 1715--1740 cm⁻¹ and no broad hydroxyl band around 3200--3500 cm⁻¹ | No detectable oxidation or hydrolysis within the limits of this test. |
| PVC | No new carbonyl/hydroxyl damage features, no obvious loss in the C-Cl region, and no clear polyene growth | No detectable dehydrochlorination, oxidation or bleach-related surface breakdown. |
| Nylon | No clear new carbonyl/hydroxyl degradation feature, but the signal was weaker and noisier | No evidence of degradation, but repeat testing would strengthen confidence. |

The honest interpretation is therefore two-part. First, the data quality is limited because the films did not always make ideal contact with the ATR crystal. Second, within the detection limit of the spectra we collected, there was no evidence that three days in 3--5% sodium hypochlorite chemically degraded PP, PVC or Nylon. No clear oxidation products, chain-scission markers, hydrolysis markers or PVC dehydrochlorination signatures were detected.

### Microscopy

After ATR-FTIR analysis, we tried to use a profilometer to quantify surface roughness and possible physical damage. This would have been useful because profilometry can measure roughness, pitting and topography more quantitatively. However, the profilometer was not working and could not be repaired within the available time. We therefore used optical microscopy as an alternative.

For microscopy, we examined all samples visually. We adjusted the microscope focus and magnification so that the sample surfaces could be compared as consistently as possible. To estimate the scale of the microscope images, we used a practical calibration method: we measured the diameter of a hair using a micrometer and then placed the hair under the microscope. This gave us a reference object with a known approximate size, allowing us to interpret the microscope images with some sense of scale.

This was a useful workaround, but it was still less precise than using a calibrated microscope scale or profilometer.

Recommended supporting files:

```text
figures/microscope_PP_PVC_Nylon.png
protocols/microscope_protocol.md
```

### Microscopy results

Under optical microscopy, the bleach-exposed surfaces did not show substantial differences from the controls. We did not observe obvious micro-cracking, crazing, pitting, etching, frosting, loss of gloss, or visible discolouration in PP, PVC or Nylon at the tested concentrations.

This result should be interpreted carefully. Optical microscopy shows surface morphology, not molecular chemistry. It would catch visible cracking, pitting or discolouration, but it cannot detect early molecular-scale oxidation as sensitively as ATR-FTIR. Its value here is therefore corroboration: ATR-FTIR looked for surface chemical changes, while microscopy looked for physical surface damage. Both methods suggested the same conclusion under our short test conditions: sodium hypochlorite did not cause detectable surface damage.

### Overall interpretation

The experiment provided two complementary types of evidence. ATR-FTIR gave the more chemistry-focused evidence, while microscopy gave visual surface evidence. Both were screening methods, and both had limitations, but together they support the conclusion that **3--5% sodium hypochlorite exposure over three days did not produce detectable chemical or visible surface damage in PP, PVC or Nylon**.

This means none of the three candidates should be ruled out on sodium hypochlorite resistance alone. The final material choice should therefore depend on other design requirements, including transparency, food-contact suitability, moisture behaviour, cost, local availability, manufacturability and relevance to the partner design.

For our final recommendation, this supports choosing **PVC** as the lead material for the next SOLARSAFE prototype because it survived the sodium hypochlorite screen, is transparent, and is directly relevant to the current partner design. **PP** remains a strong comparator because it also survived the chemical screen and has advantages in cost, low moisture uptake and food-contact practicality. **Nylon** remains possible but needs further testing because of its weaker ATR signal and higher moisture absorption concern.

The important caveat is that the ATR-FTIR signal quality was limited. If a formal degradation claim is needed, the measurement should be repeated with flatter coupons, stronger and more reproducible crystal contact, replicate samples, and ideally profilometry or mechanical testing.

### Future improvements

Future teams should repeat and strengthen this experiment with:

* longer exposure times, such as 7, 14 and 28 days;
* at least three replicate samples per material and condition;
* clearly recorded sodium hypochlorite concentration and exposure time;
* flatter film cut-outs or heat-flattened coupons to improve ATR-FTIR contact;
* careful ATR crystal pressure and repeated spectra when the signal is weak;
* profilometry to quantify roughness, pitting and surface topography;
* calibrated microscopy images;
* mass, transparency and flexibility measurements before and after exposure;
* simple tensile or flexural testing, because brittleness may appear before obvious visible damage;
* UV or heat ageing to better represent solar-dryer conditions.

The most useful next improvement would be to combine ATR-FTIR with profilometry and a simple mechanical test. ATR-FTIR would show whether surface chemistry changed, profilometry would show whether the physical surface became rougher or damaged, and mechanical testing would show whether the material became more brittle after exposure.


## Final material recommendation

The current recommendation is:

> **Use PVC as the leading material candidate for the next SOLARSAFE drying-bag prototype, while continuing to compare it against PP and Nylon in longer tests.**

| Criterion | PP | PVC | Nylon |
|---|---|---|---|
| NaOCl resistance, 3 days | No detectable chemical degradation in ATR-FTIR; no visible surface damage in microscopy | No detectable chemical degradation in ATR-FTIR; no visible surface damage in microscopy | No detectable degradation markers, but ATR-FTIR signal was weaker/noisier |
| Humidity behaviour in maize-bag test | Highest peak humidity, 96.7% | Lowest peak humidity, 88.5% | High peak humidity, 94.1% |
| CO2 behaviour in maize-bag test | Reached 9999 ppm within 24 hours and retained most CO2 after opening | Accumulated more slowly and had lower post-opening CO2 than PP | Reached 9999 ppm within 24 hours |
| Material integrity | Stable candidate, light and practical | Strong and transparent; long-term ageing and food-contact grade should be checked | Tough, but may absorb moisture |
| Practicality | Low-cost and strong comparator | Transparent and directly relevant to the current partner design | Heavier/costlier and less straightforward for moisture control |
| Recommendation | Strong comparator | **Best current candidate** | More testing needed |

PVC is recommended because it combines short-term sodium hypochlorite compatibility with strong transparency, direct relevance to the current partner design, and the best headspace result among the three materials tested. In the maize-bag experiment, PVC reached the lowest peak humidity and accumulated CO2 more slowly than PP and Nylon, suggesting that it may be less prone to trapping moisture and gas when used in a drying context.

PP remains a strong comparator because it also showed no detectable chemical or visible surface damage under sodium hypochlorite exposure and has advantages in cost, low moisture uptake and food-contact practicality. However, in the sealed maize-bag experiment PP trapped the most humidity and retained the most CO2 after opening, which is a disadvantage for drying unless ventilation is engineered into the bag. Nylon requires further testing because of weaker ATR-FTIR signal quality, high humidity build-up and its moisture absorption concern.

This recommendation should not be treated as a final field-certified material choice. It is a first-stage material screen that gives the partner and future teams a practical starting point. The maize-bag result also makes one design requirement very clear: even with PVC, SOLARSAFE should not rely on a fully sealed drying bag. The next prototype should include an engineered moisture-escape path, such as vents, breathable panels, controlled opening, or solar-driven airflow.

Before field adoption, the next team should verify PVC grade, food-contact suitability, plasticiser formulation, long-term sunlight ageing, mechanical durability and moisture behaviour under realistic drying conditions.

## Repository handover

The following files should be included in the repository so that future teams can continue the work.

### Main report

```text
www/material-selection-and-surface-testing-kunran.md
```

This file should contain the main individual report.

### Raw and processed data

```text
data/atr/raw/
data/atr/processed/
data/atr/ATR_quality_notes.md
data/maize_bag_experiment/
```

These folders should include raw ATR `.csv` files, processed ATR summaries, ATR quality notes, and maize-bag CO2/humidity/moisture readings.

Suggested ATR file names:

```text
PP_control.csv
PP_NaOCl_day3.csv
PVC_control.csv
PVC_NaOCl_day3.csv
Nylon_control.csv
Nylon_NaOCl_day3.csv
```

Suggested maize-bag data files:

```text
raw_readings.csv
moisture_summary.csv
```

### Figures

```text
figures/material_selection_funnel.png
figures/ATR_results_PP_PVC_Nylon.png
figures/microscope_PP_PVC_Nylon.png
figures/maize_bag_setup.png
figures/moisture_CO2_result.png
```

Figures should be linked inside the Markdown report using:

```markdown
![ATR results](../figures/ATR_results_PP_PVC_Nylon.png)
```

### Protocols

```text
protocols/NaOCl_ATR_protocol.md
protocols/microscope_protocol.md
protocols/maize_bag_CO2_moisture_protocol.md
```

These should describe exactly how the experiments were performed so that another team can repeat them.

### References

```text
references/literature_review_table.md
```




| Source                                                                                                                                                                                              | Crop/product                                               | Materials         | Method                                                         | Key finding                                                                                                  | Relevance to SOLARSAFE                                                                                                   |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------- | ----------------- | -------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------ |
| Macri et al. (2021), *The Occurrence of Aflatoxins in Nuts and Dry Nuts Packed in Four Different Plastic Packaging from the Romanian Market*                                                        | 64 ready-packed nuts and dried fruits from Romanian market | LDPE, PP, PE, PET | Immunoaffinity cleanup + RIDASCREEN FAST ELISA                 | Total aflatoxins highest in LDPE, followed by PP, PE, and lowest in PET; most PET samples had AfB1 < 1 µg/kg | Used as screening evidence to deprioritise LDPE and suggest PE/PET as future comparators                                 |
| John et al. (2019), *The effects of different packaging materials, temperatures and water activities to control aflatoxin B1 production by Aspergillus flavus and A. parasiticus in stored peanuts* | Inoculated stored peanut kernels                           | LDPE, PP, PELA    | Storage under controlled temperature/water activity + HPLC-FLD | Highest AFB1 detected in LDPE, followed by PP; PELA reduced or prevented AFB1 under some conditions          | Reinforced decision to deprioritise LDPE and showed that moisture/water activity must be considered with material choice |

## Strengths

* The project narrowed a broad aflatoxin-control problem into a specific material-selection question.
* The recommendation is based on partner needs, expert feedback, literature evidence and laboratory testing.
* The literature review helped justify why LDPE was removed from the first experimental shortlist rather than simply choosing materials based on availability.
* The maize-bag experiment produced a clear headspace result: all sealed bags became humid and CO2-rich, but PVC had the lowest peak humidity and slower CO2 accumulation than PP and Nylon.
* The plastic-lab work included both ATR-FTIR spectroscopy and microscope observation, giving a stronger first screen than visual inspection alone.
* The humidity drop after opening the bags showed that ventilation is essential; material choice should be evaluated together with airflow design, not in isolation.
* The ATR-FTIR analysis checked the relevant diagnostic regions for oxidation, hydrolysis and PVC-specific degradation, rather than relying only on visual appearance.
* The report and repository structure give future teams a clear starting point.

## Limitations

* The sodium hypochlorite experiment was short-term and does not prove long-term durability.
* The ATR-FTIR spectra were low-signal because thin film samples did not always make good contact with the ATR crystal.
* Some ATR-FTIR spectra had to be retaken because weak sample contact or small air gaps at the ATR interface could distort the signal.
* The ATR-FTIR data are useful for detecting obvious degradation markers, but should not be used for confident quantitative peak-height claims.
* The profilometer was unavailable, so surface roughness and pitting could not be quantified.
* The microscope images were mainly qualitative and did not show clear surface differences.
* The CO2 sensor saturated at 9999 ppm, so the true maximum CO2 concentration inside the maize bags could not be measured.
* The bags were opened on Day 3, so later humidity and CO2 readings should be interpreted as post-ventilation values rather than purely sealed-bag behaviour.
* No direct aflatoxin-retention experiment was performed.
* The literature reviewed was mainly from nuts, dried fruits and peanuts rather than maize, so it should be treated as screening evidence rather than direct proof for SOLARSAFE.
* Nylon results were less conclusive because of the weaker ATR-FTIR signal and its moisture absorption concern.
* Aflasafe was identified as an interesting future direction, but it was outside the scope of the material-focused project.

## Next steps

Future teams should:

1. repeat the sodium hypochlorite test with longer exposure times and replicate samples;
2. improve ATR-FTIR measurement quality using flatter coupons, stronger contact and repeated scans;
3. add UV, heat and mechanical ageing to better represent field use;
4. perform folding, puncture, tensile or flexural tests after chemical exposure;
5. use profilometry to quantify surface roughness and pitting;
6. repeat the maize-bag experiment with a higher range CO2 sensor;
7. compare fully sealed bags against controlled vents, breathable panels or solar-driven airflow paths;
8. build small PVC and PP prototype bags and test them with maize under sunlight;
9. test PE and PET as future comparators if time allows;
10. investigate Aflasafe or other biocontrol options as a separate pre-harvest direction;
11. run field validation in Kenya before final material adoption.

## Final handover summary

My individual work helped turn SOLARSAFE’s broad material-longevity problem into a structured technical decision. The main output is the evidence-based shortlist and recommendation:

> **PVC should be prioritised for the next SOLARSAFE drying-bag prototype, with PP retained as a strong comparator and Nylon requiring further testing.**

The sodium hypochlorite experiment supports this recommendation because no candidate was ruled out by short-term bleach resistance: ATR-FTIR showed no detectable chemical degradation markers, and microscopy showed no visible surface damage. The maize-bag headspace experiment then made the material decision more practical: all sealed bags accumulated humidity and CO2, but PVC had the lowest peak humidity and slower CO2 build-up than PP and Nylon.

The most important design lesson is that material choice alone does not solve drying. Even PVC still reached high humidity, so SOLARSAFE needs an engineered route for moisture to escape. The next stage should therefore focus on PVC prototype testing with controlled ventilation, longer ageing tests, improved ATR-FTIR/profilometry measurements, mechanical durability, and field trials in Kenya.
