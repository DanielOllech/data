# data

The data included in this repository are a non-random sample of the simulated data for the paper published as
Ollech, D., and Webel, K. (2023). A random forest-based approach to combining and ranking seasonality tests. Journal of Econometric Methods, 12(1), 117-130.

They can be loaded in R as follows

NSseries10_4 <- readRDS("NSseries10_4.rds")
series10_2 <- readRDS("series10_2.rds")

The data correspond are simulated from the non-seasonal ARIMA(100) and the seasonal ARIMA(010)(011) model, respectively (see table 2 in the discussion paper version of the aforementioned paper: Ollech, D., & Webel, K. (2020). A random forest-based approach to identifying the most informative seasonality tests)

The full set of data can be obtained at request.
