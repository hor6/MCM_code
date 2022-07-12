# Mixture-cure model

The cure-mixture model was performed using R software following the methodology described by Felizzi et al 2021. 

#How to run the code

To run the code you may need to install the following packeges:
- flexsurv
- MASS
- RCurl

You also need to have a high-quality mortality data to approximate background mortality in the model. In this example we used the mortality from Human Mortality Database and you can find it in the folder "data"

The code provide two options of script: 

(1)  the cure fraction is estimated from the available trial data a

(2) an external data source is used to estimate the cure fraction


# References
Felizzi F, Paracha N, Pöhlmann J, Ray J. Mixture Cure Models in Oncology: A Tutorial and Practical Guidance. Pharmacoecon Open. 2021 Jun;5(2):143-155. doi: 10.1007/s41669-021-00260-z. Epub 2021 Feb 26. PMID: 33638063; PMCID: PMC8160049.
