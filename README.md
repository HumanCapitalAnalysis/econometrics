# Econometrics of Human Capital

> Intermediate between mathematics, statistics, and economics, we find a new discipline which for lack of a better name, may be called econometrics. Econometrics has as its aim to subject abstract laws of theoretical political economy or 'pure' economics to experimental and numerical verification, and thus to turn pure economics, as far as possible, into a science in the strict sense of the word. (Frisch, 1926)

We study the econometrics of human capital analysis. We frame the discussion around the generalized Roy model (Roy, 1951; Heckman and Vytlacil, 2005) which provides a coherent framework to explore the econometrics of policy evaluation. We discuss alternative objects of interest such as the individual-specific, average, distributional, and marginal effects of treatment and the policy-questions they address. We contrast the economic assumptions behind alternative estimation strategies such as (quasi-)experimental methods, ordinary least squares, matching, (local) instrumental variables, regression discontinuity designs.

We will use [grmpy](https://grmpy.readthedocs.io) in several hand-on tutorials to explore the mechanics of the generalized Roy model. For further information, please do not hesitate to [contact us](https://hca.zulipchat.com/join/84tlhl1nmm4fke4dpg5mo74u/).

**Key References**

*  Heckman, J. J., and Vytlacil, E. J. (2007a). [Econometric evaluation of social programs, part I: Causal effects, structural models and econometric policy evaluation.](http://econ.ucsb.edu/~doug/245a/Papers/Econometric%20Evaluation%20Social%20Programs.pdf) In J. J. Heckman, and E. E. Leamer (Eds.), *Handbook of Econometrics* (Vol. 6B, pp. 4779–4874). Elsevier Science, Amsterdam, Netherlands.

* Heckman, J. J., and Vytlacil, E. J. (2007b). [Econometric evaluation of social programs, part II: Using the marginal treatment effect to organize alternative economic estimators to evaluate social programs and to forecast their effects in new environments.](https://www.sciencedirect.com/science/article/pii/S1573441207060710) In J. J. Heckman, and E. E. Leamer (Eds.), *Handbook of Econometrics* (Vol. 6B, pp. 4875–5144). Elsevier Science, Amsterdam, Netherlands.

* Abbring, J., and Heckman, J. J. (2007). [Econometric evaluation of social programs, part III: Distributional treatment effects, dynamic treatment effects, dynamic discrete choice, and general equilibrium policy evaluation.](https://www.sciencedirect.com/science/article/pii/S1573441207060722) In J. J. Heckman, and E. E. Leamer (Eds.), *Handbook of Econometrics* (Vol. 6B, pp. 5145–5303). Elsevier Science, Amsterdam, Netherlands.

The manuscript [Issues in the Econometrics of Policy Evaluation](https://github.com/HumanCapitalAnalysis/policy-evaluation/blob/master/distribution/Eisenhauer_2012.pdf) provides an accessible introduction to the material in the context of the returns to college.

Please use the table of content to navigate the rest of the material.

1. [Lectures](#lectures)
2. [Additional Resources](#additional_resources)
3. [Frequently Asked Questions](#faq)
4. [References](#references)
5. [Iterations](#iterations)

***
## Lectures <a name="lectures"></a>

You can access each individual lecture by simply clicking at their respective title. All lectures are also available for download as a single file [here](https://github.com/HumanCapitalAnalysis/policy-evaluation/blob/master/distribution/course_deck.pdf).

#### [Introduction to the Econometrics of Policy Evaluation](https://github.com/HumanCapitalAnalysis/policy-evaluation/blob/master/distribution/01_intro_policy_metrics.pdf)

We provide a brief introduction to the econometrics of policy evaluation. We discuss the evaluation tasks, preview the discussion about parameters of interest, and alternative estimation strategies.

#### [Generalized Roy Model](https://github.com/HumanCapitalAnalysis/policy-evaluation/blob/master/distribution/02_generalized_roy_model.pdf)

We introduce the generalized Roy model, which provides the conceptual framework for the whole course.

#### [Parameters of Interest](https://github.com/HumanCapitalAnalysis/policy-evaluation/blob/master/distribution/03_parameters_interest.pdf)

We discuss alternative parameters of interest and clarify the policy questions they address.

#### [Estimation Strategies](https://github.com/HumanCapitalAnalysis/policy-evaluation/blob/master/distribution/04_estimation_strategies.pdf)

We explore alternative estimation strategies with a focus on the underlying economic assumptions about information available to the individual and econometrician.

#### [*grmpy* Tutorial](https://github.com/OpenSourceEconomics/grmpy/blob/develop/promotion/04_grmpy_tutorial/main.pdf)

We explore the capabilities of the *grmpy* package. The accompanying notebook is available [here](https://github.com/OpenSourceEconomics/grmpy/blob/develop/promotion/04_grmpy_tutorial_notebook/04_grmpy_tutorial_notebook.ipynb).

#### [Monte Carlo Exploration](https://github.com/HumanCapitalAnalysis/policy-evaluation/blob/master/distribution/06_monte_carlo_exploration.pdf)

We revisit our discussion about the issues in the econometrics of policy evaluation, alternative parameters of interest, and estimation strategies in a variety of Monte Carlo exercises. The accompanying notebook is available [here](http://nbviewer.jupyter.org/github/HumanCapitalAnalysis/policy-evaluation/blob/master/lectures/material/06_monte_carlo_exploration/lecture.ipynb).

## Additional Resources <a name="additional_resources"></a>

We provide some additional references that discuss selected issues in more detail.

### Overviews <a name="overviews"></a>

* Blundell, R., and Costa Dias, M. (2009). [Alternative approaches to evaluation in empirical microeconomics.](http://jhr.uwpress.org/content/44/3/565.full.pdf) *Journal of Human Resources, 44*(3), 565-640.

* Heckman, J. J. (2001). [Micro data, heterogeneity, and the evaluation of public policy: Nobel lecture.](http://www.jstor.org/stable/10.1086/322086) *Journal of Political Economy, 109*(4), 673-748.

* Imbens, G. W., and Wooldridge, J. M. (2009). [Recent developments in the econometrics of program  evaluation.](http://www.jstor.org/stable/pdf/27647134.pdf?refreqid=excelsior%3Ad0849f5f5ace327f62d6275ec81b16d0) *Journal of Economic Literature, 47*(1), 5-86.

* Heckman, J. J. (2000). [Causal parameters and policy analysis in economics: A twentieth century
retrospective.](https://www.jstor.org/stable/2586935) *The Quarterly Journal of Economics, 115*(1), 45-97.

* DiNardo, J., and Lee, D. S. (2011). [Program evaluation and research designs.](http://www.sciencedirect.com/science/article/pii/S0169721811004114) *Handbook of Labor Economics, 4*, 463-536

### Instrumental Variables

* Heckman, J. J., Urzua, S., and Vytlacil, E. J. (2006).
[Understanding instrumental variables in models with essential heterogeneity.](http://www.mitpressjournals.org/doi/pdfplus/10.1162/rest.88.3.389?v=1392752313000/_/jcr:system/jcr:versionStorage/82/42/bb/8242bb30-bb82-447a-a9d3-643bb66de830/1.8/jcr:frozenNode) *The Review of Economics and Statistics, 88*(3), 389-432.

* Heckman, J. J. (1997). [Instrumental variables: A study of implicit behavioral assumptions used in making program evaluations.](https://www.jstor.org/stable/146178?seq=1#page_scan_tab_contents) *The Journal of Human Resources, 32*(3), 441-462.



### Matching

* Heckman, J. J., Ichimura, H., and Todd, P. E. (1997). [Matching as an econometric evaluation estimator: Evidence from evaluating a job training programme.](https://www.jstor.org/stable/2971733?seq=1#page_scan_tab_contents) *The Review of Economic Studies*, 64*(4), 605-654.

* Heckman, J. J., and Navarro-Lozano, S. (2004). [Using matching, instrumental variables, and control functions to estimate economic choice models.](http://www.jstor.org/stable/3211658) *The Review of Economics and Statistics, 86*(1), 30-57.

* Rubin, D. (1973), [Matching to remove bias in observational studies.](https://www.jstor.org/stable/2529684?seq=1#page_scan_tab_contents) *Biometrics, 29*(1), 159-183.

### Experiments

* Burtless, G. (1995). [The case for randomized field trials in economic and policy research.](https://www.aeaweb.org/articles?id=10.1257/jep.9.2.63) *Journal of Economic Perspectives, 9*(2), 63-84.

* Heckman, J. J., and Smith, J. A. (1995). [Assessing the case for social experiments.](https://www.aeaweb.org/articles?id=10.1257/jep.9.2.85) *Journal of Economic Perspectives, 9*(2), 85-110.

* Banerjee, A., Banerji, R., Berry, J., Duflo, E., Kannan, H., Mukerji, S., Shotland, M., and Walton, M. (2017). [From proof of concept to scalable policies: Challenges and solutions, with an application.](https://www.aeaweb.org/articles?id=10.1257/jep.31.4.73) *Journal of Economic Perspectives, 31*(4), 73-102.

### Regression Discontinuity Design

* Hahn, J., Todd, P. E., and Van der Klaauw, W. (2001). [Identification and estimation of treatment effects with a regression-discontinuity design.](https://www.jstor.org/stable/2692190) *Econometrica, 69*(1), 201-209.

* Imbens, G. W., and Lemieux, T. (2008). [Regression discontinuity designs: A guide to practice.](http://www.sciencedirect.com/science/article/pii/S0304407607001091) *Journal of Econometrics, 142*(2), 615-635.

## Frequently Asked Questions <a name="faq"></a>

We collect the answer to frequently asked questions below.

* **Are there any prerequisites?**

We will not cover each estimation method in detail and instead focus on the relationships between them. Thus a basic familiarity with applied economic research and its methods is required. Also, we use numerous online collaboration tools throughout the course such as [GitHub](https://github.com), [Gitter](https://gitter.im) and thus a willingness to adopt these tools is necessary. A basic knowledge of [Python](https://www.python.org) and the [Jupyter Notebook](http://jupyter.org/) is helpful for the tutorials. The [Scipy Lecture Notes](http://www.scipy-lectures.org/) provide an excellent introduction to both. The manuscript [Introduction to Python for econometrics, statistics and data analysis](https://www.kevinsheppard.com/files/teaching/python/notes/python_introduction_2019.pdf) focuses on the use of [Python](https://www.python.org) for  econometrics and data analysis.

* **What are helpful resources to improve my presentation and writing skills?**

We found the following references useful:

- Strunk, W., and White, E. B. (2000). [The elements of style.](https://books.google.de/books?id=MhTEmgEACAAJ&dq=the+elements+of+style+2000&hl=de&sa=X&ved=0ahUKEwjXhoeJtZjXAhVFlxoKHfu-DakQ6AEIKjAA) Longman, New York, NY. 
- Wallwork, A. (2016). [English for writing research papers.](https://books.google.de/books?id=a0-vCwAAQBAJ&hl=de&source=gbs_book_other_versions) Springer International Publishing, Basel, Switzerland. 
- Wallwork A. (2016). [English for presentations at international conferences.](https://books.google.de/books?id=ntKwCwAAQBAJ&dq=English+for+presentations+at+international+conferences&hl=de&source=gbs_navlinks_s) Springer International Publishing, Basel, Switzerland.
- Booth, W. C., Colomb, G. G., Williams, J. M., Bizup, J., and FitzGerald, W. T. (2016). [The craft of research.](https://books.google.de/books?id=SjPqDAAAQBAJ&dq=The%20Craft%20of%20Research&hl=de&source=gbs_book_other_versions) University of Chicago Press., Chicago, IL.
- Adler, M. J., and Van Doren, C. (2011). [How to read a book.](https://books.google.de/books/about/How_to_Read_a_Book.html?id=Z5PpkQadm5EC&redir_esc=y) Touchstone, New York, NY.
- Clark, R. P. (2006). [Writing tools: 50 essential strategies for every writer](https://www.amazon.com/Writing-Tools-Essential-Strategies-Writer/dp/0316014990). Little, Brown, and Co.,  New York.
- King, S. (2000). [On writing: A memoir of the craft](https://www.amazon.de/Writing-Memoir-Craft-Stephen-King/dp/1439156816). Scribner,  New York.
- McCloskey, D. N. (2000). [Economical writing](https://www.amazon.com/Economical-Writing-Deirdre-McCloskey/dp/1577660633). Waveland Press, Long Grove, IL.


## References <a name="references"></a>

* Heckman, J. J., and Vytlacil, E. J. (2005). [Structural equations, treatment effects, and
econometric policy evaluation.](http://www.jstor.org/stable/pdf/3598865.pdf?refreqid=excelsior%3Ae813a7ff3994cedb4ed08cbaad44cd7a) *Econometrica, 73*(3), 669–739.

* Frisch, R. (1926). On a problem in pure economics: Translated by JS Chipman. *Preferences, Utility, and Demand: A Minnesota Symposium*.

* Roy, A. D. (1951). [Some thoughts on the distribution of earnings.](http://www.jstor.org/stable/pdf/2662082.pdf?refreqid=excelsior%3A39f3e3e019e3b93098b829785bbd6293) *Oxford Economic Papers,
3*(2), 135–146.

## Iterations <a name="iterations"></a>

* **Winter Quarter 2018**, Graduate Program at the University of Bonn, please see [here](https://github.com/HumanCapitalAnalysis/policy-evaluation/blob/master/iterations/bonn_ws_2018/README.md) for details.

* **Winter Quarter 2017**, Graduate Program at the University of Bonn, please see [here](https://github.com/HumanCapitalAnalysis/policy-evaluation/blob/master/iterations/bonn_ws_2017/README.md) for details.

[![Build Status](https://travis-ci.org/HumanCapitalAnalysis/policy-evaluation.svg?branch=master)](https://travis-ci.org/HumanCapitalAnalysis/policy-evaluation)
