Code to reproduce the results of [**"Whisker stimulation reinforces a resting-state network in the
barrel cortex: nested oscillations and avalanches"**](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1014521) by Mariani et al, published in PLOS Computational Biology, 2026.

The data used are available at this [**Zenodo link**](https://zenodo.org/records/23187126) 

***Main Dependencies***

The project requires the following Python packages:

```bash
Packages used and their versions:
numpy==1.21.6
scipy==1.10.0
matplotlib==3.7.2
statsmodels==0.14.0
powerlaw==1.5
emd==0.5.5
pandas==2.0.3
```
`functions.py`, `avalanches_functions.py`, and `plotting_functions.py` support spike, firing-rate, and avalanche analysis. `power.py`, `powerlaw_fit.py`, and `stats.py` provide power-law fitting and statistical tools and were copied from [Testing Statistical Laws in Complex Systems](https://github.com/martingerlach/testing-statistical-laws-in-complex-systems) by Martin Gerlach and Eduardo G. Altmann.

![Model](figs/Model.jpg)
