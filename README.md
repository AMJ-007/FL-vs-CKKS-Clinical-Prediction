# FL-vs-CKKS-Clinical-Prediction

## Comparative Evaluation of Centralised Learning, Federated Learning, and CKKS Homomorphic Encryption for Privacy-Preserving Clinical Prediction
This repository contains the complete experimental artefacts for a comparative evaluation of three machine-learning deployment paradigms for privacy-preserving clinical prediction:

* **Centralised Logistic Regression**
* **Federated Learning (FedAvg)**
* **CKKS Homomorphic-Encryption-Based Inference**

The study evaluates predictive performance, runtime, communication overhead, robustness under IID and non-IID data distributions, and deployment suitability using two widely used clinical datasets.

## Motivation

Privacy-preserving healthcare AI requires balancing predictive performance with the protection of sensitive patient information.
While Federated Learning (FL) and Homomorphic Encryption (HE) are often discussed together, they solve different privacy problems:
* **Federated Learning** enables collaborative model training without routinely transferring raw patient records.
* **CKKS Homomorphic Encryption** enables encrypted inference on outsourced computing infrastructure without exposing patient features.

This repository provides a reproducible experimental comparison of these complementary approaches under a unified evaluation framework.

## Clinical Datasets

* UCI Cleveland Heart Disease Dataset
* Stroke Prediction Dataset

## Methods Compared

* Centralised Logistic Regression
* Federated Logistic Regression (FedAvg)
* CKKS Homomorphic Encryption-Based Inference

## Evaluation Metrics

### Predictive Performance

* Accuracy
* Precision
* Recall
* F1-score
* Balanced Accuracy
* ROC-AUC

### Computational Performance

* Runtime
* Communication Overhead
* Repeated Experimental Stability
* IID vs Non-IID Robustness

### Deployment Analysis

* Resource Requirements
* Communication Cost
* Practical Deployment Suitability
## Repository Structure

architecture/
    Architecture diagrams

figures/
    Experimental figures used throughout the study

notebooks/
    Reproducible Jupyter notebooks

references/
    BibTeX database and citation mapping

results/
    Experimental outputs (CSV)

src/
    Core implementation modules

README.md
requirements.txt

## Running the Experiments

The notebooks are intended to be executed in the following order:

1. Heart Disease Centralised Learning
2. Stroke Prediction Centralised Learning
3. Combined Performance Evaluation
4. Repeated Experimental Evaluation
5. IID vs Non-IID Federated Learning
6. Manuscript Result Synthesis

## Main Outputs

The repository generates:

* Comparative performance tables
* Runtime analysis
* Communication-overhead analysis
* IID vs Non-IID robustness analysis
* Deployment trade-off analysis
* Publication-quality figures

## Reproducibility

This repository contains all experimental artefacts required to reproduce the reported comparative evaluation.

The accompanying manuscript is under journal review. The manuscript will be linked after publication, subject to the publisher's sharing policy.

## Related Research Repositories

* SustainHE-Med
* Privacy-Preserving-AI-Lab
* PPA-AI-Healthcare-Reproducibility

## Citation

If you use this repository in your research, please cite the associated journal article once it becomes publicly available.

## License

This repository is provided for academic research and reproducibility purposes.
