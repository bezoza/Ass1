Random sample of 2002 New York City Marathon finishers
========================================================
author: Jose Eusebio Oliva


Description, Usage,  Format
========================================================

- Description
A random sample of finishers from the New York City Marathon.

- Usage
 data(nym.2002)
- Format
A data frame with 1000 observations on the following 5 variables.

  place: Place in the race
  gender: What gender
  age: Age on day of race
  home: Indicator of hometown or nation
  time: Time in minutes to finish
  
Details, Source
========================================================

- Details
Each year thousands of particpants line up to run the New York City Marathon. This list is a random
sample from the finishers.

- Source
From the New York City Road Runners web site http://www.nyrrc.org

Examples
========================================================


```r
library(UsingR)
data(nym.2002)
with(nym.2002, cor(time,age))
```

```
[1] 0.1899
```

Plot Examples
========================================================

![plot of chunk unnamed-chunk-2](Slide-figure/unnamed-chunk-2.png) 
