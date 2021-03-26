# Chao-PTEN-functionalization-2020
Manuscript link (July 2020 cover!): https://cancerres.aacrjournals.org/content/80/13/2775

The following files accompany the PTEN functionalization manuscript\
Requirements: Python 3 with Jupyter Notebook
1. Fig. 3
- 1_plot_domain_ClinVar.ipynb:\
    generates the domain organization and ClinVar significance heatmaps
- 2_plot_MCF10A_LOF_scores (heatmap).ipynb:\
    generates the heatmap for visualizing LOF scores
       
2. Fig. 4
- 3_plot_MCF10A_stability.ipynb:\
    generates the graph in Fig. 4A
- 4_MCF10A_stability_LR.ipynb:\
    computes logistic regression on the mean normalized stability scores\
    generates the graph in Fig. 4B
- 5_comapre_stability_HEK_SDM.ipynb:\
    compares stability scores from MCF10A cells, HEK cells and SDM predictions\
    generates the graphs in Fig. 4C, 4D and 4E
3. Fig. 5
- 6_compare_yeast_vs_MCF10A.ipynb:\
    compares LOF scores from yeast (Mighell et al 2018 PMID:29706350)\
    generates the graphs in Fig. 5A, 5B and 5C
4. Fig. 6      
- 7_LOF_scores_SVM.ipynb:\
    builds SVM model for classifying LOF scores into 3 classes\
    generates the data for Fig. 6A
- 8_plot_MCF10A_SVM_classification.ipynb:\
    generates the plot in Fig. 6B from SVM classification
- 9_plot_ROC_BINARY.ipynb:\
    generates the ROC curves for binary classification in Fig. 6C
- 10_plot_ROC_multiclass.ipynb:\
    generates the ROC curves for multiclass classification in Fig. 6D
- 11_compare_LOF_vs_predictions.ipynb:\
    compares LOF scores to CADD, SNAP2, PolyPhen-2 and SIFT\
    generates the graphs in Fig. 6E
        
