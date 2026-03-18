# IntubAid Changelog

## v1.0.0 — 2026-03-18
- Initial App Store submission

## v2.0.0-dev (in progress)
- 2026-03-18: Fixed mitigation chips not syncing across devices in Work Together mode (missing sync wrapper + text mismatch for chips with info icons)
- 2026-03-18: Updated anatomical difficulty mitigations — separated AFOI/VAFI and awake tracheostomy, combined double setup/mark neck, added AFOI/VAFI info modal
- 2026-03-18: Changed "Vasopressor running" to "Inotrope/vasopressor running" in haemodynamic instability mitigations
- 2026-03-18: Redesigned difficult airway assessment modal — added MACOCHA score (De Jong 2013) with live scoring, per-finding likelihood ratios from Detsky JAMA 2019, contextual guidance on each finding, sticky score footer with risk bands, and "About this score" section noting VL limitations. Added retrognathia and previous difficult intubation as assessment items. Consolidated cervical mobility items into single row.
- 2026-03-18: Added agitated/uncooperative risk with DSI mitigation chip and evidence modal (Bandyopadhyay 2023)
- 2026-03-18: Added Pre-ox tab to SET phase with four oxygenation strategies (NP+NRB, BVM, HFNP, NIV), timeline phase visualisation, and evidence pearls (PREOXI, Casey, Sjöblom, FLORALI-II)
- 2026-03-18: Added PREPARE II evidence note to drugs panel
- 2026-03-18: Added evidence nudges on airway tab — gentle prompts when user selects direct laryngoscopy (DEVICE 2023) or no adjunct (STYLETO 2021)
- 2026-03-18: Added pre-ox plan display to GO phase summary
- 2026-03-18: Updated reset to clear pre-ox selection and evidence nudges
- 2026-03-18: Removed instructional text from risks panel
- 2026-03-18: Removed default adjunct selection — requires explicit selection (human factors)
- 2026-03-18: Reordered GO summary: Risks → Pre-ox → Drugs → Airway (clinical briefing sequence)
- 2026-03-18: Updated post-intubation checklist wording; clarified Plan C/D labels
