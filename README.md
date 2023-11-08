# iSEEdemo


The `iSEE` package is a flexible, powerful and extendible application to explore any dataset stored in SummarizedExperiment objects, including single cell and spatially resolved data. 

`iSEE` enables a multitude of panels to gain in-depth insight in your data; it does so combining interactivity and reproducibility, and providing an ideal companion to CELLxGENE for deeper dives into data.

## How to install

```
library("remotes")
remotes::install_github("iSEE/iSEEdemo", 
                        dependencies = TRUE, 
                        build_vignettes = TRUE)
```

## How to run this demo

- Open the `iSEEdemo.Rproj` project file
- Navigate to the `vignettes` folder
- Make sure the datasets are included in the `datasets` subfolder (if using Seurat or AnnData)
- Open the `iSEEdemo.Rmd` Rmarkdown file and execute its content live!
