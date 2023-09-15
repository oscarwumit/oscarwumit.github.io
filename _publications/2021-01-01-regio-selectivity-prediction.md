---
title: "Regio-selectivity prediction with a machine-learned reaction representation and on-the-fly quantum mechanical descriptors"
collection: publications
permalink: /publication/2021-01-01-regio-selectivity-prediction
excerpt: 'We construct a reactivity descriptor database based on ab initio calculations of 130k organic molecules, and train a multi-task constrained model to calculate demanded descriptors on-the-fly. The proposed platform enhances the inter/extra-polated performance for regio-selectivity predictions and enables learning from small datasets with just hundreds of examples.<br/><img src="/images/regio-selectivity.png" width="300" height="300">'
date: 2021-01-01
venue: 'Chemical Science'
paperurl: 'https://pubs.rsc.org/en/content/articlelanding/2021/SC/d0sc04823b'
citation: 'Guan, Yanfei; Coley, Connor W; Wu, Haoyang; Ranasinghe, Duminda; Heid, Esther; Struble, Thomas J; Pattanaik, Lagnajit; Green, William H; Jensen, Klavs F. (2021). &quot;Regio-selectivity prediction with a machine-learned reaction representation and on-the-fly quantum mechanical descriptors.&quot; <i>Chemical Science</i>. 12(6). 2198-2208.'
---
Abstract

Accurate and rapid evaluation of whether substrates can undergo the desired the transformation is crucial and challenging for both human knowledge and computer predictions. Despite the potential of machine learning in predicting chemical reactivity such as selectivity, popular feature engineering and learning methods are either time-consuming or data-hungry. We introduce a new method that combines machine-learned reaction representation with selected quantum mechanical descriptors to predict regio-selectivity in general substitution reactions. We construct a reactivity descriptor database based on ab initio calculations of 130k organic molecules, and train a multi-task constrained model to calculate demanded descriptors on-the-fly. The proposed platform enhances the inter/extra-polated performance for regio-selectivity predictions and enables learning from small datasets with just hundreds of examples. Furthermore, the proposed protocol is demonstrated to be generally applicable to a diverse range of chemical spaces. For three general types of substitution reactions (aromatic C–H functionalization, aromatic C–X substitution, and other substitution reactions) curated from a commercial database, the fusion model achieves 89.7%, 96.7%, and 97.2% top-1 accuracy in predicting the major outcome, respectively, each using 5000 training reactions. Using predicted descriptors, the fusion model is end-to-end, and requires approximately only 70 ms per reaction to predict the selectivity from reaction SMILES strings.

![](/images/regio-selectivity.png)

[Download paper here](https://pubs.rsc.org/en/content/articlelanding/2021/SC/d0sc04823b)

[Download the dataset for free](https://doi.org/10.6084/m9.figshare.12818702.v1)
