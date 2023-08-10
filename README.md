Please follow the instructions below to reproduce the tables, figures, etc from the manuscript. 

## Data

There are 10 different datasets that each have a training set, validation set, and testing set of size 500, 100, and 100 respectively. The features available for each sample are the embeddings for the multi-omics and the drug features from the DeepCDR model. The DeepCDR model was trained on a training dataset with approximately 69,000 samples and a validation set of approximately 18,000 was used for early stopping.  The 10 different datasets can be accessed using the link [Data](https://github.com/Ved-Piyush/DeepCDR_MEnKF-ANN/tree/main/Data) . The training and the validation datasets in [Data](https://github.com/Ved-Piyush/DeepCDR_MEnKF-ANN/tree/main/Data) are random samples from the larger training and validation dataset of size 69,000 and 18,000, respectively. The test sets in the 10 datasets were neither used for training nor for the validation set that was used in early stopping. 

## Results

Scenario II results can be obtained using the following three scripts: 

* [Phase I](https://github.com/Ved-Piyush/DeepCDR_MEnKF-ANN/blob/main/DeepCDR_MEnKF-ANN/DeepCDR_MEnKF-ANN_all_drugs_all_omics/Real_World_EnKF_Old_Strategy_DeepCDR_var_0.5_size_ens_801_first_three.ipynb)
* [Phase II](https://github.com/Ved-Piyush/DeepCDR_MEnKF-ANN/blob/main/DeepCDR_MEnKF-ANN/DeepCDR_MEnKF-ANN_all_drugs_all_omics/Real_World_EnKF_Old_Strategy_DeepCDR_var_0.5_size_ens_801_second_three.ipynb)
* [Phase III](https://github.com/Ved-Piyush/DeepCDR_MEnKF-ANN/blob/main/DeepCDR_MEnKF-ANN/DeepCDR_MEnKF-ANN_all_drugs_all_omics/Real_World_EnKF_Old_Strategy_DeepCDR_var_0.5_size_ens_801_last_three.ipynb)

Scenario I results can be obtained using the following seven scripts: 

* [Drug Features and Gene Mutation Features](https://github.com/Ved-Piyush/DeepCDR_MEnKF-ANN/blob/main/DeepCDR_MEnKF-ANN/DeepCDR_MEnKF-ANN_all_drugs_mutation/Real_World_EnKF_Old_Strategy_DeepCDR_var_1_size_ens_801.ipynb)
* [Drug Features and Gene Expression Features](https://github.com/Ved-Piyush/DeepCDR_MEnKF-ANN/blob/main/DeepCDR_MEnKF-ANN/DeepCDR_MEnKF-ANN_all_drugs_expression/Real_World_EnKF_Old_Strategy_DeepCDR_var_0.5_size_ens_534.ipynb)
* [Drug Features and DNA Methylation Features](https://github.com/Ved-Piyush/DeepCDR_MEnKF-ANN/blob/main/DeepCDR_MEnKF-ANN/DeepCDR_MEnKF-ANN_all_drugs_methyl/Real_World_EnKF_Old_Strategy_DeepCDR_var_0.5_size_ens_534.ipynb)
* [Drug Features and (Gene Mutation, DNA Methylation) Features](https://github.com/Ved-Piyush/DeepCDR_MEnKF-ANN/blob/main/DeepCDR_MEnKF-ANN/DeepCDR_MEnKF-ANN_all_drugs_mutation_methyl/Real_World_EnKF_Old_Strategy_DeepCDR_var_0.5_size_ens_801.ipynb)
* [Drug Features and (Gene Expression, DNA Methylation) Features](https://github.com/Ved-Piyush/DeepCDR_MEnKF-ANN/blob/main/DeepCDR_MEnKF-ANN/DeepCDR_MEnKF-ANN_all_drugs_expression_methyl/Real_World_EnKF_Old_Strategy_DeepCDR_var_0.5_size_ens_534.ipynb)
* [Drug Features and (Gene Expression, Gene Mutation) Features](https://github.com/Ved-Piyush/DeepCDR_MEnKF-ANN/blob/main/DeepCDR_MEnKF-ANN/DeepCDR_MEnKF-ANN_all_drugs_mutation_expression/Real_World_EnKF_Old_Strategy_DeepCDR_var_1_size_ens_801.ipynb)
* [Drug Features and (Gene Expression, Gene Mutation, DNA Methylation) Features](https://github.com/Ved-Piyush/DeepCDR_MEnKF-ANN/blob/main/DeepCDR_MEnKF-ANN/DeepCDR_MEnKF-ANN_all_drugs_all_omics/Real_World_EnKF_Old_Strategy_DeepCDR_var_0.5_size_ens_801.ipynb)

The cross validated metrics for MEnKF-ANN on all multi-omics features and all multi-omics features except gene expression can be obtained using the scripts below: 

* [All Drugs Features and All Multi-Omics Features except Gene Expression](https://github.com/Ved-Piyush/DeepCDR_MEnKF-ANN/blob/main/DeepCDR_MEnKF-ANN/DeepCDR_MEnKF-ANN_all_drugs_all_omics/Real_World_EnKF_Old_Strategy_DeepCDR_var_0.5_size_ens_801_ALL_10_with_PCA_proper_CV_no_validation.ipynb)
* [All Drugs Features and All Multi-Omics](https://github.com/Ved-Piyush/DeepCDR_MEnKF-ANN/blob/main/DeepCDR_MEnKF-ANN/DeepCDR_MEnKF-ANN_all_drugs_all_omics/Real_World_EnKF_Old_Strategy_DeepCDR_var_0.5_size_ens_801_ALL_10_proper_CV_no_validation_all_features.ipynb)
