# Transcriptome Analysis Pipeline
Our RNA-Seq analysis pipeline begins with quality control using FastQC to evaluate raw sequence data. Next, reads are processed with Trimmomatic to remove adapters and low-quality sequences. The cleaned reads are aligned to a reference genome using HISAT2, followed by transcript assembly and quantification with StringTie. Downstream analysis is then conducted to identify and interpret differentially expressed genes. This pipeline ensures a comprehensive approach to RNA-Seq data analysis for meaningful biological insights.
