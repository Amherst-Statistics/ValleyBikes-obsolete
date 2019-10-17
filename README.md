# ValleyBikes

This package contains route and station data for the Valley Bike service.

## Installation

```R
# Install the development version from Github
devtools::install_github("Amherst-Statistics/ValleyBikes")
```

For more information on Valley Bike visit: https://valleybike.org/

## Example

    library(ValleyBikes)
    library(dplyr)

    glimpse(stations)

    ## Observations: 54
    ## Variables: 6
    ## $ Serial_Num   <dbl> 19, 50, 17, 22, 23, 13, 30, 603, 45, 35, 2, 43, 48,…
    ## $ Address      <chr> "330 Homestead Avenue Holyoke Community College", "…
    ## $ Station_Name <chr> "Holyoke Community College", "Congress Street", "So…
    ## $ Num_Docks    <int> 16, 10, 15, 17, 13, 4, 16, 10, 9, 14, 16, 10, 20, 1…
    ## $ Latitude     <dbl> 42.19513, 42.10925, 42.19757, 42.32858, 42.31672, 4…
    ## $ Longitude    <dbl> -72.65270, -72.59456, -72.60377, -72.64394, -72.635…

    glimpse(routes)

    ## Observations: 189,419
    ## Variables: 6
    ## $ route_id  <chr> "route_06_2018@dd896500-39aa-4e4f-8f48-1c368afb3ca6", …
    ## $ bike      <chr> "924", "924", "984", "984", "935", "935", "965", "965"…
    ## $ date      <chr> "2018-06-28 14:09:32+00", "2018-06-28 17:33:57+00", "2…
    ## $ latitude  <dbl> 42.31419, 42.31415, 42.31752, 42.32057, 42.31745, 42.3…
    ## $ longitude <dbl> -72.64003, -72.64034, -72.63335, -72.62835, -72.63348,…
    ## $ user_id   <chr> "1cc1e858-857a-4f80-96e8-974f0e920620", "1cc1e858-857a…


