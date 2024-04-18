Code and data for the manuscript titled "Individual behavioral variation does not affect social organization or reproductive success in a cooperative small mammal"

DESCRIPTION We studied the common degu, Octodon degus, a social and group-living rodent, to evaluate whether individual behavioral variation affects i) 
the composition of social groups, and ii) the reproductive success of individuals in groups. 
We identified several social groups in a population in central-north Chile, tested adults in an open field and poke test to quantify individual behavioral variation, 
determined assortment based on individual behavioral differences across social groups, and performed genetic analyses.

CITATION
DOI: 10.5281/zenodo.8156905 
License: CC0

METADATA
We included the code in the Rmarkdown file titled "Rmd_degu_personality_v2.0_R2.Rmd"

The data files can be found in the data folder. 

poke_test.csv: datafile with poke test results
- date = date of poke test trial
- id	= unique identifier of adult degu
- obs = trial number
- capture	= number of capture
- burrow = at which burrow the degus was captured
- sex = male or female
- mass	= mass at capture
- poke = binomial poke response (0 = no response, 1 = response)

open_field_test.csv: datafile with open field test results
- trial = total number of trials performed
- date = date of open field test trial
- ID = unique identifier of degu
- video = trial number
- group = unique identifier to which group the degu belonged
- age = age of degu (adult or pup)
- sex = male or female
- weight = mass at capture
- hide_placement	= at which side of the arena the hide was placed
- hide = at which side of the arena the hide was placed
- distance_moved	= total distance moved in arena in cm,
- mean_velocity = average speed the degu was moving during trial
- time_moving_s	= total time spent moving in arena
- time_notmoving_s	= total time spent not moving in arena
- entry_number_arena	= how many times the degu entered the arena from the hide
- time_in_arena = total time spent in arena
- latency_hide = how many seconds it took the degu to leave the arena and enter the arena

  
parentage.csv: data file with parentage information
- OffspringID	= unique identifier of offsrping
- first_weight_offspring	= mass measured first time capturing
- motherID	= unique identifier of mother
- mother_groupID = to which social group the mother belonged
- fatherID	= unique identifier of father
- father_groupID = to which social group the father belonged


socialgroups2017.csv: datafile with social group information
- groupID	= identifier of the social group
- ID	= identifier of degu
- sex = male or female



SESSIONINFO R:  

R version 4.2.2 (2022-10-31 ucrt)
Platform: x86_64-w64-mingw32/x64 (64-bit)
Running under: Windows 10 x64 (build 22621)

Matrix products: default

locale:
[1] LC_COLLATE=English_Canada.utf8  LC_CTYPE=English_Canada.utf8   
[3] LC_MONETARY=English_Canada.utf8 LC_NUMERIC=C                   
[5] LC_TIME=English_Canada.utf8    

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

loaded via a namespace (and not attached):
  [1] nlme_3.1-160         matrixStats_0.63.0   xts_0.13.0          
  [4] threejs_0.3.3        rstan_2.26.16        tensorA_0.36.2      
  [7] job_0.3.0            tools_4.2.2          backports_1.4.1     
 [10] utf8_1.2.3           R6_2.5.1             DT_0.27             
 [13] colorspace_2.1-0     tidyselect_1.2.0     gridExtra_2.3       
 [16] prettyunits_1.1.1    processx_3.8.0       Brobdingnag_1.2-9   
 [19] emmeans_1.8.5        curl_5.0.0           compiler_4.2.2      
 [22] cli_3.6.1            shinyjs_2.1.0        sandwich_3.0-2      
 [25] colourpicker_1.2.0   posterior_1.4.1      scales_1.2.1        
 [28] dygraphs_1.1.1.6     checkmate_2.1.0      brms_2.19.0         
 [31] mvtnorm_1.1-3        gamlss_5.4-12        ggridges_0.5.4      
 [34] callr_3.7.3          stringr_1.5.0        digest_0.6.31       
 [37] StanHeaders_2.26.16  rmarkdown_2.21       base64enc_0.1-3     
 [40] pkgconfig_2.0.3      htmltools_0.5.5      fastmap_1.1.1       
 [43] htmlwidgets_1.6.2    rlang_1.1.0          rstudioapi_0.14     
 [46] shiny_1.7.4          gamlss.data_6.0-2    farver_2.1.1        
 [49] generics_0.1.3       zoo_1.8-11           jsonlite_1.8.4      
 [52] crosstalk_1.2.0      gtools_3.9.4         dplyr_1.1.1         
 [55] distributional_0.3.2 inline_0.3.19        magrittr_2.0.3      
 [58] loo_2.6.0            bayesplot_1.10.0     Matrix_1.5-1        
 [61] Rcpp_1.0.10          munsell_0.5.0        fansi_1.0.4         
 [64] abind_1.4-5          lifecycle_1.0.3      yaml_2.3.7          
 [67] stringi_1.7.12       multcomp_1.4-23      MASS_7.3-58.1       
 [70] gamlss.dist_6.0-5    pkgbuild_1.4.0       plyr_1.8.8          
 [73] grid_4.2.2           parallel_4.2.2       promises_1.2.0.1    
 [76] crayon_1.5.2         miniUI_0.1.1.1       lattice_0.20-45     
 [79] splines_4.2.2        knitr_1.42           ps_1.7.4            
 [82] pillar_1.9.0         faux_1.2.1           igraph_1.4.1        
 [85] markdown_1.5         estimability_1.4.1   shinystan_2.6.0     
 [88] reshape2_1.4.4       codetools_0.2-18     stats4_4.2.2        
 [91] rstantools_2.3.1     glue_1.6.2           evaluate_0.20       
 [94] V8_4.2.2             RcppParallel_5.1.7   vctrs_0.6.1         
 [97] httpuv_1.6.9         gtable_0.3.3         ggplot2_3.4.2       
[100] xfun_0.38            mime_0.12            xtable_1.8-4        
[103] asnipe_1.1.16        coda_0.19-4          later_1.3.0         
[106] survival_3.4-0       tibble_3.2.1         shinythemes_1.2.0   
[109] fitdistrplus_1.1-8   TH.data_1.1-1        ellipsis_0.3.2      
[112] bridgesampling_1.1-2

 

