Various boosting algorithms in matlab/C,C++.

**All the codes here are provided "AS IS", without any guarantee. Do not try to sue me!**

1. Codes for the paper "_**Positive Semidefinite Metric Learning with Boosting**_", by C. Shen, J. Kim, L, Wang and A. van den Hengel, NIPS 2009. The extended version can be downloaded here http://arxiv.org/abs/0910.2279

PLEASE NOTE:

This package doesn't implement the cross-valiation part.
Same as in AdaBoost; for BoostMetric, you need to determine when to
stop the iteration; and this might have a significant impact on the
final test error and of course, running time.

We found that some papers have used the default value for
``pars.maxiter'' (default 1000) and reported that, BoostMetric has
very poor peformance. This is not very fair for BoostMetric
**You need to cross-validate ``pars.maxiter''!**



Chunhua Shen, 3 May 2011

BibTeX:
```
@inproceedings{Shen2009PSD,
   author    = {Chunhua Shen and Junae Kim and Lei Wang and Anton van den Hengel},
   title     = {Positive semidefinite metric learning with Boosting},
   booktitle = {Advances in Neural Information Processing Systems (NIPS'09)},
   year      = {2009},
   pages     = {1651-1659},
   volume    = {},
   editor    = {Y. Bengio and D. Schuurmans and J. Lafferty and C. Williams and A. Culotta},
   address   = {Vancouver, B.C., Canada},
   month     = {December},
   publisher = {MIT Press},
}
```