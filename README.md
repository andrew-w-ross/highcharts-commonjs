# Highcharts Wrapper for CommonJS

Forked and added HighStock charts support

### Example Usage
```javascript
'use strict';
var Highcharts = require('highcharts-commonjs');

var someDOMDiv = ...;

// create chart
var chart = Highcharts.createChart(
  // dom element to inject the chart
  someDOMDiv,
  // highcharts options
  {
    title: {
      text: 'My chart'
    },
  ...
  },
  // callback, called when initialization of chart is done
  function() {
    console.log('Chart initialized');
  }
);

...

// destroy chart
Highcharts.destroy(chart);

```
