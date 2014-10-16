# BIOMD0000000234: Tham2008_PDmodel_TumourShrinkage

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000234.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000234.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000234 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Tham2008_PDmodel_TumourShrinkage

This model is described in the article:

[A pharmacodynamic model for the time course of tumor shrinkage by gemcitabine
+ carboplatin in non-small cell lung cancer
patients.](http://identifiers.org/pubmed/18594002)

Tham LS, Wang L, Soo RA, Lee SC, Lee HS, Yong WP, Goh BC, Holford NH.

Clin. Cancer Res. 2008 Jul; 14(13): 4213-4218

Abstract:

PURPOSE: This tumor response pharmacodynamic model aims to describe primary
lesion shrinkage in non-small cell lung cancer over time and determine if
concentration-based exposure metrics for gemcitabine or that of its
metabolites, 2',2'-difluorodeoxyuridine or gemcitabine triphosphate, are
better than gemcitabine dose for prediction of individual response.
EXPERIMENTAL DESIGN: Gemcitabine was given thrice weekly on days 1 and 8 in
combination with carboplatin, which was given only on day 1 of every cycle.
Gemcitabine amount in the body and area under the concentration-time curves of
plasma gemcitabine, 2',2'-difluorodeoxyuridine, and intracellular gemcitabine
triphosphate in white cells were compared to determine which best describes
tumor shrinkage over time. Tumor growth kinetics were described using a
Gompertz-like model. RESULTS: The apparent half-life for the effect of
gemcitabine was 7.67 weeks. The tumor turnover time constant was 21.8 week.cm.
Baseline tumor size and gemcitabine amount in the body to attain 50% of tumor
shrinkage were estimated to be 6.66 cm and 10,600 mg. There was no evidence of
relapse during treatment. CONCLUSIONS: Concentration-based exposure metrics
for gemcitabine and its metabolites were no better than gemcitabine amount in
predicting tumor shrinkage in primary lung cancer lesions. Gemcitabine dose-
based models did marginally better than treatment-based models that ignored
doses of drug administered to patients. Modeling tumor shrinkage in primary
lesions can be used to quantify individual sensitivity and response to
antitumor effects of anticancer drugs.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[BIOMD0000000234](http://identifiers.org/biomodels.db/BIOMD0000000234).

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024).

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


