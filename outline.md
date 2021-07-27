submission
Journal of Statistics and Data Science Education

Title
Promoting analysis reproducibility with accessibility: An example in phylogenetics.

Authors
Luna L Sanchez-Reyes and Emily Jane McTavish

Goal of the ms:
A lesson in reproducible analyses and workflows for phylogenetics and evolution, separate from package publication.


Outline
Introduction - leading argument
There are different arguments we can lead with:
Poor data sharing practices are one of the main issues preventing scientific reproducibility.
Reasons for prevalence of poor data sharing practices: lack of platforms and sharing standards, fear of being scooped, ...
Accessibility is one of the key characteristics of reproducibility. Availability is not the same as accessibility.
Programming is one of the main technologies facilitating reproducibility in science.
Specifically, programming facilitates making analyses reproducible.
Teaching programming skills to a diverse audience with varying preparation and computing knowledge is one of the challenges to address.

Introduction - OpenTree
In the natural sciences, considering evolutionary relationships among organisms (with phylogenetic trees) is key for studying and understanding biological processes.
The Open Tree of Life (OpenTree) is a platform that standardizes sharing and storing of phylogenetic data with the goal of synthesizing a single phylogenetic tree encompassing all life.
Data in OpenTree can be accessed programmatically through its many Application Programming Interface (API) services.
R packages and Python libraries have been developed as wrappers for OpenTree API services for the benefit of a wider programming audience.
The R and Python OpenTree wrappers have been used by researchers and educators to seamlessly establish reproducible workflows to use and reuse expert phylogenetic knowledge for biological research (CITE datelife, ...) and education (CITE phylotastic, galacticEdTools, ...).

Introduction - second argument
Computational presence in the field of phylogenetics and evolution has increased considerably in the last 10 years.
Yet, computing is not a common skill or interest among biologists and high-level programming language wrappers are still hard to be adopted by students and researchers with little computer science training, and sometimes even by biologists that have been programming for a long time.
We identify that one of the main difficulties is the prevailing (probably necessary) use of expert programming lingo to document functions and software packages.
Using accessible language to explain function usage, outputs, warnings and errors should improve accessibility of any software to facilitate adoption of software usage in general (CITE).
“community-developed best practices and standards must play a central role in improving reproducibility” (Freedman LP, Cockburn IM, Simcoe TS (2015) The Economics of Reproducibility in Preclinical Research. PLoS Biol 13(6): e1002165. https://doi.org/10.1371/journal.pbio.1002165)

Introduction - goal
We identify a set of accessible features (colorful and explained with “normal” language) and use them as guideline to develop teaching materials (tutorials, vignettes and notebooks)
The teaching materials showcase reproducible workflows using the OpenTree resources (data and APIs) in phylogenetic analyses.
The scientific data and tools that were available through the OpenTree platform are made more accessible to a wider audience through this teaching materials.

Methods - How do we make R and Python function usage more accessible?
Create documents that persist and are free of use and reuse, so they are available for the users to go back to them any time they need them, and to be passed on to other users.
Use charismatic organisms to make examples
Demonstrate errors
Demonstrate warnings
Help users to not be afraid of errors and warnings, but instead to use them to their advantage (CITE carpentries)
Give alternatives on what to do when faced with an error or warning, and demonstrate these alternatives.

General goal of our tutorials:
Create vetted and inclusive curricular materials for reproducible phylogenetic analyses, using the Open Tree of Life.
vetted, a.k.a, tested by undergrads and researchers, and improved accordingly to feedback.
inclusive, a.k.a., accessible to users with all levels of programming experience (and phylogenetics knowledge, too!)

Examples from our tutorials:
Which ones to include in ms? all?
SSB workshop tutorials http://opentreeoflife.github.io/SSBworkshop/
use of DateLife and rotl https://lunasare.github.io/ssb2020_workshop/
use of python-opentree, bulk tnrs and GBIF https://github.com/snacktavish/OpenTree_SSB2020/tree/master/notebooks
      2)  Felipe’s python-opentree tutorial
      3)  ropentree vignettes https://github.com/McTavishLab/ropentree
https://mctavishlab.github.io/ropentree/articles/plant_genera.html
https://mctavishlab.github.io/ropentree/articles/nameset_tool.html


Conclusion
Making accessible reproducible workflows has several advantages:
save explanation/training time when analyses are run again by students and collaborators.
save research time for yourself when analyses are run again with more data, a different dataset, a different organism or biological model.
scientific efforts can build off of each other


Random thoughts and quotes:
Can research be reproducible without programming? yes, lol. But reproducibility is greatly facilitated by programming.

​​”Some factors that contribute to non-reproducible research are inappropriate study design, failure to adequately address biases, non-publication of studies with disappointing results, and insufficient descriptions of interventions and methods”
(from https://www.nature.com/articles/d42473-019-00004-y)


JSDSE Call for papers [here](https://nhorton.people.amherst.edu/call_reproducibility.pdf)

Subject: “Teaching reproducibility and responsible workflow”

Premise:
The importance of workflow and reproducibility as a component of data acumen needed in our graduates.

Challenges to address:
1. technologies are rapidly evolving
2. few faculty were trained in the use of these methods
3. best practices have not been clearly identified
4. insufficient vetted and inclusive curricular materials are available
5. accounting for student heterogeneity and broadening participation
6. many aspects of student understandings in this area are unknown

To highlight work in this important and developing area, the Journal of Statistics and Data Science Education is inviting submission of papers related to “Teaching reproducibility and responsible workflow” to appear in a forthcoming issue.

Sample topics (non-exhaustive):
Teaching workflows and workflow systems
Fostering reproducible analysis
Promoting reproducibility as a component of replicability and scientific conduct
Developing and implementing documentation and code standards
Incorporating source code (version) control systems
Supporting collaboration Integrating ethics
Conducting effective formative and summative assessment
