# Coronavirus Traffic Congestion Impact in Latin America with Waze Data


The Coronavirus Impact Dashboard has been created by me to track in real
time the impact of the coronavirus (also known as COVID-19) on the countries of Latin America
and the Caribbean. The dashboard aims to track a range of variables of interest in order to provide
policymakers, epidemiologists, and the general public in the region with measures of the impact
that “social distancing” restrictions and recommendations due to the coronavirus outbreak are
having on the population and on economic activity.




## Use the data

The data was also though to be used by the broad community of researchers, journalists and developers. If you have any ideas or doubts about using the data, do not hesitate to submit an [issue](https://github.com/EL-BID/IDB-IDB-Invest-Coronavirus-Impacto-Dashboard/issues/new).

But first, make sure you understand the data:
- [Data Dictionary](docs/Data%20Dictionary.md)
- The [Methodological Note](https://iadb-comms.org/COVID19-Impact-Dashboard-Methodological-Note)  will also continuously track and update methodological changes (when necessary) and changes/additions to data sources. The version of the Methodological Note and its date of creation are shown at the top of the document.

The latest version of the data is easily available through the methods below.



### Download Manually

- [daily](https://drive.google.com/file/d/1w7agEtKX54c7pGW5Ua1Q8d0cyZZvFZAM/view?usp=sharing)
- [weekly](https://drive.google.com/file/d/1DGpJAjpGRjKCaIXH6Zg0P7Iq6yPzM8zd/view?usp=sharing)
- [metadata](https://docs.google.com/spreadsheets/d/1PAS6uPwJ3nX-oh-6__-OPO8PXUA87yg_/edit?usp=sharing&ouid=101752774292135053408&rtpof=true&sd=true)

Access the [sheets](http://tiny.cc/idb-traffic-sheets)


### Python

```
import pandas as pd

daily = pd.read_csv('[daily]')
weekly = pd.read_csv('[weekly]')
metadata = pd.read_csv('[metadata]')
```

### R

```
library(readr)

daily<-read_csv('[daily]')
weekly<-read_csv('[weekly]')
metadata<-read_csv('[metadata])
```

### Stata

```
import delimited using "[daily]", clear
import delimited using "[metadata]", clear
import delimited using "[metadata]", clear
```

#team

Aryan Dixit
.
