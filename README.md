This repository describes the preprocessing steps to predict the cell type composition in cord blood using both the "auto" and "IDOL" method.

The [auto](https://bioconductor.org/packages/release/data/experiment/vignettes/FlowSorted.Blood.EPIC/inst/doc/FlowSorted.Blood.EPIC.html) method uses the underlying differentially methylated probes the deconvolute the cell type composition of various tissues with the embedded function in minfi while [IDOL](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-016-0943-7) uses an algorithm to iteratively scan for a candidate set of cell type specific markers to allow for the deconvolution of cell types and cell fractionalization. 

Using the Conditions Affecting Neurocognitive Development and Learning in Early Childhood (CANDLE) cohort, I attempt to benchmark both methods to determine their predictive accuracy to deconvolute cell types in cord blood. The output of my findings is described in the attached presentation deck. 
