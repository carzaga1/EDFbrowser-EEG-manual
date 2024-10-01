# Background

## Thesis Title:
### *Generalizability of an Unsupervised Deep Learning Algorithm in Detecting Burst Suppression in Pediatric EEG Data* 

**HSLU MSc Student**:  Carlos Arzaga  

**Supervisors**: [Oliver Staubli](https://www.oliverstaubli.ch/de/about/work/), [Prof. Dr. Mirko Birbaeur](https://www.hslu.ch/de-ch/hochschule-luzern/ueber-uns/personensuche/profile/?pid=1537) 

**Co-Supervisors**: Prof. Dr. med Georgia Ramantani, Prof. Dr. Med Emanuela Keller 

**Internal Support**: Dr. med Andrea Rüegger, Alex Lo Biundo Santo Pietro

**External Support**: Jenny Schmid, Marko Seric 

## Research Objectives: 

1. Assess the generalizability (geographical/domain) via an external validation of a pre-validated unsupervised ML algorithm for BS detection in pediatric patients. 

2. Improve BS detection by pairing the ML algorithm with a DL architecture.  
    - Identify the most effective unsupervised DL architecture for EEG data analysis. 
        - Self Organizing Maps (SOM) 
        - Autoencoder (AE) 
        - Artificial Neural Networks (ANN) 
    - Evaluate new architecture pairing(s).

3. Investigate the agreement between human EEG annotators and the DL algorithm. 

## Methodology: 

- **Data**: Retrospective collection of EEG data from pediatric patients in neurocritical care at the Universitäts-Kinderspital Zürich (KISPI). 
- **Data Preparation**: Anonymization and preprocessing of EEG and clinical data. 
- **Data Labelling**: Manual labeling of BS patterns by experienced EEG annotators. 
    - Dr. Med. Rüegger Andrea | Kinderspital Zürich 
    - Alex Lo Biundo Santo Pietro | Kinderspital Zürich 

- **Model Development**: Iterative process in training and validation of unsupervised ML and DL models. 
- **Evaluation**: Assessment of model performance using metrics like sensitivity, specificity, precision, AUROC, F1-score, NPV, MAE, and Cohen's kappa. 


