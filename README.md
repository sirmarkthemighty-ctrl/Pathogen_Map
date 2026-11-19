# Pathogen Map (beta)
### Interactive encyclopedia of infectious pathogens and their antimicrobials

A bedside and teaching tool by Warodom Phaenthong, M.D. It is one self-contained HTML page
(`pathogen-map.html`, opened by `index.html`) that runs in the browser, with no installation and no data
sent anywhere. Version 0.8.8 (beta).

It is decision support for healthcare professionals. It does not replace the source documents, your local
antibiogram, hospital protocols, renal function and allergy checks, or clinical judgement.

**Open it:** https://sirmarkthemighty-ctrl.github.io/Pathogen_Map/

## What it does

- **248 pathogens** plus 15 infection-site (empirical therapy) entries, in two views: **Notes** (handwritten-style
  outline, the default) and **Map** (mind map; drag to pan, pinch or scroll to zoom).
- **Grouped as in the handbook's diagrams:** Gram-positive, Gram-negative and other bacteria, fungi, protozoa,
  parasites, viruses and prions; species of one genus sit under one node.
- **Detail box** (right-click or long-press): key points, first-line, alternative and avoid drugs, endemic area,
  vector, screening and diagnostic tests, and **source buttons** (IDAT, CDC Yellow Book, handbook page, or
  "general knowledge"). Only key points and first-line open by default; "Show all details" opens the rest.
  Print one organism on a page.
- **Filters** (persistent box under the toolbar): pathogenicity, community or hospital acquired, type, vector
  (mosquito, tick, mite, flea, louse, sandfly, tsetse fly, blackfly, triatomine bug, deer fly), Gram stain, endemic
  area and tropical. Search, Saved and Recent lists, optional first-line drug beside each name, and an optional "Show related (grey)" setting that shows the neighbouring organisms and groups of a search match in grey, for comparing.
- **Tools:** drug-first view grouped by class, empirical helper, clinical clues, compare up to three.
- Thai or English interface, light and dark themes, a **Key** button explaining the colours, keyboard access.

## Sources and what is not covered

Drug lists follow the Siriraj *Handbook of Infectious Disease* (Faculty of Medicine Siriraj Hospital, Mahidol
University), with the more recent guidance used as the main source where it differs:

- **IDAT 2026** (Infectious Disease Association of Thailand): Guidance for the Treatment of Multidrug-Resistant
  Gram-Negative Bacterial Infections (AmpC, ESBL, CRE, Acinetobacter, Pseudomonas, Stenotrophomonas) and the
  melioidosis guideline, with the Thai DDC Melioidosis Manual 2021.
- **CDC Yellow Book 2026** for the endemic areas of 18 organisms.
- **Thai NTP 2021** (TB) and the **Thai national HIV guideline**, as already used in the author's TB Regimen
  Guide and HIV guide.

About 30 organisms are not covered by any of these (for example mpox, prions, yellow fever, West Nile virus,
*H. pylori*, *T. cruzi*, the endemic fungi) and are labelled as written from general knowledge. The vector,
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
