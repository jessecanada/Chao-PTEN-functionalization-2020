# Chao-PTEN-functionalization-2019
The following files accompany the PTEN functionalization manuscript

1. Fig. 3
- plot_domain_ClinVar.ipynb:\
    generates the domain organization and ClinVar significance heatmaps
- plot_MCF10A_LOF_scores (heatmap).ipynb:\
    generates the heatmap for visualizing LOF scores
       
2. Fig. 4
- plot_plot_western_stability.ipynb:\
    generates the graph in Fig. 4A
- PTEN_stability_LR.ipynb:\
    computes logistic regression on the mean normalized stability scores\
    generates the graph in Fig. 4B
- comapre_stability_HEK_SDM.ipynb:\
    compares stability scores from MCF10A cells, HEK cells and SDM predictions\
    generates the graphs in Fig. 4C, 4D and 4E
3. Fig. 5
- compare_yeast_vs_MCF10A.ipynb:\
    compares LOF scores from yeast (Mighell et al 2018 PMID:29706350)\
    generates the graphs in Fig. 5A, 5B and 5C
4. Fig. 6      
- LOF_scores_SVM.ipynb:\
    builds SVM model for classifying LOF scores into 3 classes\
    generates the data for Fig. 6A
- plot_SVM_classification.ipynb:\
    generates the plot in Fig. 6B from SVM classification
- ROC_PRC_BINARY.ipynb:\
    generates the ROC curves for binary classification in Fig. 6C
- ROC_multiclass.ipynb:\
    generates the ROC curves for multiclass classification in Fig. 6D
- compare_LOF_vs_predictions.ipynb:\
    compares LOF scores to CADD, SNAP2, PolyPhen-2 and SIFT\
    generates the graphs in Fig. 6E
        
