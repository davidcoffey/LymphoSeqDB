# LymphoSeqDB
This package provides annotation databases that support the package LymphoSeq.

### Installation instructions

#### Install release version 0.99.2
###### Install from [Bioconductor](https://www.bioconductor.org/packages/LymphoSeq)
```
source("https://bioconductor.org/biocLite.R")
biocLite("LymphoSeq")
```

#### Install developer version 0.99.3
###### Option 1:  Install from [Bioconductor developer branch](https://www.bioconductor.org/developers/how-to/useDevel/)
```
# Switch to Bioconductor developer branch (requires latest version of R)
library(BiocInstaller)
useDevel()

# Download developer release
source("https://bioconductor.org/biocLite.R")
biocLite("LymphoSeq")

# Switch back to Bioconductor release branch
library(BiocInstaller)
useDevel()
```
###### Option 2:  Install from GitHub
```
# Install the latest version of Bioconductor
source("https://bioconductor.org/biocLite.R")
biocLite()

# Download developer tools
install.packages("devtools")

# Download package from GitHub
devtools::install_github("davidcoffey/LymphoSeqDB")
devtools::install_github("davidcoffey/LymphoSeq")
```

### Documentation
* [LymphoSeq vignette](https://bioconductor.org/packages/release/bioc/vignettes/LymphoSeq/inst/doc/LymphoSeq.pdf)
* [LymphoSeqDB manual](https://bioconductor.org/packages/release/data/annotation/manuals/LymphoSeqDB/man/LymphoSeqDB.pdf)
* [LymphoSeq news](https://bioconductor.org/packages/release/bioc/news/LymphoSeq/NEWS)
