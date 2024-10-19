# Call for Papers: Special Issue on "Replications and Negative Results"

## Editors of the Special Issue

Rahul Yedida (LexisNexis, USA) [rahul@ryedida.me](mailto:rahul@ryedida.me)

Tim Menzies (NC State University, USA) [timm@ieee.org](mailto:timm@ieee.org)

<hr/>

The field of software engineering is inherently empirical, and it is not surprising that most research published in premier SE venues (TSE, EMSE, ICSE, FSE, ASE, etc.) are experimental in nature. However, for any such field, it is important that studies be *reproducible*. This Special Issue presents an opportunity for SE researchers to demonstrate the ease (or lack thereof) of replicating prior work. Such prior work must have been peer-reviewed and published in an SE journal, conference, or workshop. Where studies *are* reproducible, we are also interested in their extensibility to other datasets or methods, or some extension of the scope of the original work. Importantly, a paper solely reporting that some prior work's results was reproduced is **not** sufficient. For papers that could *not* be replicated, we are interested in the specific failure that led to the authors concluding that, such as 

* Data or code availability
* Lack of instructions on how to run the code, if it is not obvious (for example, if a repo has a `main.py` file with no explicit instructions to run it, this does not qualify).
* Code errors caused by dependency versions. Such papers must additionally experiment with fixing those versions and document any changes made. For example, a straightforward solution is to use the latest releases at the time of the prior paper's publication.
* Obtaining results that are statistically significantly different, despite repeated, good-faith attempts, such as changing any parameters of the code.

Separately from the above, we also solicit research on *negative results*. Papers falling into this category should *not* be replications of prior work; instead, we seek papers where the authors tried some non-trivial, reasonable method on a problem, where such method did not work. This category of papers has the same scope as the [Insights Workshop at NAACL](https://insights-workshop.github.io/) and the [RENE Workshop at ASE '24](https://conf.researchr.org/track/ase-2024/ase-2024--workshop--rene):

* Broadly applicable empirical recommendations, especially if X that didn't work is something that many practitioners would think reasonable to try, and if the demonstration of X's failure is accompanied by some explanation/hypothesis;
* Ablation studies of components in previously proposed models, showing that their contributions are different from what was initially reported (for example, if a paper reported significant improvements as being due to component X, an ablation study that shows the majority of the improvement being due to component Y);
* Datasets or probing tasks showing that previous approaches do not generalize to other domains;
* Trivial baselines that work suspiciously well for a given task/dataset;
* Experiments on (in)stability of the previously published results due to hardware, random initializations, preprocessing pipeline components, etc., including sensitivity analysis on the identified source of instability;

Finally, we also invite papers demonstrating issues with widely used methodology in the SE literature, such as data collection/preprocessing practices, evaluation metrics (e.g. accuracy, F1), etc. which prevent fair comparison of methods.

Please note that the above list of topics is *not* exhaustive. If you are unsure if your paper falls into the scope of this Special Issue, please contact the guest editors.

## Important Dates

Deadline for submission: May 2, 2025

## Submission Instructions

Papers should be submitted through the Empirical Software Engineering website [http://www.editorialmanager.com/emse/](http://www.editorialmanager.com/emse/). Choose "SI: RENE" as the Article Type.

If you have questions/comments or would like to volunteer to be a reviewer of the papers, please contact the guest editors.
