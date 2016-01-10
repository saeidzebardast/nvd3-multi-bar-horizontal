# &lt;nvd3-multi-bar-horizontal&gt; [![Build Status](https://travis-ci.org/saeidzebardast/nvd3-multi-bar-horizontal.svg?branch=master)](https://travis-ci.org/saeidzebardast/nvd3-multi-bar-horizontal)
Multi bar horizontal chart element for [Polymer](https://www.polymer-project.org) using [nvd3](http://nvd3.org/). It's part of [nvd3 charting elements](https://github.com/saeidzebardast/nvd3-elements).

## Install

```
bower install nvd3-multi-bar-horizontal
```

## Usage
### Tag

```
<nvd3-multi-bar-horizontal
    data="[[data]]"
    height="100"
    width="400"
    auto-resize
    show-legend></nvd3-multi-bar-horizontal>
```

### Data Format

```
[{
  "key": "Series1",
  "color": "#d62728",
  "values": [{
    "label": "Group A",
    "value": -1.8746444827653
  }, {
    "label": "Group B",
    "value": -8.0961543492239
  }, {
    "label": "Group C",
    "value": -0.57072943117674
  }]
}, {
  "key": "Series2",
  "color": "#1f77b4",
  "values": [{
    "label": "Group A",
    "value": 25.307646510375
  }, {
    "label": "Group B",
    "value": 16.756779544553
  }, {
    "label": "Group C",
    "value": 18.451534877007
  }]
}]
```

## Demo and Options
See the [component page](http://saeidzebardast.github.io/nvd3-multi-bar-horizontal) for demo and options.

## License
MIT © [Saeid Zebardast](http://zebardast.com)
