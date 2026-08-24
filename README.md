## Excitatory progenitors drive cerebellar nucleus development and evolution 
Manjari M-G Anant, Eli Zuercher, Maggie Lowman, Caleb Shi, Dylan Z. Faltine-Gonzalez, Michael L. Piacentino, Jean Fan, Justus M. Kebschull
### Data Explorer Website: https://mmganant.github.io/CNdev_website/ 
### Data Repository: https://zenodo.org/records/21796565
### Figures and Analysis Code 
```text
CNdev_analysis/
├── single-cell/
│   ├── Cb_URL.rmd
│   ├── Cb_excCN.rmd
│   ├── Cb_inhibitory.rmd
│   ├── MousevsChickenDev.rmd
│   ├── RL_cyclingprog.rmd
│   └── scATACseq_analysis.rmd
│
└── spatial-barseq3/
    ├── individual_tps/
    │   ├── E11.5/
    │   │   ├── raw_pipeline/
    │   │   ├── label_transfer.py
    │   │   └── cell_type_analysis.py
    │   ├── E12.5/
    │   │   ├── raw_pipeline/
    │   │   ├── label_transfer.py
    │   │   └── cell_type_analysis.py
    │   └── ...
    │
    ├── excCN_allslices.ipynb
    ├── excCN_barseq3corr_M-Lquant.ipynb
    ├── inhibitory_integration.ipynb
    ├── integrated_all_slices_all_tps.ipynb
    ├── scrnaseq_spatial_correlations.ipynb
    │
    ├── Zsgreen1_analysis/
    │   ├── Raw_data_analysis_pipeline/
    │   └── Cell_type_analysis/
    │
    └── Adult_CN_cell_type_analysis/
