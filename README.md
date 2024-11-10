The aim of this project is to explore computational drug discovery using bioinformatics
techniques and machine learning models. The focus is on building quantitative structureactivity relationship (QSAR) models to predict biological activity and improve drug design.
Initially, biological activity data is collected from the ChEMBL database, which contains
extensive datasets of compounds and their associated bioactivity. This data is then preprocessed for machine learning applications. Molecular descriptors, such as Lipinski’s
descriptors, are computed using SMILES notation and explored through statistical analysis to
distinguish between active and inactive compounds.
The project progresses to feature the calculation of molecular descriptors for
Acetylcholinesterase inhibitors using PADEL-Descriptor software, preparing datasets for
model building. Various machine learning algorithms, including Random Forest and
LightGBM, are used to predict pIC50 values, which represent the potency of the inhibitors.
Finally, the LazyPredict library is employed to compare different regression models, leading
to insights on model performance. This project combines bioinformatics, data science, and
machine learning techniques to demonstrate a practical approach to drug discovery,
emphasizing the importance of accurate predictive modelling in optimizing pharmaceutical
research.

![Architecture Diagram](https://github.com/user-attachments/assets/424e3b0f-6feb-44ca-a388-438695501308)



