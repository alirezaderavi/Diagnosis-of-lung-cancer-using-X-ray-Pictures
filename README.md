# Diagnosis of Lung Cancer using X-ray Pictures

## Description
Lung cancer is a growing concern due to factors like air pollution and urban living. Medical
imaging has become increasingly useful for diagnosing lung cancer, but not all procedures are
accessible or cost-effective. X-ray scans may be the best option for cost-effective imaging. This
study employs X-ray images that were frequently used in recent papers. Machine learning
algorithms are used to extract information from these photographs in order to identify between a
healthy person and a patient. Six machine learning models were selected out of the 11 available
for this paper, and every combination has been tried. A vote classifier was used to combine these
combinations. Model combination strategies were used to improve the model’s Accuracy,
Sensitivity, precision, Specificity, and F1 score. The importance weights of each model can be
determined in a variety of ways, however, in this investigation, q-learning and the multi-armed
bandit were used as two well-known reinforcement learning strategies. The decision tree technique
gave us the highest accuracy rate, which was 70.15%, thanks to the use of machine learning
models. Notably, our novel strategy resulted in a considerable improvement, raising the accuracy
rate to a remarkable 72.78%. This achievement surpasses that of other models with 7.27%. It is
important to note that the previous dataset had shadows present, whereas we used photos with no
shadows. This improvement had a favorable effect on a number of metrics, including Sensitivity,
Precision, Specificity, and F1 score, which will be covered in more depth later.
## Dataset
A publicly accessible dataset collected from the Japanese Society of Radiological Technology
(JSRT) was used in the study (Japanese Society of Radiological Technology 2023). In the 247
frontal chest X-ray images that make up the JSRT dataset, 154 images (100 malignant cases and
54 benign cases) are found to have lung nodules, while the remaining 93 images serve as negative
instances without lung nodules. The dataset's images all have a resolution of 2048 and 2048 pixels,
which is noteworthy(Kaggle 2023). However, a modified dataset is known as BSE JSRT was
produced in light of the negative effects that bone shadows had on the accuracy of the results. The
bone shadows were excluded from this derivative dataset, which was obtained from the original
JSRT dataset. The experiments and analysis for this paper were done using the BSE JSRT dataset.

"Link Dataset:" https://www.kaggle.com/datasets/hmchuong/xray-bone-shadow-supression/

## Methodology

## Results
- Accuracy: 72.78%
- Sensitivity: 60.41%
- Precision: 81.43%
- Specificity: 85.12%
- F1_score: 69.16%


## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/alirezaderavi/Diagnosis-of-lung-cancer-using-X-ray-Pictures.git
