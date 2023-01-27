## Contributions of Acoustic Measures to the Classification of Laryngeal Voice Quality in Continuous English Speech

This repository contains all the supplementary materials for the ICPhS submission *Contributions of Acoustic Measures to the Classification of Laryngeal Voice Quality in Continuous English Speech*.

### Data

The acoustic measures of the audio files were extratced using [VoiceSauce](http://www.phonetics.ucla.edu/voicesauce/) implemented in Matlab. All measurement of a speaker (P1 to P4) was saved in a `.txt` file in the [`data`](data/) directory.

### Data Exploration

An [R script](icphs.html) was used to process, explore, and visualise the data.

The resulting files:
[vsdatas.csv](data/vsdatas.csv): The means and standard deviations of each measurement for each audio file.
[vsdatasint_nosoe.csv](data/vsdatasint_nosoe.csv): The means and standard deviations of each measurement for 1/6 of each audio file. In other words, each audio file is divided into six even intervals.

### Data Analysis

Data analysis was conducted using Python, and the workflow is available in [models_vs.html](models_vs.html).