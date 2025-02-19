# Awesome R

A curated list of awesome R frameworks, packages and software. Inspired by [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning).

- [Awesome R](#awesome-)
    - [Integrated Development Environment](#integrated-development-environment)
    - [Syntax](#syntax)
    - [Data Manipulation](#data-manipulation)
    - [Graphic Displays](#graphic-displays)
    - [Reproducible Research](#reproducible-research)
    - [Web Technologies and Services](#web-technologies-and-services)
    - [Parallel Computing](#parallel-computing)
    - [High Performance](#high-performance)
    - [Language API](#language-api)
    - [Database Management](#database-management)
    - [Machine Learning](#machine-learning)
    - [Statistical Modeling](#statistical-modeling)
    - [Bayesian Analysis](#bayesian-analysis)
    - [Genetic and Genomic Analysis](#genetic-and-genomic-analysis)
    - [R Development](#r-development)
- [Resources](#resources)
    - [Websites](#websites)
    - [Books](#books)
    - [Reference Card](#reference-card)
- [Other Awesome Lists](#other-awesome-lists)

## Integrated Development Environment
*Integrated Development Environment* 

* [RStudio](http://www.rstudio.org/) - A powerful and productive user interface for R. Works great on Windows, Mac, and Linux.
* [Emacs + ESS](http://ess.r-project.org/) - Emacs Speaks Statistics is an add-on package for emacs text editors.
* [StatET](http://www.walware.de/goto/statet) - An Eclipse based IDE (integrated development environment) for R.
* [Revolution R Enterprise](http://www.revolutionanalytics.com/get-revolution-r-enterprise) - Revolution R would be offered free to academic users and commercial software would focus on big data, large scale multiprocessor functionality.
* [R Commander](http://socserv.mcmaster.ca/jfox/Misc/Rcmdr/) - A package that provides a basic graphical user interface.
* [IPython](http://ipython.org/ipython-doc/rel-0.13/config/extensions/rmagic.html#extensions-rmagic) - An interactive Python interpreter,and it supports execution of R code while capturing both output and figures.
* [Radiant](http://vnijs.github.io/radiant/) - A platform-independent browser-based interface for business analytics in R, based on the Shiny package.
* [Visual Studio Code](https://code.visualstudio.com/) - One of the most popular IDEs available for coding multiple programs including R. 

## Syntax
*Packages change the way you use R.*

* [magrittr](https://github.com/smbache/magrittr) - Let's pipe it.
* [pipeR](https://github.com/renkun-ken/pipeR) - Multi-paradigm Pipeline Implementation.
* [Forward Pipe Operator](https://stat.ethz.ch/R-manual/R-devel/library/base/html/pipeOp.html) - R 4.1.0 introduces a pipe operator |> into the base R syntax.
* [pacman](http://trinker.github.io/pacman/vignettes/Introduction_to_pacman.html) - Package Management Tool

## Exploratory Data Analysis (EDA)
*Packages for Automated Exploratory Data Analysis*

* [DataExplorer](https://cran.r-project.org/web/packages/DataExplorer/vignettes/dataexplorer-intro.html) - helps to get an overview of the data set quickly with automated EDA in just a line of code.
* [dlookr](https://choonghyunryu.github.io/dlookr/) - A collection of tools that support data diagnosis, exploration, transformation and automated data diagnostic reports.
* [GGally](https://ggobi.github.io/ggally/index.html) - providing features to automatically visualize datasets and combine geometric objects.
* [SmartEDA](https://cran.r-project.org/web/packages/SmartEDA/vignettes/SmartEDA.html#parallel-co-ordinate-plots) - concentrates on providing data comprehension using visuals and descriptive statistics.

## Data Manipulation
*Packages for cooking data.*

* [dplyr](https://github.com/hadley/dplyr) -  Blazing fast data frames manipulation and database query.
* [data.table](https://github.com/Rdatatable/data.table) - Fast data manipulation in a short and flexible syntax.
* [dtplyr](https://dtplyr.tidyverse.org/) - easier data.table for dplyr users.
* [reshape2](https://github.com/hadley/reshape) - Flexible rearrange, reshape and aggregate data.
* [readr](https://github.com/hadley/readr) -  A fast and friendly way to read tabular data into R.
* [tidyr](https://github.com/hadley/tidyr) - Easily tidy data with spread and gather functions.
* [janitor](https://garthtarr.github.io/meatR/janitor.html) - A R package for examining and cleaning dirty data.
* [haven](https://haven.tidyverse.org/) - allows you to load foreign data formats (SAS, Spss and Stata) into R.
* [broom](https://github.com/dgrtwo/broom) - Convert statistical analysis objects into tidy data frames.
* [rlist](https://github.com/renkun-ken/rlist) - A toolbox for non-tabular data manipulation with lists.
* [ff](http://ff.r-forge.r-project.org/) - Data structures designed to store large datasets.
* [lubridate](http://cran.r-project.org/web/packages/lubridate/index.html) - A set of functions to work with dates and times.
* [stringi](http://www.rexamine.com/resources/stringi/) - ICU based string processing package.
* [stringr](https://github.com/hadley/stringr) -  Consistent API for string processing.
* [vroom](https://www.tidyverse.org/blog/2019/05/vroom-1-0-0/) - The fastest delimited reader for your R data-manipulation.
* [purrr](https://purrr.tidyverse.org/) - It is part of tidyverse package and is a toolkit to apply functions for iteration.
* [forcats](https://forcats.tidyverse.org/) - Provides a suite of tools that solve common problems with factors.
* [gdata](https://github.com/r-gregmisc/gdata) - Various R Programming Tools for Data Manipulation.
* [here](https://here.r-lib.org/) - An amazing package that can help you better organise your R folders and make every dataset and script easier to find. 
* [skimr](https://github.com/ropensci/skimr) - Displays summary statistics the user can skim quickly to understand their data.
* [summarytools](https://cran.r-project.org/web/packages/summarytools/vignettes/introduction.html) - Providing tools to neatly and quickly summarize data

## Graphic Displays
*Packages for showing data.*

* [ggplot2](https://github.com/hadley/ggplot2) -  An implementation of the Grammar of Graphics.
* [ggvis](https://github.com/rstudio/ggvis) - Interactive grammar of graphics for R.
* [rCharts](https://github.com/ramnathv/rCharts) - Interactive JS Charts from R.
* [lattice](http://lattice.r-forge.r-project.org/) -  A powerful and elegant high-level data visualization system.
* [rgl](http://cran.r-project.org/web/packages/rgl/index.html) - 3D visualization device system for R.
* [Cairo](http://cran.r-project.org/web/packages/Cairo/index.html) - R graphics device using cairo graphics library for creating high-quality display output.
* [extrafont](https://github.com/wch/extrafont) - Tools for using fonts in R graphics.
* [showtext](https://github.com/yixuan/showtext) - Enable R graphics device to show text using system fonts.
* [dygraphs](https://github.com/rstudio/dygraphs) - Charting time-series data in R.
* [rbokeh](http://hafen.github.io/rbokeh/) - R Interface to [Bokeh](http://bokeh.pydata.org/en/latest/).
* [DiagrammeR](https://github.com/rich-iannone/DiagrammeR) - Create JS graph diagrams and flowcharts in R.
* [plotly](https://github.com/ropensci/plotly) - Integration with [plot.ly](https://plot.ly).
* [pairsD3](https://github.com/garthtarr/pairsD3) - Interactive pairs plots (scatterplot matrices).
* [esquisse](https://cran.r-project.org/web/packages/esquisse/readme/README.html) - This is a Shiny gadget to create ggplot charts interactively with retrieving the ggplot code to reproduce the graph.
* [ggstatsplot](https://indrajeetpatil.github.io/ggstatsplot/) - An extension of ggplot2 package for creating graphics with details from statistical tests
* [ggpubr](https://rpkgs.datanovia.com/ggpubr/) -  provides some easy-to-use functions for creating and customizing ggplot2-based publication ready plots

## Reproducible Research
*Packages for literate programming.*

* [knitr](http://yihui.name/knitr/) - Easy dynamic report generation in R.
* [kableExtra](https://cran.r-project.org/web/packages/kableExtra/vignettes/awesome_table_in_html.html)- help you build common complex tables and manipulate table styles.
* [xtable](http://cran.r-project.org/web/packages/xtable/index.html) -  Export tables to LaTeX or HTML.
* [rapport](http://rapport-package.info/#intro) - An R templating system.
* [rmarkdown](http://rmarkdown.rstudio.com/) -  Dynamic documents for R.
* [slidify](https://github.com/ramnathv/slidify) - Generate reproducible html5 slides from R markdown.
* [Sweave](https://www.statistik.lmu.de/~leisch/Sweave/) - A package designed to write LaTeX reports using R.
* [texreg](http://www.philipleifeld.de/software/texreg/texreg.html) - Formatting statistical models in LaTex and HTML.

## Web Technologies and Services
*Packages to surf the web.*

* [shiny](https://github.com/rstudio/shiny) - Easy interactive web applications with R.
* [RCurl](http://cran.r-project.org/web/packages/RCurl/index.html) - General network (HTTP/FTP/...) client interface for R.
* [httpuv](https://github.com/rstudio/httpuv) - HTTP and WebSocket server library.
* [XML](http://cran.r-project.org/web/packages/XML/index.html) - Tools for parsing and generating XML within R.
* [rvest](https://github.com/hadley/rvest) - Simple web scraping for R. 
* [OpenCPU](https://www.opencpu.org/) - HTTP API for R. 

## Parallel Computing
*Packages for parallel computing.*

* [parallel](http://cran.r-project.org/web/views/HighPerformanceComputing.html) -  R started with release 2.14.0 which includes a new package parallel incorporating (slightly revised) copies of packages [multicore](http://cran.r-project.org/web/packages/multicore/index.html) and [snow](http://cran.r-project.org/web/packages/snow/index.html).
* [Rmpi](http://cran.r-project.org/web/packages/Rmpi/index.html) - Rmpi provides an interface (wrapper) to MPI APIs. It also provides interactive R slave environment.
* [foreach](http://cran.r-project.org/web/packages/foreach/index.html) - Executing the loop in parallel.
* [SparkR](https://github.com/amplab-extras/SparkR-pkg) - R frontend for Spark.

## High Performance
*Packages for making R faster.*

* [Rcpp](http://rcpp.org/) - Rcpp provides a powerful API on top of R, make function in R extremely faster.
* [Rcpp11](https://github.com/Rcpp11) - Rcpp11 is a complete redesign of Rcpp, targetting C++11.
* [compiler](http://stat.ethz.ch/R-manual/R-devel/library/compiler/html/compile.html) - speeding up your R code using the JIT 

## Language API
*Packages for other languages.*

* [rJava](http://cran.r-project.org/web/packages/rJava/) - Low-level R to Java interface.
* [jvmr](https://github.com/cran/jvmr) - Integration of R, Java, and Scala.
* [rJython](http://cran.r-project.org/web/packages/rJython/index.html) - R interface to Python via Jython.
* [rPython](http://cran.r-project.org/web/packages/rPython/index.html) - Package allowing R to call Python.
* [runr](https://github.com/yihui/runr) - Run Julia and Bash from R.
* [RJulia](https://github.com/armgong/RJulia) - R package Call Julia.
* [RinRuby](https://sites.google.com/a/ddahl.org/rinruby-users/) -  a Ruby library that integrates the R interpreter in Ruby.
* [R.matlab](http://cran.r-project.org/web/packages/R.matlab/index.html) - Read and write of MAT files together with R-to-MATLAB connectivity.
* [RcppOctave](RcppOctave) - Seamless Interface to Octave and Matlab.
* [RSPerl](http://www.omegahat.org/RSPerl/) - A bidirectional interface for calling R from Perl and Perl from R.
* [V8](https://github.com/jeroenooms/V8) - Embedded JavaScript Engine.
* [htmlwidgets](http://www.htmlwidgets.org/) - Bring the best of JavaScript data visualization to R.
* [rpy2](http://rpy.sourceforge.net/) - Python interface for R.
* [reticulate](https://rstudio.github.io/reticulate/) - Provides a comprehensive set of tools for interoperability between Python and R

## Database Management
*Packages for managing data.*

* [dbplyr](https://dbplyr.tidyverse.org/) - The database backend for dplyr allowing you to work with remote database tables as if they are in-memory data frames.
* [RODBC](http://cran.r-project.org/web/packages/RODBC/) - ODBC database access for R.
* [DBI](https://github.com/rstats-db/DBI) - Defines a common interface between the R and database management systems.
* [RMySQL](http://cran.r-project.org/web/packages/RMySQL/) - R interface to the MySQL database.
* [ROracle](http://cran.r-project.org/web/packages/ROracle/index.html) - OCI based Oracle database interface for R.
* [RPostgreSQL](https://code.google.com/p/rpostgresql/) - R interface to the PostgreSQL database system.
* [RSQLite](http://cran.r-project.org/web/packages/RSQLite/) - SQLite interface for R
* [RJDBC](http://cran.r-project.org/web/packages/RJDBC/) - Provides access to databases through the JDBC interface.
* [rmongodb](https://github.com/mongosoup/rmongodb) - R driver for MongoDB.
* [rredis](http://cran.r-project.org/web/packages/rredis/) - Redis client for R.
* [RCassandra](http://cran.r-project.org/web/packages/RCassandra/index.html) - Direct interface (not Java) to the most basic functionality of Apache Cassanda.
* [RHive](https://github.com/nexr/RHive) -  R extension facilitating distributed computing via Apache Hive.
* [RNeo4j](https://github.com/nicolewhite/Rneo4j) - Neo4j graph database driver. 
* [ibmdbR](https://www.ibm.com/docs/en/db2-warehouse?topic=science-r-development-environment) - Connecting an R development environment to a Db2 database

## Machine Learning
*Packages for making R cleverer.*

* [AnomalyDetection](https://github.com/twitter/AnomalyDetection) - AnomalyDetection R package from Twitter.
* [h2o](http://cran.r-project.org/web/packages/h2o/index.html) - Deep learning, Random forests, GBM, KMeans, PCA, GLM
* [Clever Algorithms For Machine Learning](https://github.com/jbrownlee/CleverAlgorithmsMachineLearning)
* [Machine Learning For Hackers](https://github.com/johnmyleswhite/ML_for_Hackers)
* [rpart](http://cran.r-project.org/web/packages/rpart/index.html) - Recursive Partitioning and Regression Trees
* [randomForest](http://cran.r-project.org/web/packages/randomForest/index.html) - Breiman and Cutler's random forests for classification and regression
* [lasso2](http://cran.r-project.org/web/packages/lasso2/index.html) - L1 constrained estimation aka ‘lasso’
* [gbm](http://cran.r-project.org/web/packages/gbm/index.html) - Generalized Boosted Regression Models
* [e1071](http://cran.r-project.org/web/packages/e1071/index.html) - Misc Functions of the Department of Statistics (e1071), TU Wien
* [tgp](http://cran.r-project.org/web/packages/tgp/index.html) - Bayesian treed Gaussian process models
* [rgp](http://cran.r-project.org/web/packages/rgp/index.html) - R genetic programming framework
* [arules](http://cran.r-project.org/web/packages/arules/index.html) - Mining Association Rules and Frequent Itemsets
* [frbs](http://cran.r-project.org/web/packages/frbs/index.html) - Fuzzy Rule-based Systems for Classification and Regression Tasks
* [rattle](http://cran.r-project.org/web/packages/rattle/index.html) - Graphical user interface for data mining in R
* [ahaz](http://cran.r-project.org/web/packages/ahaz/index.html) - Regularization for semiparametric additive hazards regression
* [arules](http://cran.r-project.org/web/packages/arules/index.html) - Mining Association Rules and Frequent Itemsets
* [bigrf](http://cran.r-project.org/web/packages/bigrf/index.html) - Big Random Forests: Classification and Regression Forests for Large Data Sets
* [bigRR](http://cran.r-project.org/web/packages/bigRR/index.html) - Generalized Ridge Regression (with special advantage for p >> n cases)
* [bmrm](http://cran.r-project.org/web/packages/bmrm/index.html) - Bundle Methods for Regularized Risk Minimization Package
* [Boruta](http://cran.r-project.org/web/packages/Boruta/index.html) - A wrapper algorithm for all-relevant feature selection
* [bst](http://cran.r-project.org/web/packages/bst/index.html) - Gradient Boosting
* [C50](http://cran.r-project.org/web/packages/C50/index.html) - C5.0 Decision Trees and Rule-Based Models
* [caret](http://cran.r-project.org/web/packages/caret/index.html) - Classification and Regression Training
* [CORElearn](http://cran.r-project.org/web/packages/CORElearn/index.html) - Classification, regression, feature evaluation and ordinal evaluation
* [CoxBoost](http://cran.r-project.org/web/packages/CoxBoost/index.html) - Cox models by likelihood based boosting for a single survival endpoint or competing risks
* [Cubist](http://cran.r-project.org/web/packages/Cubist/index.html) - Rule- and Instance-Based Regression Modeling
* [earth](http://cran.r-project.org/web/packages/earth/index.html) - Multivariate Adaptive Regression Spline Models
* [elasticnet](http://cran.r-project.org/web/packages/elasticnet/index.html) - Elastic-Net for Sparse Estimation and Sparse PCA
* [ElemStatLearn](http://cran.r-project.org/web/packages/ElemStatLearn/index.html) - Data sets, functions and examples from the book: "The Elements of Statistical Learning, Data Mining, Inference, and Prediction" by Trevor Hastie, Robert Tibshirani and Jerome Friedman
* [evtree](http://cran.r-project.org/web/packages/evtree/index.html) - Evolutionary Learning of Globally Optimal Trees
* [frbs](http://cran.r-project.org/web/packages/frbs/index.html) - Fuzzy Rule-based Systems for Classification and Regression Tasks
* [GAMBoost](http://cran.r-project.org/web/packages/GAMBoost/index.html) - Generalized linear and additive models by likelihood based boosting
* [gamboostLSS](http://cran.r-project.org/web/packages/gamboostLSS/index.html) - Boosting Methods for GAMLSS
* [gbm](http://cran.r-project.org/web/packages/gbm/index.html) - Generalized Boosted Regression Models
* [glmnet](http://cran.r-project.org/web/packages/glmnet/index.html) - Lasso and elastic-net regularized generalized linear models
* [glmpath](http://cran.r-project.org/web/packages/glmpath/index.html) - L1 Regularization Path for Generalized Linear Models and Cox Proportional Hazards Model
* [GMMBoost](http://cran.r-project.org/web/packages/GMMBoost/index.html) - Likelihood-based Boosting for Generalized mixed models
* [grplasso](http://cran.r-project.org/web/packages/grplasso/index.html) - Fitting user specified models with Group Lasso penalty
* [grpreg](http://cran.r-project.org/web/packages/grpreg/index.html) - Regularization paths for regression models with grouped covariates
* [hda](http://cran.r-project.org/web/packages/hda/index.html) - Heteroscedastic Discriminant Analysis
* [ipred](http://cran.r-project.org/web/packages/ipred/index.html) - Improved Predictors
* [kernlab](http://cran.r-project.org/web/packages/kernlab/index.html) - kernlab: Kernel-based Machine Learning Lab
* [klaR](http://cran.r-project.org/web/packages/klaR/index.html) - Classification and visualization
* [lars](http://cran.r-project.org/web/packages/lars/index.html) - Least Angle Regression, Lasso and Forward Stagewise
* [lasso2](http://cran.r-project.org/web/packages/lasso2/index.html) - L1 constrained estimation aka ‘lasso’
* [LiblineaR](http://cran.r-project.org/web/packages/LiblineaR/index.html) - Linear Predictive Models Based On The Liblinear C/C++ Library
* [LogicReg](http://cran.r-project.org/web/packages/LogicReg/index.html) - Logic Regression
* [maptree](http://cran.r-project.org/web/packages/maptree/index.html) - Mapping, pruning, and graphing tree models
* [mboost](http://cran.r-project.org/web/packages/mboost/index.html) - Model-Based Boosting
* [mvpart](http://cran.r-project.org/web/packages/mvpart/index.html) - Multivariate partitioning
* [ncvreg](http://cran.r-project.org/web/packages/ncvreg/index.html) - Regularization paths for SCAD- and MCP-penalized regression models
* [nnet](http://cran.r-project.org/web/packages/nnet/index.html) - eed-forward Neural Networks and Multinomial Log-Linear Models
* [oblique.tree](http://cran.r-project.org/web/packages/oblique.tree/index.html) - Oblique Trees for Classification Data
* [pamr](http://cran.r-project.org/web/packages/pamr/index.html) - Pam: prediction analysis for microarrays
* [party](http://cran.r-project.org/web/packages/party/index.html) - A Laboratory for Recursive Partytioning
* [partykit](http://cran.r-project.org/web/packages/partykit/index.html) - A Toolkit for Recursive Partytioning
* [penalized](http://cran.r-project.org/web/packages/penalized/index.html) - L1 (lasso and fused lasso) and L2 (ridge) penalized estimation in GLMs and in the Cox model
* [penalizedLDA](http://cran.r-project.org/web/packages/penalizedLDA/index.html) - Penalized classification using Fisher's linear discriminant
* [penalizedSVM](http://cran.r-project.org/web/packages/penalizedSVM/index.html) - Feature Selection SVM using penalty functions
* [quantregForest](http://cran.r-project.org/web/packages/quantregForest/index.html) - quantregForest: Quantile Regression Forests
* [randomForest](http://cran.r-project.org/web/packages/randomForest/index.html) - randomForest: Breiman and Cutler's random forests for classification and regression
* [randomForestSRC](http://cran.r-project.org/web/packages/randomForestSRC/index.html) - randomForestSRC: Random Forests for Survival, Regression and Classification (RF-SRC)
* [rda](http://cran.r-project.org/web/packages/rda/index.html) - Shrunken Centroids Regularized Discriminant Analysis
* [rdetools](http://cran.r-project.org/web/packages/rdetools/index.html) - Relevant Dimension Estimation (RDE) in Feature Spaces
* [REEMtree](http://cran.r-project.org/web/packages/REEMtree/index.html) - Regression Trees with Random Effects for Longitudinal (Panel) Data
* [relaxo](http://cran.r-project.org/web/packages/relaxo/index.html) - Relaxed Lasso
* [rgenoud](http://cran.r-project.org/web/packages/rgenoud/index.html) - R version of GENetic Optimization Using Derivatives
* [rgp](http://cran.r-project.org/web/packages/rgp/index.html) - R genetic programming framework
* [Rmalschains](http://cran.r-project.org/web/packages/Rmalschains/index.html) - Continuous Optimization using Memetic Algorithms with Local Search Chains (MA-LS-Chains) in R
* [rminer](http://cran.r-project.org/web/packages/rminer/index.html) - Simpler use of data mining methods (e.g. NN and SVM) in classification and regression
* [ROCR](http://cran.r-project.org/web/packages/ROCR/index.html) - Visualizing the performance of scoring classifiers
* [RoughSets](http://cran.r-project.org/web/packages/RoughSets/index.html) - Data Analysis Using Rough Set and Fuzzy Rough Set Theories
* [rpart](http://cran.r-project.org/web/packages/rpart/index.html) - Recursive Partitioning and Regression Trees
* [RPMM](http://cran.r-project.org/web/packages/RPMM/index.html) - Recursively Partitioned Mixture Model
* [RSNNS](http://cran.r-project.org/web/packages/RSNNS/index.html) - Neural Networks in R using the Stuttgart Neural Network Simulator (SNNS)
* [sda](http://cran.r-project.org/web/packages/sda/index.html) - Shrinkage Discriminant Analysis and CAT Score Variable Selection
* [SDDA](http://cran.r-project.org/web/packages/SDDA/index.html) - Stepwise Diagonal Discriminant Analysis
* [svmpath](http://cran.r-project.org/web/packages/svmpath/index.html) - svmpath: the SVM Path algorithm
* [tgp](http://cran.r-project.org/web/packages/tgp/index.html) - Bayesian treed Gaussian process models
* [tree](http://cran.r-project.org/web/packages/tree/index.html) - Classification and regression trees
* [varSelRF](http://cran.r-project.org/web/packages/varSelRF/index.html) - Variable selection using random forests
* [xgboost](https://github.com/tqchen/xgboost/tree/master/R-package) - eXtreme Gradient Boosting Tree model, well known for its speed and performance.
* [SuperLearner](https://github.com/ecpolley/SuperLearner) - Prediction model ensembling method
* [subsemble](http://cran.r-project.org/web/packages/subsemble/index.html)- Multi-algorithm ensemble learning packages.
* [Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/)
* [igraph](http://igraph.org/r/)  - A collection of network analysis tools.
* [Keras](https://tensorflow.rstudio.com/guide/keras/)- A high-level neural networks API developed with a focus on enabling fast experimentation for deep learning.

## Statistical modeling
*Packages for statistics and statistical modeling.*
* [tidymodels](https://rviews.rstudio.com/2019/06/19/a-gentle-intro-to-tidymodels/)- This package includes a group of packages to make all the tasks around fitting the model much easier.
* [car](https://cran.r-project.org/web/packages/car/index.html) - ANOVA analysis, matrix and vector transformations, printing readable tables of coefficients from several regression models, creating residual plots, tests for the autocorrelation of error terms, and many other general interest statistical and graphing functions.
* [MASS](https://cran.r-project.org/web/packages/MASS/index.html) - Includes many useful functions and data examples, including functions for estimating linear models through generalized least squares (GLS), fitting negative binomial linear models, the robust fitting of linear models, and Kruskal's non-metric multidimensional scaling.
* [glmnet](https://cran.r-project.org/web/packages/glmnet/index.html) - Contains many extremely efficient procedures in order to fit the entire Lasso or ElasticNet regularization path for linear regression, logistic and multinomial regression models, Poisson regression, and the Cox model.
* [lme4](https://cran.r-project.org/web/packages/lme4/index.html) - Fit linear and generalized linear mixed-effects models.
* [nlme](https://cran.r-project.org/web/packages/nlme/index.html) - Fit and compare Gaussian linear and nonlinear mixed-effects models.
* [multcomp](https://cran.r-project.org/web/packages/multcomp/index.html) - Simultaneous tests and confidence intervals for general linear hypotheses in parametric models, including linear, generalized linear, linear mixed effects, and survival models. 
* [emmeans](https://cran.r-project.org/web/packages/emmeans/index.html) - Obtain estimated marginal means (EMMs) for many linear, generalized linear, and mixed models. Compute contrasts or linear functions of EMMs, trends, and comparisons of slopes.
* [easystats](https://github.com/easystats/easystats) - a collection of R packages, which aims to provide a unifying and consistent framework to tame, discipline, and harness the scary R statistics and their pesky models.
* [DescTools](https://cran.r-project.org/web/packages/DescTools/index.html) - A collection of miscellaneous basic statistic functions and convenience wrappers for efficiently describing data.
* [lmtest](https://cran.r-project.org/web/packages/lmtest/index.html) - A collection of tests, data sets, and examples for diagnostic checking in linear regression models.
* [metan](https://tiagoolivoto.github.io/metan/index.html) - provides useful functions for analyzing multi-environment trial data using parametric and non-parametric methods.

## Bayesian Analysis
*Packages for Bayesian Inference.*

* [coda](http://cran.r-project.org/web/packages/coda/index.html) - Output analysis and diagnostics for MCMC.
* [mcmc](http://cran.r-project.org/web/packages/mcmc/index.html) - Markov Chain Monte Carlo.
* [MCMCpack](http://mcmcpack.berkeley.edu/) - Markov chain Monte Carlo (MCMC) Package.
* [R2WinBUGS](http://cran.r-project.org/web/packages/R2WinBUGS/index.html) - Running WinBUGS and OpenBUGS from R / S-PLUS.
* [BRugs](http://cran.r-project.org/web/packages/BRugs/index.html) - R interface to the OpenBUGS MCMC software.
* [rjags](http://cran.r-project.org/web/packages/rjags/index.html) - R interface to the JAGS MCMC library.
* [rstan](http://mc-stan.org/rstan.html) - R interface to the Stan MCMC software.

## Genetic and Genomic Analysis
*Packages for processing genetic and genomic analysis.*
* [snpReady](https://cran.r-project.org/web/packages/snpReady/vignettes/snpReady-vignette.html) - Preparing Genotypic Datasets in Order to Run Genomic Analysis
* [optiSel](https://cran.r-project.org/web/packages/optiSel/index.html) - Optimum Contribution Selection and Population Genetics
* [nadiv](https://cran.r-project.org/web/packages/nadiv/index.html) - Constructs (non)additive genetic relationship matrices, and their inverses, from a pedigree to be used in linear mixed effect models.
* [synbreed](https://r-forge.r-project.org/R/?group_id=710) - A framework for the analysis of genomic prediction data (Genomic Selection, GWAS, QTL-mapping)
* [BGLR](https://github.com/gdlc/BGLR-R) - An R Package for (Bayesian) High-Dimensional Regression for genomic prediction.
* [SNPRelate](https://www.bioconductor.org/packages/devel/bioc/vignettes/SNPRelate/inst/doc/SNPRelate.html) - Parallel Computing Toolset for Relatedness and Principal Component Analysis of SNP Data
* [ape](http://ape-package.ird.fr/) - Analysis of Phylogenetics and Evolution.
* [adegenet](https://github.com/thibautjombart/adegenet) - R Package for the Multivariate Analysis of Genetic markers
* [pegas](https://github.com/emmanuelparadis/pegas) - Population and Evolutionary Genetics Analysis System.
* [mmod](https://github.com/dwinter/mmod) - an R package for calculating modern population divergence statistics.
* [strataG](https://github.com/EricArcher/strataG) - A toolkit for haploid sequence and multilocus genetic data summaries, and analyses of population structure.
* [hierfstat](https://github.com/jgx65/hierfstat) - Analysis of population structure using genetic markers. It is suitable for both haploid and diploid data.
* [Biostrings](https://bioconductor.org/packages/release/bioc/html/Biostrings.html) - Memory efficient string containers, string matching algorithms, and other utilities, for fast manipulation of large biological sequences or sets of sequences.
* [vispedigree](https://www.r-bloggers.com/2018/11/drawing-an-animal-pedigree-using-the-vispedigree-package/) - Tidying and visualization for animal pedigree.
* [kinship2](https://cran.r-project.org/web/packages/kinship2/) - Package to handle family data with a pedigree object.
* [ggroups](https://cran.r-project.org/web/packages/ggroups/index.html) - Calculates additive and dominance genetic relationship matrices and their inverses, in matrix and tabular-sparse formats.
* [pedigreeTools](https://github.com/Rpedigree/pedigreeTools) - This package offers a suit of functions for pedigree analyses such as sorting and editing pedigree data, computing inbreeding, and additive relationships.
* [lme4GS](https://github.com/perpdgo/lme4GS) - The [lme4GS](https://www.frontiersin.org/articles/10.3389/fgene.2021.680569/full) package focuses on genomic prediction models and can fit LMMs using different variance–covariance matrices.
* [rrBLUP](https://cran.r-project.org/web/packages/rrBLUP/) - Ridge regression and other kernels for genomic selection and genome wide association studies
* [sommer](https://cran.r-project.org/web/packages/sommer/index.html) - Structural multivariate-univariate linear mixed model solver for estimation of multiple random effects with unknown variance-covariance structures, designed for genomic prediction and genome wide association studies.
* [AlphaSimR](https://cran.r-project.org/web/packages/AlphaSimR/index.html) - An R package for breeding program simulations ([paper](https://academic.oup.com/g3journal/article/11/2/jkaa017/6025179))
* [statgenGWAS](https://biometris.github.io/statgenGWAS/articles/GWAS.html) - Prforming single trait Genome Wide Association Studies (GWAS).

## R Development
*Packages for packages.*

* [devtools](https://github.com/hadley/devtools) - Tools to make an R developer's life easier.
* [testthat](https://github.com/hadley/testthat) - An R package to make testing fun.
* [R6](https://github.com/wch/R6) - simpler, faster, lighter-weight alternative to R's built-in classes.
* [pryr](https://github.com/hadley/pryr) -  Make it easier to understand what's going on in R.
* [roxygen](https://github.com/klutometis/roxygen) - Describe your functions in comments next to their definitions.
* [lineprof](https://github.com/hadley/lineprof) - Visualise line profiling results in R.
* [packrat](https://github.com/rstudio/packrat) - Make your R projects more isolated, portable, and reproducible.
* [installr](https://github.com/talgalili/installr/) - Functions for installing softwares from within R (for Windows).
* [Rocker](https://github.com/rocker-org) - R configurations for Docker.

# Resources

Where to discover new R-esources.

## Websites

* [R-project](http://www.r-project.org/) - The R Project for Statistical Computing.
* [R Bloggers](http://www.r-bloggers.com/) - There are people scattered across the Web who blog about R. This is simply an aggregator of many of those feeds.
* [DataCamp](https://www.datacamp.com/) - Learn R data analytics online.
* [Quick-R](http://www.statmethods.net/) - An excellent quick reference.
* [Advanced R](http://adv-r.had.co.nz/) -  An in-progress book site for Advanced R.
* [The R Programming Wikibook](https://en.wikibooks.org/wiki/R_Programming) - A collaborative handbook for R. 
* [R-users](https://www.r-users.com/) - A job board for R users (and the people who are looking to hire them)
* [Analytics for industRy](https://garthtarr.github.io/meatR/index.html) - A workshop introduces R as an efficient tool for data manipulation and visualisation.
* [Statistical Programming in R](https://american-stat-412612.netlify.app/) - Learn the basics of programming using the open source statistical program R, an interactive programming language for data science. 


## Books

* [The Art of R Programming](http://shop.oreilly.com/product/9781593273842.do) -  It's a good resource for systematically learning fundamentals such as types of objects, control statements, variable scope, classes and debugging in R.
* [R in Action](http://www.manning.com/kabacoff2/) - This book aims at all levels of users, with sections for beginning, intermediate and advanced R ranging from "Exploring R data structures" to running regressions and conducting factor analyses.
* [Use R!](http://www.springer.com/series/6991?detailsPage=titles) - This series of inexpensive and focused books from Springer publish shorter books aimed at practitioners. Books can discuss the use of R in a particular subject area, such as bayesian networks, ggplot2 and Rcpp.
* [R for Data Science](https://r4ds.had.co.nz/) - This book will teach you how to do data science with R: You’ll learn how to get your data into R, get it into the most useful structure, transform it, visualise it and model it.
* [Statistics in Natural Resources: Applications with R](https://stats4nr.com/) - Well suited to graduate students enrolled in natural resources, agricultural, and environmental science disciplines.
* [YaRrr! The Pirate’s Guide to R](https://bookdown.org/ndphillips/YaRrr/) - The purpose of this book is to help you learn R from the ground-up.
* [R Markdown Cookbook](https://bookdown.org/yihui/rmarkdown-cookbook/) - This online book is designed to provide on how to extend the functionality of your R Markdown documents.
* [R Markdown: The Definitive Guide](https://bookdown.org/yihui/rmarkdown/) - this online book is intended to be a guide instead of the comprehensive documentation of all topics related to R Markdown.
* [Omic Association Studies with R and Bioconductor](https://isglobal-brge.github.io/book_omic_association/index.html#book-summary) - The aim of the book is to offer a practical guide to researchers, graduate students and those interested in the analysis of omic data.
* [Computational Genomics with R](https://compgenomr.github.io/book/index.html) - The aim of this book is to provide the fundamentals for data analysis for genomics.
* [List of featured online books in R](https://bookdown.org/) - Authoring Books and Technical Documents with R Markdown
* [Mixed Models with R](https://m-clark.github.io/mixed-models-with-R/) - The goal of this book is primarily to provide a sense of when one would use mixed models
* [flextable R package](https://ardata-fr.github.io/flextable-book/index.html) - provides a framework for easily create tables for reporting and publications. 
* [R for applied epidemiology and public health](https://epirhandbook.com/en/index.html)
* [Big Book of R](https://www.bigbookofr.com/index.html) - Bookmark collection for over 300 R-related programming book


## Reference Card

* [R Reference Card 2.0](http://cran.r-project.org/doc/contrib/Baggott-refcard-v2.pdf) - Material from R for Beginners by permission of Emmanuel Paradis (Version 2 by Matt Baggott).
* [Data Mining Refcard](http://www.rdatamining.com/docs/R-refcard-data-mining.pdf) - R Reference Card for Data Mining.
* [Regression Analysis Refcard](http://cran.r-project.org/doc/contrib/Ricci-refcard-regression.pdf) - R Reference Card for Regression Analysis.
* [Reference Card for ESS](http://ess.r-project.org/refcard.pdf) - Reference Card for ESS.
* [R Markdown Cheat sheet](chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf) - Quick reference guide for writing reports with R Markdown.
* [Shiny Cheat sheet](chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://rstudio.github.io/cheatsheets/shiny.pdf) - Quick reference guide for building Shiny apps.
* [Reticulate Cheat sheet](https://raw.githubusercontent.com/rstudio/cheatsheets/main/reticulate.pdf) - Use Python with R with reticulate package.
* [purrr Cheat sheet](https://github.com/rstudio/cheatsheets/blob/main/purrr.pdf) - Provides a complete and consistent set of tools for working with functions and vectors. iteratively. 
* [forcats Cheat sheet](https://raw.githubusercontent.com/rstudio/cheatsheets/main/factors.pdf) - Quick reference guide for working with factors.
* [R colours guide](https://www.nceas.ucsb.edu/sites/default/files/2020-04/colorPaletteCheatsheet.pdf)- Quick reference guide for using colors in R.
* [ggplot2 Cheat sheet](https://www.rstudio.com/wp-content/uploads/2015/03/ggplot2-cheatsheet.pdf) - Quick reference guide for Data visualization. 
* [dplyr Cheat sheet](https://raw.githubusercontent.com/rstudio/cheatsheets/main/data-transformation.pdf) - Quick reference guide for Data transformation. 
* [tidyr Cheat sheet](https://raw.githubusercontent.com/rstudio/cheatsheets/main/tidyr.pdf) - Quick reference guide for tidying data.
* [stringr Cheat sheet](https://raw.githubusercontent.com/rstudio/cheatsheets/main/strings.pdf) - Quick reference guide for string manipulation.
* [lubridate Cheat sheet](https://raw.githubusercontent.com/rstudio/cheatsheets/main/lubridate.pdf) - Quick reference guide for working with Dates and times.
* [RStudio Cheat sheets](https://www.rstudio.com/resources/cheatsheets/) - Provides a set of contributed cheatsheets for R users using favorite packages.

# Other Awesome Lists

* [Coding Club](https://ourcodingclub.github.io/)

