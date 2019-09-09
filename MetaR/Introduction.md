![MetaR logo](images/MetaR-logo-4-SMALL-300x111.png)

MetaR takes advantage of Language Workbench Technology to facilitate data analysis with the R language. It can be used by:

* biologists with limited computational experience. No programming skills are required to start analyzing data.
* bioinformaticians who need to perform repetitive analyses and find it beneficial to design and use specialized analyses micro-languages to increase productivity and consistency of data analysis.
* bioinformaticians who wish to package state of the art analysis methods into user friendly metaR analysis language constructs. MetaR can act as a bridge between analysis experts who develop analysis methods in R and wish to distribute these methods to the broadest audience without investing a lot of effort in developing user interfaces.

MetaR is designed to work well with other languages of the platform. Importantly, users who learn how to use one component will acquire skills useful with other languages offered on the platform.

The following snapshot illustrates how metaR simplifies data analysis: we call differentially expressed genes with edgeR, join the resulting table with the table of counts, and produce a heatmap for the top 5% differentially regulated genes:
 
![MetaR snapshot](images/MetaR_Home_Snapshot.png){:height="60%" width="60%"}

Here’s another example showing how to look at intersection of gene lists with the integration of UpSetR/MetaR integration:

![MetaR snapshot2](images/UpSet_in_MetaR_Snapshot.png){:height="60%" width="60%"}