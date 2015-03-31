R project: RNAseq_using_shiny_markdown

Description:  Demo showing how shiny and markdown can be used to create an interactive report for RNAseq analysis using the edgeR and GOseq packages
-.  Demo was presented "RMarkdown/Shiny for Interactive Bioinformatics" at RSaint Louis R User Group meeting on March 17th, 2015

Summary:  RMarkdown and Shiny can be combined to generate interactive documents and analysis reports. 
For this meetup, I will demonstrate the use of R to analyze gene expression (RNA-seq) via the edgeR and goseq packages 
from Bioconductor. By combining RMarkdown/Shiny with the edgeR and goseq packages, we will create an interactive report 
that will allow the user to explore how changing parameters will affect the genes and gene ontology categories identified. 
 
Running this demo:
1.  Upgrade to latest version of Rstudio (v[masked])

2.  Install and switch to R 3.1.3 in rstudio

3.  Upgrade to newest version of Bioconductor

source(" http://bioconductor.org/biocLite.R")
biocLite("BiocUpgrade")

4.  Install required bioconductor packages

biocLite("edgeR")

biocLite("goseq")

biocLite("org.Hs.eg.db")

biocLite("geneLenDataBase")

5.  Install required cran packages

install.packages("shiny")

install.packages("data.table")

install.packages("knitr")

