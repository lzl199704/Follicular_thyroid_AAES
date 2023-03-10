# Follicular_thyroid_AAES

Here are the scripts for using radiomics to analyze follicular thyroid nodule. 

In the scripts foler, extract_radiomics.ipynb will extract radiomics features on each image by pairing with its mask. The radiomics features will then paired with clinical features based on each subject for further analysis.

The feature_study.ipynb will study radiomics features and clinical features. Three different analysis were applied: using only clinical feature, using only TSNE-image features, and using clinical and TSNE-image features.
