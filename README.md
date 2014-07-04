# Pollen

This uses the pollen forecast json API from [Benadryl's Social Pollen Count](https://benadryl.co.uk/social-pollen-count/).

![](http://i.imgur.com/TieN0BP.png)

Whipped up to be used with Arduino and [johnny-five.js](https://github.com/rwaldron/johnny-five) to output to an LCD screen, but this version will just output to your terminal, and does not depend on johnny-five.

Only tested with UK-based latitude/longitude.

Defaults to centre of Oxford if latitude/longitude not provided.

## Usage

``` bash
$ node index.js [latitude] [longitude]
```
