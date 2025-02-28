### Absorption <a id="model-parameters-and-assumptions-absorption"></a>

The parameters values for `Intestinal permeability` and `Permeability P(intracellular->interstitial) Mucosa` were optimized based on clinical oral data, see [Section 2.3.4](#model-parameters-and-assumptions-identification). 
The measured solubility of lisinopril was taken from Product information from Cayman Chemical Co (see [Section 2.2.1](#invitro-and-physico-chemical-data)).

Tablet dissolution was modeled using an empirical Weibull dissolution approach, with the corresponding parameters estimated accordingly.

### Distribution <a id="model-parameters-and-assumptions-distribution"></a>

Lisinopril does not bind to plasma proteins (fu = 100 %) (see [Section 2.2.1](#invitro-and-physico-chemical-data)) ([Beermann 1989](#main-references)). In this PBPK model, a value of 100% was assigned to `Fraction unbound (plasma, reference value)`.

An important parameter influencing the resulting volume of distribution is lipophilicity, which was also estimated. 

After testing the available organ-plasma partition coefficient and cell permeability calculation methods built in PK-Sim®, observed clinical data was best described by choosing the partition coefficient calculation by `Schmitt` and cellular permeability calculation by `Charged dependent Schmitt`.

### Metabolism and Elimination <a id="model-parameters-and-assumptions-metabolism-and-elimination"></a>

After absorption, lisinopril remains unbound to plasma proteins, does not undergo metabolism, and is not secreted into bile. The drug is primarily eliminated through renal plasma clearance, with `Plasma Clearance` estimated accordingly.

### Automated Parameter Identification <a id="model-parameters-and-assumptions-parameter-identification"></a>

This is the result of the final parameter identification.

| Model Parameter      | Optimized Value | Unit |
| -------------------- | --------------- | ---- |
| `lipophilicity` |          -0.58       |   Log Units   |
| `Plasma Clearance` |        1.18         |      |ml/min/kg
| `Intestinal permeability` |     1.35E-8            | cm/s     |
| `Weibul Dissolution time` |        120         |  min    |
| `Weibul Dissolution shape` |        3.00         |   -   |
| `Permeability P(intracellular->interstitial) Mucosa (large intestine)` |        8.1132E-6         |   cm/min   |
| `Permeability P(intracellular->interstitial) Mucosa (small intestine)`  |        3E-09         |   cm/min   |


