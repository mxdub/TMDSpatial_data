# TMDSpatial_data

Installation JAGS (prefer version 4.3.0 - 4.3.1 only works with last R pre-release (4.3.0))
+ Windows : https://sourceforge.net/projects/mcmc-jags/files/ (ou https://mcmc-jags.sourceforge.io/)
+ Unix : sudo apt-get update && sudo apt-get install jags

Depuis CRAN (pour R):

+ vegan
+ R2jags (after installing JAGS above, test with library(R2jags) whether the module find jags; if not, install lower JAGS version)

and from GitHub : https://github.com/mxdub/TMDSpatial, with R : devtools::install_github("mxdub/TMDSpatial")

# Content :

You can download the repo on your computer, we will use model/ and data/).

+ Practical I : ordination methods (especially, variation partitioning on simulated data), associated data in the data/ folder
+ Practical II :  dyn. occupancy models (from metapop. to two-species metapopulation with environmental effects), models are stored in the model/ folder.
+ examples.R : bench of stuff... more or less all presented methods and some jSDM 