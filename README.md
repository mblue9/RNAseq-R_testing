# RNAseq analysis in R

In this workshop, you will be learning how to analyse RNA-seq count data, using R. This will include importing the data into R, quality control and performing differential expression analysis and gene set testing, with a focus on the limma-voom analysis workflow. You will learn how to generate common plots for analysis and visualisation of gene expression data, such as boxplots and heatmaps. You will also be learning how alignment and counting of raw RNA-seq data can be performed in R. This workshop is aimed at biologists interested in learning how to perform differential expression analysis of RNA-seq data when reference genomes are available. It was first taught [here](http://combine-australia.github.io/2016-05-11-RNAseq/).

## Prerequisites

Some basic R knowledge is assumed.
If you are not familiar with the R statistical programming language we
strongly encourage you to work through an introductory R course before
attempting these materials.
We recommend the Software Carpentry
[R for Reproducible Scientific Analysis](http://swcarpentry.github.io/r-novice-gapminder/)
lessons up to and including Subsetting Data. Links to these modules are listed under **Supplementary lessons** below.


## Data

- Mouse mammary data (counts): [https://figshare.com/s/1d788fd384d33e913a2a](https://figshare.com/s/1d788fd384d33e913a2a)
- Drosophila data (counts): [https://figshare.com/s/e08e71c42f118dbe8be6](https://figshare.com/s/e08e71c42f118dbe8be6)

## RNAseq analysis in R

- [R for RNAseq](articles/00-r-rstudio-intro.html)
- [Quality control, differential expression, and gene set testing](articles/06-rnaseq-day1.html)
- [Applying RNAseq](articles/08-applying-rnaseq.html) ([solutions](articles/09-applying-rnaseq-solutions.html))

### Lecture slides

- [RNASeq basics](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/COMBINE-Australia/RNAseq-R/gh-pages/slides/RNASeq_basics.pdf)
- [Filtering and QC](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/COMBINE-Australia/RNAseq-R/gh-pages/slides/RNASeq_filtering_qc.pdf)
- [Differential expression](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/COMBINE-Australia/RNAseq-R/gh-pages/slides/Differential_Expression_Analysis.pdf)
- [Gene set testing](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/COMBINE-Australia/RNAseq-R/gh-pages/slides/Gene_set_testing.pdf)

### Supplementary lessons

Introductory R materials:

- [Introduction to R and RStudio](https://swcarpentry.github.io/r-novice-gapminder/01-rstudio-intro/index.html)
- [Project Management With RStudio](https://swcarpentry.github.io/r-novice-gapminder/02-project-intro/index.html)
- [Seeking help](https://swcarpentry.github.io/r-novice-gapminder/03-seeking-help/index.html)
- [Data Structures](https://swcarpentry.github.io/r-novice-gapminder/04-data-structures-part1/index.html)
- [Exploring Data Frames](https://swcarpentry.github.io/r-novice-gapminder/05-data-structures-part2/index.html)
- [Subsetting Data](https://swcarpentry.github.io/r-novice-gapminder/06-data-subsetting/index.html)

Additional RNAseq materials:

- [Alignment and feature counting](07-rnaseq-day2.html)

Data: Mouse mammary data (fastq files): [https://figshare.com/s/f5d63d8c265a05618137](https://figshare.com/s/f5d63d8c265a05618137)

### Additional resources

[Bioconductor help](https://www.bioconductor.org/help/)  
[Biostars](https://www.biostars.org/)  
[SEQanswers](http://seqanswers.com/)  
