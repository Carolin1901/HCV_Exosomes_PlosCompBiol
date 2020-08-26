# HCV_Exosomes_PlosCompBiol
## Aim of this project
We developed and studied a series of mathematical models reflecting the intracellular HCV replication in presence and absence of HCV RNA secretion and virus assembly and release. 

## Data and models
The data set (Keum_HCV.xls) used for model calibration can be found in [Keum et al. (2012)](https://www.sciencedirect.com/science/article/pii/S0042682212004278?via%3Dihub). The Keum et al. data set has been extracted using the [WebPlotDigitizer]( https://automeris.io/WebPlotDigitizer/userManual.pdf). 

Model fitting and profile likelihood analysis have been performed by using the [Data2Dynamics toolbox]( https://academic.oup.com/bioinformatics/article/31/21/3558/195191) for the MATLAB environment (MATLAB 2016b) and hence, the structure of model folders follows that toolbox structure. Please see for more information the GitHub page and all references within ([Data2Dynamics GitHub](https://github.com/Data2Dynamics/d2d)).

In brief: [Download the toolbox]( https://github.com/Data2Dynamics/d2d) and make sure to meet all [system requirements]( https://github.com/Data2Dynamics/d2d/wiki/Installation) in order to run the models in Data2Dynamics. 

The folder structure for a model (e.g. 1_SM_Models) contains a *data*, *models* subfolder and *Setup* scripts. Run a particular model by executing the *Setup* script. 

The secretion models can be found in the folder *1_SM_Models* and *S1_SM_Models*. The latter ones are considering the secretion of HCV negative-strand RNA (see supplementary inforamtion). The models describing virus assembly and release processes can be found in folder *2_AM_Models*, while the combination of HCV RNA secretion and virus assembly and release are in folder *3_CM_Models*. 

For model CM4 we performed a sensitivity analysis with [eFast]( https://www.sciencedirect.com/science/article/abs/pii/S0022519308001896?via%3Dihub). 

## Results and plots
Plotting has been performed with R.

## References
> [Zitzmann et al.](link) Our paper can be found here. 
> [Keum et al. (2012)](https://www.sciencedirect.com/science/article/pii/S0042682212004278?via%3Dihub)
> [Data2Dynamics toolbox]( https://academic.oup.com/bioinformatics/article/31/21/3558/195191)
> PLE
> [eFast]( https://www.sciencedirect.com/science/article/abs/pii/S0022519308001896?via%3Dihub)


