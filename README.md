# Comparison of de novo assemblies from Illumina and Oxford nanopore sequences in _Dynastes tityus_
This is a repository working as the annex of "Comparison of de novo assemblies from Illumina and Oxford nanopore sequences in _Dynastes tityus_" project.

## Illumina short-reads
The steps followed are:

- Obtaining of data
- FastQC
- Trimmomatic
- FastQC on trimmed data
- SPAdes

These steps are published here:

```
https://usegalaxy.org/u/silviagenome/h/illumina-de-novo
```

- Annotation of assembly with Augustus with data from SPAdes previous step.

This step is published here:

```
https://dayhoff.inf.um.es:8080/u/jaime94/h/illumina-de-novo-anotacin
```

## Nanopore long-reads
The steps followed are:

- Obtaining of data
- FastQC
- Cutadapt
- FastQC on trimmed data

These steps are published here:

```
https://usegalaxy.org/u/silviagenome/h/oxford-nanopore-de-novo
```

- Assembly with wtdbg v1.2.8 (https://github.com/fantasticair/wtdbg-1.2.8)
- Annotation of assembly with Augustus with data from wtdbg previous step.

This step is published here:
```
https://dayhoff.inf.um.es:8080/u/jaime94/h/nanopore-de-novo-anotacin
```
