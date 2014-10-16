# MODEL1011080001: 

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1011080001.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1011080001.git@20140916`

## Usage

Importing the model package.

`import MODEL1011080001 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This is metabolic network reconstruction of _Natronomonas pharaonis_ described
in the article  
**Characterization of growth and metabolism of the haloalkaliphile Natronomonas pharaonis.**   
Gonzalez O, Oberwinkler T, Mansueto L, Pfeiffer F, Mendoza E, Zimmer R,
Oesterhelt D. _PLoS Comput Biol._ 2010 Jun 3;6(6):e1000799. PMID:
[20543878](http://www.ncbi.nlm.nih.gov/pubmed/20543878) , DOI: [e1000799.
doi:10.1371/journal.pcbi.1000799](http://dx.doi.org/e1000799.
doi:10.1371/journal.pcbi.1000799)

Abstract:  
Natronomonas pharaonis is an archaeon adapted to two extreme conditions: high
salt concentration and alkaline pH. It has become one of the model organisms
for the study of extremophilic life. Here, we present a genome-scale, manually
curated metabolic reconstruction for the microorganism. The reconstruction
itself represents a knowledge base of the haloalkaliphile's metabolism and, as
such, would greatly assist further investigations on archaeal pathways. In
addition, we experimentally determined several parameters relevant to growth,
including a characterization of the biomass composition and a quantification
of carbon and oxygen consumption. Using the metabolic reconstruction and the
experimental data, we formulated a constraints-based model which we used to
analyze the behavior of the archaeon when grown on a single carbon source.
Results of the analysis include the finding that Natronomonas pharaonis, when
grown aerobically on acetate, uses a carbon to oxygen consumption ratio that
is theoretically near-optimal with respect to growth and energy production.
This supports the hypothesis that, under simple conditions, the microorganism
optimizes its metabolism with respect to the two objectives. We also found
that the archaeon has a very low carbon efficiency of only about 35%. This
inefficiency is probably due to a very low P/O ratio as well as to the other
difficulties posed by its extreme environment.

This model was downloaded from the supplemetary materials to the article. To
make this file valid SBML, some minor changes had to be done. The reaction
Test_sink and empty lists were removed.

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


