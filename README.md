# SNVFormer

This repository contains the code from the 2022 ICML Computational biology workshop paper 'SNVformer: an attention-based deep neural network for GWAS data.'

Run `python setup_psm.py build_ext --inplace` to compile the .pyx file

`./src/train_create_paper_figures` runs the benchmarks in the paper.

N.B. paths are read from the (excluded from repo) file `environ.py`, and access to data from the UK BioBank is required to actually re-produce the results.
