Methylation Data Analysis Kit (minfi, methylumi, wateRmelon and illuminaio)

```
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
BiocManager::install("data.table", version = "3.8")
BiocManager::install("minfi", version = "3.8")
BiocManager::install("wateRmelon", version = "3.8")
BiocManager::install("methylumi", version = "3.8")
BiocManager::install("illuminaio", version = "3.8")

if (!requireNamespace("minfi", quietly = TRUE))
BiocManager::install("minfi", version = "3.8")



```
