# Charts.use
apexcharts liberary for using charts in your web project using vanilla javascript or frontend framework or library.
## Installation
to install this package in your project via npm:
```bash
npm install apexcharts
```

## To use directly using CDN
``` html
<script src="https://cdn.jsdelivr.net/npm/apexcharts"></script> <!-- html body -->
```

## Usage
```js
import ApexCharts from 'apexcharts'
```

after loading all files. you are ready to build your first chart. To create a chart with minimal configuration, write as follows:
``` js
var options = {
  chart: {
    type: 'line'
  },
  series: [{
    name: 'sales',
    data: [30,40,35,50,49,60,70,91,125]
  }],
  xaxis: {
    categories: [1991,1992,1993,1994,1995,1996,1997, 1998,1999]
  }
}

var chart = new ApexCharts(document.querySelector("#chart"), options);

chart.render();
```
## For help
you can easily use [apexGPT](https://apexcharts.com/apexgpt/) for help.
## For more
you can see: [apexcharts.com](https://apexcharts.com/)