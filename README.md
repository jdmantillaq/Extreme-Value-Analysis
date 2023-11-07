# Extreme Value Analysis

  This beginner's guide provides comprehensive instructions for performing Extreme Value Analysis (EVA), a crucial technique in statistical hydrology and climatology. It serves as an updated version of a previous repository by [royalosyin](https://github.com/royalosyin/A-Beginner-Guide-to-Carry-out-Extreme-Value-Analysis-with-Codes-in-Python), ensuring compatibility with Python3 and lmoments3. All the credits shall go to [him](https://github.com/royalosyin/A-Beginner-Guide-to-Carry-out-Extreme-Value-Analysis-with-Codes-in-Python).

Whether you are interested in extreme rainfall analysis or working with other climatic variables such as temperature and wind speed, this guide equips you with the knowledge and code examples needed for your EVA endeavors.


## Examples

Among the functionalities, it is possible to adapt the data to different extreme distributions [2_extremeMultipleDistributions](2_extremeMultipleDistributions.ipynb):

* Exponential (EXP)
* Gamma (GAM)
* Generalised Extreme Value (GEV)
* Generalised Logistic (GLO)
* Generalised Normal (GNO)
* Generalised Pareto (GPA)
* Gumbel (GUM)
* Kappa (KAP)
* Normal (NOR)
* Pearson III (PE3)
* Wakeby (WAK)
* Weibull (WEI)

<figure style="text-align: center;">
<img src="figures/distributions.png" alt="Distributions" width="500"/>
</figure>

As well as calculating confidence intervals for a given distribution [`3_extremeConfidenceIntervals`](3_extremeConfidenceIntervals.ipynb):
<figure style="text-align: center;">
<img src="figures/confidence_intervals.png" alt="Confidence_Intervals" width="500"/>
</figure>

## Modules

`lmoments3` and `lmfit` can be installed by:
* `pip install lmoments3`
* `pip install lmfit`


### Notes:

The implementation of the [`5_extremeIDF`](5_extremeIDF.ipynb) file, could not be updated in python3 and was left as the original file.