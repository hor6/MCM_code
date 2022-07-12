# Mixture-cure model

The mixture-cure model was performed using R software following the methodology described by Felizzi et al 2021. 

In general, mixture-cure models assumes the patient population comprises two subpopulations; the first subpopulation is considered “statically cured” and to be at the same risk of mortality as the age- and sex-matched general population (long-term remission or cured patients), whilst in the second population the disease is shortening the life expectancy and this disease related excess mortality  is modelled using standard parametric survival functions (non long-term remission or non cured patients). 

#How to run the code

To run the code you may need to install the following packeges:
- flexsurv
- MASS
- RCurl

You also need to have a high-quality mortality data to approximate background mortality in the model. In this example we used the mortality from Human Mortality Database and you can find it in the folder "data"

The code provide two options of script: 

(1)  the cure fraction is estimated from the trial data 

(2) an external data source is used to inform the cure fraction



# References
Felizzi F, Paracha N, Pöhlmann J, Ray J. Mixture Cure Models in Oncology: A Tutorial and Practical Guidance. Pharmacoecon Open. 2021 Jun;5(2):143-155. doi: 10.1007/s41669-021-00260-z. Epub 2021 Feb 26. PMID: 33638063; PMCID: PMC8160049.
