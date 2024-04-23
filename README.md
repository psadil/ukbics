## UKB Independent Components (ukbics)

This repo walks through one approach to visualizing the UKB components. 

## Setup

Packages are recorded using [`renv`](https://rstudio.github.io/renv/index.html). If you open the project in RStudio, the `renv` infrastructure should be boostrapped (via .Rprofile). If that works, then you can install the dependencies with.

```r
renv::restore()
```

The quarto document relies on a nifti image `melodic_IC_100.nii.gz`. The comes from the [UKB imaging analysis page](https://www.fmrib.ox.ac.uk/datasets/ukbiobank/fbp/), under [Templates and training data needed by the pipeline](https://www.fmrib.ox.ac.uk/datasets/ukbiobank/fbp/templates/dckr_build/DATA_public.tar.gz) that links to a compressed archive called `Data_public.tar.gz`. The relevant template is the `group/` folder (i.e., `group/melodic_IC_100.nii.gz`).

