# all packages is necessary for airway differential expression(DE) with DESeq2

if (!requireNamespace("BiocManager", quietly = TRUE))  install.packages("BiocManager")
BiocManager::install("DESeq2")
BiocManager::install("airway")
BiocManager::install("ggplot2")
BiocManager::install("EnhancedVolcano")
BiocManager::install("dplyr")
BiocManager::install("org.Hs.eg.db")
BiocManager::install("AnnotationDbi")
BiocManager::install("genefilter")
install.packages("pheatmap")
install.packages("PoiClaClu")

library(DESeq2)
library(airway)
library(RColorBrewer)
library(pheatmap)
library(PoiClaClu)
library(ggplot2)
library(genefilter)
library(EnhancedVolcano)
library(dplyr)
library(org.Hs.eg.db)
library(AnnotationDbi)
