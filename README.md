# ACpop - novel variant annotations
A repository for annotations of novel variants in ACpop, a whole-genome sequenced northern Swedish population. Variants were called as described in [1]. Novel variants are defined as not being present in dbSNP 150.

## ACpop
The cohort consists of 300 whole-genome sequenced (30x) individuals from Västerbotten County in northern Sweden. Initially selected to function as a control population in cancer studies in northern Sweden. Samples must have had reached an age of at least 80 years and never been diagnosed with cancer. A VCF file with aggregated data is available from The Swedish Frequency resource for genomics (SweFreq): https://swefreq.nbis.se/dataset/ACpop.

## Annotations
Variant deleteriousness scores were annotated with the Combined Annotation Dependent Depletion (CADD) software [2-3]. Functional effects were predicted using the Variant Effect Predictor (VEP) [4] software from Ensembl.

The `VariantID` column in `ACpop_CADD.tsv.gz` contain custom variant IDs that match those in the `#Uploaded_variation` column in `ACpop_VEP.tsv.gz`.

## References
> [1] -  Svensson D, Rentoft M, Dahlin A.M., Lundholm E, Olason P.I., Sjödin A, Nylander C, Melin B.S., Trygg J, Johansson E. A whole-genome sequenced control population in northern Sweden reveals subregional genetic differences. bioRxiv 2020.02.18.933622; [doi:10.1101/2020.02.18.933622](https://www.biorxiv.org/content/10.1101/2020.02.18.933622v1)

> [2] - Kircher M, Witten DM, Jain P, O'Roak BJ, Cooper GM, Shendure J. A general framework for estimating the relative pathogenicity of human genetic variants. Nat Genet. 2014;46(3):310-315. [doi:10.1038/ng.2892](https://www.nature.com/articles/ng.2892)

> [3] - Rentzsch P, Witten D, Cooper GM, Shendure J, Kircher M. CADD: predicting the deleteriousness of variants throughout the human genome. Nucleic Acids Res. 2019;47(D1):D886-D894. [doi:10.1093/nar/gky1016](https://academic.oup.com/nar/article/47/D1/D886/5146191)

> [4] - McLaren W, Gil L, Hunt SE, Riat HS, Ritchie GR, Thormann A, Flicek P, Cunningham F. The Ensembl Variant Effect Predictor. Genome Biology Jun 6;17(1):122. (2016) [doi:10.1186/s13059-016-0974-4](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-016-0974-4)
