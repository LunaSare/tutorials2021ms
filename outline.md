Title
Promoting reproducibility with accessibility: An example in phylogenetics.

Outline
Introduction
Poor data sharing practices are one of the main issues preventing scientific reproducibility.
Reasons for prevalence of poor data sharing practices: lack of platforms and sharing standards, fear of being scooped, …
Availability is not the same as accessibility.

Introduction - OpenTree
In the natural sciences, understanding and knowing evolutionary relationships among organisms is key for studying biological processes.
The Open Tree of Life (OpenTree) is a platform that standardizes sharing and storing of phylogenetic data with the goal of constructing a single synthetic tree of all life.
The result of this is the ability to seamlessly establish reproducible workflows to use and reuse expert phylogenetic knowledge.
Data in OpenTree can be accessed programmatically through its many Application Programming Interface (API) services. R packages and Python libraries have been developed as wrappers for OpenTree API services for the benefit of a wider programming audience.
However, these high-level programming language wrappers are still hard to access by students and researchers with little computer science training.
The main difficulty is the prevailing (probably necessary) use of expert programming lingo to document functions in software packages.
Using accessible language to explain function usage, outputs, warnings and errors should facilitate adoption of usage of software in general (CITE?).
We developed a set of accessible (colorful and explained with “normal” language) tutorials, vignettes and notebooks that showcase different workflows using the OpenTree resources (data and APIs) to create reproducible phylogenetic analyses.
In this way, the data that was available through the OpenTree platform is now made accessible to a wider audience.


How do we make R and Python function documentation more accessible?
Fun examples with charismatic organisms
Demonstrate errors
Demonstrate warnings
Help users to not be afraid of errors and warnings, but instead to use them to their advantage (CITE carpentries)
Give alternatives on what to do when faced with an error or warning, and demonstrate these alternatives.







Goal of the ms:
A lesson in reproducible analyses for phylogenetics and evolution, separate from package publication.

Tutorials to include in ms (all?):
SSB workshop use of DateLife and rotl
Felipe’s python-opentree tutorial
ropentree tutorials


Goal of our tutorials:
Create vetted and inclusive curricular materials for reproducible phylogenetic analyses, using the Open Tree of Life.
vetted, a.k.a, tested by undergrads and researchers, and improved accordingly to feedback.
inclusive, a.k.a., accessible to users with all levels of programming experience (and phylogenetics knowledge, too!)

Challenges that we consider:
Computational presence in the field of phylogenetics and evolution has increased considerably in the last 10 years.
Computing is not a common skill or interest among biologists. Teaching computing to a diverse audience with varying preparation and computing skills is one of the challenges.
Programming is one of the main technologies facilitating reproducibility in science.
Can research be reproducible without programming? yes, lol. But reproducibility is greatly facilitated by programming.


A reproducible workflow for phylogenetics and evolution.

​​Some factors that contribute to non-reproducible research are
inappropriate study design,
failure to adequately address biases,
non-publication of studies with disappointing results, and
insufficient descriptions of interventions and methods
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
