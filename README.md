# MVTec AD to Lung Infiltration 
A collection of resources related to our paper, "Applying Best Practices from Image Anomaly Detection to Identifying Infiltration in Chest X-rays: A Review"
The goal of our review paper was to identify what the best performing models for IAD were in industrial applications, where advancements have been notable, and compare them to the SOTA for medical applications (specifically, Chest X-Rays for detecting lung infiltration) to identify potential methods for research in applying them in a medical context. 
# Top performing MVTec AD code bases
| Reference | Methodology Name | AUROC | Description | Article | Codebase |
|---|---|---|---|---|---|
| [Chen et al., 2024] | **GLASS** | **99.9** | WideResNet based CNN with gradient ascent, combines feature-level and image-level anomaly synthesis to detect subtle anomalies. | https://doi.org/10.48550/arXiv.2407.09359 | https://github.com/cqylunlun/glass |
| [Batzner et al., 2024] | EfficientAD | 99.8 | Lightweight CNN with student-teacher architecture. | https://doi.org/10.48550/arXiv.2303.14535 | NOTE: Unofficial implementation: https://github.com/rximg/EfficientAD |
| [Mousakhan et al., 2023] | DDAD | 99.8 | U-Net (CNN) based denoising diffusion model. |
| [Liu et al., 2023] | SimpleNet | 99.6 | WideResNet (CNN) based feature extraction technique. |
| [Liu et al., 2023] | PRFF-AD | 99.1 | Combines CNN and Transformer to accurately detect and localize anomolies. |

**Table 1:** Top algorithm performance for image-level detection in the MVTec AD dataset

# SOTA for lung infiltration detection
The top performing model for lung infiltration detection at the time of our paper was Slide Detect:
https://direct.mit.edu/dint/article/5/4/1048/117747/Slide-Detect-An-Accurate-Deep-Learning-Diagnosis
<br>
Slide Detect acheived an AUROC Score of 91.47%
