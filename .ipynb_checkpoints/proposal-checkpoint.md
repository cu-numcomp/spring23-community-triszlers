# Community Software Analysis Proposal
Please edit this file and push to your repository.

## Software: Python NumPy on Github

NumPy has a global audience, it is the go-to package for linear algebra/scientific computing in Python. It is centered around the ndarray (n-dimensional array object) which allows the user to perform various math functions on arrays with ease. These include trig, hyberbolic, rounding/sum/product/difference, exponents/logarithm, bitwise, rational, matrix and specific arithmetic functions on arrays. The functions strive to perform at C/C++ speeds with the syntactic simplicity of Python. It is a go-to package for machine learning projects done in Python, when paired with Pandas for graph creation. It also includes tools for integrating C/C++ and Fortran.

Note: Numpy has various repositories on Git (numpy, numpy-tutorials, numpy.org, etc...), I will be observing "numpy/numpy."

### Stats

| Description | "The fundamental package for scientific computing with Python" |
|---------|-----------|
| Repository URL |  https://github.com/numpy/numpy.git  |
| Main/documentation website |  https://numpy.org/doc/stable/user/whatisnumpy.html  |
| Year project was started | 1995  |
| Number of contributors in the past year | `git shortlog -se --since=2022-03-01` 30 contributors after running command |
| Number of contributors in the lifetime of the project | 1,462  |
| Number of distinct affiliations | 1, 2-5, 5-10, >10 |
| Where do development discussions take place? | GitHub/GitLab issues, a changelog tracks all changes made by developers  |
| Typical number of emails/comments per week? | unknown  |
| Typical number of commits per week? | ~12 commits per week |
| Typical commit size | `git log --shortstat` typically 1-2 insertions per commit, sometimes dozens, sometimes over 100 |
| How does the project accept contributions? | e.g., pull requests, patches on mailing lists   |
| Does the project have an automated test suite? | yes |
| Does the project use continuous integration? | yes |
| Are any legal/licensing steps required to contribute? | The license.txt doc does not appear to prohibit contribution, meetings on Slack are open to public |

### Install and run

Check the following boxes when complete or add a note below if you
encountered a problem.

- [Y] I have installed the software
- [Y] I have run at least one example
- [Y] I have run the test suite    
    (run setup.py, run runtests.py)
- [N] The test suite passes    
    fails: no module named 'Cython'
    Cython installation likely required for setup

### Notes/concerns/risks

Please comment on any anomalies or known risks to following this
project, if you were unable to answer any questions above, or
otherwise have concerns about the appropriateness of the software.  If
the project requires a contributor license agreement or other
procedural steps, please explain here.  "None at this time" is
acceptable for this question.

#### Note on copyright
Students retain copyright on any work done in completion of a CU
course, so you are authorized to sign a [contributor license
agreement (CLA)](https://en.wikipedia.org/wiki/Contributor_License_Agreement),
affirm a [developer's certificate of
origin (DCO)](https://en.wikipedia.org/wiki/Developer_Certificate_of_Origin),
etc.  If you have concerns about this, please note them and/or reach
out to Jed directly.
