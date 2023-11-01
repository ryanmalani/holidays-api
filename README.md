# Simple Holidays API

[https://inflow-holidays.netlify.app/](https://inflow-holidays.netlify.app/)


## US Holiday Resources

- https://www.federalreserve.gov/aboutthefed/k8.htm

### `parse.js`

Scrapes the federal-reserve website for holiday data, and does some light formatting.


### `filterDates.js`

Return all holidays that are AROUND today, within `N` number of days.

`filterDates(holidays, 'prettyDate', 7)`

Originally created by [Blair Anderson](https://github.com/blairanderson)
