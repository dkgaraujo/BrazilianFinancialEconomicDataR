# Introduction

This is a collection of R packages that facilitate download and use of Brazilian financial and economic data. 

These packages help users by: (a) providing a more convenient browsing of datasets, and (b) facilitating the download and use of the selected datasets. This helps overcome issues that may arise from accessing the data directly from their APIs, such as having to transform each dataset from its native format into an R-friendly format (not to mention the native formats probably vary from one dataset to the other).

The goal of this compilation is to be a one-stop-shop for R users interested in Brazilian financial and economic datasets. Even if you know some of these packages, this list might help you know other packages that could be useful to you.

This list is a best-efforts compilaton, therefore it may be neither comprehensive nor necessarily up-to-date. Please feel free to contribute with updates, corrections or information about new packages that help users access Brazilian financial and economic data by creating a [pull request](https://github.com/dkgaraujo/BrazilianFinancialEconomicDataR/pulls). If you notice any issue with this compilation or if you have any ideas for features that could be added with a reasonable amount of effort, please create a [new issue](https://github.com/dkgaraujo/BrazilianFinancialEconomicDataR/issues).

Please note there are no liabilities for the maintainers or colaborators of this repository from any problems that may arise due to the use of data downloaded from those packages.

# Brazilian Financial and Economic Data in R

Please note the packages below are organised by alphabetical order of their short name.

| Package | Title | Description | CRAN page | Source code |
|---|---|---|---|---|
| BETS | Brazilian Economic Time Series | It provides access to and information about the most important Brazilian economic time series - from the [Getulio Vargas Foundation](http://portal.fgv.br/en), the [Central Bank of Brazil](http://www.bcb.gov.br) and the [Brazilian Institute of Geography and Statistics](http://www.ibge.gov.br). It also presents tools for managing, analysing (e.g. generating dynamic reports with a complete analysis of a series) and exporting these time series. | [link](https://cran.r-project.org/web/packages/BETS/index.html)  |  [link](https://github.com/nmecsys/BETS) |
| GetBCBData | Imports Datasets from BCB (Central Bank of Brazil) using Its Official API | Downloads and organizes datasets using BCB's API ([https://www.bcb.gov.br/](https://www.bcb.gov.br/)). Offers options for caching with the 'memoise' package and , multicore/multisession with 'furrr' and format of output data (long/wide). | [link](https://cran.r-project.org/web/packages/GetBCBData/index.html) | [link](https://github.com/msperlin/GetBCBData/) |
| meedr | Macroeconomic Expectations Data in R using the Central Bank of Brazil API | Provides quick and easy access to market expectations data to the main macroeconomic indicators in the Focus report, made available by the Central Bank of Brazil through the Expectations System [data API](https://dadosabertos.bcb.gov.br/). This package offers an R interface to the API and other advantages, such as using a caching system and the option to use all the machine's cores (parallel computing). | [link]() | [link](https://github.com/schoulten/meedr) |
| rbcb | R interface to Brazilian Central Bank web services | An interface to structure the information provided by the Brazilian Central Bank. This package interfaces the Brazilian Central Bank web services to provide data already formatted into R's data structures and download currency data from Brazilian Centra Bank web site. | N/A | [link](https://github.com/wilsonfreitas/rbcb) |
| siconfir | Quick and Easy Access Tax and Accounting Data of Brazil | Access tax and accounting data of Brazilian states and municipalities provided by the Brazilian Public Sector Accounting and Tax Information System. | [link](https://cran.r-project.org/web/packages/siconfir/index.html) | [link](https://github.com/aspeddro/siconfir) |
| siconfiBD | siconfiBD | Public financial data from Brazillian municipalities | - | [link](https://github.com/tchiluanda/siconfiBD) |
