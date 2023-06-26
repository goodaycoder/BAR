[![N|Solid](https://mingxia.web.unc.edu/wp-content/uploads/sites/12411/2020/12/logo_MagicLab-horizontal-4.png)](https://mingxia.web.unc.edu/)

# BAR

## _Source code for our paper on MICCAI 2023, "Brain Anatomy-Guided MRI Analysis for Assessing Clinical Progression of Cognitive Impairment with Structural MRI"



## Abstract  

- **Brain structural MRI has been widely used for assessing future progression of cognitive impairment (CI) based on learning-based methods. Previous studies generally suffer from the limited number of labeled training data, while there exists a huge amount of MRIs in large-scale public databases. Even without task-specific label information, brain anatomical structures provided by these MRIs can be used to boost learning performance intuitively. Unfortunately, existing research seldom takes advantage of such brain anatomy prior. To this end, this paper proposes a brain anatomy-guided representation (BAR) learning framework for assessing the clinical progression of cognitive impairment with T1-weighted MRIs. The BAR consists of (a) a pretext model and (b) a downstream model, with a shared brain anatomy-guided encoder for MRI feature extraction. The pretext model also contains a decoder for brain tissue segmentation, while the downstream model relies on a predictor for classification. We first train the pretext model through a brain tissue segmentation task on large-scale auxiliary MRIs, yielding a generalizable encoder. To provide accurate brain anatomy, we perform tissue segmentation for 9,544 MRIs from ADNI to generate ground truth using an established toolbox with manual verification. The downstream model with learned encoder is further fine-tuned on target MRIs for prediction tasks. We validate the proposed BAR on two CI-related studies of late-life depression analysis with 309 subjects and diabetes mellitus analysis with 82 subjects. Experimental results suggest that the BAR outperforms several state-of-the-art (SOTA) methods in MRI-based depression recognition and cognitive impairment identification, and the pretext model can be potentially used for tissue segmentation in other MRI-based studies.**


##### The model is realized on the basis of open source project [MONAI](https://github.com/Project-MONAI/MONAI).
