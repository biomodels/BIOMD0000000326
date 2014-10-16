# BIOMD0000000326: DellOrco2009_phototransduction

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000326.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000326.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000326 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
** Network-level analysis of light adaptation in rod cells under normal and altered conditions. **   
Dell'Orco D, Schmidt H, Mariani S, Fanelli F _Mol Biosyst_2009 Oct;
5(10):1232-46 [19756313](http://www.ncbi.nlm.nih.gov/pubmed/19756313),  
**Abstract:**   
Photoreceptor cells finely adjust their sensitivity and electrical response
according to changes in light stimuli as a direct consequence of the feedback
and regulation mechanisms in the phototransduction cascade. In this study, we
employed a systems biology approach to develop a dynamic model of vertebrate
rod phototransduction that accounts for the details of the underlying
biochemistry. Following a bottom-up strategy, we first reproduced the results
of a robust model developed by Hamer et al. (Vis. Neurosci., 2005, 22(4),
417), and then added a number of additional cascade reactions including: (a)
explicit reactions to simulate the interaction between the activated effector
and the regulator of G-protein signalling (RGS); (b) a reaction for the
reformation of the G-protein from separate subunits; (c) a reaction for
rhodopsin (R) reconstitution from the association of the opsin apoprotein with
the 11-cis-retinal chromophore; (d) reactions for the slow activation of the
cascade by opsin. The extended network structure successfully reproduced a
number of experimental conditions that were inaccessible to prior models. With
a single set of parameters the model was able to predict qualitative and
quantitative features of rod photoresponses to light stimuli ranging over five
orders of magnitude, in normal and altered conditions, including genetic
manipulations of the cascade components. In particular, the model reproduced
the salient dynamic features of the rod from Rpe65(-/-) animals, a well
established model for Leber congenital amaurosis and vitamin A deficiency. The
results of this study suggest that a systems-level approach can help to
unravel the adaptation mechanisms in normal and in disease-associated
conditions on a molecular basis.

  

**Note:**

Figure 7 of the reference is reproduced here. Each plot is obtained by
increasing flash strength. More details about generating the plots can be
obtained from the comments in the curation figure (go to curation tab).

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html).  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


