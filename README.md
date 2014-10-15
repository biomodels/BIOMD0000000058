# BIOMD0000000058: Bindschadler_Ca_Oscillator

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000058.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000058.git@20140916`


# Model Notes


The model reproduces the same amplitude antiphase calcium oscillations of
coupled cells depicted in Figure 5B of the publication. This model was
successfully tested on Jarnac and MathSBML. The values of "h1" and "h2" are
not given in the publication, but the antiphase oscillations are reproduced
over a narrow range of values of h1, h2,c1,c2,D and p. The values of D and p
are given, while the other values were plugged in, in order to simulate the
time profiles shown in the Figure. The time t=0 in the figure may have been
fixed after the system was allowed to settle, and hence does not correspond to
the t=0 of the simulation.

  

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not.

  

To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


