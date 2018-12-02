# Ozone-day-detection
In this project, we employed logistic regression to classify an ozone day from 1/1/1998 to 1/26/2004.
According to Texas Commission on Environmental Quality (TCEQ), the following attributes (see Table 1) are the most important 
factors influencing ozone level in the atmosphere.

O3: Local ozone peak prediction
Upwind: Upwind ozone background level
EmFactor: Precursor emissions related factor
Tmax: Maximum temperature in degrees F
Tb: Base temperature where net ozone production begins (50 F)
SRd: Solar radiation total for the day
Wsa: Wind speed near sunrise (using 09-12 UTC forecast mode)
WSp: Wind speed mid-day (using 15-21 UTC forecast mode)

In our dataset, we have the 72 attributes. We performed analysis as follows:

step1: check goodness of fit and multicollinearity
step2: Detect outlier by looking at CBAR, DIFDEV and DIFCHISQ 
step3: stepwise regression 

We finally achieved Somer's D of 0.877 with only 6 attributes.
