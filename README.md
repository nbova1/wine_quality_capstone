# wine_quality_capstone

This project has been prepared for the HarvardX PH125 Data Science Capstone Course

There are four files available.  
  1. The report in PDF format - wine_quality_notebook.pdf  
  2. The Rmd file - wine_quality_notebook.rmd  
  3. A script in R format that performs a supervised and unsupervised machine   
  learning task - wine_quality.R  
  4. The dataset (in semi-colon delimited format) - wine_quality-white.csv  
  
The dataset is also available at: https://archive.ics.uci.edu/ml/datasets/Wine+Quality 
  
Note: 15 models are used in the modeling section. Since we are using the caret package, these are not being loaded upfront and they are not detected by RStudio as a dependency. I have attempted to load all modeling packages. If you are running the code, when the caret package is run in the modeling section, you will be prompted in the console window to load any missing packages. These prompts happen individually for each missing package. Pre-loading all potential libraries used by caret was found to create errors due to masking.