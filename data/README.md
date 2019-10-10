# Datasets

Datasets that can be used to have a quick test of a pipeline.

# 10x Genomics

Some 10x datasets that can be used to run the `tenx_single_sample` pipeline:
- 1k PBMCs from a Healthy Donor (v2 chemistry)
```
wget http://cf.10xgenomics.com/samples/cell-exp/3.0.0/pbmc_1k_v2/pbmc_1k_v2_filtered_feature_bc_matrix.tar.gz
mkdir -p data/10x/1k_pbmc/1k_pbmc_v2_chemistry/outs/
tar -xzvf pbmc_1k_v2_filtered_feature_bc_matrix.tar.gz -C data/10x/1k_pbmc/1k_pbmc_v2_chemistry/outs/
```
- 1k PBMCs from a Healthy Donor (v3 chemistry)
```
wget http://cf.10xgenomics.com/samples/cell-exp/3.0.0/pbmc_1k_v3/pbmc_1k_v3_filtered_feature_bc_matrix.tar.gz
mkdir -p data/10x/1k_pbmc/1k_pbmc_v3_chemistry/outs/
tar -xzvf pbmc_1k_v3_filtered_feature_bc_matrix.tar.gz -C data/10x/1k_pbmc/1k_pbmc_v3_chemistry/outs/
```

If these links appear not work, you can always download them from https://support.10xgenomics.com/single-cell-gene-expression/datasets.
