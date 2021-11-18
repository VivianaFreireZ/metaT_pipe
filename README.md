# metaT_pipe
<p align="center"><img src="metaT_pipeline_graph.png" alt="pipelines"></p>
Scripts for running metatranscriptomic analysis
## Dependencies
The following software is required to run this pipeline:
- [dRep](https://github.com/MrOlm/drep) pipeline used to "de-replicate" genomes
- [cd-hit](https://github.com/weizhongli/cdhit/wiki) "de-replication" of contigs using clustering
- [DRAM](https://github.com/shafferm/DRAM/wiki) metagenomic assembled genomes annotation
- [CheckM](https://github.com/Ecogenomics/CheckM) quality control of metagenomes
- [GTDB-Tk](https://ecogenomics.github.io/GTDBTk/) taxonomic assignment
- [CoverM](https://github.com/wwood/CoverM) reads mapping
- [dirseq](https://github.com/wwood/dirseq) gene counts
