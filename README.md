# Datasets and scripts for the paper Compositionally constrained sites drive long branch attraction

In [this repository](https://github.com/drenal/cat-pmsf-paper) all code and datasets are available to reproduce the results described in the article [Compositionally constrained sites drive long branch attraction](https://doi.org/10.1093/sysbio/syad013) and to run the introduced CAT-PMSF pipeline on arbitrary datasets.

Structure of the repository:
- [datasets](datasets/): empirical datasets analyzed in the article
- [datasets/simulation](datasets/simulation/): simulation dataset and scripts to generate them with [ELynx](https://github.com/dschrempf/elynx)
- [scripts](scripts/): scripts to perform data transformation and analysis at various steps of the CAT-PMSF pipeline
- [step1_iqtree_lg](step1_iqtree_lg/): results of the 1st step of the CAT-PMSF pipeline applied to the empirical datasets
- [step1_iqtree_lg/simulation](step1_iqtree_lg/simulation/): correct (good) and incorrect (bad) topologies of the simulations
- [step2_pb](step2_pb/): results of the 2nd step of the CAT-PMSF pipeline applied to the empirical datasets
- [step2_pb/simulation](step2_pb/simulation/): results of the 2nd step of the CAT-PMSF pipeline applied to the simulated trees
- [step3_iqtree](step3_iqtree/): results of the 3rd step of the CAT-PMSF pipeline applied to the empirical datasets
- [step3_iqtree/simulation](step3_iqtree/simulation/): results of the 3rd step of the CAT-PMSF pipeline applied to the simulated trees
- [homo](homo): results of the tests for compositional heterogeneity across lineages with [Homo v2.1](https://github.com/lsjermiin/Homo.v2.1)
