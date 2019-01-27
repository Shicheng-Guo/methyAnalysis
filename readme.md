Methylation Data Analysis Kit (minfi, methylumi, wateRmelon and illuminaio)
* 486427=485512+65+850
* Be sure it is Admin account
```
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
BiocManager::install("data.table", version = "3.8")
BiocManager::install("minfi", version = "3.8")
BiocManager::install("wateRmelon", version = "3.8")
BiocManager::install("methylumi", version = "3.8")
BiocManager::install("illuminaio", version = "3.8")
BiocManager::install("minfi", version = "3.8")

# control probes=850
require(IlluminaHumanMethylation450kmanifest)
control<-getProbeInfo(IlluminaHumanMethylation450kmanifest, type = "Control")
type1<-getProbeInfo(IlluminaHumanMethylation450kmanifest, type = "I")
type2<-getProbeInfo(IlluminaHumanMethylation450kmanifest, type = "II")
SnpI<-getProbeInfo(IlluminaHumanMethylation450kmanifest, type = "SnpI")
SnpII<-getProbeInfo(IlluminaHumanMethylation450kmanifest, type = "SnpII")
```
