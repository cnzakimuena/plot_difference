# Difference Plot
Script to generate a difference plot. The chick weight dataset (Crowder & Hand, 1990) including weight units ([Roberts, 1964](https://doi.org/10.3382/ps.0430238); [Knížetová et al, 1991](https://doi.org/10.1080/00071669108417427)) is used for demonstration.

Environment setup:

```bash
conda create -n myenv python=3.11
conda activate myenv
```

Dependencies installation:

```bash
pip install -r requirements.txt
```

Usage:

```bash
python plot_difference.py
```

<p align="center">
    <img src="figure.png" alt="example image" height="500">
</p>

Cite As

[Nzakimuena, C. B., Solano, M. M., Marcotte-Collard, R., Lesk, M. R., & Costantino, S. (2025). Spatial and temporal changes in choroid morphology associated with long-duration spaceflight. Investigative Ophthalmology & Visual Science, 66(5), 17-17.](https://doi.org/10.1167/iovs.66.5.17)

### References

1. [De Kort, H., Prunier, J. G., Ducatez, S., Honnay, O., Baguette, M., Stevens, V. M., & Blanchet, S. (2021). Life history, climate and biogeography interactively affect worldwide genetic diversity of plant and animal populations. Nature communications, 12(1), 516.](https://doi.org/10.1038/s41467-021-20958-2)
1. Crowder, M. J., & Hand, D. J. (1990). Analysis of repeated measures (Vol. 41). CRC Press.
1. [Roberts, C. W. (1964). Estimation of early growth rate in the chicken. Poultry Science, 43(1), 238-252.](https://doi.org/10.3382/ps.0430238)
1. [Knížetová, H., Hyanek, J., Kníže, B., & Roubíček, J. (1991). Analysis of growth curves of fowl. I. Chickens. British Poultry Science, 32(5), 1027-1038.](https://doi.org/10.1080/00071669108417427)