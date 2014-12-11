# rangedate

Generate an array of dates

# Install

```bash
npm install rangedate
```

# Usage

```javascript
var rangeDate = require('rangedate');

rangeDate(new Date(2014,11,01), new Date(2014,11,05))
  .map(function(date) {
    return date.getDate();
  });

// [1,2,3,4,5]
```

# Docs

### `rangeDate(startDate, [endDate=Date.now()])`

# License

MIT
