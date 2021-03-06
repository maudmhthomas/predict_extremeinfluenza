# Real-time prediction of severe influenza epidemics using Extreme Value Statistics 

This repository contains the R code attached to the paper "Predict extremes: influenza in France", M. Thomas and H. Rootzén included simulations of multivariate Generalized Pareto distributed vectors, fits of multivariate Generalized Pareto models and conditionnal predictions of exceedances of high thresholds. 

### Librairies
To run the codes, install the following R librairies:
  - extRemes (2.0-10)
  - ggplot2 (3.2.1)
  - gridExtra (2.3)
  - doParallel (1.0.14)
  - foreach (1.4.4)
  - glmnet (2.0-16)
  - pracma (2.2.5)
  - pROC (1.15.3)
  - MLmetrics (1.1.1)
  - energy (1.7-7)

### Description of the files:
Files are provided in the format Rmarkdown. To run them, please select in RStudio "run all the chunkes" to run them in the R console or "knit to html" to provide a hmtl file containing all the codes and all outputs.

- FinalCode03102019.Rproj: R project. 
- PredictEpidemicTools.Rmd: Rmarkdown file with all the R functions.
- ILIincidences1985-2019.csv: Real data associated with the codes.
- SimulatedDataWeek3.csv: simulated data for the prediction of Week 3.
- SimulatedDataSize.csv: simulated data for the prediction of the Size.
- PredSimus_Week3: predictions for Simulations of Week3 (needed for RunWeek3, can be obtained with RunSimulationsWeek3)
- GumbelSimulate.Rmd: Rmarkdown file to obtain the simulated data (SimulatedDataWeek3.csv and SimulatedDataSize.csv).
- RunRealWeek3.Rmd: Rmarkdown file to produce all the results about the prediction of Week 3 from the real data.
- RunRealSize.Rmd: Rmarkdown file to produce all the results about the prediction of Size from the real data.
- RunSimulationsWeek3.Rmd: Rmarkdown file to produce all the results about the prediction of Week 3 from the simulated data.
- RunSimulationsSize.Rmd: Rmarkdown file to produce all the results about the prediction of Size from the simulated data.

The codes	were built on R version 3.6.0.
