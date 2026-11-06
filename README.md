# TEA_Model

Techno-economic analysis (TEA) work for ENGG 192: LCA/TEA of sodium-ion battery electrolytes (solid-state and gel polymer).

Live page: https://sfreitas1118.github.io/TEA_Model/

## Contents

| File | What it is |
|---|---|
| `index.html` | Process flows for the NaPF₆ liquid baseline and oxide (NASICON), sulfide, halide and PEO–PPC–NASICON composite electrolytes, with LCA/TEA hotspots, a worst-case H₂S bound and a per-kWh electrolyte cost calculator. Also the baseline TEA results (cell cost, material prices, sensitivity, benchmarks, conclusions). Open in any browser. |
| `SF_TEA_tables.xlsx` | Stationary-storage Na-ion cell plant TEA (8 GWh/yr, 1 kWh functional unit), rebuilt from Julian Chitu's Na-ion EV model ("NA EV" TEM project): Inputs, PFD mass balance, CapEx, OpEx, levelized cell cost and sensitivity, plus the Argonne reference tables and a list of model issues. |

## Current baseline result (Nov 2026)

- Levelized cell cost: **$52.63/kWh** (was $69.27/kWh with Li-ion proxy prices).
- Prussian White, hard carbon and Na-ion electrolyte now use SMM prices (28 Aug 2026); the previous Li-ion proxy prices are kept in column I of the OpEx sheet.
- Other materials still use Argonne BatPaC 2024 (Li-ion) prices.

## Notes

- Temperatures, thicknesses and $/kg values in the process-flow cards and calculator are illustrative placeholders, not cited values.
- In the spreadsheet, blue cells are inputs, black cells are formulas, and the "Julian's value" columns hold his original numbers for comparison.
- The earlier `NaEV_Julian_TEA_tables.xlsx` was replaced by `SF_TEA_tables.xlsx`; it is still in the git history.
