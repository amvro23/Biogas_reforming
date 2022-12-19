# Biogas_reforming
Thermodynamic and kinetic analysis of Biogas Dry Reforming

# Equilibrium - Usage

```Python
from biogas_gibbs_minimization import CarbonEquilibrium
```
Create an object for the desired temperature and pressure of the system (e.g., 800 K, 1 atm).
```
mix = CarbonEquilibrium(800, 1)
```
Create plot for the gas mixture compositions.
```Python
mix.plot_molar_ratio
```
![molar_ratio_gas](https://user-images.githubusercontent.com/91277572/208422723-ac6be97a-8302-4e15-bf37-a0c5e39c63c1.png)
Create plot for the gas mixture conversions, yields and ratios.
```Python
mix.plot_conversions_yields_carbon
```
Create plot for the gas mixture compositions considering carbon formation.
```Python
mix.plot_molar_ratio_carbon
```
Create plot for the gas mixture conversions, yields and ratios considering carbon formation.
```Python
mix.plot_molar_ratio_carbon
```
