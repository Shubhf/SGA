# Geometry Without Structure

Code and results for the EMNLP 2026 submission 
"Geometry Without Structure: How Biomedical Language 
Models Fail to Encode Molecular Similarity"

## Requirements
- Python 3.9+
- RDKit 2022.09.5
- transformers 4.35.0
- torch 2.0.0
- scikit-learn 1.3.0
- scipy 1.11.0

See requirements.txt for full dependencies.

## Data
DrugBank descriptions are not redistributed due to 
licensing. Split DrugBank IDs are provided in 
data/splits/. To reconstruct the dataset, obtain 
a DrugBank academic license at https://www.drugbank.ca 
and match IDs to descriptions.

DDInter, ADE Corpus, and BC5CDR are publicly available 
and can be downloaded from their respective sources.

## Reproducibility
- Random seed: 42
- RDKit version: 2022.09.5
- Morgan fingerprints: radius=2, nBits=2048
- Pair sampling: 20,000 pairs from test set

## Results
Pre-computed geometry results are in results/.
