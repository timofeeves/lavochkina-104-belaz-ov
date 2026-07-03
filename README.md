# Object Control Repository: Lavochkina 104 - OV

Working repository for the ventilation and heating/ventilation coordination of the non-residential premises at Smolensk, Lavochkina street, 104.

## Purpose

This repository is used to keep one controlled record of:

- incoming source data;
- missing and expected data;
- questions to the client, technologist, and equipment suppliers;
- received answers;
- design assumptions;
- ventilation concept notes;
- equipment-specific local exhaust decisions;
- calculation files and final outputs.

## Current Focus

The current design question is the ventilation arrangement for a repair workshop with equipment for diesel engines, electrical machines, drying, blowing/cleaning, fuel equipment, machining, grinding, and testing.

Key coordination point:

The existing Teplovey T-170iH air heater may be used as air heating/recirculation equipment, but it should not be treated as a substitute for sanitary or technological ventilation. Local exhausts, technological gas exhausts, and compensating supply air must be coordinated by air balance.

## Repository Map

| Folder | Purpose |
|---|---|
| `00_admin` | Object card, decision log, meeting notes |
| `01_incoming` | Register of received files and source data |
| `02_questions` | Questions to client, technologist, suppliers |
| `03_answers` | Received answers and confirmations |
| `04_source-data` | Structured source-data register |
| `05_expected-data` | Missing data and requested documents |
| `06_technical-notes` | Design notes, matrices, assumptions |
| `07_calculations` | Calculation inputs, calculation notes, checked outputs |
| `08_norms` | Normative base and applicability notes |
| `09_outputs` | Issued drafts, final PDFs/DOCX/XLSX, transmittals |
| `templates` | Reusable templates for questions and decisions |

## Working Rule

Do not silently assume data for equipment emissions. If a source of harmful emissions, heat, dust, fuel vapors, or exhaust gases is unclear, create a question in `02_questions/questions-register.md` and track the answer in `03_answers/answers-register.md`.
