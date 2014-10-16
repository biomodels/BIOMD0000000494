# BIOMD0000000494: MODEL1311220000

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000494.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000494.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000494 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Roblitz2013 - Menstrual Cycle following GnRH analogue administration

The model describes the menstrual cycle feedback mechanisms. GnRH, FSH, LH,
E2, P4, inbibins A and B, and follicular development are modelled. The model
predicts hormonal changes following GnRH analogue administration. Simulation
results agree with measurements of hormone blood concentrations. The model
gives insight into mechanisms underlying gonadotropin supression.

This model is described in the article:

[A mathematical model of the human menstrual cycle for the administration of
GnRH analogues.](http://identifiers.org/pubmed/23206386)

Röblitz S, Stötzel C, Deuflhard P, Jones HM, Azulay DO, van der Graaf PH,
Martin SW.

J. Theor. Biol. 2013 Mar; 321: 8-27

Abstract:

The paper presents a differential equation model for the feedback mechanisms
between gonadotropin-releasing hormone (GnRH), follicle-stimulating hormone
(FSH), luteinizing hormone (LH), development of follicles and corpus luteum,
and the production of estradiol (E2), progesterone (P4), inhibin A (IhA), and
inhibin B (IhB) during the female menstrual cycle. Compared to earlier human
cycle models, there are three important differences: The model presented here
(a) does not involve any delay equations, (b) is based on a deterministic
modeling of the GnRH pulse pattern, and (c) contains less differential
equations and less parameters. These differences allow for a faster simulation
and parameter identification. The focus is on modeling GnRH-receptor binding,
in particular, by inclusion of a pharmacokinetic/pharmacodynamic (PK/PD) model
for a GnRH agonist, Nafarelin, and a GnRH antagonist, Cetrorelix, into the
menstrual cycle model. The final mathematical model describes the hormone
profiles (LH, FSH, P4, E2) throughout the menstrual cycle of 12 healthy women.
It correctly predicts hormonal changes following single and multiple dose
administration of Nafarelin or Cetrorelix at different stages in the cycle.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[BIOMD0000000494](http://identifiers.org/biomodels.db/BIOMD0000000494) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


