### `sesamize` convert back and forth from `minfi::RGChannelSet` to `SESAMe::SigDF`

Here we are illustrating using the `FlowSorted.Blood.450k` object, which is 
distributed in the `minfi::RGChannelSet`.
```{r message=FALSE, eval=FALSE}
library(sesame)
source("")
library(FlowSorted.Blood.450k)
options(rmarkdown.html_vignette.check_title = FALSE)
```

```{r eval=FALSE}
grSet <- sesamize(FlowSorted.Blood.450k[,1:4])
grSet
```
