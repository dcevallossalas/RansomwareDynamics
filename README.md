# Ransomware dynamics: Mitigating personal data exfiltration through the SCIRAS lens

This repository provides all the files and elements required for experiments reproducibility of the research project: "Ransomware dynamics: Mitigating personal data exfiltration through the SCIRAS lens".

This research is part of the project "PRIVIA: Identificación Automatizada de Brechas de Privacidad en Ecuador usando Inteligencia Artificial Generativa y LLMs" conducted by Escuela Politécnica Nacional.

## Research information

- **Main project:** PRIVIA: Identificación Automatizada de Brechas de Privacidad en Ecuador usando Inteligencia Artificial Generativa y LLMs" conducted by Escuela Politécnica Nacional.
- **Main project reference:** PIGR-24-06.
- **Date:** 2025-07-27

## How to use this repository?

The repository contains 5 folders with a set of files that detail the results of the research. For experiments reproducibility, just open the file and execute it.

### Folder SCIRAS Model

This folder contains all the files for analyzing the triple extortion SCIRAS model. The files are the following:

- Solution_ODE.ipynb: An example of how to use the Gekko tool.
- 3A_SCIRAS.ipynb: Solution to the optimization problem using Gekko.

### Folder RanSAP120GB

This folder contains the training and inference results of RansomSentinel and traditional machine learning classifers, as well as the t-SNE visualization, for RanSAP120GB dataset. The files are the following:

- TsneVisualization.ipynb: t-SNE data visualization of the RanSAP120GB dataset.
- TraditionalMachineLearning.ipynb: Traditional machine learning classifiers.
- BatchSize512.ipynb: RansomSentinel classifier.

### Folder RanSAP250GB

This folder contains the training and inference results of RansomSentinel and traditional machine learning classifers, as well as the t-SNE visualization, for RanSAP250GB dataset. The files are the following:

- TsneVisualization.ipynb: t-SNE data visualization of the RanSAP250GB dataset.
- TraditionalMachineLearning.ipynb: Traditional machine learning classifiers.
- BatchSize256.ipynb: RansomSentinel classifier.

### Folder RanSMAP

This folder contains the training and inference results of RansomSentinel and traditional machine learning classifers, as well as the t-SNE visualization, for RanSMAP dataset. The files are the following:

- RanSMAP_TsneVisualization.ipynb: t-SNE data visualization of the RanSMAP dataset.
- RanSMAP_TraditionalML.ipynb: Traditional machine learning classifiers.
- RanSMAP_FinalDNN.ipynb: RansomSentinel classifier.

### Folder Statistics

This folder contains the R files with the statistical analysis of the research. The files are the following:

- Statistics.Rmd: DLL injection statistics.
- StatisticalAnalysis_120GB.Rmd: Statistics for the RanSAP120GB dataset.
- StatisticalAnalysis_250GB.Rmd: Statistics for the RanSAP1250GB dataset.
- StatisticalAnalysis_RanSMAP.Rmd: Statistics for the RanSMAP dataset.

