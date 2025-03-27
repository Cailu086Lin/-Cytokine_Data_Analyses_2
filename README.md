# Cytokine_Data_Analyses_2
Analysis provided in the "Long-term aspirin desensitization has mucosal cytokine features of immune tolerance" manuscript

This repository is meant to provide the source code for the analysis provided in the above manuscript by Michael A Kohanski MD PhD,*, Anas Qatanani BA, Cailu Lin PhD, Li Hui Tan PhD, Jeremy Chang BA, Andrew Corr BA, Sabrina Herzberg BA, Nithin D Adappa MD, James N Palmer, John V Bosso MD, Danielle Reed PhD, Noam A Cohen MD PhD

# Abstract

Background: Aspirin desensitization for patients with aspirin exacerbated respiratory disease (AERD) is performed over 1-2 days and it can take 6-12 months for the full clinical benefits to manifest. It is unclear if desensitization is dependent solely on aspirin-mediated inhibition of COX pathways or if there are also COX-independent mechanisms.
Objective: To determine if there are inflammatory shifts in the sinus mucosa at least 6-months after aspirin desensitization.

Methods: Samples were acquired from the ethmoid mucosa of AERD patients pre-sinus surgery and pre-aspirin desensitization (pre-ASA, N=28), and from patients who had undergone complete sinus surgery and were at least 6-months post-aspirin desensitization (post-ASA, N=45). We quantified 8 cytokines/chemokines (IFN-, IL-10, IL-6, CCL20, IL-13, IL-5, IL-33, TNF) using the Luminex platform.

Results: Baseline comparisons between the 2 groups showed no clinically significant differences. The post-ASA group had well controlled asthma and chronic sinusitis with a median aspirin dose of 700mg a day and a mean time since desensitization of 29.5 months. Among the measured cytokines, IFN-, IL-10, CCL20 and IL-13 were all significantly elevated in the post-ASA cohort compared to the pre-ASA cohort. IL-33 and IL-6 were significantly decreased in the post-ASA cohort and there were no significant changes in IL-5 or TNF.
Conclusion: Increased IL-10 and IFN- and decreased IL-6 in sinus mucosa in the post-ASA group suggests that long-term aspirin desensitization may lead to development of immune tolerance. Further studies are indicated to understand the cellular context and mechanisms associated with the observed shift in cytokine levels.


# sessionInfo()
R version 4.2.1 (2022-06-23 ucrt)
Platform: x86_64-w64-mingw32/x64 (64-bit)
Running under: Windows 7 x64 (build 7601) Service Pack 1

Matrix products: default

locale:
[1] LC_COLLATE=English_United States.1252  LC_CTYPE=English_United States.1252   
[3] LC_MONETARY=English_United States.1252 LC_NUMERIC=C                          
[5] LC_TIME=English_United States.1252    

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] rstatix_0.7.0     xlsx_0.6.5        broom_1.0.1       pheatmap_1.0.12  
 [5] scales_1.2.1      ggstatsplot_0.9.4 plyr_1.8.7        tableone_0.13.2  
 [9] gtsummary_1.6.2   irr_0.84.1        lpSolve_5.6.17    goeveg_0.5.1     
[13] sjmisc_2.8.9      GGally_2.1.2      ggpubr_0.4.0      readxl_1.4.0     
[17] forcats_0.5.2     stringr_1.4.1     dplyr_1.0.10      purrr_0.3.4      
[21] readr_2.1.3       tidyr_1.2.1       tibble_3.1.8      ggplot2_3.3.6    
[25] tidyverse_1.3.2  

loaded via a namespace (and not attached):
  [1] TH.data_1.1-1          googledrive_2.0.0      colorspace_2.0-3      
  [4] ggsignif_0.6.3         ellipsis_0.3.2         sjlabelled_1.2.0      
  [7] estimability_1.4.1     parameters_0.19.0      fs_1.5.2              
 [10] rstudioapi_0.14        fansi_1.0.3            mvtnorm_1.1-3         
 [13] lubridate_1.8.0        xml2_1.3.3             codetools_0.2-18      
 [16] splines_4.2.1          knitr_1.40             zeallot_0.1.0         
 [19] spam_2.9-1             jsonlite_1.8.2         gt_0.7.0              
 [22] rJava_1.0-6            cluster_2.1.3          dbplyr_2.2.1          
 [25] compiler_4.2.1         httr_1.4.4             emmeans_1.8.1-1       
 [28] backports_1.4.1        assertthat_0.2.1       Matrix_1.5-1          
 [31] fastmap_1.1.0          gargle_1.2.1           survey_4.1-1          
 [34] cli_3.3.0              htmltools_0.5.3        tools_4.2.1           
 [37] dotCall64_1.0-2        coda_0.19-4            gtable_0.3.1          
 [40] glue_1.6.2             maps_3.4.0             Rcpp_1.0.9            
 [43] carData_3.0-5          cellranger_1.1.0       vctrs_0.4.1           
 [46] nlme_3.1-157           broom.helpers_1.9.0    insight_0.18.5        
 [49] xfun_0.31              xlsxjars_0.6.1         rvest_1.0.3           
 [52] lifecycle_1.0.3        pacman_0.5.1           googlesheets4_1.0.1   
 [55] zoo_1.8-11             MASS_7.3-57            hms_1.1.2             
 [58] sandwich_3.0-2         parallel_4.2.1         rematch2_2.1.2        
 [61] RColorBrewer_1.1-3     fields_14.1            yaml_2.3.5            
 [64] gridExtra_2.3          reshape_0.8.9          stringi_1.7.8         
 [67] paletteer_1.4.1        bayestestR_0.13.0      permute_0.9-7         
 [70] rlang_1.0.6            pkgconfig_2.0.3        evaluate_0.17         
 [73] lattice_0.20-45        patchwork_1.1.2        cowplot_1.1.1         
 [76] tidyselect_1.2.0       magrittr_2.0.3         R6_2.5.1              
 [79] generics_0.1.3         multcomp_1.4-20        DBI_1.1.3             
 [82] pillar_1.8.1           haven_2.5.1            withr_2.5.0           
 [85] mgcv_1.8-40            survival_3.3-1         datawizard_0.6.2      
 [88] abind_1.4-5            performance_0.10.0     modelr_0.1.9          
 [91] crayon_1.5.2           car_3.1-0              utf8_1.2.2            
 [94] correlation_0.8.3      tzdb_0.3.0             rmarkdown_2.17        
 [97] viridis_0.6.2          grid_4.2.1             vegan_2.6-4           
[100] reprex_2.0.2           digest_0.6.29          xtable_1.8-4          
[103] statsExpressions_1.3.4 munsell_0.5.0          viridisLite_0.4.1     
[106] mitools_2.4           
