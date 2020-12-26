# Power Production Tracker

## 72 Hours Overview

<div id="html" markdown="0">
<div id="day3" markdown="0"></div>

<script type="text/javascript" markdown="0">
  var spec3 = "graph3.json";
  var opt = { actions: {export: true, source: false, compiled: false, editor: false}};
  vegaEmbed('#day3', spec3, opt).then(function(result) {
    // Access the Vega view instance (https://vega.github.io/vega/docs/api/view/) as result.view
  }).catch(console.error);
</script></div>

## 30 Days Overview

<div id="html" markdown="0">
<div id="month1" markdown="0"></div>

<script type="text/javascript" markdown="0">
  var spec30 = "graph30.json";
  vegaEmbed('#month1', spec30, opt).then(function(result) {
    // Access the Vega view instance (https://vega.github.io/vega/docs/api/view/) as result.view
  }).catch(console.error);
</script></div>

### About

Data is scraped from the publicly available sites of the producers - Vattenfall AB ([Forsmark F1, F2, F3](https://group.vattenfall.com/se/var-verksamhet/forsmark) and [Ringhals R3, R4](https://group.vattenfall.com/se/var-verksamhet/ringhals)) and OKG Aktiebolag ([Oskarshamn O3](https://www.okg.se/en)).

&copy; 2021 Gennady Loskutov
