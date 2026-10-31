# Gold as an electrical conductor

A data-driven look at why gold is used in electronics even though it is not the best conductor.

## What it does
1. Ranks metals by electrical conductivity.
2. Tests the Wiedemann–Franz law on gold and other metals.
3. Compares conductivity with corrosion resistance (standard electrode potential).
4. Optional cost-per-conductance step once dated prices are added to `data/prices.csv`.

## Run it
```
pip install -r requirements.txt
jupyter notebook gold_conductivity.ipynb
```

## Data
Element properties come from the `pymatgen` periodic table (Ong et al., Comput. Mater. Sci. 68, 314, 2013). Electrode potentials are standard-table values. Check key values against a primary source (e.g. CRC Handbook) and cite it before publishing.

## Limitations
Values are rounded and near room temperature. Electrode potential is not a corrosion rate. Bulk metals only; thin-film size effects are planned.

## Planned
Size-effect model for gold thin films, and uses beyond currency and jewellery.

## Licence
Code: MIT (add a LICENSE file). Data: see sources above.
