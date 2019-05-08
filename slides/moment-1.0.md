### Moment.js 1.0.1 (Oct 2011)

##### 2.2 kb (min + gzip)

```js
moment.add({ M : 1 }) // next month
moment( new Date() ).subtract({ d : 360 }) // 360 days ago
moment( new Date() ).format("dddd, MMMM Do YYYY, h:mm:ss a") // "Thursday, May 9th 2019, 12:25:50 pm"
moment( [2007, 0, 29] ).from( moment([2007, 0, 28] ) ) // a day ago
moment(1316116057189).fromNow() // 13 hours ago

moment(1316116057189).lang('pt').fromNow() // 13 horas atrás

//
```


<small>https://github.com/moment/moment/tree/1.0.1</small>
