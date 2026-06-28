# FL vs HE Clinical Prediction: Section-wise Reference Deployment Matrix (v2)
Target: at least 60 unique references. This v2 set contains **70 BibTeX entries**.
Use this as the manuscript citation plan before moving `references.bib` into the repository.

## 1. Introduction
### Clinical AI motivation and benefits
- `Topol2019HighPerformanceMedicine`
- `Esteva2019GuideDeepLearningHealthcare`
- `Rajkomar2019MLMedicine`
- `Beam2018BigDataMLHealthCare`
- `Rajpurkar2022AIinHealthCare`
### Clinical deployment, safety, ethics, trust
- `Kelly2019KeyChallengesAIHealthcare`
- `Wiens2019DoNoHarmMLHealthcare`
- `Vayena2018MachineLearningMedicineEthics`
- `Mittelstadt2016EthicsAlgorithms`
- `Choudhury2020TrustworthyAIHealthcare`
### Privacy, governance and regulatory motivation
- `Kaissis2020SecurePrivacyPreservingMedicalAI`
- `GDPR2016`
- `HIPAA1996`
- `HHS2022HIPAAPrivacyRule`
- `GuerraManzanares2023PPMLHealthcare`

## 2. Related Work: Federated Learning in Healthcare
### FL foundation and general surveys
- `McMahan2017FedAvg`
- `Kairouz2021AdvancesOpenProblemsFL`
- `Yang2019FederatedMachineLearningConcepts`
- `Flower2020`
- `Niknam2020FederatedLearningCommunications`
### Healthcare FL reviews and applications
- `Rieke2020FutureDigitalHealthFL`
- `Xu2021FederatedLearningHealthcareSurvey`
- `Antunes2022FederatedLearningHealthcareSurvey`
- `Rahman2023FederatedLearningSmartHealthcareSurvey`
- `Choi2024MedicalApplicationsFLSurvey`
- `Prayitno2021SystematicFLHealthcare`
### Medical FL case studies
- `Sheller2020FLBrainTumorSegmentation`
- `Dayan2021FederatedCovid`
- `Pati2022FeTS`

## 3. Related Work: Non-IID Federated Learning and Robustness
### Heterogeneity and non-IID behaviour
- `Zhao2018FederatedNonIID`
- `Li2020FedProx`
- `Karimireddy2020SCAFFOLD`
- `Li2022FederatedLearningNonIIDSurvey`
- `Liu2021NonIIDSurvey`
### Security/privacy limits of FL
- `Mothukuri2021SecurityPrivacyFLSurvey`
- `Bonawitz2017PracticalSecureAggregation`
- `Nasr2019ComprehensivePrivacyFL`
- `Zhu2019DeepLeakageGradients`
- `Geiping2020InvertingGradients`
- `Melis2019ExploitingUnintendedFeatureLeakage`

## 4. Related Work: Homomorphic Encryption and CKKS
### HE foundations and libraries
- `Gentry2009FHE`
- `Cheon2017CKKS`
- `Acar2018HESurvey`
- `MicrosoftSEAL`
- `TenSEAL2021`
### Encrypted inference and ML under HE
- `Dowlin2016CryptoNets`
- `Bost2015MachineLearningConfidentiality`
- `Wood2020HEMedicineBioinformatics`
- `AlBadawi2024PrivatePathologyFHE`
- `Wu2025CKKSSurvey`
- `Kucur2025PPMLSurvey`
- `Nandakumar2019HEGenomicPrediction`

## 5. Privacy Risks and Complementary Protections
### Inference and leakage attacks
- `Shokri2017MembershipInference`
- `Fredrikson2015ModelInversion`
- `Carlini2022MembershipInference`
- `Nasr2019ComprehensivePrivacyFL`
### Differential privacy context
- `Dwork2006DifferentialPrivacy`
- `Abadi2016DeepLearningDP`
### Positioning FL and HE as complementary
- `Kaissis2020SecurePrivacyPreservingMedicalAI`
- `GuerraManzanares2023PPMLHealthcare`
- `Rieke2020FutureDigitalHealthFL`
- `Wood2020HEMedicineBioinformatics`

## 6. Methodology and Evaluation Metrics
### Metrics and imbalanced evaluation
- `Fawcett2006ROC`
- `Saito2015PrecisionRecall`
- `Powers2011Evaluation`
### Tools and reproducibility
- `Pedregosa2011ScikitLearn`
- `Harris2020NumPy`
- `McKinney2010Pandas`
- `Hunter2007Matplotlib`
- `TenSEAL2021`
- `Flower2020`
### Datasets
- `Dua2019UCI`
- `Janosi1988HeartDiseaseUCI`
- `Soriano2021StrokePredictionDataset`

## 7. Results and Discussion
### Trade-off interpretation
- `McMahan2017FedAvg`
- `Kairouz2021AdvancesOpenProblemsFL`
- `Li2020FedProx`
- `Cheon2017CKKS`
- `Wood2020HEMedicineBioinformatics`
- `Kaissis2020SecurePrivacyPreservingMedicalAI`
### Limitations and future work
- `Rieke2020FutureDigitalHealthFL`
- `Xu2021FederatedLearningHealthcareSurvey`
- `Mothukuri2021SecurityPrivacyFLSurvey`
- `Acar2018HESurvey`
- `Kucur2025PPMLSurvey`

## Recommended citation density by section
| Manuscript section | Approx. citations to deploy | Notes |
|---|---:|---|
| Introduction | 12 | Use broad clinical-AI, privacy, and deployment motivation anchors. |
| Related Work | 25 | Divide into FL, HE/CKKS, PPML healthcare, and privacy leakage. |
| Methodology | 12 | Cite FedAvg, CKKS, metrics, datasets, tools, and non-IID setup. |
| Results | 6 | Cite metrics and prior work only where interpreting trade-offs. |
| Discussion | 10 | Use privacy-risk, deployment, regulatory, and limitation anchors. |

## Items needing final metadata verification before journal submission
- `Prayitno2021SystematicFLHealthcare`: retain as useful, but verify author list/venue details in final reference pass.
- `GuerraManzanares2023PPMLHealthcare`: retain as useful, but verify author list/venue details in final reference pass.
- `Nandakumar2019HEGenomicPrediction`: retain as useful, but verify author list/venue details in final reference pass.
- `Liu2021NonIIDSurvey`: retain as useful, but verify author list/venue details in final reference pass.
- `Wu2025CKKSSurvey`: retain as useful, but verify author list/venue details in final reference pass.
- `Kucur2025PPMLSurvey`: retain as useful, but verify author list/venue details in final reference pass.
