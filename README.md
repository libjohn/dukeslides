# pkg-test
just a folly to see about making a packge

## Example

foo ipsum ballipsumdeedum


## How To Create a Package & Template

- https://github.com/r-lib/usethis 

- https://www.tidyverse.org/articles/2017/11/usethis-1.0.0/

```
library(usethis)
create_package("TESTslides")
use_mit_license("John Little")
use_package("xaringan", "Imports")
use_roxygen_md()
use_rcpp()
use_revdep()
use_readme_rmd()
use_news_md()
use_test("my-test_whatwhat")
https://rmarkdown.rstudio.com/developer_document_templates.html
```
## Resources

- library(usethis)
- library(devtools)
- library(roxygen2)
- library(xaringan)
- http://usethis.r-lib.org/
- http://usethis.r-lib.org/articles/articles/usethis-setup.html
- https://rawgit.com/jimhester/presentations/master/2018_02_03-You-can-make-a-package-in-20-minutes/2018_02_03-rstudio_conf-You_can_make_a_package_in_20_minutes.html#/section
- https://hilaryparker.com/2014/04/29/writing-an-r-package-from-scratch/
- http://tinyheero.github.io/jekyll/update/2015/07/26/making-your-first-R-package.html
- http://www.masalmon.eu/2017/12/11/goodrpackages/
- http://r-pkgs.had.co.nz/



``` r
install.packages("TESTslides")
```
