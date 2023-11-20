# BEE5750-Plan2014
**BEE-5750 final project Plan 2014 sensitivity analysis**

This repo contains code to perform a sensitivity analysis on the Plan 2014 simulation model. The Plan-2014-Python folder is directly from Kyla Semmendinger's repo, titled "Plan-2014-Python". My intent for this project is to adapt this code to adjust certain parameters in the simulation model, and then observe the changes in the simulation model output, such as changes in water levels. I plan to then examine the impacts on various performance metrics (e.g., recreational boating, coastal impacts). 

In the folder titled Plan-2014-Python, you will see a folder titled "simulation_model." In this folder, there will be a scripts folder that contains my code for conducting the sensitivity analysis. Both the Method of Morris approach and Sobol approach were implemented on the simulation model. The SALib python library waas used to perform the sensitivity analysis. Here is the documentation for SALib: https://github.com/SALib/SALib/tree/main 

Kyla's original model can be found here: https://github.com/ksemmendinger/Plan-2014-Python
