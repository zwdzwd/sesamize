### `sesamize` convert back and forth from `minfi::RGChannelSet` to `SESAMe::SigDF`

Here we are illustrating using the `FlowSorted.Blood.450k` object, which is 
distributed in the `minfi::RGChannelSet`.

```{r message=FALSE, eval=FALSE}
library(sesame)
library(FlowSorted.Blood.450k)
source("https://github.com/zwdzwd/sesamize/raw/main/sesamize.R")

grSet <- sesamize(FlowSorted.Blood.450k[,1:4])
grSet
```
