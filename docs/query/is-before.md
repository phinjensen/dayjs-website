---
id: is-before
title: Is Before
---

This indicates whether the Day.js object is before the other supplied date-time.

```js
dayjs().isBefore(dayjs('2011-01-01')) // default milliseconds
```
If you want to limit the granularity to a unit other than milliseconds, pass it as the second parameter.

```js
dayjs().isBefore('2011-01-01', 'year')
```

Units are case insensitive, and support plural and short forms.

[List of all available units](../get-set/get#list-of-all-available-units)