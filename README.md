## TmS

Cancer transcriptomes vary greatly. Single-cell RNA sequencing shows that total mRNA content correlates with tumor phenotypes. Technical and analytical challenges, however, impede at-scale pan-cancer examination of total mRNA content. We propose to quantify tumor-specific total mRNA expression (TmS) from bulk sequencing data, taking into account tumor transcript proportion, purity and ploidy, which are estimable through transcriptomic/genomic deconvolution. We estimate and validate TmS in 6,590 patients across 15 cancer types identifying significant inter-tumor variability. Across cancers, high TmS is associated with increased risk of disease progression and death.  Cancer-specific patterns of gene alterations, intra-tumor genetic heterogeneity, as well as pan-cancer trends in metabolic dysregulation contribute to TmS. Taken together, our results suggest that measuring cell type-specific total mRNA expression offers an unique perspective on cancer transcriptomes, with biological and clinical implications [1].  


## Package installation
We used ``DeMixT`` v1.2.2 to calculate the TmS values provided in our current study [1]. The DeMixT source files are compatible with Windows, Linux and MacOS. For further information about ``DeMixT``, please visit [https://github.com/wwylab/DeMixT](https://github.com/wwylab/DeMixT).

#### Install ``DeMixT``
```
git clone https://github.com/wwylab/DeMixT.git
cd DeMixT
R CMD INSTALL DeMixT_1.2.2.tar.gz
```
Check if ``DeMixT`` is installed successfully:

```
# load package
library(DeMixT)
```

#### Install ``OpenMP``
``DeMixT`` requires ``OpenMP`` to enable the parallel computing. We provide a brief instruction for installing ``OpenMP``. Please check the file https://github.com/wwylab/DeMixT/raw/master/HowtoinstallOpenMP.docx.

### More information

Please visit the [TmS resource page for tutorial and data](https://wwylab.github.io/TmS/articles/TmS.html).

## Contact
For questions or support related to the inquiries of TmS, please contact Dr. Wenyi Wang (<wwang7@mdanderson.org>).

## Cite ``TmS``

[1] Cao, S. et al. Estimation of tumor cell total mRNA expression in 6,590 cancers predicts disease progression. bioRxiv 2020.09.30.306795 (2021) doi:10.1101/2020.09.30.306795.
