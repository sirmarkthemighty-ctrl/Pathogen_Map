# Pathogen Map
### Interactive encyclopedia of infectious pathogens and their antimicrobials, as a mind map

A bedside and teaching tool by Warodom Phaenthong, M.D. It is one self-contained HTML page
(`pathogen-map.html`, opened by `index.html`) that runs in the browser, with no installation and no data
sent anywhere.

It is decision support for healthcare professionals. It does not replace the source documents, your local
antibiogram, hospital protocols, renal function and allergy checks, or clinical judgement.

**Open it:** https://sirmarkthemighty-ctrl.github.io/Pathogen_Map/

## What it does

- **Mind map** from *Infectious pathogens* to Bacteria, Fungi, Protozoa, Parasites and Viruses, then to
  groups and individual pathogens. Tap a node to open it; drag to pan, pinch or scroll to zoom.
- **Gram-positive cocci split by lab test:** staphylococci (coagulase-positive / -negative) and
  streptococci and enterococci (β-, α-, γ-hemolytic).
- **Drug leaves** under each pathogen: first-line (green), alternative (blue), avoid or intrinsic
  resistance (red). Tap a drug to list every pathogen that uses it.
- **Notes view:** the same data as a handwritten-style outline on grid paper with bracket connectors.
- Search by pathogen or drug, light and dark themes, phone layout. Tap the version badge for the changelog.

## Sources and what is missing

Drug lists were checked against the Siriraj *Handbook of Infectious Disease* (Faculty of Medicine
Siriraj Hospital, Mahidol University). **92 of 96 entries** cite the printed handbook page in their panel.
Lists are condensed, not quoted. **4 entries are not covered by the handbook** (AmpC producers,
*H. pylori*, *P. knowlesi*, *T. cruzi*) and are labelled as written from general knowledge.

The handbook was read by OCR from a scan, so a few OCR-read details should be confirmed against the page:
the *S. suis* course lengths, the dengue "avoid NSAIDs" line and the measles vitamin A doses. The
COVID-19 entry reflects the handbook's edition; check current guidance.

## Editing

The page is hand-edited as a single file; there is no build step. Open `pathogen-map.html` in a browser
to check a change, and check the phone layout at 375 px before publishing.

## Licence

Code, layout and views: Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International
(CC BY-NC-SA 4.0) — see `LICENSE` and `NOTICE`. The condensed drug information belongs to the authors of
the cited sources.
