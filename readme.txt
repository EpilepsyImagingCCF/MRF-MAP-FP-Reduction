Author: Zheng Ding
Paper: Combining magnetic resonance fingerprinting with voxel-based morphometric analysis to reduce false positives for focal cortical dysplasia detection. Epilepsia. 2024 Jun;65(6):1631-1643. doi: 10.1111/epi.17951.

Use training data generation to extract data from valNN output and MNI space MRF data
generated excel sheet can be used to train models in FP_reduction_model_results.ipynb.
the ipynb generates the ROC curves, tables, as well as the pie chart.
t_test_for... is used to conduct the t-test between MRF properties of TP and FP clusters
thresholdANNmap.m is used to check the # of FP clusters at different threshold level on the valNN output.
colorful_MRF file contain sections that generate the figures for the paper.
