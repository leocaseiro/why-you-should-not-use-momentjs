### Underscore.date 0.6.1 < 2011

##### 1.8 kb (min + gzip)

```js
_date.add({ M : 1 }) // next month
_date( new Date() ).subtract({ d : 360 }) // 360 days ago
_date( new Date() ).format("dddd, MMMM Do YYYY, h:mm:ss a") // "Thursday, May 9th 2019, 12:25:50 pm"
_date( [2007, 0, 29] ).from( _date([2007, 0, 28] ) ) // a day ago
_date(1316116057189).fromNow() // 13 hours ago

_date(1316116057189).lang('pt').fromNow() // 13 horas atrás

//
```


https://github.com/moment/moment/tree/0.6.1
