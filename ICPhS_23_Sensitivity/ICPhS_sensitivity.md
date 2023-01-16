# Sensitivity of x-vectors and automatic speaker recognition scores to vocal variation

This markdown file details the workflow for the ICPhS submission *Sensitivity of x-vectors and automatic speaker recognition scores to vocal variation* (include link if/when becomes available online)

## x-vectors and tSNE plots

x-vectors were generated using the default VOCALISE x-vector model using MFCCs (2021-XVector-Adaptable-20F-512-OCMS-02Nov2021) for P0001 (PF - 2022-11-22) and P0004 (FN - 2022-12-13). The x-vectors generated are available in [the x-vector folder](https://github.com/uoy-research/pasr-output/tree/main/ICPhS_23_Sensitivity/x-vectors) in this repo 


## Scores and distributions

Within-speaker comparisons were carried out in VOCALISE using the default x-vector PDLA comparison with minimum duration set to 10 seconds. For each participant, each sample was compared to every other sample. The score matrix generated from these comparisons are:
- [2022-11-22_1129_P0001-HDM-m2m_2021-XVector-Adaptable-20F-512-OCMS-02Nov2021_XVector - PLDA.csv](https://github.com/uoy-research/pasr-output/blob/main/ICPhS_23_Sensitivity/scores/2022-11-22_1129_P0001-HDM-m2m_2021-XVector-Adaptable-20F-512-OCMS-02Nov2021_XVector%20-%20PLDA.csv) for P0001
- [2022-12-13-1309-P0004-HDM-m2m_2021-XVector-Adaptable-20F-512-OCMS-02Nov2021_XVector - PLDA.csv](https://github.com/uoy-research/pasr-output/blob/main/ICPhS_23_Sensitivity/scores/2022-12-13-1309-P0004-HDM-m2m_2021-XVector-Adaptable-20F-512-OCMS-02Nov2021_XVector%20-%20PLDA.csv) for P0004 