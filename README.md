

<div id="badges"><!-- pkgdown markup -->

<a href="https://github.com/HenrikBengtsson/TopDom/actions?query=workflow%3AR-CMD-check"><img border="0" src="https://github.com/HenrikBengtsson/TopDom/workflows/R-CMD-check/badge.svg?branch=develop" alt="Build status"></a></a>
<a href="https://travis-ci.org/HenrikBengtsson/TopDom"><img border="0" src="https://travis-ci.org/HenrikBengtsson/TopDom.svg" alt="Build status"></a></a>
<a href="https://ci.appveyor.com/project/HenrikBengtsson/topdom"><img border="0" src="https://ci.appveyor.com/api/projects/status/github/HenrikBengtsson/TopDom?svg=true" alt="Build status"></a></a>
<a href="https://codecov.io/gh/HenrikBengtsson/TopDom"><img border="0" src="https://codecov.io/gh/HenrikBengtsson/TopDom/branch/develop/graph/badge.svg" alt="Coverage Status"></a></a>

</div>

# TopDom: An Efficient and Deterministic Method for Identifying Topological Domains in Genomes 

This is an R package that originates from the original TopDom R script by Shin et al. (2016).  This package was put together by Henrik Bengtsson independently of the TopDom authors based on that original TopDom R script and the original TopDom PDF documentation.

The original R script (versions 0.0.1 and 0.0.2) and the TopDom manual were made available on a website of the TopDom author (http://zhoulab.usc.edu/TopDom/).  As of 2019, that website is no longer available.  Instead, TopDom is now listed as a paragraph on <https://labs.dgsom.ucla.edu/zhou/pages/software> with a link to one of the author GitHub repository [jasminezhoulab/TopDom](https://github.com/jasminezhoulab/TopDom), which holds the TopDom manual and version 0.0.2 of the script but no version 0.0.1.

This git repository holds verbatim copies of the two iterations of the original TopDom R script: [TopDom_v0.0.1.R](https://github.com/HenrikBengtsson/TopDom/tree/0.0.1/R/TopDom.R) and [TopDom_v0.0.2.R](https://github.com/HenrikBengtsson/TopDom/tree/0.0.2/R/TopDom.R), as well as the original TopDom documentation [TopDom Manual_v0.0.2.pdf](https://github.com/HenrikBengtsson/TopDom/blob/0.0.2/docs/TopDom%20Manual_v0.0.2.pdf).

The **TopDom** package is licensed under the [GNU Public License (GPL)](https://www.gnu.org/licenses/gpl.html) (per email from XJ Zhou on 2018-11-12).


## Citing TopDom - the method and the package

Whenever using the TopDom method, please cite:

* Hanjun Shin, Yi Shi, Chao Dai, Harianto Tjong, Ke Gong, Frank Alber, Xianghong Jasmine Zhou; TopDom: an efficient and deterministic method for identifying topological domains in genomes, Nucleic Acids Research, Volume 44, Issue 7, 20 April 2016, Pages e70, [10.1093/nar/gkv1505](https://doi.org/10.1093/nar/gkv1505). PMCID: [PMC4838359](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4838359/), PMID: 26704975.

Whenever using the **TopDom** package, please cite:

* Henrik Bengtsson, Hanjun Shin, Harris Lazaris, Gangqing Hu and Xianghong Zhou (2020). R Package TopDom: An Efficient and Deterministic Method for Identifying Topological Domains in Genomes. R package version 0.9.1-9000. https://github.com/HenrikBengtsson/TopDom

The above information is also available as plain text as well as BibTeX entries via `citation("TopDom")`.



[R]: https://www.r-project.org/
[TopDom]: https://github.com/HenrikBengtsson/TopDom/
[TopDomData]: https://github.com/HenrikBengtsson/TopDomData/

## Installation
R package TopDom is only available via [GitHub](https://github.com/HenrikBengtsson/TopDom) and can be installed in R as:
```r
remotes::install_github("HenrikBengtsson/TopDom", ref="master")
```


### Pre-release version

To install the pre-release version that is available in Git branch `develop` on GitHub, use:
```r
remotes::install_github("HenrikBengtsson/TopDom", ref="develop")
```
This will install the package from source.  


<!-- pkgdown-drop-below -->

## Contributing

To contribute to this package, please see [CONTRIBUTING.md](CONTRIBUTING.md).
