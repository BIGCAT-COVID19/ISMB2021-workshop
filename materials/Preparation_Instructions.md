# ISMB Tutorial 8 Preparation Instructions: 
## Reproducible omics data analysis workflows with the COVID-19 Disease Map, WikiPathways and Cytoscape

**Installation instructions**

Please install the following tools (available on all platforms):
* [Cytoscape v3.8.2](https://cytoscape.org/download.html)
* [R v4.1.0](https://cloud.r-project.org/)
* [RStudio v1.4](https://www.rstudio.com/products/rstudio/download/#download)

<hr/>

**Install required R-packages**

Install BioCManager and required packages
```R
install.packages("BiocManager")
BiocManager::install("RCy3") 
BiocManager::install("rWikiPathways") 
BiocManager::install("clusterProfiler") 
BiocManager::install("org.Hs.eg.db") 
BiocManager::install("RColorBrewer") 
BiocManager::install("EnhancedVolcano") 
BiocManager::install("dplyr") 
BiocManager::install("tidyverse") 
BiocManager::install("clusterProfiler") 
BiocManager::install("DESeq2") 
```

<hr/>

**Contact**

Feel free to contact us in case you have problems installing the software or packages (ideally before the workshop!).<br/>
Submit an issue in the [Issue Tracker](https://github.com/BIGCAT-COVID19/ISMB2021-workshop/issues) and we will get back to you as soon as possible.
