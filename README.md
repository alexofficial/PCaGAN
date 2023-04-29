# PCaGAN
## A Comparison of Generative Adversarial Networks for Automated Prostate Cancer Detection on T2-weighted MRI

### Abstract
Generative Adversarial Networks (GANs) have shown potential in medical imaging. In this study, several previously developed GANs were investigated for prostate cancer (PCa) detection on T2-weighted (T2W) magnetic resonance images (MRI).

T2W MRI from an in-house collected dataset (N=961) were used to train, validate, and test an automated computer-aided detection (CAD) pipeline. The open-access PROSTATEx training dataset (N=199) was used as an external test set. The CAD pipeline consisted of normalization, prostate segmentation, quality control, prostate gland cropping, and a GAN model. Six GANs (f-AnoGAN, HealthyGAN, StarGAN, StarGAN-v2, Fixed-Point-GAN and DeScarGAN) were evaluated for PCa detection on the patient-level using the area under the receiver operating characteristic curve (AUC). The best performing GAN (validation set) was trained with five different initializations and evaluated on the internal and external test sets to assess its robustness.

Fixed-Point-GAN performed best (validation, AUC 0.76) and was selected for further assessment. The highest performance on the internal and external test sets were an AUC of 0.73 (95% CI: 0.68-0.79) and 0.77 (95% CI: 0.70-0.83), respectively. The average AUCs standard deviation across all runs corresponded to 0.71 ± 0.01 and 0.71 ± 0.04, respectively.

Fixed-Point-GAN was identified as a promising GAN for the detection of PCa on T2W MRI. This model needs to be further investigated and trained on a larger dataset of multiparametric or biparametric MR images to assess its full potential as a support tool for radiologists.

DOI: https://doi.org/10.1016/j.imu.2023.101234
