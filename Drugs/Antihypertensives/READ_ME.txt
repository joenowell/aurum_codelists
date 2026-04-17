1. Source Data
The codelist was created from a comprehensive merger of a codelist previously used in the lab and mapping DMD codes from published studies of CPRD gold data. Citations: Alison K Wright, Evangelos Kontopantelis, Richard Emsley, Ian Buchan, Mamas A Mamas, Naveed Sattar, Darren M Ashcroft, Martin M Rutter. PH917 / 1913 - Antihypertensives. Phenotype Library [Online]. 04 April 2022. Available from: http://phenotypes.healthdatagateway.org/phenotypes/PH917/version/1913/detail/. [Accessed 02 April 2026]

Mathur, RORCID logo (2023). Therapy codelist - CPRD Gold - Antihypertensive medications read codes. [Dataset]. London School of Hygiene & Tropical Medicine, London, United Kingdom. 10.17037/DATA.00003491.

2. Inclusion Principles
Included drug classes:
- ACE inhibitors
- ARBs
- Beta-blockers
- Calcium channel blockers
- Thiazide and thiazide-like diuretics
- Loop diuretics
- Potassium-sparing diuretics
- Aldosterone antagonists
- Oral combination antihypertensive products

3. Exclusion Rules
The following medications were removed using manual checks and m365 copilot:

A. Alpha-blockers (dual indication for BPH and hypertension)
These were removed because their indication cannot be reliably determined without diagnosis linkage:
- Doxazosin
- Prazosin
- Terazosin
- Indoramin
- Tamsulosin

B. Intravenous or Injectable Products
All IV, IM, SC, and infusion products were removed because they are used only for acute care and not chronic hypertension management.

Additional suggested removal in "merged list for copilot"
C. Non-antihypertensive cardiovascular agents
Drugs that may affect blood pressure transiently but are not prescribed for hypertension were removed, e.g. Isoprenaline.

D. BPH-specific starter packs
Products such as Hytrin BPH starter packs were removed due to non-hypertensive indication.

E. Titration Packs
- Ramipril titration packs were kept because they contain standard oral antihypertensive doses.
- Other titration packs that were packaging constructs (e.g., certain Tritace titration packs) were removed.

4. Final Output
Each product was assigned a KEEP or REMOVE flag according to the above rules. The final filtered antihypertensive list contains only medications suitable for QRISK3's blood-pressure-treatment variable.


