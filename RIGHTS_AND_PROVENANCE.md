# Rights and Provenance

The public engineering source classifies A17 CAD, meshes, diagrams/manual artwork, and decal artwork as original producer-run material. NASA identifiers, NASA spacecraft CAD/geometry, NASA imagery, and third-party product expression are excluded from the deliverable. Factual safety and interoperability sources remain identified in the source provenance ledger.

This release does not broaden the rights status of any source. The full source records are reproduced below for inspection.

## Rights inventory

```csv
asset_or_source,classification,included_in_deliverable,rights_status,action
NASA logos/insignia/logotype/Artemis identifier,PROHIBITED,NO,Protected/restricted NASA identifiers,Exclude completely
NASA spacecraft CAD/geometry,PROHIBITED,NO,No exact replica or copied CAD admitted,Exclude completely
NASA imagery,REFERENCE_ONLY,NO,Not needed for product,Exclude to simplify rights posture
Estes Orion 3D geometry/STLs/manual art,PROHIBITED,NO,Third-party product expression,Use factual architectural lesson only
Estes Mean Machine geometry/manual art,PROHIBITED,NO,Third-party product expression,Use factual modularity lesson only
A17 CAD source and meshes,ORIGINAL,YES,Created in producer run,Admit
A17 diagrams/manual artwork,ORIGINAL,YES,Created in producer run,Admit
A17 decal artwork,ORIGINAL,YES,Created in producer run,Admit
NAR safety facts,FACTUAL_DATA,YES,Factual safety guidance paraphrased with source citation,Admit with citation/currentness note
OpenRocket file specification facts,FACTUAL_DATA,YES,Used for interoperable file structure,Admit with source citation
```

## Source provenance ledger

```csv
source_id,classification,authority,purpose,url,checked_utc,currentness_note
SRC-001,FACTUAL_DATA,National Association of Rocketry,Model Rocket Safety Code,https://www.nar.org/ModelRocketSafetyCode,2026-09-19,Current page crawled within 3 months; live canary PASS during producer run
SRC-002,FACTUAL_DATA,National Association of Rocketry,Certified motor listing / D12 current certification,https://www.nar.org/content.aspx?club_id=114127&module_id=670148&page_id=22,2026-09-19,Interactive list states Last Updated 2026 August 12; D12-0/3/5/7 listed
SRC-003,FACTUAL_DATA,National Association of Rocketry,Laws and Regulations overview,https://www.nar.org/LawsandRegulations,2026-09-19,Used only to require current jurisdiction/site verification; no universal legal claim
SRC-004,FACTUAL_DATA,OpenRocket Documentation,.ork file architecture and model handoff,https://openrocket.readthedocs.io/en/latest/dev_guide/file_specification.html,2026-09-19,Current documentation page crawled 2026-09-17
SRC-005,REFERENCE_ONLY,Estes Rockets,Hybrid 3D printed model-rocket architecture baseline,https://estesrockets.com/products/orion,2026-09-19,Concept-only reference: fin can/coupler/nose cone hybrid architecture; no copied geometry/artwork
SRC-006,REFERENCE_ONLY,Estes Rockets,Tall modular model rocket transport baseline,https://estesrockets.com/products/mean-machine,2026-09-19,Concept-only reference: tall airframe/modular transport; no copied geometry/artwork
SRC-007,FACTUAL_DATA,NASA,Brand restrictions and protected identifiers,https://www.nasa.gov/nasa-brand-center/brand-guidelines/,2026-09-19,Page last updated 2026-02-27; used to exclude NASA identifiers and endorsement implications
SRC-008,FACTUAL_DATA,NASA,Advertising / endorsement restrictions,https://www.nasa.gov/nasa-brand-center/advertising-guidelines/,2026-09-19,Used to prohibit official/approved/co-created implications
SRC-009,FACTUAL_DATA,NASA,Merchandise / toy naming guidance,https://www.nasa.gov/nasa-brand-center/merchandise-approvals/,2026-09-19,Used to avoid NASA product-title/branding use
```
