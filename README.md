# TMDSpatial_data

Installation JAGS 
+ Windows : https://sourceforge.net/projects/mcmc-jags/files/ (ou https://mcmc-jags.sourceforge.io/)
+ Unix : sudo apt-get update && sudo apt-get install jags

Depuis CRAN (pour R):

+ vegan
+ R2jags (after installing JAGS above)
+ Hmsc

and from GitHub : https://github.com/mxdub/TMDSpatial, with R : devtools::install_github("mxdub/TMDSpatial")

# Content :

+ Practical I : ordination methods (especially, variation partitioning on simulated data), associated data in the data/ folder
+ Practical II :  dyn. occupancy models (from metapop. to two-species metapopulation with environmental effects), models are stored in the model/ folder.
+ examples.R : bench of stuff... more or less all presented methods and some jSDM 