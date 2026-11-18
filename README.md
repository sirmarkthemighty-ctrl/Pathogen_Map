# Pathogen Map
### Interactive encyclopedia of infectious pathogens and their antimicrobials, as a mind map

A bedside and teaching tool by Warodom Phaenthong, M.D. It is one self-contained HTML page
(`pathogen-map.html`, opened by `index.html`) that runs in the browser, with no installation and no data
sent anywhere.

It is decision support for healthcare professionals. It does not replace the source documents, your local
antibiogram, hospital protocols, renal function and allergy checks, or clinical judgement.

**Open it:** https://sirmarkthemighty-ctrl.github.io/Pathogen_Map/

## What it does

- **Mind map** from *Infectious pathogens* to Bacteria, Fungi, Protozoa, Parasites, Viruses and a *By infection
  site* branch of 15 empirical-therapy syndromes. Tap a node to open it; drag to pan, pinch or scroll to zoom.
- **Bacteria grouped as in the handbook's Gram-stain diagrams** (Gram-positive, Gram-negative, Others), colour-coded
  violet, red and teal. Gram-positive cocci are split by coagulase and hemolysis.
- **Drug leaves** under each pathogen: first-line (green), alternative (blue), avoid or intrinsic resistance (red).
  Tap a drug to see its handbook class, dose, use and adverse effects, and every pathogen that lists it.
- **Notes view:** the same data as a handwritten-style outline on grid paper, with boxed groups.
- **Filters and tools:** search, Tropical and Mosquito-borne filters, a Saved list, expand all / collapse all,
  a count of pathogens shown, links to one pathogen (`#mrsa`), keyboard access, light and dark themes,
  Thai or English interface (group names and labels). Tap the version badge for the changelog.

## Sources and what is missing

Drug lists were checked against the Siriraj *Handbook of Infectious Disease* (Faculty of Medicine
Siriraj Hospital, Mahidol University). About 170 pathogens plus 15 infection-site entries; nearly every entry cites the printed handbook page in its panel; lists are
condensed, not quoted. **Five entries are not covered by the handbook** (AmpC producers, *H. pylori*, *T. cruzi*,
yellow fever, West Nile virus) and are labelled as written from general knowledge. Every organism named in the handbook's Gram-stain
diagrams is in the map; those the handbook gives no treatment for (for example *Bacillus*, *Brucella*,
*Francisella*) show no drugs and say so in their panel.

The handbook was read from a scan, partly by OCR; the drug dose table and the checked details were confirmed on the
page images, but verify any dose you rely on. The COVID-19 entry reflects the handbook's edition; check current
guidance. The Tropical and Mosquito-borne lists are the author's selection, not handbook lists.

## Editing

The page is hand-edited as a single file; there is no build step. Open `pathogen-map.html` in a browser
to check a change, and check the phone layout at 375 px before publishing.

## Licence

Code, layout and views: Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International
(CC BY-NC-SA 4.0) — see `LICENSE` and `NOTICE`. The condensed drug information belongs to the authors of
the cited sources.
