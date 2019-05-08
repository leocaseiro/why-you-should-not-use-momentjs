### Moment.js 2.24.0 (329KB)

```js
moment.add({ M : 1 }) // next month
moment( new Date() ).subtract({ d : 360 }) // 360 days ago
moment( new Date() ).format("dddd, MMMM Do YYYY, h:mm:ss a") // "Thursday, May 9th 2019, 12:25:50 pm"
moment( [2007, 0, 29] ).from( moment([2007, 0, 28] ) ) // a day ago
moment(1316116057189).fromNow() // 13 hours ago

moment(1316116057189).lang('pt').fromNow() // 13 horas atrás
//
```
<small class="fragment fade-up">react.js (57.75 kB)</small><br>
<small class="fragment fade-up">react-dom (692.45 kB)</small>

<small>https://github.com/moment/moment/releases/tag/2.24.0</small>
