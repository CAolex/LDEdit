# LDEdit: Local Disease-guided Editing for Longitudinal Data Synthesis

Codes for  ___LDEdit: Local Disease-guided Editing for Longitudinal Data Synthesis___


## Abstract

> In this paper, we concentrate on the controlled synthesis of longitudinal radiography data. Capitalizing on the extensive semantic knowledge within GANs’ latent spaces, we introduce a novel semantic medical image editing framework, Local Disease-guided Editing (LDEdit). This framework is designed to enable precise, localized control over disease-specific semantics, allowing for the generation of gradual, user-defined changes that reflect the progression of disease attributes. LDEdit features two innovative components, i.e., (1) Link-LR: Establishes connections between pixels of interest in the synthesized image and their corresponding latent codes, and (2) Link-PCA: Refines these latent codes to identify and align with semantic directions associated with specific diseases, thereby guiding the synthesis process. Our method excels at navigating the latent manifold of GANs, effectively separating local disease semantics from unrelated elements. We rigorously tested LDEdit using two prominent chest radiography datasets: Chest X-ray and CheXpert. The results from extensive experiments on three prevalent diseases highlight the significant improvement in terms of lesion synthesis. For instance, the probability of accurate disease classification from generated sequences has notably increased from 0.2 to 0.7. Furthermore, LDEdit has demonstrated substantial improvements in downstream applications, including unsupervised lesion segmentation, chest radiograph summarization, disease data augmentation, as well as skin lesion synthesis task. These findings not only validate the practical utility of LDEdit but also suggest its potential for predicting disease progression, offering a valuable tool for future medical advancements. 


<img src="https://github.com/CAolex/LDEdit/blob/main/images/flow.png" alt="flow" width="600">

<img src="https://github.com/CAolex/LDEdit/blob/main/images/results.png" alt="results" width="600">

<img src="https://github.com/CAolex/LDEdit/blob/main/images/ISIC.png" alt="ISIC" width="600">

<img src="https://github.com/CAolex/LDEdit/blob/main/images/calssification.png" alt="calssification" width="600">

<img src="https://github.com/CAolex/LDEdit/blob/main/images/diagnostic.png" alt="diagnostic" width="600">

## Result


