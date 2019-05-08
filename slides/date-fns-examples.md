### Date-fns Format Usage

```js
import {
    format, formatDistance, formatRelative, subDays
} from 'date-fns'

format(new Date(), "'Today is a' iiii")
//=> "Today is a Wednesday"

formatDistance(subDays(new Date(), 3), new Date())
//=> "3 days ago"

formatRelative(subDays(new Date(), 3), new Date())
//=> "last Friday at 7:26 p.m."
```
