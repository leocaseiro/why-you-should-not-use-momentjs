### Date-fns Format I18n

```js
import {
    format, formatDistance, formatRelative, subDays
} from 'date-fns'
import { es, ru } from 'date-fns/locale'

formatRelative(subDays(new Date(), 3), new Date())
//=> "last Friday at 7:26 p.m."

formatRelative(subDays(new Date(), 3), new Date(), { locale: es })
//=> "el viernes pasado a las 19:26"

formatRelative(subDays(new Date(), 3), new Date(), { locale: ru })
//=> "в прошлую пятницу в 19:26"
```
