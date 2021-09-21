### The code and datasets for the manuscript: 

# ETV2 functions as a pioneer factor to regulate and reprogram the endothelial lineage

## Processed datasets

| | link | Format | Script | 
| --- | --- | --- | --- | 
| ATAC-seq counts | [link](https://s3.msi.umn.edu/gongx030/datasets/dataset=Etv2ATAC_version=20190228a/all_ATAC.rds) | SummarizedExperiment | [R](ATAC_seq_preprocess.Rmd) |
| scRNA-seq of Etv2 induced reprogramming | [link](https://s3.msi.umn.edu/gongx030/etv2_pioneer/data/processed_Etv2_scRNAseq.rds) | SummarizedExperiment | [R](scRNA_seq_preprocess.Rmd) |
| Bulk RNA-seq of EB differentiation induced by Etv2 Dox | [link](https://s3.msi.umn.edu/gongx030/datasets/dataset=Etv2RNA-seq_version=20190909a/se.rds) | SummarizedExperiment | |
| A union set of Etv2 ChIP-seq peaks in ES/EB and MEFs | [link](https://s3.msi.umn.edu/gongx030/datasets/dataset=Etv2PioneerChIPseq_version=20191203a/all_Etv2_peaks.rds) | SummarizedExperiment | [R](generate_union_Etv2_peakset.ipynb) |

## Notebooks

|  | Figures | Preview | Colab link | Time |
| --- | --- | --- | --- | --- |
| Identifying Candidates for shRNA Knock Down testing of additional SWI/SNF Factors  | | [R](Etv2_Project_SWI_SNF_shRNA_Candidate_gene_Expression_Testing.ipynb) | [R](https://colab.research.google.com/github/gongx030/Etv2_pioneer/blob/master/Etv2_Project_SWI_SNF_shRNA_Candidate_gene_Expression_Testing.ipynb) | 1 hr | |
| Differential Expressing testing candidate genes for knockdown in MEFs | | [R](Etv2_Project_Candidate_gene_Expression_Testing.ipynb) | [R](https://colab.research.google.com/github/gongx030/Etv2_pioneer/blob/master/Etv2_Project_Candidate_gene_Expression_Testing.ipynb) | 1 hr | |
| Generate a union set of Etv2 ChIP-seq peaks | | [R](generate_union_Etv2_peakset.ipynb) | | | |
| Process scRNA-seq of<br> Etv2 reprogramming | | [R](scRNA_seq_preprocess.Rmd) |  | | |
| Process ATAC-seq data | | [R](ATAC_seq_preprocess.Rmd) |  |   |  |
| scRNA-seq of Etv2 induced reprogramming | Figure 1c-1g <br> Supplementary Figure 2 <br> Supplementray Figure 4 | [R](scRNA_seq.ipynb) | [R](https://colab.research.google.com/github/gongx030/etv2_pioneer/blob/master/scRNA_seq.ipynb) | 11 mins |
| ATAC-seq and combined ATAC-seq/RNA-seq of <br> Etv2 induced MEF reprogramming and ES/EB differentiation | Figure 1h <br> Figure 1i <br> Supplementary Figure 5 | [R](ATAC_analysis.ipynb) | [R](https://colab.research.google.com/github/gongx030/etv2_pioneer/blob/master/ATAC_analysis.ipynb) | 9 mins |
| Overlap of Etv2 ChIP-seq peaks in MEF and EB | Supplementary Figure 8 | [R](Etv2_ChIP_seq_peaks.ipynb) | [R](https://colab.research.google.com/github/gongx030/etv2_pioneer/blob/master/Etv2_ChIP_seq_peaks.ipynb) | 1 min | 
| Pathway analysis of early, late and sustained Etv2 peaks | Supplementary Figure 9d | [R](Pathway_Etv2_peaks.ipynb) | [R](https://colab.research.google.com/github/gongx030/etv2_pioneer/blob/master/Pathway_Etv2_peaks.ipynb) | 3.9 mins | 
| Etv2 motifs in early, late and sustained Etv2 peaks | Figure 3a and 3b | [R](Etv2_motifs_in_early_Etv2_peaks.ipynb) | [R](https://colab.research.google.com/github/gongx030/etv2_pioneer/blob/master/Etv2_motifs_in_early_Etv2_peaks.ipynb) | 1 min |
| Early, late and sustained Etv2 peaks in **MEF** | Figure 3e | [R](early_Etv2_peaks_in_MEF.ipynb) | [R](https://colab.research.google.com/github/gongx030/etv2_pioneer/blob/master/early_Etv2_peaks_in_MEF.ipynb) |  |
| D7 Brg1 KD ATAC-seq | Figure 4c <br> Supplementary Figure 12 | [R](Brg1_KD_sustained_Etv2_peaks.ipynb) | [R](https://colab.research.google.com/github/gongx030/etv2_pioneer/blob/master/Brg1_KD_sustained_Etv2_peaks.ipynb) |  |
| chromVAR analysis of Brg1 KD ATAC-seq at D7| Figure 4b | [R](chromVAR_Brg1_KD_ATAC_D7.ipynb) | [R](https://colab.research.google.com/github/gongx030/etv2_pioneer/blob/master/chromVAR_Brg1_KD_ATAC_D7.ipynb) | 2 mins |
| D7 scRNA-seq including Brg1 KD samples | Figure 4e-4h | [R](Brg1KD_scRNA_seq_D7.ipynb) | [R](https://colab.research.google.com/github/gongx030/etv2_pioneer/blob/master/Brg1KD_scRNA_seq_D7.ipynb) | 1.1 hrs |
| D0 scRNA-seq including Brg1 KD samples | Supplementary Figure 13a-13g | [R](Brg1KD_scRNA_seq_D0.ipynb) | [R](https://colab.research.google.com/github/gongx030/etv2_pioneer/blob/master/Brg1KD_scRNA_seq_D0.ipynb) |  |
| D0 ChIP-seq H3K27ac in Brg1 KD samples | Supplementary figure 13h | [R](H3K27ac_Chip_seq_Analysis.ipynb) | [R](https://colab.research.google.com/github/gongx030/etv2_pioneer/blob/master/H3K27ac_Chip_seq_Analysis.ipynb) | 23 mins |
| Lmo2 binding sites | Figure 2f | [R](Lmo2_track.ipynb) | [R](https://colab.research.google.com/github/gongx030/etv2_pioneer/blob/master/Lmo2_track.ipynb) | 1 min |
| Enriched TFBS in commonly <br> up- and down-regulated genes <br> in EB and MEFs on Etv2 induction | Supplementary Figure 5i, 5j, 5k | [R](FBS_in_commonly_regulated_genes.ipynb) | [R](https://colab.research.google.com/github/gongx030/etv2_pioneer/blob/master/FBS_in_commonly_regulated_genes.ipynb) | 10 mins |
| NFR vs NOR at EB D2.5 | Figure 2d | [R](Etv2_ChIP_seq_analysis.ipynb) |  |  |
| NFR vs NOR at Etv2 binding sites at D1 MEF reprogramming | Figure 2c | [R](Etv2_binding_D1_MEF.ipynb) | [R](https://colab.research.google.com/github/gongx030/etv2_pioneer/blob/master/Etv2_binding_D1_MEF.ipynb) | 1.5 hrs | 
| NFR vs NOR at Etv2 binding sites at D1 MEF reprogramming <br> (including additional epigenetic marks) | Supplementary Figure 6a | [R](Etv2_binding_D1_MEF_extended.ipynb) | [R](https://colab.research.google.com/github/gongx030/etv2_pioneer/blob/master/Etv2_binding_D1_MEF_extended.ipynb) | 1.5 hrs |
| D7 Brg1 KD ATAC-seq (NOR vs NFR) | Figure 4a | [R](Brg1_KD_sustained_Etv2_peaks_NOR_NFR.ipynb) | [R](https://colab.research.google.com/github/gongx030/etv2_pioneer/blob/master/Brg1_KD_sustained_Etv2_peaks_NOR_NFR.ipynb) | 53 mins |
| scRNA-seq of Etv2 induced reprogramming at MEF and D1 | | [R](scRNA_seq_D1.ipynb) | [R](https://colab.research.google.com/github/gongx030/etv2_pioneer/blob/master/scRNA_seq_D1.ipynb) | |



## Notebooks for Supplementary Figure

| Description | Figure | Colab link | 
| --- | --- | --- |
| We look at the enrichment of signals +/-1kb of Etv2 binding sites using Etv2 ChIP-seq 3h and 12h and Brg1 Control and KO ATAC-seq at Day 4. | Figure 15h | [R](https://colab.research.google.com/github/gongx030/etv2_pioneer/blob/master/Enriched_heatmap_of_Etv2_chip_seq_data_and_Brg1_floxed_Brg1_KO.ipynb) |
| chromVAR analysis for the change in chromatin accessibililty of Transcription factors at Brg1 Control and KO ATAC-seq at Day 4. | Figure 15g | [R](https://colab.research.google.com/github/gongx030/etv2_pioneer/blob/master/chromVAR_analysis_of_Brg1_floxed_D4_and_Brg1_KO.ipynb) |



## Notebooks for Reviewer Issues

| Description | Reviews | Figure | Colab link | 
| --- | --- | --- | --- |
| We look at the expression pattern of 4 categories (HATs, HDACs, Inflammatory response related terms and NFkB related pathways), to comapre the 2 systems ES/EB and MEF. We look at the common up regulated and downregulated genes is the treatment compared to the control, and GSEA for both the systems | Reviewer 1: Issue #1 & #2 |  | [R](https://colab.research.google.com/github/gongx030/etv2_pioneer/blob/master/Gene_expression_Inflammatory.ipynb) |
| We select the genomic ranges or chip seq based on the 5 criteria's highlighted in the pioneer document | Reviewer 3: Issue #2 |  | [R](https://colab.research.google.com/github/gongx030/etv2_pioneer/blob/master/Etv2_chipseq_genomicranges_find_v_final.ipynb) |
| Generating avergae profile plots for ChIP seq (MEF_BRG1) and ATAC-Seq data (MEF's and BRG1_KD) to see the profile for transcription factors selected | Reviewer 3: Issue #2 |  | [R](https://colab.research.google.com/github/gongx030/etv2_pioneer/blob/master/BRG1_profile_of_TFs.ipynb) |



[ChIP_seq_preprocess.Rmd](ChIP_seq_preprocess.Rmd) R script for preprocessing Etv2 ChIP-seq, H3K27ac ChIP-seq and Brg1 ChIP-seq in ES/EB and MEF.  The combined ChIP-seq dataset sheet can be found [here](https://docs.google.com/spreadsheets/d/1UWiduM3Pv-GsVGmfxFApnyVBI1THMR8n8wHg5st3b5c/edit?usp=sharing).  

[diff_Etv2_motifs_between_NFR_and_nucleosome.Rmd](diff_Etv2_motifs_between_NFR_and_nucleosome.Rmd) R script for performing motif analysis of finding relatively enriched motifs in NFR compared with nucleosome within Etv2 ChIP-seq peaks regions. 

[find_de_novo_motifs_Etv2_chipseq_peaks.Rmd](find_de_novo_motifs_Etv2_chipseq_peaks.Rmd) R script for finding de novo motifs within Etv2 ChIP-seq peaks in EB and MEF.  The de novo motifs were identified by Homer. 

[ChIP-seq_Brg1_KO_H3K27ac_preprocess.sh](ChIP-seq_Brg1_KO_H3K27ac_preprocess.sh) Bash script for preprocessing the Brg1 KO H3K27ac ChIP-seq in MEF. 

### UCSC genome browser track

Figure 2f. https://genome.ucsc.edu/s/gongx030/Etv2_pioneer_Lmo2

All ChIP-seq tracks: https://genome.ucsc.edu/s/gongx030%40umn.edu/Etv2_pioneer_ms

## Fastq datasets

https://docs.google.com/spreadsheets/d/1T3c2zDoSaZWDznwXzm1ZYgpRdAG76lofFHX2Y6HTEAY/edit?usp=sharing
