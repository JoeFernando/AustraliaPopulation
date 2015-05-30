

Population of Australia as provided by the Australian Bureau of Statistics.
---------------------------------------------------------------------------

* An R package with population data for Australia (for both states and nationally)
* Sourced from Australian Bureau of Statistics: [3105.0.65.001 - Australian Historical Population Statistics, 2014](http://www.abs.gov.au/AUSSTATS/abs@.nsf/DetailsPage/3105.0.65.0012014?OpenDocument)
* License: MIT

Contains 3 datasets corresponding to Tables in the above document:

1. `population`: End-of-year population by state and nationally from 1788 to 2010 onward. Corresponds to `Table 1.1 Population by sex, states and territories, 31 December, 1788 onwards`
2. `population.recent`: Mid-year population by state and nationally. Corresponds to `Table 1.2 Population by sex, states and territories, 30 June, 1901 onwards`
3. `population.change`: Births, deaths, interstate and international migration. Corresponds to `Table 1.3 Population and components of change (no.), states and territories, year ended 30 June, 1971 onwards`

Install directly from github with:
```{r}
`devtools::install_github("coolbutuseless/AustraliaPopulation")`
```