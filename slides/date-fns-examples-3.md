### Date-fns Functional Programming composition

```js
import {
    addYears, formatWithOptions, toUpper
} from 'date-fns/fp'
import { pt } from 'date-fns/locale'

const addFiveYears = addYears(5)

const dateToString = formatWithOptions({ locale: pt }, 'D MMMM YYYY')

const dates = [ new Date(2017, 0, 1), new Date(2017, 1, 11), new Date(2017, 6, 2) ]

const toUpper = arg => String(arg).toUpperCase()

const formattedDates = dates.map(addFiveYears)
    .map(dateToString).map(toUpper)
//=> ['1 JANEIRO 2022', '11 FEVEREIRO 2022', '2 JULHO 2022']
```
