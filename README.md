# Pathogen Map (beta)
### Interactive encyclopedia of infectious pathogens and their antimicrobials

A bedside and teaching tool by Warodom Phaenthong, M.D. It is one self-contained HTML page
(`pathogen-map.html`, opened by `index.html`) that runs in the browser, with no installation and no data
sent anywhere. Version 0.9.6 (beta).

It is decision support for healthcare professionals. It does not replace the source documents, your local
antibiogram, hospital protocols, renal function and allergy checks, or clinical judgement.

**Open it:** https://sirmarkthemighty-ctrl.github.io/Pathogen_Map/

## What it does

- **248 pathogens** plus 15 infection-site (empirical therapy) entries, in two views: **Notes** (handwritten-style
  outline, the default) and **Map** (mind map; drag to pan, pinch or scroll to zoom).
- **Grouped as in the handbook's diagrams:** Gram-positive, Gram-negative and other bacteria, fungi, protozoa,
  parasites, viruses and prions; species of one genus sit under one node.
- **Table view** (Map | Notes | Table): organism, group, first-line, alternative, avoid and source in one scrolling table that follows the search and filters.
- **Detail box** (right-click or long-press): key points, first-line, alternative and avoid drugs, endemic area,
  vector, screening and diagnostic tests, and **source buttons** (IDAT, CDC Yellow Book, handbook page, or
  "general knowledge"). Only key points and first-line open by default; "Show all details" opens the rest.
  Print one organism on a page.
- **Filters** (persistent box under the toolbar; one row per group, every group folds and shows what is chosen, a bar of removable chips lists the active filters, and every chip shows how many organisms it gives and greys out at zero): pathogenicity, community or hospital acquired, type, vector
  (mosquito, tick, mite, flea, louse, sandfly, tsetse fly, blackfly, triatomine bug, deer fly), Gram stain, endemic
  area and tropical, and source (Thai guideline, international source, handbook, handbook only, no regimen listed). Search, Saved and Recent lists, first-line drug beside each name and the "Show related (grey)" setting (both on by default) that shows the neighbouring organisms and groups of a search match in grey, for comparing. On phones the detail sheet has a drag handle (drag up for a taller sheet) and a Plain font option makes the Notes view easier to read.
- **Tools:** drug-first view grouped by class, empirical helper, clinical clues, compare up to three.
- Thai or English interface, light and dark themes, a **Key** button explaining the colours, keyboard access.

## Sources and what is not covered

Drug lists follow the Siriraj *Handbook of Infectious Disease* (Faculty of Medicine Siriraj Hospital, Mahidol
University), with the more recent guidance used as the main source where it differs:

- **Thai guidelines used as the main source where available:** the Thai COVID-19 guideline of 12 Aug 2024, the Thailand H. pylori consensus 2015 and the Thai DDC rabies guide (2019).
- **IDAT 2026** (Infectious Disease Association of Thailand): Guidance for the Treatment of Multidrug-Resistant
  Gram-Negative Bacterial Infections (AmpC, ESBL, CRE, Acinetobacter, Pseudomonas, Stenotrophomonas) and the
  melioidosis guideline, with the Thai DDC Melioidosis Manual 2021.
- **CDC and WHO** clinical pages and guidelines, for example anthrax (CDC 2023), tetanus, botulism (CDC 2021, with the Ramathibodi Poison Center antitoxin protocol), plague, tularemia, diphtheria, pertussis, yellow fever, Ebola, Lassa, CCHF, MERS, Nipah, polio, HTLV-1, prion diseases, and several protozoa and worms; the **CDC Yellow Book 2026** for the endemic areas of 18 organisms.
- **IDSA / ATS guidelines:** blastomycosis (2008), coccidioidomycosis (2016), nontuberculous mycobacteria (2020) and the 2022 consensus on less common NTM.
- **Mandell, Douglas and Bennett's *Principles and Practice of Infectious Diseases*, 9th ed (2020):** the source for rare yeasts and bacteria (Trichosporon, *Malassezia*, *Streptomyces* and other *Bacillus* species), and a cross-check for about 80 existing entries; where it adds a dose or a different first-line drug, the entry shows both and says which is which. Other references: ESC 2023 endocarditis guideline, IDSA catheter-infection guideline 2009, ATS/IDSA NTM statement 2007, UKHSA, and the MSD Manual for a few rare organisms.
- **NIH adult and adolescent HIV opportunistic infection guideline:** cryptococcosis, PCP, toxoplasmosis, MAC, CMV, HSV, VZV, syphilis, leishmaniasis, candidiasis, talaromycosis, histoplasmosis, bartonellosis, mpox, microsporidiosis, malaria and TB in HIV.
- **Thai NTP 2021** (TB) and the **Thai national HIV guideline**, as already used in the author's TB Regimen
  Guide and HIV guide.

Every organism now names a source. Three entries (the *Staphylococcus intermedius* group, the non-pathogenic *Neisseria* and other *Moraxella* species) are named in the handbook's diagrams only and have no regimen: they show N/A. Several rare organisms rest on weak evidence (case series, a regional protocol or an extrapolation from a related organism), and each of those entries says so. The vector,
hospital-acquired and non-pathogenic lists, most endemic areas and many test descriptions are also general
knowledge. A review sheet for a clinician to tick off is kept with the author.

The handbook was read from a scan, partly by OCR; verify any dose you rely on.

## Editing

The page is hand-edited as a single file; there is no build step. Open `pathogen-map.html` in a browser
to check a change, and check the phone layout at 375 px before publishing.

## Licence

Code, layout and views: Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International
(CC BY-NC-SA 4.0) — see `LICENSE` and `NOTICE`. The condensed drug information belongs to the authors of
the cited sources.
