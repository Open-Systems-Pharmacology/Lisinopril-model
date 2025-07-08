### In vitro / physico-chemical Data <a id="invitro-and-physico-chemical-data"></a>

A literature search was performed to collect available information on physicochemical properties of lisinopril. The obtained information from literature is summarized in the table below. 

| **Parameter**   | **Unit** | **Value** | Source                                     | **Description**                                 |
| :-------------- | -------- | --------- | ------------------------------------------ | ----------------------------------------------- |
| MW              | g/mol    |405.49     | [PubChem 2024](#main-references)               | Molecular weight                                |
| pK<sub>a</sub>  |  -        | 1.63 (strongest acidic)          | [Takács-Novák 2003](#main-references)         | Acid dissociation constant                      |
| pK<sub>a</sub>  |   -       | 10.75 (strongest basic)          | [Takács-Novák 2003](#main-references)         | Acid dissociation constant                      |
| Solubility (pH) |  1 at pH7.2        |     mg/mL      | [Product information from Cayman Chemical Co](#main-references)               | Aqueous Solubility, FaSSIF, ...                 |
| fu              | %        |   100        | [Cayman Chem 2022](#main-references)                | Fraction unbound in plasma                      |

### Clinical Data  <a id="clinical-data"></a>

A literature search was performed to collect available clinical data on lisinopril in healthy adults.

#### Model Building <a id="model-building"></a>

The following studies were used for model building (training data):

| **Dose [mg]** | **Dosing** | **PK data** |**Dataset**| **Reference** |
| --------------- | ------------------- | ----------------------- | ----------------- |----------------- |
| 10| po, tab, fasted, sd |plasma|training|[Ulm 1982](#5-references)| 
| 5| po, tab, fasted, qd |plasma|training|[Gautam 1987](#5-references)| 
| 20| po, tab, fasted, sd |plasma|training|[Mojaverian 1986](#5-references)| 
| 20| po, tab, fed, sd |plasma|training|[Mojaverian 1986](#5-references)| 

#### Model Verification <a id="model-verification"></a>

The following studies were used for model verification:

| **Dose [mg]** | **Dosing** | **PK data** |**Dataset**| **Reference** |
| --------------- | ------------------- | ----------------------- | ----------------- |----------------- |
| 10| po, tab, fasted, sd |plasma|training|[Ulm 1982](#5-references)| 
| 5| po, tab, fasted, qd |plasma|training|[Gautam 1987](#5-references)| 
| 20| po, tab, fasted, sd |plasma|training|[Mojaverian 1986](#5-references)| 
| 20| po, tab, fed, sd |plasma|training|[Mojaverian 1986](#5-references)| 
