# MODEL8685104549: Pandit2003_VentricularMyocytes

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL8685104549.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL8685104549.git@20140916`

## Usage

Importing the model package.

`import MODEL8685104549 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**A mathematical model of the electrophysiological alterations in rat ventricular myocytes in type-I diabetes.**   
Pandit SV, Giles WR, Demir SS. _Biophys J._ 2003;84(2 Pt 1):832-41.
[12547767](http://www.ncbi.nlm.nih.gov/pubmed/12547767) ,  
**Abstract:**   
Our mathematical model of the rat ventricular myocyte (Pandit et al., 2001)
was utilized to explore the ionic mechanism(s) that underlie the altered
electrophysiological characteristics associated with the short-term model of
streptozotocin-induced, type-I diabetes. The simulations show that the
observed reductions in the Ca(2+)-independent transient outward K(+) current
(I(t)) and the steady-state outward K(+) current (I(ss)), along with slowed
inactivation of the L-type Ca(2+) current (I(CaL)), can result in the
prolongation of the action potential duration, a well-known experimental
finding. In addition, the model demonstrates that the slowed reactivation
kinetics of I(t) in diabetic myocytes can account for the more pronounced
rate-dependent action potential duration prolongation in diabetes, and that a
decrease in the electrogenic Na(+)-K(+) pump current (I(NaK)) results in a
small depolarization in the resting membrane potential (V(rest)). This
depolarization reduces the availability of the Na(+) channels (I(Na)), thereby
resulting in a slower upstroke (dV/dt(max)) of the diabetic action potential.
Additional simulations suggest that a reduction in the magnitude of I(CaL), in
combination with impaired sarcoplasmic reticulum uptake can lead to a
decreased sarcoplasmic reticulum Ca(2+) load. These factors contribute to
characteristic abnormal [Ca(2+)](i) homeostasis (reduced peak systolic value
and rate of decay) in myocytes from diabetic animals. In combination, these
simulation results provide novel information and integrative insights
concerning plausible ionic mechanisms for the observed changes in cardiac
repolarization and excitation-contraction coupling in rat ventricular myocytes
in the setting of streptozotocin-induced, type-I diabetes.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Pandit, Giles, Demir. (2003) - version02**
](http://www.cellml.org/models/pandit_giles_demir_2003_version02)  
The original CellML model was created by:  
**Noble, Penny,**   
penny.noble@dpag.ox.ac.uk  
University of Oxford  

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


