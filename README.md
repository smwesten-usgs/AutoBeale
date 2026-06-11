# AutoBeale
AutoBeale: code to calculate loads by means of Beale's Ratio Estimator.

> [!NOTE] This is not my code! I am posting it here because I think it is a piece of software that deserves to be remembered. AutoBeale was used in many load estimations around the Great Lakes.

The following information is from Peter Richards, the original author of this version of the AutoBeale estimator software:

> "The Beale Ratio Estimator is described in Tin (1965).  It has been widely used for computation of substance loadings to receiving waters, particularly in the Great Lakes system.  The initial code was developed by Ken Baun of Wisconsin DNR (1982).  It was subsequently used and developed by Kevin McGunagle at the International Joint Commission (IJC), from whom the current version was received. It was then developed in the 1990’s by Pete Richards at the National Center for Water Quality Research at Heidelberg University (www.heidelberg.edu/academiclife/distinctive/ncwqr).  Peter developed the code to work with the Macintosh computer of the time (“Motorola" architecture, which was replaced by Intel architecture ca. 2005), and included a Graphic User Interface (GUI) and an algorithm that objectively and sequentially searched out the best stratification given the data, with “best” being defined as minimizing the root-mean-square error (RMSE) given the data at hand. This is the current and final version.  A Windows version of the code was also developed, with a minimal GUI."  


**The code included in this archive contains the minimal Windows GUI.**

#### Earlier implementations of the Beale Ratio Estimator

A report by the International Joint Commission (Sonzogni and others, 1978) references an earlier piece of software:

> Loadings calculated for this report, other than those to Lake Erie, were done using the ratio estimator method, employing a computer  program developed specifically for applying the calculation method (Clark, 1976). This method has been widely reviewed and is generally accepted by the Great Lakes research and surveillance community as the preferred and, importantly, standard method for calculating tributary loads. 

The earlier code was presumably written by J. Clark, of the International Joint Commission Great Lakes Regional Office in Windsor, Ontario. Another IJC report goes on to describe this software (Konrad and others, 1978):

> John Clark, IJC statistician, proposed (March, 1977, PLUARG Task C Handbook Amendments) that a stratified random sampling model enhanced by a ratio estimator be used for load calculations. The assumptions of the model proposed by  Clark are: 
> 
> a) simple random sampling of water quality withing [sic] nonoverlapping subpopulations or strata, and
>  
> b) use of available supplemental population flow information for the several strata (rather than instantaneous flows only for those times when water quality samples were taken). 
 
> The statistical technique of stratifying subsample data was applied in the calculation of loads in order to provide more precision in the loading estimate for a particular parameter by clustering units
> which are homogeneous in terms of concentration of that parameter.  The underlying assumption is that the population of all water quality concentrations of the parameter of interest can be more accurately represented as the sum of subpopulations, rather than as a single, homogeneous population. The determination of strata was critical, since these strata reflected the hypothesized (or  observed) subpopulations of water quality concentrations. 
> 
> Using a stratification scheme which included: (1) season, (2) event versus nonevent within each season, and (3) high flow versus low flow times within the events, loading estimates were calculated for the sampling stations. 

### References
Baun, K., 1982. Alternative methods of estimating pollutant loads in flowing water: Technical Bulletin 133, Wisconsin Department of Natural Resources, p. 1–16.

Konrad, J., Chesters, G., and K Bauer, 1978. Menomonee River Pilot Watershed Study, International Joint Commission, Reference Group on Pollution from Land Use Activities (PLUARG), 90p. 

Tin, M., 1965. Comparison of some ratio estimators: Journal of the American Statistical Association, p. 294–307.

Sonzogni, W., Monteith, T., Bach, W., and V. G. Hughes, 1978. United States Great Lakes Tributary Loadings, Great Lakes Basin Commission, Ann Arbor, Michigan, 200p. 
