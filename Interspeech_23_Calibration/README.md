# Automatic speaker recognition with variation across vocal conditions

This markdown file details the workflow for the Interspeech submission *Automatic speaker recognition with variation across vocal conditions: a controlled experiment with implications for forensics* (include link if/when becomes available online)

## Test Data

| Participant Number | Participant initials |
| --- | --- |
| P0001 | PF |
| P0002 | JT |
| P0003 | BGR |
| P0004 | FN |
| P0006 | RO |
| P0009 | DW |

| VC Group | Vocal Conditions |
| --- | --- |
| Baseline | MOD - Modal voice |
| Accent Guises | RPR - Received Pronunciation <br />ACC - Non-standard guises (*Geordie, Manchester, NYC, Yorkshire*)|
| Laryngeal | BRT - Breathy <br />CRK - Creaky <br />WHS - Whisper |
| Supralaryngeal | FTB - Fronted Tongue Body <br />BTB - Backed Tongue Body <br />RET - Retroflex <br />LLX - Lowered Larynx |
| Miscellaneous | HIG - High pitch <br />LOW - Low pitch <br />FAS - Fast <br />LIV - Lively <br />MON - Monotone <br />PEN - Pen between the teeth <br />PIN - Pinched nose |

*The following vocal conditions were not included in this paper:*
- NAS - Nasal
- DEN - Denasal 
- RLX - Raised Larynx
- SCO - Scottish 
- FOR - Foreign accented

These conditions were not completed by all participants. They were excluded to ensure each participant had completed the same number of conditions. 

Only included R01-R03. This analysis excluded the additional repetitions within a session from P0001 to ensure all participants had 3 repetitions of each vocal condition per session.

## Calibration Data
Used 20 speakers from DyViS who took part in Task 3 and Task 5

## Comps and scores
Include x-vectors (?)

Vocalise outputs (available in the [*VocaliseOutput*](https://drive.google.com/drive/folders/1dHXavYfNbPlqgIaOfZmdUScgfXkrWs41) folder on GoogleDrive):
2023-02-21-0945_P1-2-3-4-6-9-HDM-m2m_2021-XVector-Adaptable-20F-512-OCMS-02Nov2021_XVector - PLDA.csv
2023-02-06-0924_DyViS_Recall_2019A-XVector-Adaptable-AP-512-CMS-10Oct2018_XVector - PLDA.csv

Converted dataframes used in analysis (available in the [*2023-02 - Many-many...*](https://drive.google.com/drive/folders/1zUoF8sPScbPksuMB7sg7UXPiDCu7cHZW) folder on GoogleDrive):
2023-02-21_AC_P_male_Spectral_LF_cross_session.csv
2023-01-30_dyvis_spectral.csv

Formatting and converting dataframes done in R. The code is documented in the score_dist_visualisations.R script (version [5b10255e5f698056e6925f0b65d8184f11ca00fc](https://github.com/uoy-research/pasr-analysis/blob/5b10255e5f698056e6925f0b65d8184f11ca00fc/score_dist_visualisations.R) - 2023-03-06) in the pasr-analysis repo. 

### Analysis 
Include link to version of Matlab code used to do Score-to-LR conversion
Include link to version of Matlab code used to evaluate performance

## Results
Include plot from article on git and include link here. Also link to version of R code used to generate final plot
Include code or plots which weren't included in final article (?)