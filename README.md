<!-- README.md is generated from README.Rmd. Please edit that file -->
<!-- github markdown built using
rmarkdown::render("README.Rmd",output_format = "md_document")
-->
nichenetr
=========

[![Build
Status](https://travis-ci.org/browaeysrobin/nichenetr.svg?branch=master)](https://travis-ci.org/browaeysrobin/nichenetr)
[![Coverage
Status](https://codecov.io/gh/browaeysrobin/nichenetr/branch/master/graph/badge.svg)](https://codecov.io/gh/browaeysrobin/nichenetr)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1484138.svg)](https://doi.org/10.5281/zenodo.1484138)

**nichenetr: the R implementation of the NicheNet method.** The goal of
NicheNet is to study intercellular communication from a computational
perspective. NicheNet integrates expression data of interacting cells
with prior information on potential links between ligands and target
genes. Hereby, NicheNet can be used to study how one cell (or cell type)
influences gene expression in an interacting cell (or cell type). This
type of analysis can provide novel functional insights into
intercellular signaling processes compared to limiting the analyis to
ligand-receptor inference.

Specific functionalities include:

-   assessing how well ligands expressed by a sender cell can predict
    changes in gene expression in the receiver cell
-   prioritizing ligands based on their effect on gene expression
-   inferring putative ligand-target links active in the system under
    study
-   inferring potential signaling paths between ligands and target genes
    of interest

Installation of nichenetr
-------------------------

You can install nichenetr from github with:

    # install.packages("devtools")
    devtools::install_github("browaeysrobin/nichenetr")

Learning to use nichenetr
-------------------------

To learn using nichenetr, read one of the following, preliminary,
vignettes explaining several types of analyses:

-   [NicheNet's ligand activity analysis on a gene set of
    interest](vignettes/ligand_activity_geneset.md):
    `vignette("ligand_activity_geneset", package="nichenetr")`
-   [Inferring ligand-to-target signaling
    paths](vignettes/ligand_target_signaling_path.md):
    `vignette("ligand_target_signaling_path", package="nichenetr")`
-   [Model evaluation: target gene and ligand activity
    prediction](vignettes/model_evaluation.md):
    `vignette("model_evaluation", package="nichenetr")`
-   [Model construction](vignettes/model_construction.md):
    `vignette("model_construction", package="nichenetr")`

Note that documenation and vignettes are still under development and
that vignettes on additonal application possibilities, model validation,
model development and parameter optimization will be added in the near
future.
