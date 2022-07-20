--- 
title: "A Guide to The New Statistics with R"
author: "Pete Apicella"
date: "2022-07-19"
site: bookdown::bookdown_site
documentclass: book
bibliography: [book.bib, packages.bib]
link-citations: yes
github-repo: rstudio/bookdown-demo
---

# About {-}

This resource encompasses my compiled notes on Dr. Andy Hector's text, *The New Statistics with R: An Introduction for Biologists* Second edition. Throughout the book he emphasizes the use of Rmarkdown for reproducible research. I take this recommendation a step further by taking all R-related notes in Rmarkdown documents. Nearly every section header corresponds to Dr. Hector's chapter headings. These notes are not meant to replace the textbook. Instead they may act as a helpful guide written by someone who is a student of biostatistics. 





```r
sessionInfo()
#> R version 4.1.1 (2021-08-10)
#> Platform: aarch64-apple-darwin20 (64-bit)
#> Running under: macOS Monterey 12.4
#> 
#> Matrix products: default
#> BLAS:   /Library/Frameworks/R.framework/Versions/4.1-arm64/Resources/lib/libRblas.0.dylib
#> LAPACK: /Library/Frameworks/R.framework/Versions/4.1-arm64/Resources/lib/libRlapack.dylib
#> 
#> locale:
#> [1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8
#> 
#> attached base packages:
#> [1] stats     graphics  grDevices utils     datasets 
#> [6] methods   base     
#> 
#> loaded via a namespace (and not attached):
#>  [1] bookdown_0.27   digest_0.6.29   R6_2.5.1       
#>  [4] jsonlite_1.7.3  magrittr_2.0.3  evaluate_0.15  
#>  [7] stringi_1.7.6   cachem_1.0.6    rlang_1.0.2    
#> [10] cli_3.2.0       fs_1.5.2        rstudioapi_0.13
#> [13] jquerylib_0.1.4 xml2_1.3.3      bslib_0.3.1    
#> [16] rmarkdown_2.14  tools_4.1.1     stringr_1.4.0  
#> [19] xfun_0.31       yaml_2.2.1      fastmap_1.1.0  
#> [22] compiler_4.1.1  memoise_2.0.1   htmltools_0.5.2
#> [25] downlit_0.4.0   knitr_1.39      sass_0.4.0
```

